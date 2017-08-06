require 'rake-jekyll'

Rake::Jekyll::GitDeployTask.new(:deploy) do |t|
  t.committer = 'jayMcoder'
  t.deploy_branch = -> {
    gh_user = ENV['TRAVIS_REPO_SLUG'].to_s.split('/').first
    remote_url.match(/[:\/]#{gh_user}\.github\.io\.git$/) ? 'master' : 'gh-pages'
  }
end

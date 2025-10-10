# source "https://rubygems.org"
# # Hello! This is where you manage which Jekyll version is used to run.
# # When you want to use a different version, change it below, save the
# # file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
# #
# #     bundle exec jekyll serve
# #
# # This will help ensure the proper Jekyll version is running.
# # Happy Jekylling!
# # gem "jekyll", "~> 4.4.1"
# # This is the default theme for new Jekyll sites. You may change this to anything you like.
# # gem "minima", "~> 2.5"
# # If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# # uncomment the line below. To upgrade, run `bundle update github-pages`.
# # gem "github-pages", group: :jekyll_plugins
# # If you have any plugins, put them here!
# group :jekyll_plugins do
#   gem "jekyll-feed", "~> 0.12"
# end

# # Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# # and associated library.
# platforms :mingw, :x64_mingw, :mswin, :jruby do
#   gem "tzinfo", ">= 1", "< 3"
#   gem "tzinfo-data"
# end

# # Performance-booster for watching directories on Windows
# gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# # Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# # do not have a Java counterpart.
# gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# gem "github-pages", group: :jekyll_plugins
# gem "jekyll-remote-theme"

# # 如果你还需要本地运行，可以保留这一行来确保使用正确的 Jekyll 版本
# # gem "jekyll" 
# gem "faraday-retry", "~> 2.3"

source "https://rubygems.org"

# 启用 GitHub Pages，它会安装兼容的 Jekyll 核心和插件
gem "github-pages", group: :jekyll_plugins

# 以下是所有额外的插件
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  # 远程主题插件，用于识别 _config.yml 中的 remote_theme
  gem "jekyll-remote-theme"
  gem "jekyll-polyglot"
end

# 针对本地环境的额外修复或依赖
gem "faraday-retry", "~> 2.3"
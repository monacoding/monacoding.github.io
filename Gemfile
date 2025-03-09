source "https://rubygems.org"



#gem "jekyll-theme-clean-blog"
gem "github-pages", group: :jekyll_plugins
gem "jekyll-remote-theme" # 원격 테마를 사용할 경우 필요
gem "webrick" # Ruby 3.0 이상에서 필요

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
  gem "jekyll-sass-converter"  # 추가
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

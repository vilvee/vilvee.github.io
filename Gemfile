# frozen_string_literal: true

source "https://rubygems.org"

<<<<<<< HEAD
gem "jekyll-theme-chirpy", "~> 6.2.3"

group :test do
  gem "html-proofer", "~> 4.4"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
=======
gem "jekyll-theme-chirpy", "~> 7.2"

gem "html-proofer", "~> 5.0", group: :test

>>>>>>> v7.2.0
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

<<<<<<< HEAD
# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

#compose new posts
#draft      # Creates a new draft post with the given NAME
#post       # Creates a new post with the given NAME
#publish    # Moves a draft into the _posts directory and sets the date
#unpublish  # Moves a post back into the _drafts directory
#page       # Creates a new page with the given NAME
#rename     # Moves a draft to a given NAME and sets the title
#compose    # Creates a new file with the given NAME
#https://github.com/jekyll/jekyll-compose
gem 'jekyll-compose', group: [:jekyll_plugins]

# Lock jekyll-sass-converter to 2.x on Linux-musl
if RUBY_PLATFORM =~ /linux-musl/
  gem "jekyll-sass-converter", "~> 2.0"
end
=======
gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
>>>>>>> v7.2.0

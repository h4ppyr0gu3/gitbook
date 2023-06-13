---
description: Inline bundling allows us to require gems on run time
---

# Inline Bundling

Ruby provides an option to have a script that executes and requires dependencies inline, This is pretty impressive and allows for very complex scripts to be written and only require dependencies on run time

```ruby
#! /usr/bin/env ruby
# frozen_string_literal: true

require 'bundler/inline'

gemfile true do
  source 'https://rubygems.org'

  gem 'debug', '~> 1.4'
end

# rest of code here
```

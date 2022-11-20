---
description: Using Bundle add is a huge timesaver
---

# Bundle add

When adding gems to a gemfile for a private project we will often just type the gem name and then bundle install, this is not the best way,

#### use bundle add

`bundle add <gem_name>` will install the gem as well as write the version number to the `Gemfile` this can save time locking gem versions manually by doing it during the installation process

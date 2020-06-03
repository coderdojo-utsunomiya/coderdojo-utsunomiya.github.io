# coderdojo-utsunomiya.github.io

## How to install

```
gem install bundler
git submodule update --init
bundle install
```

(Ubuntu)
If you failed installing ``nokogiri`` during ``bundle install``, let you try again after installing ``zlib1g-dev``

```
apt-get install zlib1g-dev
```

(for Ubuntu 20.04 on WSL)

```
sudo apt install -y ruby ruby-dev zlib1g-dev
sudo gem install bundler
git submodule update --init
bundle install
```

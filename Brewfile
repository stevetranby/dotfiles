# Install command-line tools using Homebrew
# Usage: `brew bundle Brewfile`

# Make sure we’re using the latest Homebrew
update

# Upgrade any already-installed formulae
upgrade

install git
install caskroom/cask/brew-cask

# Install GNU core utilities (those that come with OS X are outdated)
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
install coreutils

# Install some other useful utilities like `sponge`
install moreutils

# Install GNU `find`, `locate`, `updatedb`, and `xargs`, `g`-prefixed
install findutils

# Install GNU `sed`, overwriting the built-in `sed`
install gnu-sed --default-names

# Install Bash 4
# Note: don’t forget to add `/usr/local/bin/bash` to `/etc/shells` before running `chsh`.
install bash
install bash-completion

# Install ZSH
install zsh zsh-completions

# Install wget with IRI support
install wget --enable-iri

# Development
install node
install homebrew/versions/lua52
install ant
install vim --override-system-vi
install docker
install sqlite3
install postgresql
install mysql

# Ruby
#brew install rbenv rbenv-gem-rehash ruby-build

# Utils
install ack 			# search
install imagemagick		# cmdline image edit
install nmap			# network diagnostics
install p7zip
install rename
install tree			# display cwd as tree (sub dirs)
install ucspi-tcp 		# `tcpserver` et al. to pass each connection to your script
install webkit2png		# create screenshots of websites from cmdline
install zopfli

# Remove outdated versions from the cellar
cleanup

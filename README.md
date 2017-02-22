BBTools is a collection of scripts and extensions for BBEdit

The project contains helpful tools collected from using BBEdit for well over ten years. The tools fall into a couple general forms:

* Clippings - useful snippets
* Color Schemes - BBEdit color schemes (some slightly modified from defaults)
* Custom Keywords - Additional keywords for existing languages
* Language Modules - additional language syntax
* Scripts - Scripts for interacting with BBEdit and generally extending it
* Stationery - Templates
* Text Filters - General purpose text filters

## Requirements

* [BBEdit](http://barebones.com/products/bbedit) 11.6 or greater
* Mac OS X 10.11 or greater
* [Ruby](http://ruby-lang.org) 2.0 or greater (default on Mac OS X)

These may work on older versions of BBEdit and Mac OS X but are not actively supported.

## Install

    rake install

## Uninstall

    rake uninstall

## Customize

The best way to extend BBTools for your own use is to clone in GitHub and start adding your own items. The `Rakefile` is generally designed to read all files added to easily
allow new items to be added.

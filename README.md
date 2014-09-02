-*- mode: markdown; mode: auto-fill; fill-column: 80 -*-

# Public_profiles Puppet Module 

[![Puppet Forge](http://img.shields.io/puppetforge/v/ulhpc/public_profiles.svg)](https://forge.puppetlabs.com//ulhpc/public_profiles)
[![License](http://img.shields.io/:license-apache2.0-blue.svg)](LICENSE)
![Supported Platforms](http://img.shields.io/badge/platform-debian-lightgrey.svg)

Public Puppet ULHPC profiles to be used in r10k environments

      Copyright (c) 2014 S. Varrette, H. Cartiaux, V. Plugaru <hpc-sysadmins@uni.lu>
      

* [Online Project Page](https://github.com/ULHPC/puppet-public_profiles)  -- [Sources](https://github.com/ULHPC/puppet-public_profiles) -- [Issues](https://github.com/ULHPC/puppet-public_profiles/issues)

## Synopsis

Public Puppet ULHPC profiles to be used in r10k environments,  typically in Vagrant boxes -- see [vagrant-vms](https://github.com/Falkor/vagrant-vms) for instance
The various operations of this repository are piloted from a `Rakefile` which
assumes that you have [RVM](https://rvm.io/) installed on your system.

## Dependencies

See `metadata.json`.

## public_profiles class parameters

* `$ensure` [Default: 'present']: Ensure ulhpc-public_profiles is present, absent etc. 

## Usage

### class public_profiles

     include 'public_profiles'


## Documentation

Please refer to the header of each manifest files to understand the usage of
classes and definitions associated to the 'ulhpc-public_profiles' module.
 
Alternatively, generate automatically the documentation via
[`puppet doc`](http://docs.puppetlabs.com/man/doc.html) as follows:  

       $> rake doc   # Not yet implemented
       
For other information, please refer to the `metadata.json` file in this directory 

## Librarian-Puppet / R10K Setup

You can of course configure ulhpc-public_profiles in your `Puppetfile` to make it 
available with [Librarian puppet](http://librarian-puppet.com/) or
[r10k](https://github.com/adrienthebo/r10k) by adding the following entry:

     mod ulhpc-public_profiles, 
         :git => https://github.com/ULHPC/puppet-public_profiles,
         :ref => production 


## Issues / Feature request

You can submit bug / issues / feature request using the 
[ulhpc-public_profiles Tracker](https://github.com/ULHPC/puppet-public_profiles/issues). 


## Developments / Contributing to the code 

If you want to contribute to the code, you shall be aware of the way this module
is organized.
These elements are detailed on [`doc/contributing.md`](doc/contributing.md)

You are more than welcome to contribute to its development by 
[sending a pull request](https://help.github.com/articles/using-pull-requests). 

## Resources

### Git 

You should become familiar (if not yet) with Git. Consider these resources: 

* [Git book](http://book.git-scm.com/index.html)
* [Github:help](http://help.github.com/mac-set-up-git/)
* [Git reference](http://gitref.org/)


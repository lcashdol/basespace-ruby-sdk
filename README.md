INTRODUCTION	
=========================================

BaseSpaceRuby is a Ruby based SDK to be used in the development of Apps and scripts for working with Illumina's BaseSpace cloud-computing solution for next-gen sequencing data analysis. 

The primary purpose of the SDK is to provide an easy-to-use Ruby environment enabling developers to authenticate a user, retrieve data, and upload data/results from their own analysis to BaseSpace.

If you haven't already done so, you may wish to familiarize yourself with the general BaseSpace developers documentation (https://developer.basespace.illumina.com/) and create a new BaseSpace App to be used when working through the examples provided in 'examples' folder.


AUTHORS
=========================================

Joachim Baran, Raoul Bonnal, Toshiaki Katayama, Francesco Strozzi


REQUIREMENTS
=========================================

TBD

The multi-part file upload will currently only run on a unix setup.


INSTALL
=========================================

TBD

BUILDING A NEW VERSION OF THE GEM
=========================================

    bundle exec rake gemspec
    bundle exec gem build basespace-ruby-sdk.gemspec
    sudo gem1.9 install basespace-ruby-sdk

### Unit Testing

First, install the gem as described just above. Then use [RSpec](http://rspec.info) for unit testing:

    rspec -c -f d

CHANGELOG
=========================================

v 0.1.0
-----------------------------------------
 
Initial release of BaseSpacePy

COPYING / LICENSE
=========================================

See License.txt in the basespace-ruby-sdk directory for details on licensing and distribution.

KNOWN BUGS
=========================================
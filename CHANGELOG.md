cashrb v1.3.1
=============
 - update minitest to be a development dependency not a runtime dependency

cashrb v1.3.0
=============
 - add #abs

cashrb v1.2.2
=============
 - fix formatting in README.md
 - package using 1.8.7 to remove specification date error caused by 1.9 and
   rubygems

cashrb v1.2.1
=============
 - ensure objects created from internal functions such as (+ - * / % divmod)
   return new objects that are consistent with their parents options

cashrb v1.2.0
=============
 - allow creation using decimal values instead of cents if you'd rather

cashrb v1.1.1
=============
 - fix bug in #to_s/#to_f regarding negative amounts

cashrb v1.1.0
=============
 - use "include Comparable" instead of custom functions
 - #== no longer throws an IncompatibleCurrency exception
 - cleanup tests that we auto passing
 - if currency implements :cents_in_whole, use it

cashrb v1.0.3
=============
 - change to "require 'cashrb'" to avoid clash with 'cash' gem

cashrb v1.0.2
=============
 - fix error with scope for ruby 1.8.7
 - require 'rubygems' in tests

cashrb v1.0.1
=============
 - revert to hashrocket syntax for compatibility with rubies prior to 1.9.2

cashrb v1.0.0
=============
 - first release!

# pyaXeHelper

This package contains functions helping pyaXe. This works with:

    - pyaxe version '0.1.dev29+gf57de55.d20200106'

    - sextractor version 2.19.5 (2014-11-16)

Functions include:

    - change_catalog_order()
    
    - change_magiso2magwavelength()
    
    - write_catalog()
    
    - read_catalog()
    
    - select_source()
    
Known issues:
    
    - These functions mainly fix the source catalog files (including cookbook.cat and *_1.cat) produced by sextractor and axeiol.py. The issues about these files were posted in https://github.com/spacetelescope/pyaxe with tickets [#5](https://github.com/spacetelescope/pyaxe/issues/5) and [#6](https://github.com/spacetelescope/pyaxe/issues/6).
    
v.1.0.0

    - Implement: change_catalog_order, change_magiso2magwavelength, write_catalog, read_catalog, select_source
    

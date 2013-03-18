Zelpex\Layouts
================
Version 1.0 Created by Andrew Boyko

Introduction
------------

EasyLayouts is a simple ZF2 module that simply
allows you to specify alternative layouts to use for each module.

The default layout is layout/layout from ZendSkeletonApplication.

Usage
-----

Using EasyLayouts is simple. In any module config or autoloaded
config file simply specify the following:

//php
array(
    'module_layout' => array(
        'moduleName' => 'layout/any-layout-name',
    ),
);
//

That's it!
This is taken from https://github.com/EvanDotPro/EdpModuleLayouts and updated

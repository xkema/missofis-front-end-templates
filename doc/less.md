[Missofis Front-End Templates](http://missofis.com) | [Documentation Table of Contents](TOC.md)

# LESS files

Missofis LESS file structure is consist of theese LESS style files

* [__normalize.less](../less/__normalize.less)
* [__base.less](../less/__base.less)
* [__helpers.less](../less/__helpers.less)
* [__queries.less](../less/__queries.less)
* [__print.less](../less/__print.less)
* [__components.less](../less/__components.less)
* [__data-images.less](../less/__data-images.less)
* [__fonts.less](../less/__fonts.less)
* [__grid.less](../less/__grid.less)
* [__mixins.less](../less/__mixins.less)
* [__plugins.less](../less/__plugins.less)
* [__user.less](../less/__user.less)
* [main.less](../less/main.less)

## __normalize.less

A CSS reset file from html5boilerplate. Use your own to change reset behaviour.

## __base.less

Basic CSS styles.

## __helpers.less

CSS helper classes to speed up development processes.

## __queries.less

Media queries.

## __print.less

Print styles to prevent unnecessary print paper consuming.

## __components.less

Pre-defined CSS components.

## __data-images.less

Base64 encoded data images.

## __fonts.less

Font-face definitions goes here.

## __grid.less

CSS griddefinitions.

## __mixins.less

LESS mixins. (derived from LESS Elements 0.9)

## __plugins.less

Copy & paste vendor plugin styles to this less file if any.

## __user.less

Author custom styles goes here. Write your site styles to this file.

## main.less

This less file @imports all other less files into a single file. When you consider mobile-first approach change file import order.
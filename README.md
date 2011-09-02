# Lilydate

This is a tiny javascript jquery plugin for implementing quick date pickers.

## Requirements

This plugin requires [jQuery](http://jquery.com/) and
[Date.js](http://www.datejs.com/). jQuery you'll need to get from it's website,
but I have included a version of Date.js in this repo. Feel free to grab the
newest version off of their website however.

## Usage

Very simple. If I have a date field such as:

    <input type="text" name="date" id="date" />

You can use lilydate with it via the following (jQuery) javascript:

    $(function() { $('#date').lilydate(); });

## Styling

I use [lesscss](http://lesscss.org/) a lot so I include the less file and the
compiled css file for reference in how to style this plugin. The easiest way to
quickly customize colors is to edit the less file colors that are at the top and
then recompile the css and use the result.

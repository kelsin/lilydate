# Lilydate

This is a tiny javascript jquery plugin for implementing quick date pickers.

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

Holiday Request Script
======================

A simple script to email a holiday request form.

To be used with [holiday_form.odt](holiday_form.odt)

Setup
-----

Assign relevant values to the following constants in  [hrq](hrq):

 * `DIR_HOLIDAY_REQUESTS`
 * `HOLIDAYS_EMAIL_ADDRESS`
 * `NAME`

Move [holiday_form.odt](holiday_form.odt) to your `DIR_HOLIDAY_REQUESTS`

Usage
-----

*N.B. There is no validation nor user confirmation...*

`hq DAYS DATES...`

E.g.

`./hq 5 16/09/2015-20/09/2015 25/09/2015`

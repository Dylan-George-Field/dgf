# dgf
Simple function that changes the difference between a date and the current date into a 'YouTube style' format.
Eg, "today", "yesterday", "2 days ago", "over 1 month ago", "over a year ago" etc.

I made this for Wordpress, add this to the file that will be calling it.

  include "your-path-to-file/youtubeDateChanger.php";

Usage (in the loop):
  echo youtubeDateChanger(get_the_time('d/m/Y'));

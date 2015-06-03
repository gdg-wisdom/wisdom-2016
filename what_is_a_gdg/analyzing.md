# Analyzing
### Have you ever wondered if you've completed all your GDG attendance metrics? There's an app for that! :)

![chart](https://lh3.googleusercontent.com/-36GvJvLXmII/VW0mur3DNXI/AAAAAAABksk/GZwql9i8lZw/s400/redash_charts_2015-06-02T03_03_02.586.png)

This is a chart of GDG chapters with GDG events with no Attendance numbers.

This may be caused by the fact that the event is old (precedes the participant count metric in dev site)  OR the organizer(s) simply missed typing it in.

Here's a sheet that makes it easy to input the attendance metrics.  See https://j.mp/gdgattendance

The instructions are simple, go to https://j.mp/gdgattendance look for your group, wherever it says MISSING-participantsCount click on the link and add the appropriate counts.

This report can be re-generated every day if it is useful.  Let me know.

An example is: I find my group (e.g., New York)  then I click on the link.


![example1] (https://lh3.googleusercontent.com/-3r6qcvB9clw/VW0qe-P-NlI/AAAAAAABksw/gWylBPM6oKw/s1600/Screen%2BShot%2B2015-06-01%2Bat%2B11.59.54%2BPM.png)



After clicking I am taken to the google dev site metrics page for that event:

![example2] (https://lh3.googleusercontent.com/-x2MVVmTKv5k/VW0rIEDjBxI/AAAAAAABks4/MsQUbtFrgLo/s1600/Screen%2BShot%2B2015-06-02%2Bat%2B12.02.23%2BAM.png)

I enter the values and click "update"

For those that like to run queries, the data is in bigquery here: https://bigquery.cloud.google.com/table/personal-real-estate:gdg.attendance

For those that like to visualize the data, fork the project here: http://demo.redash.io/queries/303 and here: http://demo.redash.io/queries/303#384



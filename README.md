# Linking Android Activities (secondactivityassignment-melvincabatuan)

secondactivityassignment-melvincabatuan created by Classroom for GitHub

This assignment illustrates the linking and passing data between activities using the Intent object.

## Problem:

Design and Implement an Android application that determines the day of the week (Sunday through Saturday) given any date entered by the user. You could use this program, for example, to determine what day of the week you were born or what day of the week an upcoming exam is. Use Zeller's congruence algorithm to calculate the day of the week. The output day should be printed in a second Android activity.

## Formula:

```Java
day_out = (day + (int)(26 *(month + 1)/10.0) + year + (int)(year/4.0) + (int)(century/4.0) + 5 * century ) % 7;
```

where:

day_out - is the calculated day of the week (0..6) 

day     - is the day entered by the user.

month   - is the adjusted month (January and February are 13 and 14, not 1 and 2)

year    - is the last two digits of the adjusted year (January and February are in the previous year). For example: if year is 2003, then year would be 03

century - is the century of the adjusted year (January and February are in the previous year). For example, if year is 2003, then century is 20

## Accept

To accept the assignment, click the following URL:

https://classroom.github.com/assignment-invitations/a608021886fe020a5b777963b6be0ca2

## Sample Solution:

https://github.com/DeLaSalleUniversity-Manila/secondactivityassignment-melvincabatuan

## Submission Procedure with Git: 

https://gist.github.com/melvincabatuan/712e476605213e0ab9ac 

## Screenshots:

![alt tag](https://github.com/DeLaSalleUniversity-Manila/secondactivityassignment-melvincabatuan/blob/master/device-2015-09-29-193049.png)

![alt tag](https://github.com/DeLaSalleUniversity-Manila/secondactivityassignment-melvincabatuan/blob/master/device-2015-09-29-193123.png)


"For many are invited, but few are chosen." - Matthew 22:14

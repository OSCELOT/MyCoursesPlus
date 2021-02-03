# MyCoursesPlus
Legacy Seneca MyCoursesPlus B2

Should work with OpenJDK11

README:

- version 9.5.0
- updated bb version in manifest to 9.1.0

- version 9.4.7 (View JSP changes same version)
1)  View.jsp -  line 1065 to 1118 - Changed sorting of courses being taught. Now they are sorted in the following order; Year(Descending), Code(Ascending) and section(Ascending).

- Version 9.4.7
1) Removed the Picture Class list link. - view.jsp changed boolean to false.


- version 9.4.6
1) Remove double loading of lightwindow pop-up while still supporting calling the scripts if not already loaded.
2) Enable Calendar tool changed link from viewCalendar?context=cp_course to viewCalendar?calcontext=cp_course


-Version 9.4.5
1) fixed issue with lighwindow conflicting with Announcements and College news
modfied view.jsp and coursesplus.css

-Version 9.4.4
1) Enabled subject class list
2) Added Seneca class library.

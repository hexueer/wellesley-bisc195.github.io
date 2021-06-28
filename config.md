<!--
Add here global page variables to use throughout your
website.
The website_* must be defined for the RSS to work
-->
@def website_title = "BISC195"
@def website_descr = "Essential Skills for Computational Biology"
@def website_url   = "http://bisc195.wellesley.edu/"

@def author = "Kevin Bonham, PhD"
@def course_calendar = "https://calendar.google.com/calendar/u/0?cid=Y192ZHJxM243cTh0czluOGZ1aGpzZnVmMHFzMEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t"

@def mintoclevel = 2

<!--
Add here files or directories that should be ignored by Franklin, otherwise
these files might be copied and, if markdown, processed by Franklin which
you might not want. Indicate directories by ending the name with a `/`.
-->
@def ignore = ["node_modules/", "franklin", "franklin.pub", "assignment_repos/"]

<!--
Add here global latex commands to use throughout your
pages. It can be math commands but does not need to be.
For instance:
* \newcommand{\phrase}{This is a long phrase to copy.}
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}

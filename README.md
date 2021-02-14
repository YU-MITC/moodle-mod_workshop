# moodle-mod_workshop
Customized Moodle workshop plugin

Due to the spread of COVID-19 infection, distance learning has increased in Japanese schools.
The Moodle "workshop" module has a mutual evaluation function between students.
With the increase in distance learning, the workshop activities are  used in more classes/subjects.
However, conventional workshop module does not have download function of submissions.

So that, we add a download function for the workshop module.
For this function, we have added some statements to "view.php", and have added some functions to "locallib.php".
And, we have added some language strings.

Additionally, for the Microsoft Windows and Japanese environments, we have added some statements in order to prevent text garbling of ZIP filename.
Note that, it is not possible to completely prevent filename garbling of submitted files contained in the ZIP file.
Because, complete character code conversion from the UTF-8 to the Shift JIS is not possible.

Now, codes of this plugin are based on the workshop plugin for the Moodle 3.9.

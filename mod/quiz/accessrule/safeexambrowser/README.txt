Safe Exam Browser (SEB) quiz access rule

This quiz access rule was created by Tim Hunt at the Open University. It can be
used with versions 2.3.7 of Moodle, or later. (For Moodle 2.4, you should be
using 2.4.4 or later.)

If you install this plugin, there is a new option 'Allowed browser exam keys'
on the quiz settings form where you can enter valid keys for version of SEB
that should be allowed to attempt the quiz. There is also a new capability
'Not required to use Safe Exam Browser'. Users with that capability (by default
teachers and above) are exempt from the secure browser check.

To install using git, type this command in the root of your Moodle install
    git clone git://github.com/moodleou/moodle-quizaccess_safeexambrowser.git mod/quiz/accessrule/safeexambrowser
    echo '/mod/quiz/accessrule/safeexambrowser/' >> .git/info/exclude

Alternatively, download the zip from
    https://github.com/moodleou/moodle-quizaccess_safeexambrowser/zipball/master
unzip it into the mod/quiz/accessrule folder, and then rename the new
folder to safeexambrowser.

Once installed you need to go to the Site administration -> Notifications page
to let the plugin install itself.

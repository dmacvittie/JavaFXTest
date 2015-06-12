Initial test of JavaFX 8 configuration

Initially this class generated errors on every import.
Went to Window | Preferences, in the dialog Treeview (left side) selected Java | Compiler | Errors/Warnings. Then scrolled on the right to "Deprecated and restricted API" and set "Forbidden reference (access rules): to "warning"

This turned the dozens of errors into warnings, so added 
@SuppressWarnings("restriction")

To the top of the class definition.

Compiles and runs peachy (have only tested Windows 8.1, but docs show it working cross platform just fine)

Original sourcce: 
https://docs.oracle.com/javase/8/javafx/api/javafx/stage/Stage.html

This is a test. This is only a test.

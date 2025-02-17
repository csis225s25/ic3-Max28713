# In Class Problem Set 3
# Max Weisman and Nicholas Rapecciuolo
I used ComboBoxDemo.java a few years ago.  It used to compile cleanly.  Even though the code has not changed, it now  will not compile without throwing warnings.

Doing everything from a command prompt or Git Bash (no IDEs allowed), your mission is to debug the code and find out why it stopped compiling cleanly.  When you have figured it out,  note what you changed and why it stopped working in the README.md file.


**Changes to code**
We casted a String datatype to the JComboBox because it was previously a raw type taking in Strings.

**What caused it to stop working?**
When java 5 was released raw data types were introduced.  This created new problems involving type safety such as the problem that we fixed in the code.

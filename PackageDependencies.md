# Introduction #

Any application might require a certain package or packages in order for it run.
These dependencies are then automatically downloaded as necessary if it does not exists on the user's system.

**NOTE:**
  * This rules/how to also applies to other information such as:
    * Pre-dependencies_* Recommends_
    * Suggests_* Breaks_
    * Conflicts_* Replaces_
    * Provides


# Details #

http://lh6.google.com/welemski/R6hwgRjUovI/AAAAAAAAAOQ/EZ3DZ-3_dsE/Dependencies.png?imgmax=640

As seen on the picture above adding package dependencies are very straight forward.
All you need to do is:

  * Add the official package name in the package name entry.
  * Provide the version your application depends on.
    * You application might need a certain version which might require a higher version or lower version or any version of the package/library. You would need to choose from the dropdown/combo box if your application requires a certain version. Could be _Any, Less than,Less than or equal to,Greater than, so on and so forth_.
  * The bit drop down box/combo box is used only for hierarchal order of package dependencies. Which you may prefer a certain package shoudl exist or a certain package must  and should exists. This can be group using the bit **OR / AND**. If your uncertain leave it by default.
  * Click the add button when you're done to add it to the lists of packages your application depends on.

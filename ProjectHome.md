DebianPackageMaker is a simple user interface/tool to make a debian package easier and straightforward to use and deploy your linux application to any debian based distro.


You can build debian packages using two modes:

  * **Target Mode**
    * Manually specify the installation directory and the files to be installed in the target installation directory.

  * **Source Mode**
    * Debian Package Maker will configure the source for you, compile them and then build a package using the target rules.
    * configure/autogen scripts and Makefile/rules is required for DPM to automate the whole process for you.

Provides user interface for package information that will be used as control file to create a debian based package.

It also provides a different tabs for adding package dependencies:

  * **Dependencies**
  * **Pre-dependencies**
  * **Recommends**
  * **Suggests**
  * **Breaks**
  * **Conflicts**
  * **Replaces**
  * **Provides**

Can add scripts like postins,changelogs etc
Straight forward to use

### Details ###

**Trunk**
> https://code.launchpad.net/~welemski/debianpackagemaker/active

**Blue Prints / Road Map**
> https://blueprints.launchpad.net/debianpackagemaker/+specs?show=all

**Current Release**
> 0.4.1

**Next Release**
> 0.4.2

**Help Needed**
> You can try the latest unstable source in the trunk. You can help me by compiling it in your current choice of distro and filling a bug at:

> https://www.launchpad.net/~welemski/debianpackagemaker

> You can also submit a translation in the main project site.


---

### SCREEN SHOTS ###

**Target Mode**
> ![http://lh4.google.com/welemski/R6hwqxjUo2I/AAAAAAAAAPI/h3Z_stHspOo/s400/TargetMode.png](http://lh4.google.com/welemski/R6hwqxjUo2I/AAAAAAAAAPI/h3Z_stHspOo/s400/TargetMode.png)

**Source Mode**
> ![http://lh3.google.com/welemski/R6hwqhjUo0I/AAAAAAAAAO4/6zSzAy29RdU/s400/SourceMode.png](http://lh3.google.com/welemski/R6hwqhjUo0I/AAAAAAAAAO4/6zSzAy29RdU/s400/SourceMode.png)

**Package Information**
> ![http://lh5.google.com/welemski/R6hwhBjUoyI/AAAAAAAAAOo/Vhd39Hzul7g/s400/PackageInfo.png](http://lh5.google.com/welemski/R6hwhBjUoyI/AAAAAAAAAOo/Vhd39Hzul7g/s400/PackageInfo.png)
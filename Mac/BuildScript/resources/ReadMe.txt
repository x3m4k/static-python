This package will install Python $FULL_VERSION for Mac OS X
$MACOSX_DEPLOYMENT_TARGET for the following architecture(s):
$ARCHITECTURES.

               **** IMPORTANT ****

Installing on OS X 10.8 (Mountain Lion) or later systems
========================================================

If you are attempting to install on an OS X 10.8+ system, you may
see a message that Python can't be installed because it is from an
unidentified developer.  This is because this Python installer
package is not yet compatible with the Gatekeeper security feature
introduced in OS X 10.8.  To allow Python to be installed, you
can override the Gatekeeper policy for this install.  In the Finder,
instead of double-clicking, control-click or right click the "Python"
installer package icon.  Then select "Open using ... Installer" from
the contextual menu that appears.

       **** IMPORTANT changes if you use IDLE and Tkinter ****

Installing a third-party version of Tcl/Tk is no longer required
================================================================

Beginning with Python 3.4 alpha2, the 10.6+ 64-bit installer now
comes with its own private copy of Tcl and Tk 8.5 libraries.  For
this version of Python, it is no longer necessary to install
a third-party version of Tcl/Tk 8.5, such as those from ActiveState,
to work around the problematic versions of Tcl/Tk 8.5 shipped by
Apple in OS X 10.6 and later.  (This does not change the requirements
for older versions of Python installed from python.org.)  By default,
this version of Python will always use its own private version,
regardless of whether a third-party Tcl/Tk is installed.
The 10.5+ 32-bit-only installer continues to use Tcl/Tk 8.4,
either a third-party or system-supplied version.
Since this is a new feature, it should be considered somewhat
experimental and subject to change prior to the final release of
Python 3.4.  Please report any problems found to the Python bug
tracker at http://bugs.python.org.

Visit http://www.python.org/download/mac/tcltk/
for current information about supported and recommended versions of
Tcl/Tk for this version of Python and of Mac OS X.

Using this version of Python on OS X
====================================

Python consists of the Python programming language interpreter, plus
a set of programs to allow easy access to it for Mac users including
an integrated development environment, IDLE, plus a set of pre-built
extension modules that open up specific Macintosh technologies to
Python programs.

The installer puts applications, an "Update Shell Profile" command,
and a link to the optionally installed Python Documentation into the
"Python $VERSION" subfolder of the system Applications folder,
and puts the underlying machinery into the folder
$PYTHONFRAMEWORKINSTALLDIR. It can
optionally place links to the command-line tools in /usr/local/bin as
well. Double-click on the "Update Shell Profile" command to add the
"bin" directory inside the framework to your shell's search path.

You must install onto your current boot disk, even though the
installer may not enforce this, otherwise things will not work.

You can verify the integrity of the disk image file containing the
installer package and this ReadMe file by comparing its md5 checksum
and size with the values published on the release page linked at
http://www.python.org/download/

Installation requires approximately $INSTALL_SIZE MB of disk space,
ignore the message that it will take zero bytes.

More information on Python in general can be found at
http://www.python.org.

# xctemplateinstaller
A suite of tools purposed for the installation of Xcode templates.

#### Features

##### Xcode Source File Template Installation

Currently supports installing new source file templates for iOS with Xcode 6.3.1.

These source file templates can be discovered in Xcode under *"File > New > File > iOS > Source"*.

**Example usage:**

<code>
./xcsourcetemplateinstaller "templates/source/Bare ObjC Class.xctemplate/"
</code>

*Note that sudo privileges may be required to install templates in Xcode.*

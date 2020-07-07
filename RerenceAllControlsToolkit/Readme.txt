Get Reference to All Controls V1.2.0

Copyright © 2007, GTech Automation
All rights reserved.

Author:
Dave A. Graybeal
dag74@daimlerchrysler.com


Distribution:
This code was downloaded from the LAVA Code Repository: http://forums.lavag.org/downloads.html


Instructions:
This code has been tested to run under LabVIEW 8.2.1.  Unzip the code into any folder of your choice and open the example called, GetRefExample.vi.  This shows how to use the 'Get Reference To All Controls.vi' as well as the 'Get Control Reference by Name.vi' to obtain a reference to all controls and how to search thru those reference to obtain the reference you want.

Features:
Get Reference to All Controls.vi
-Gets the references and labels to All the controls on the front panel of the calling VI.
-Is Able to search thru all Tab Controls recursively to compile a complete list of Controls from the front panel.

Get Control Reference by Name.vi
-Polymorphic VI that allows for searching list for single reference or an array of references.
-Gets a Specific Reference from the List of All Controls by Control Name(Label).

Get Control References By Match Pattern.vi
-Gets an Array of References for all Controls containing the regular expression in the label.


Support:
If you have any problems with this code or want to suggest features:
http://forums.lavag.org/CR-Get-Reference-To-All-Controls-t7354.html

Change Log:
1.0.0:  Initial release of the code.

1.1.0:  Changed the Class ID of a Tab Control from a constant to a Property Node (To support Future LabVIEW Releases)

1.2.0:  Removed all Dialog boxes from VI's and replaced them with proper error output messages.
	Added Get Control References By Match Pattern.vi (Authored By: Justin Goeres) Thanks!
	Modified GetRefExample to Include the Get Control References By Match Pattern.vi
	Added shift registers where necessary to ensure proper error is passed out of each VI.
	Improved some performace by removing unnecessary Items from Loops (Thanks JFM!)
	Recompiled under LabVIEW 8.2.1.
	

License:
This code is distrubuted under the BSD License

Copyright (c) 2007, GTech Automation

All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

    * Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
    * Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
    * Neither the name of GTech Automation nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR
CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR
PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF
LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
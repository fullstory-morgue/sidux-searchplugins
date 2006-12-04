#  ----------------------------------------------------------------------
#  searchplugins-sidux
#  Search Plug-In for sidux.com, used in Mozilla, Firefox,
#  Iceweasel and other compatible browsers
#  Search-Plug-In for sidux.com, used in Konqueror and Safari
#  Copyright (C) 2006 by the sidux Development Team
#  Contact: Chris Hildebrandt (slam) at webmaster@sidux.com
#  ----------------------------------------------------------------------
#  LICENSE
# 
#  This program is free software; you can redistribute it and/or
#  modify it under the terms of the GNU General Public License (GPL)
#  as published by the Free Software Foundation; either version 2
#  of the License, or (at your option) any later version.
# 
#  This program is distributed in the hope that it will be useful,
#  but WIthOUT ANY WARRANTY; without even the implied warranty of
#  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
#  GNU General Public License for more details.
# 
#  To read the license please visit http://www.gnu.org/copyleft/gpl.html
#  ----------------------------------------------------------------------
#  Version 0.1.1 created: 11 October 2006
#  - added proper copyright, license and version info (slam)
#  - added Konqueror-Plug-In (x-un-i)
#  Version 0.1.0 created: 11 October 2006
#  - initial release (slam, icon by Cathbard)

Search-Plugin for Firefox
---------------------------

Download the file

wget -O ~/.mozilla/firefox/*.default/searchplugins/sidux.xml http://sidux.com/searchplugins/sidux.xml

Restart Firefox and select sidux from the search pull-down menu. After first selection it will become default.

This should work also for other Gecko-Browsers.

#######################################

Search-Plugin for Konqueror
-------------------------------

Download the file

mkdir -p ~/.kde/share/services/searchproviders && wget -O ~/.kde/share/services/searchproviders/kan.desktop http://sidux.com/searchplugins/sid.desktop

Go to Control Center -> Internet & Network -> Web Browser -> Web Shortcuts and activate the "sid" shortcut.

Now open Konqueror, click the Google Icon and select the sidux engine. After that you can always select it from the pull-down menu. After first selection it will become default.


Additional usage in Konqueror:

Simply write the url sid:keyword in the address bar and press enter.


That's it. Have Fun!

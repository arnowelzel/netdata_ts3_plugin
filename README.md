# README #

[NetData](https://github.com/firehol/netdata/) plugin for active users on TeamSpeak 3 servers.


### Installation ###

With default NetData installation copy the ts3.chart.py file to `/usr/libexec/netdata/python.d/`.

Edit the file to set the TeamSpeak Server Query user and password.
If not already set, connect to your TeamSpeak server with the TeamSpeak client and go to menu 'Extras' -> 'ServerQuery Login' and set a user and password.

Then restart NetData to activate the plugin.

To disable the ts3 plugin, edit `/etc/netdata/python.d.conf` and add `ts3: no`.

Optionally add `ts3.conf` to `/etc/netdata/python.d/`


### License ###

Copyright (C) 2016  Jan Arnold

	This program is free software: you can redistribute it and/or modify
	it under the terms of the GNU General Public License as published by
	the Free Software Foundation, either version 3 of the License, or
	(at your option) any later version.

	This program is distributed in the hope that it will be useful,
	but WITHOUT ANY WARRANTY; without even the implied warranty of
	MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
	GNU General Public License for more details.

	You should have received a copy of the GNU General Public License
	along with this program.  If not, see <http://www.gnu.org/licenses/>.

### Version ###

v0.1 - initial release



### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact
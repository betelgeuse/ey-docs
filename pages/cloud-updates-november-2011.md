# Engine Yard Cloud updates November 2011

The updates described are either important (where you need to take action) or of interest (you might want to know about these changes but you don't need to do anything). 

<a href=#update7><h2 id="update7"><b>Major:</b> Engine Yard announces Engine Yard Labs program and Node.js</h2></a>

November 16, 2011

Engine Yard Labs features are experimental features that Engine Yard makes available to developers. Some Labs features might later be incorporated into our product; some might remain as Labs features; and some Labs features might even be tested out and then deprecated.

Node.js is the first Labs feature. 

To try deploying Node.js applications on Engine Yard Cloud, sign up for the Node.js Labs feature [[here|signup-node]]. For information about how to run Node.js applications on Engine Yard Cloud and some example node.js applications, see [[Deploying Node.js applications on Engine Yard Cloud|deploy-node]].

Node.js lets you run JavaScript code in the backend, server-side--not just in a browser. To execute JavaScript in the backend, it needs to be interpreted and executed. This is what Node.js does: it interprets and executes JavaScript; it is a runtime environment and a library.


<a href=#update6><h2 id="update6">Minor: Snapshot messages are now removed from the Environment page</h2></a>

November 15th, 2011

Snapshot status messages are no longer displayed forever on the Environment page. The messages are now removed after 10 minutes.

![Example of a snapshot status message](images/snapshot_status_message.png)

<a href=#update5><h2 id="update5">Minor: Ruby 1.9.2 supports Psych</h2></a>

November 15th, 2011

Ruby 1.9.2 now supports the Psych YAML parser and emitter. Psych can be used as an alternative to the Ruby standard library Syck. 

<a href=#update4><h2 id="update4">Minor: Assorted improvements to the Engine Yard Stack</h2></a>

November 11th, 2011

* Security enhancement: date stamp appended to the command in the shell history. 
 
* Slave database setup modified to prevent problems with replication setup.

* In clustered environments, HAproxy web server error pages can now be customized via HTTP files in /etc/haproxy/errorfiles. This does not include 404 errors or (already customized) 500 errors.

* Increase the maximum length for a connection request queue in Passenger 3 to reduce likelihood of Passenger workers disconnecting from Nginx (and still using resources).

<a href=#update3><h2 id="update3">Minor: Engine Yard product renaming complete</h2></a>

November 2nd, 2011

Engine Yard Cloud is the new name for Engine Yard AppCloud. Engine Yard Managed is the new name for Engine Yard xCloud.

We have completed the renaming. You now see "Engine Yard Cloud" and "Engine Yard Managed" on our product and website ([[www.engineyard.com|http://www.engineyard.com]]) and in our docs ([[docs.engineyard.com|http://docs.engineyard.com]]) and promotional material.

<a href=#update2><h2 id="update2">Minor: Faster MySQL database backups</h2></a>

November 2nd, 2011

To speed up MySQL database backups, the max_allowed_packet size has been increased to 128M.

This change is applied when you upgrade your environment.

<a href=#update1><h2 id="update1">Minor: Debugging script for the Trinidad application server</h2></a>

November 2nd, 2011

For Trinidad, there is now a debugging script to dump information about the Trinidad application server. 
If the Trinidad application server CPU utilization is above 100% for more than 2 minutes, this debugging script is run automatically.

This change is applied when you upgrade your environment.




[1]: #update1        "update1"
[2]: #update2        "update2"
[3]: #update3        "update3"
[4]: #update4        "update4"
[5]: #update5        "update5"
[6]: #update6        "update6"
[7]: #update7        "update7"
[8]: #update8        "update8"
[9]: #update9        "update9"
[10]: #update10        "update10"
[11]: #update11        "update11"
[12]: #update12        "update12"
[13]: #update13        "update13"
[14]: #update14        "update14"
[15]: #update15        "update15"
[16]: #update16        "update16"
[17]: #update17        "update17"
[18]: #update18        "update18"

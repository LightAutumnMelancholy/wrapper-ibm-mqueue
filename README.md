# wrapper-ibm-mqueue
Wrapping some functionality for dealing with IBM mqueue failures, reloading, etc

This was an old script that I wrote back in 2014 that automated reloading from failure
queues and created profiles in the process, I had limited access to install programs where
I wrote this, so I didn't use things like dialog, because no sudo for me [sad sysadmin noises].

If you wanted to use this, you'd need to modify the filep variable for your directory of choice.
Once you have done that, you' call the script, enter those details once, and then it would create
for you a profile to use later on.

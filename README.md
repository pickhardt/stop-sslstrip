stop-sslstrip
=============

Provides a countermeasure to a SSL strip MITM attack.

More Info
---------

SSL stripping is a man-in-the-middle attack that replaces all instances of SSL connections with their non-SSL versioned. See also Moxie Marlinspike's sslstrip Python tool at https://github.com/moxie0/sslstrip and http://www.thoughtcrime.org/software/sslstrip/

This code will help defend a website against a SSL attack. Copy and paste the script tag into your project's head tag. If a man-in-the-middle attempts to replace the "https" with "http", it will be detected, and your visitor safely redirected.

It is expected that hackers may come up with ways to avoid the SSL stripping detection code presented here. This is why it is recommended you make some customizations to the code.

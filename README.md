# Pale Moon web browser

This is the source code for the Pale Moon web browser, an independent
browser derived from Firefox/Mozilla community code. The source tree is
mostly laid out like Mozilla-based products.

# My mods

My intents are among others to compile Pale Moon for the Mac and to 
frustrate access to information that is not obviously the concern of a 
web browser. I also take a hostile position with respect to advertisements.

Blocked APIs:

BatteryManager

Blocked calls:

canvas.toDataUrl

Other:

The default User Agent is set to the empty string, which leads to the 
header not being included. Some sites receive a custom User Agent via 
code from upstream, usually when the site denies access to Pale Moon. In 
that case, the fake string is something indicating a mass-market browser.

I don't care if my mods make the browser "hard to use", throw up "big 
scary warnings" or violates "standards" demanded by the advertising 
industry. If a site rejects the browser because it tries to protect the 
user, the user needs to decide whether he actually wants to visit the 
site, or to use special protective measures.

To build on the Mac, I only needed autoconf-2.13 and yaml. It builds in 
only 10 minutes. Why did we professionals stop building our own software 
again? I've included my .mozconfig. mach build to start the build process.

## Resources

 * [Mozilla Source Code Directory Structure and links to project pages](https://developer.mozilla.org/en/Mozilla_Source_Code_Directory_Structure)
 * [Build Pale Moon for Windows](https://forum.palemoon.org/viewtopic.php?f=19&t=13556)
 * [Build Pale Moon for Linux](https://developer.palemoon.org/Developer_Guide:Build_Instructions/Pale_Moon/Linux)
 * [Pale Moon home page](http://www.palemoon.org/)

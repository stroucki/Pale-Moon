# Pale Moon web browser

This is the source code for the Pale Moon web browser, an independent browser derived from Firefox/Mozilla community code. The source tree is
laid out in a "comm-central" style configuration where only the code specific to Pale Moon is kept in this repository.

The shared Unified XUL Platform source code is referenced here as a git submodule contained in the `platform/` directory and is required to build the application.

## Getting the platform sub-module
`git submodule init && git submodule update`

# My modifications
## Notes

Note where user agent is overridden

## Configuration

Set start pages to about:blank to not start the experience with an ad.

## Other

I don't care if my mods make the browser "hard to use", throw up "big
scary warnings" or violates "standards" demanded by the advertising
industry.

To build on the Mac, I only needed autoconf-2.13 and yasm. It builds in
only 10 minutes. Why did we professionals stop building our own software
again? I've included my .mozconfig. mach build to start the build process.

## Resources

 * [Build Pale Moon for Windows](https://developer.palemoon.org/build/windows/)
 * [Build Pale Moon for Linux](https://developer.palemoon.org/build/linux/)
 * [Pale Moon home page](http://www.palemoon.org/)
 * [Code of Conduct, Contributing, and UXP Coding style](https://repo.palemoon.org/MoonchildProductions/UXP/src/branch/master/docs)

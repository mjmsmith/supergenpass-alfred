# SuperGenPass for Alfred

### Extension

To create the Alfred extension file:

```zip SuperGenPass.alfredextension icon.png *.plist sgp```

### URL/domain argument

If a URL is supplied, subdomains are stripped.

If a domain is supplied, it is used exactly as specified.

If no argument is supplied, the extension tries to get the current URL from Safari.

### Standalone usage

The ```sgp``` script can be used standalone as a command-line script.  For more information:

```./sgp --help```

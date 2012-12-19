# SuperGenPass for Alfred

Copy the working directory into```~/Library/Application\ Support/Alfred/extensions/scripts```and rename it to```SuperGenPass```.

The assumed password length is 10. Edit```PASSWORD_LENGTH```at the top of```sgp```to change it.

If no URL/domain argument is given, it will try to get the current URL from Safari. If a URL is given, it will strip subdomains.  If a domain is given, it will use it exactly as specified.

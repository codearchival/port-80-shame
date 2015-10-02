# Port 80 Shame

This is a list of programs, websites, and email content that behave badly and use insecure HTTP connections over port 80. The developers or powers that be behind these programs should know better in 2015. Use HTTPS.

* For programs, being added to this list generally means that the program attempted to make an insecure outgoing connection without the user's knowledge or beyond their control.
* For websites, this means the site is only served over HTTP or does not redirect to an HTTPS version with HSTS headers when accessed over HTTP.
* For email, this means there was a link to an insecure resource (e.g. an image) that the user's email client is likely to attempt to load under default settings.

## The List

### Programs

Name | Company/Organization | Offending addresses
-----|----------------------|--------------------
Adium | The Adium Team | www.adium.im
AirPort Base Station Agent | Apple, Inc. | apsu.apple.com
Calendar/CalendarAgent | Apple, Inc. | files.apple.com
IMTransferAgent | Apple, Inc. | s3-us-west-2-w.amazonaws.com
Pixelmator (via helpd) | Pixelmator Team | help.pixelmator.com
SpotlightNetHelper | Apple, Inc. | wu-calculator.apple.com
TotalFinder | BinaryAge Software | updates.binaryage.com
com.apple.geod.xpc | Apple, Inc. | gsp1.apple.com
com.bourgeoisbits.cloak.cloakproxyd | Bourgeois Bits, LLC | redirect.getcloak.com
fpsaud | Adobe | fpdownload2.macromedia.com
nsurlsessiond | Apple, Inc. | blobstore-002.icloud.com, gcs-us-00001.storage.googleapis.com
storedownloadd | Apple, Inc. | \*.phobos.apple.com

### Websites

Name | Company/Organization | Offending addresses
-----|----------------------|--------------------
Disqus | Disqus | disqus.com
L.A. Times | The L.A. Times | www.latimes.com
New York Times | The New York Times | {a1,s1}.nyt.com, {json8,typeface,graphics8,www}.nytimes.com
Pixelmator | Pixelmator Team | www.pixelmator.com
gstatic.com | Google, Inc. | www.gstatic.com
malwaredomainlist.com | Unknown | [www.]malwaredomainlist.com
malwaredomains.lehigh.edu | Unknown | malwaredomains.lehigh.edu
pgl.yoyo.org | Unknown | pgl.yoyo.org

### Email

Purpose of email | Company/Organization | Offending addresses
-----------------|----------------------|--------------------
Trip receipt | Uber, Inc. | static.s3.amazonaws.com

## License

[Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/)

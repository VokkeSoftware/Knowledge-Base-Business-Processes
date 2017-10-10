# Extracting assets from the client

## Introduction
For projects to complete successfully we sometimes need resources from the client. These may be design guides, logos, or technical items such as the latest password to their Mailchimp account. Collectively these are called "assets".

## Timeliness of assets
A project doesn't need all assets right from the start of development. Often this isn't even possible because the client can take ages to find them. As such, it's important to identify when each asset is needed so that it's available for when it needs to be used.

## Asset extraction list for Wordpress websites

### Design guide
A design guide is a PDF or website link that shows what styles should be used, such as the fonts, colors and padding. 

### Fonts
The design guide usually stipulates what fonts to use but rarely, if ever, supply the font file itself. We cannot use a font just by knowing its name, and most of the time fonts cost, so it's important to check the design guide and ensure that either the font is already on your computer (open up Word to test this) or that you have the actual font file. The extension of the file is usually TTF or WOFF.

### Logos
The design guide usually has the logo within it, but it needs to be supplied in a specific format for best resolution. Ideally the logo would come in SVG format, but if that's not present, a PNG, BMP will suffice. JPEG or PDF are the worst form but can be used if absolutely necessary.

### Live service accounts
If we are integrating a website into a 3rd party service, such as Mailchimp, it's important to check with the client to see if they already have an account we should use. It's important to test the login details to ensure they're correct, too. About 1/5 times they're wrong.

### Social media links
Often we have social media sharing links on the website, but we cannot identify the actual URL of their social media page (often it's not present on their old site). If we have social media links, the URL of the social media page must be obtained.

### DNS details
If we are hosting the site, we will need the DNS details. The concept isn't too difficult once you get it, but getting the wrong details can delay a deployment by _weeks_ (worst case) so it's important to set it up right. If the details are wrong, the deployment process may also knock their email system, VoIP and Office 365 offline. So we have a test process to ensure we have the right ones (tbw)

Recommended reading: https://www.digitalocean.com/community/tutorials/an-introduction-to-dns-terminology-components-and-concepts







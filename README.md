Fork of mrd0x BITB technique. Will add Templates for popular services 

Origional Readme below:

# BITB
Browser templates for Browser In The Browser (BITB) attack.

More information: https://mrd0x.com/browser-in-the-browser-phishing-attack/ 

# Usage

Each folder has a `index.html` file which has 4 variables that must be modified:

* **XX-TITLE-XX** - The title that shows up for the page (e.g. Sign in to your account now)
* **XX-DOMAIN-NAME-XX** - Domain name you're masquerading as. (e.g. gmail.com)
* **XX-DOMAIN-PATH-XX** - Domain path (e.g. /auth/google/login)
* **XX-PHISHING-LINK-XX** - Phishing link which will be embedded into the iFrame (e.g. https://example.com)

Furthermore, if you're using a Windows template you should update the `logo.svg` which is the icon of the website you're masquerading as. The default logo is Microsoft.

# Demo

![Demo](https://github.com/mrd0x/BITB/blob/main/demo.gif)

# Final Thoughts

To get the most out of this you should determine the OS from the user agent and the color preference and display the appropriate template.

To find out if you should use dark or light templates check out: https://stackoverflow.com/questions/50840168/how-to-detect-if-the-os-is-in-dark-mode-in-browsers

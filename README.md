# Material Incognito Dark Theme
A theme that adds the dark Incognito Mode colour scheme to the normal mode of Chrome.

**Windows 10 users - please go to chrome://flags, scroll down to Custom-drawn Windows 10 Titlebar and press Enable. This will enable titlebar colour.**

Incognito mode currently uses a dark colour scheme to distinguish it from normal mode. This theme imitates that colour scheme and applies it throughout the whole browser.

### Installation
Install the theme from the Chrome Web Store [here](https://chrome.google.com/webstore/detail/material-incognito-dark-t/ahifcnpnjgbadkjdhagpfjfkmlapfoel).

### Github
This theme is fully open-source under the Apache License. Check out the source code on [Github](https://github.com/Fiddle-N/material-incognito-dark-theme/).

### Limitations
All elements of the official Incognito mode dark colour scheme have been ported over where possible. Unfortunately, Chrome bugs and limitations mean that I can't reproduce it with 100% full-fidelity. These are as follows:

1. The URL bar cannot be coloured and must stay white. 

Chrome theme devs currently have no ability to colour the address bar.

2. The bookmark bar colour is a lighter grey when compared to the official Incognito mode dark colour scheme. 

This is for a couple of reasons. Firstly, choosing a darker colour messes up the Incognito mode guy colour in the top left corner. Secondly, the colours of the bookmark bar, the download bar and the status bar that appears when hovering over a link are tied to each other. The status bar colour is currently accurate, but the bookmark bar colour cannot be made accurate without making the status bar colour inaccurate and vice versa. This catch-22 situation is why the bookmark bar colour is currently inaccurate.


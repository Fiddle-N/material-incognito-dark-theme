# Material Incognito Dark Theme
A theme that adds the dark Incognito Mode colour scheme to the normal mode of Chrome.

**Windows 10 users - please go to chrome://flags, scroll down to Custom-drawn Windows 10 Titlebar and press Enable. This will enable titlebar colour.**

With the release of Material Design in Google Chrome, Incognito mode uses a dark colour scheme to distinguish it from normal mode. This theme imitates that colour scheme and applies it throughout the whole browser.

Please leave comments about my theme if you wish; I enjoy seeing feedback.

For users that wish to have the normal mode light colour scheme be applied throughout the whole browser instead, please install Material Incognito Light Theme.

### Github
This theme is fully open-source under the Apache License! Check out the source code on [Github](https://github.com/Fiddle-N/material-incognito-dark-theme/).

### Limitations
All elements of the official Incognito mode dark colour scheme have been ported over where possible. Unfortunately, Chrome bugs and limitations mean that I can't reproduce it with 100% full-fidelity. These are as follows:

1. The URL bar cannot be coloured and must stay white. 

You can use the [Penumbra theme](https://scope10.deviantart.com/art/Penumbra-10-Windows-10-visual-style-568740374), which provides a system-wide dark theme on Windows.

![Penumbra](https://i.imgur.com/C2emXHk.png)

~~I could rectify this for Windows users by using Stardock's WindowBlinds software, but this would cost me $10 to develop the solution and $10 for every person that wants to use it. If enough people ask for this in the comments, I will follow through and develop a solution, but otherwise it's a waste of money for all involved.~~

2. The bookmark bar colour is a lighter grey when compared to the official Incognito mode dark colour scheme. 

This is for a few reasons. Firstly, choosing a darker colour messes up the Incognito mode guy colour in the top left corner. Secondly, the colours of the bookmark bar, the download bar and the status bar that appears when hovering over a link are tied to each other. The status bar colour is currently accurate, but the bookmark bar colour cannot be made accurate without making the status bar colour inaccurate and vice versa. This catch-22 situation is why the bookmark bar colour is currently inaccurate.

3. There is a upper white line between the URL bar row and bookmark bar. 

~~I cannot do anything about this white line; to speed up its removal, please star this issue here: https://bugs.chromium.org/p/chromium/issues/detail?id=628312 .~~
This is no longer an issue in Chrome 61. Thank you Google and all the people who raised/starred this issue!

4. There is a lower white line underneath the bookmark bar. 

~~In theory, I can remove this line; in practice, I cannot. The colour of this line is tied to the bookmark bar text colour. If the bookmark bar text is white, then so too is that line. If the bookmark bar text is black, then that line will be black as well and will fade into the background, but the bookmark bar text itself will be unreadable. This catch-22 situation is why this line must stay white. If someone opens up a Chromium bug tracker entry to allow these two elements to be set independently, I will star the entry and link to it here.~~
This is no longer an issue in Chrome 61. Thank you Google and all the people who raised/starred this issue!

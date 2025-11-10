# VS Code Extensions downloader
A utility for a manual Visual Studio Code extensions download.

Visual Studio Code [download](https://code.visualstudio.com/download) - this is the IDE;

Visual Studio Code [marketplace](https://marketplace.visualstudio.com/VSCode) - here you can find the desired extensions.

# Description
Visual Studio Code often bugs out and doesn't allow installing extensions from the IDE.

It is a well known issue for some people; while some of them (us) see an error message, the others may see a "never ending" downloading process.

**It has nothing to do with the geo-location of the end-user** and is **not the result of regional blocking**.

Also, some people may want to simply download the extensions manually and store them somewhere on their hard drive.

While VS Code has a web-site available for browsing, this web-site does not allow to download extensions (there is only an `Install` button that opens the VS Code IDE, but no `Download` button).

Meanwhile, Microsoft has a **publicly accessible** API (without the need of any API key) that allows to download the `.vsix` files manually.

So, here is a simple `.html` page that can be opened in any browser, and it provides a convenient way to use this HTTP endpoint.

# How to

- Open the `index.html` in your browser (double click).
- Fill-in the information about the desired extension (can be found on the web-site or inside the IDE application).
- Click `Download`.
- Inside the IDE in the 'Extensions' window, click 'three dots' (at top) and choose `Install from VSIX...`.

# Screenshots

Extension details inside the IDE:

<img width="1004" height="642" alt="image" src="https://github.com/user-attachments/assets/4e8f8dc0-4952-4ea0-a21f-4215ad4f12f5" />

This utility `.html` page with the same extension in placeholders (these are just **placeholders**, i.e. an example of text; you have to type everything by yourself):

<img width="841" height="565" alt="image" src="https://github.com/user-attachments/assets/29702aca-1c6e-4211-953a-a77113570110" />

_(my browser automatically applies the dark theme; by default this page is white)_

# Post Scriptum

The author of this utility (me) does not have any sort of relation to the Visual Studio Code developer team or its publishers; neither I have any relation to the other developers of the extensions.

You should use this utility only in legal ways that are not forbidden by any means. For example, changing the `.vsix` file and/or distributing it without the agreement of the original developer
does not seem very legal to me.

If someone has any questions about the utility or has any discontent about its existense, they can contact me through my GitHub profile or e-mail `moonlight9512@gmail.com` (the e-mail is also mentioned in the profile).


# SearchGTP Chome Extension / Firefox Addon

This is the smallest footprint Chrome Extension / Firefox Addon (the same manigest.json works on both) for adding ChatGPT's search to Firefox as a search provider. By doing so, you are able to optionally make it your default search provider.

## Installation

Because you are grabbing this from GitHub, you are not getting a nicely signed first class Firefox Addon. As someone looking for this on GitHub, I am making the assumption you understand that you are loading this locally, and are just happy to have this, as I was when ChatGPT helped me put this together (which is why the license is MIT by the way - have fun with this).

### Chrome

In Google Chrome, Chromium or Canary, enter `chrome://extensions` into your address bar. On the top, make sure the toggle for "Developer Mode" is on. Then, press the button "Load Unpacked". Choose the entire directory, and the plugin should load. You can confirm by checking the list of extensions for "ChatGTP Default Search".

To make it the default search engine, go to your `chrome://settings` > Search, and select ChatGTP as your default search engine.

### Firefox

In Firefox, enter `about:debugging` into your address bar. Then, on the sidebar, click "This Firefox". Under "Temporary Addons" is a button labeled "Load Temporary Addon". Navigate to the directory, and select the manifest.json directly.

Now, go to your Firefox Settings > Search, and you will see "ChatGPT" as a Search Provider. From here, you can make it your default search provider.

## Warranties

None, this is a simple json file. I make no claims that chatgpt is secure, nor that it isn't owned by aliens or other species predatory to mankind. This is simply some wiring I found useful and I share hoping you find the same.


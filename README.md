# Mit App Inventor Browser

A simple web browser created through MIT App Inventor. Designed for Chromebooks.

# Features

- Up to 10 tabs
- Search through several search engines
- Desktop mode. Other similar App Inventor browsers load pages like a phone or tablet, this loads the desktop version.
- Settings
- Supports direct URL input, with or without "http://" in front
- A lot faster than Chrome

# Guide for Use - Chromebook

Documentation is still a work in progress.

### Step 1: Install required programs

First, you will need to install MIT App Inventor Compainion. Don't worry, it's super easy. All you need to do is open Play Store on your Chromebook. Scroll down or search for MIT Ai2 Companion and click install. It should be a pretty quick install as it is fairly small.

That's it for the installation!

### Step 2: Set up App Inventor

Open Chrome on your chromebook and navigate to this [url (ai2.appinventor.mit.edu)](http://ai2.appinventor.mit.edu/). There might be a "Welcome to App Inventor" popup, which you can dismiss. You should be then taken to the home page.
Download the latest `.aia` file from above. Click on `Projects > Import project (.aia) from my computer`. Then navigate to and select the file you just downloaded. Click `OK`.
> Note: Chrombooks are not very powerful and it might take a while for the project to load and open. Be sure to be patient.

### Step 3: Launch!

The project should open automatically. If it doesn't, click on its name in the projects list. You should be presented with a screen with a phone and the UI. 
> Note: This is not what the UI will actually look like when you launch the project. App Inventor's preview is not very accurate.

Click on `Connect > Chromebook`. You may get a dialog asking you if you would like to open in "App Inventor" or similar. Select Yes. The Companion application you downloaded previously from Google Play should launch. After 10-20 seconds the browser will load and you can begin using it.
> Note: The browser itself is quite fast especially considering it is on a chromebook. However, the initial loading time can take a little, please be patient.

### Relaunching if already set up

If you have already completed the [steps above](#guide-for-use---chromebook) and would like to launch the browser, follow these steps.

Go to the same [App Inventor URL](http://ai2.appinventor.mit.edu/) you used before. Click on the project, it should be titled something like Basic_Web_Browser. Then, at the top, click on `Connect > Chromebook`. The companion application should launch and after 10-20 seconds the browser will load. You can now start browsing the web!

# FAQs and Troubleshooting

- My Companion application didn't launch. Try: 
  - Checking to see if the companion is installed
  - Opening the Companion manually to see if it will work
  - Uninstalling and reinstalling the companion
- My Companion launched but the browser doesn't load. Try:
  - Waiting 10-20 more seconds, chromebooks can be quite slow at this step
  - Quitting the companion and trying `Connect > Chromebook` again
- My Companion keeps crashing randomly. Try:
  - Quitting the companion and trying `Connect > Chromebook` again
  - Closing out of tabs and applications. Chromebooks lack power and for some reason prioritize other things over the companion; this can result in crashes and/or overall slowness
  - Restarting/Powerwashing your Chromebook
  - Filling out a bug report under the Issues tab along with **specific instructions on how to replicate the crash.**
 
 **If you find a bug or would like to suggest a feature, go to the Issues tab. Please be specific about how an issue occured or what a feature should do.**
 
 ### Features Currently in Development
 #### Checked if in beta
 
 - [X] Add more search engine options
 - [ ] Options for changing the network or adding a proxy
 - [ ] Dedicated New Tab rather than opening search engine
 - [ ] Bookmarks
 - [ ] Recover closed tab
 - [ ] Settings saved after closing and re-opening
 - [ ] Color themes
 
 # Credits
 Thanks to Sunny Gupta for his `CustomWebView` extension that makes certain features in this browser possible.

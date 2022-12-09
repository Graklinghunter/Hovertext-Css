# Hovertext-Css
Custom CSS for use with Sidebery 5. This maximizes vertical real-estate in your browser by migrating the tabs to a dynamic sidebar and hiding everything else that normally sits above the URL bar. It also capitalizes on Sidebery's flexibility to create a more robust browsing experience by allowing you to organize your tabs into categorized panels.

Sample image:
![alt text](https://i.imgur.com/VcuTwih.png)

Image Album:
https://imgur.com/a/lP9cSgg

How to Install/Configure:

Step 1: Ensure you have your userChrome.css file and folderpath created properly. You don't need anything in the file, you just need it to exist. You also don't need any other .css files in the folderpath. See this article for information about finding the path and setting it up: https://www.howtogeek.com/334716/how-to-customize-firefoxs-user-interface-with-userchrome.css/

(Note that you will need to open about:config and enable the pref toolkit.legacyUserProfileCustomizations.stylesheets in order for the .css file to do anything)

Step 2: Install the Sidebery v5 beta. https://github.com/mbnuqw/sidebery

Step 3: Open Sidebery Settings and navigate to the bottom of the main Page. Select Import Addon Data and import my Sidebery .json file. This will come with my personal Panel configurations - you should navigate up to the "Navigation Bar" settings and add/remove/change the Panels as you see fit.

Step 4: In Sidebery Settings navigate to the Styles Editor. In the right Sidebar, paste in the content of my Sidebery CSS file

Step 5: Copy the text of my userChrome.css into your userChrome.css file and save it

Step 6: Restart firefox

Step 7: Right click the top toolbar and select Customize Toolbar. Arrange the elements like in my screenshots or make it different, as your taste suits you. Just make sure there's a Flexible Space item in there so that there's room for you to grab and drag the window - I have mine between the URL bar and the Extension icons.

From there, you can make adjustments to Sidebery Settings as necessary, or open the userChrome.css and adjust pixel dimensions.


Note: I don't actually know much about CSS editing - I achieved these results through trial and error and observing others' CSS files. What you see is basically a mish-mash of ideas from various other projects, tweaked and tuned to my style and preference. I've very likely missed accounting for some browser element/configuration you would want simply because I don't use my browser that way. Feel free to comment on things you notice are broken, though I can't promise I'll know how to fix it.

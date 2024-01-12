***Yes. I do have 2 different config files for firefox, one is for my laptop, second one is for my computer.***

# Screenshots
Desktop
![desktop](https://github.com/zxxtlz/firefox/blob/main/screenshots/desktop.png?raw=true)
Laptop
![laptop](https://github.com/zxxtlz/firefox/blob/main/screenshots/laptop1.png?raw=true)

# firefox guide
![Custom_Firefox_css](https://github.com/zxxtlz/firefox/assets/75642081/83c40da7-b45e-4dba-9dbb-c212ad3ec985)

Before we start the download

Make sure you go to your firefox config by typing in the url bar

    about:config

After that, you need to type in the search

    toolkit.legacyUserProfileCustomizations.stylesheets 

And make sure that that setting is set to "true". So we can actually customize the firefox css

If you are on linux
Make sure you have Git installed

VVV

- Go to your mozilla folder, (will probably be in the home directory called .mozzila)

- Go into firefox folder

- Go into your Firefox Profile Folder and type
```sh
git clone https://github.com/zxxtlz/firefox
```

Open the folder named "firefox" (the one you just cloned)

put "chrome" into your profile folder and do the same with "user.js"

!!! If you encouter problem where your browser text at the top is black (unreadlabe), you need to go into settings and change it from white theme to dark theme

__________________________________


If you are on Windows

VVV

- install the repo

- type in your firefox search bar about:profiles

- Make a new profile

- Look at where it says "Root Directory" press the button where it says open folder to the right.

- Open the folder you downloaded, and put "chrome" into your profile folder and do the same with "user.js"

!!! If you encouter problem where your browser text at the top is black (unreadlabe), you need to go into settings and change it from white theme to dark theme

# Plugins

Here are some plugins that make my life all that much better
- Undisposition // stops links from automatically downloading stuff, (example: whenever you click on a discord video link, it wont download but instead it will act as a normal video in your browser that you can watch)
- Clipboard2File // instead of having to download images, you can just place images from your clipboard
- Ublock Origin // adblocker

# Credits

- Laptop css - https://github.com/andreasgrafen/cascade
- Desktop css (slightly edited version by me) - https://github.com/eduardhojbota/moonlight-userChrome
- Desktop css Bookmarks - https://github.com/datguypiko/Firefox-Mod-Blur/tree/master/EXTRA%20MODS/Compact%20extensions%20menu

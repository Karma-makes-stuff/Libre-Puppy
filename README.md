# 🐶 What is LibrePuppy? #

LibrePuppy is a pre-made profile for LibreWolf.
It aims to provide a light weight "just works" browsing experience.
LibrePuppy consists of changes to the default settings and a select few browser extensions.

# 🐕 Why use LibrePuppy? #

Even though LibreWolf does many things right, which is why I consider it one of the better browsers out there, it has some questionable presets that really hurt the user experence.

For example, dark mode is locked behind disabling ResistFingerprinting. 
In my opinion, a browser without dark mode is unusable.
Locking this cruicial option behind outright **disabeling an important privacy feature** really makes you think the devs hate their userbase.

There are some other issues I have with the defaults, but none come close to this.

Besides fixing the defaults, LibrePuppy comes with what I consider to be the most essential extensions for a privacy conscious person and some quality of life.

# How do I install LibrePuppy? #

-to be updated

# 🔍 The details #

This is where I list the features of LibrePuppy and the reasoning behind them. 
Mostly, this is taken from my personal setup.

I'll also list some suggestions on some options and extensions that didn't quite make the cut.

If you don't feel like making a new browser profile, you can always just copy my setup by hand.

## ⚙️ Settings ##

### Dark mode ###

For hopefully obvious reasons I have enabled dark mode. To do this, you have to disable ResistFingerprinting, which is why I've also included addons to reduce tracking as much as possible. More on that later tho.

I've also chosen not to include the Dark Reader extension since most sites already respect the browser theme. 

### Prompt to translate pages that aren’t in the browser’s configured language ###

I've chosen to disable this option since I'm multilingual and I find the popup annoying.
I also forgot to remove German from the list of languages to never translate and I'm too lazy to make a new release just for this, so you might want to clear that if you want to use the translation feature.

### Play DRM-controlled content ###

I've enabled this option since I figured most people probably don't care about DRM. This is mostly personal preferance.

### New Windows and Tabs ###

Since LibreWolf doesn't let you set a wallpaper, I've chosen mtab to fix this. More on mtab in the extensions section.

### Delete cookies and site data when LibreWolf is closed ###

I've purposefully left this on, but I personally have exceptions. Basically if you want to stay logged in on a site, you need to set it as an exception here. 

If you don't care about carrying around cookies for years, you can disable this option, but I wouldn't recommend it.

### Allow userChrome.css customization ###

Even though LibrePuppy doesn't use it, I chose to enable it, since your setup might rely on this feature.

## 🧩 Extensions ##

### 🕵️ privacy ###

Privacy Badger, Decentraleyes and CanvasBlocker all help to reduce tracking/fingerprinting. Not much to say here.

### 🔐 Bitwarden ###

Bitwarden is a password manager. If you already have another one, feel free to uninstall Bitwarden, but please please use a password manager!

I've chosen Bitwarden since it's easy to use and works well. The free version should be enough for most people.

### 🚫 NoScript ###

NoScript is a powerful JavaScript blocker. Many trackers and fingerprinters use JavaScript. 

However, JavaScript is also required by most sites to function. You'll need to manually unblock the scripts. 
Since this can be a frustrating experience, LibrePuppy comes preconfigured with my personal NoScript configuration. This should allow you to frictionlessly browse many popular sites.

If you still want to choose convenience over privacy, you can uninstall NoSricpt at any time.

### 🌴 mtab ###

mtab is used to customize the appearanc of your start page. In the bottom right you can customize the settings to your liking in a user friendly interface.

LibrePuppy comes with a finished mtab configuration, but you can easily customize it to suit your preferences.

By default, your startpage will show the first 8 bookmarks of your Other Bookmarks folder.

### 👎 Return YouTube Dislike ###

Closing out this list, we're bringing back the dislike button to YouTube. Not much to say here; they should've never removed in the first place.

## ❓ Why not X ❓ ##

### Sponsor block ###

Beacuse some YouTubers put a lot of effort into the sponsored segments so they're fun to watch even if you don't care about the product.

### Dark Reader ###

As explained above, it's mostly redundant with dark mode. 

### others ###

Because I want to keep LibrePuppy small and light weight.

If you have any additions, feel free to open an issue.

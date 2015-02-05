Themeing Stock Applications (Across all iDevices) Version 2.0 (For iOS 8.x)
***

This package has been compiled to make your job as a theme developer easier. If you develop a theme, you are guaranteed at least two things: 1) Icon Requests and 2) Please support *Insert Device your theme does not support here!* 

You're on your own making more icons and supporting more apps with your theme, but this package aims to make it as easy as possible to support all iDevices out there with your theme. It is easy to support apps from the App Store on all iOS devices, because all the icons needed for the App to run on each of the various screen resolutions Apple supports are included in the App's IPA file. (That way Apple dosnt have to host 4 different versions of each App out there on the store- its a one size fits all solution.) This is good news, because it means you will easily be able to support 99% of all apps out there on all iDevices with just a little extra effort on your part. (Theme all sizes of the App's icon in the App's original IPA package, keeping the same filenames, and you're all good.)

Stock applications (Pre-installed applications which are installed on your device when you purchase it) don't work like this though. Why? Well, because Apple is special. Their apps (With a few exceptions, its quite inconsistent really, as I've discovered while compiling this package) only include the icons needed for the App to run on the device on which it is installed. This makes it difficult to build your theme with support for all various iDevices out there, unless you own a device of each of the various resolution criterion to find the correct icon names and sizes on. (Which most people do not.)

In the past, the only way to get around this was to download a theme someone else has previously released, and build your theme using this other theme as a template. This method works just fine, but it can be difficult to find a theme which supports all devices in the first place to do this with. (And you have to hope the person who developed this original theme packaged everything correctly, which was not the case in my attempts- Icons were always missing here and there.)

So, what to do? Well, as you can see here (http://www.reddit.com/r/iOSthemes/comments/2qb69d/i_built_this_theme_development_resource_for_us/) I had the fine people of /r/iOSthemes hit me up with some download links of their /Applications/ folder located at /var/stash/applications as well as a couple other necessary files. ( /Applications/ is where all your stock apps are stored.) With a /Applications/ folder in hand for each of the various iDevice resolutions I needed-  I complied all the various icons for stock apps at all various resolutions into bundle for all to use right here! 

Conceptually, this is the same as using someone else’s theme as a template- only this is not a "theme" per se (Though it is bundled in the same Winterboard Theme format, in addition to an Icon Bundles version), it is made up entirely of the original icons of all the different devices compiled into one place.

The goal is to use this bundle as a "starting point" for your theme. After you have replaced each icon in this bundle with your own, your theme will be off to a great start. It will support each stock application on all devices, and then you can move on from there to supporting third party apps!:)

***

Included in this bundle are the following:

1) "ReadME.txt": The ReadME text file your reading right now. Duh. (Its also a duplicate of the Release Post on /r/iOSthemes for this package.)

2) "Stock Apps.theme.zip": (A zip file of the "Stock Apps.theme" template theme I have described above, to be used as a starting point for new theme developers. Alternately, it can be used to double check that your existing theme will run properly on all iOS devices— after today, hopefully many, many more themes will work universally.)

3) "Stock Apps.txt": A text file containing the BundleID's and icons names/sizes for each of the stock apps across iDevices. (If you prefer using a list for some reason as opposed to the Winterboard Template theme I have included)
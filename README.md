# Suave7 - Theme Developer Kit

**Hello Friends,**

after so many Updates of Suave7 we would like to share the Love from this amazing Theme with you. Our Goal is not to change only some Icons, we would like going into the Deep&nbsp;: We change the User Interface&nbsp;(&nbsp;UI&nbsp;) from App-Store-Apps, as will as a lot of Images from iOS.

<p align="center"><img src="https://repo.avalon-studios.de/developer/TDK_Header.png" /></p>

So we can say&nbsp;: Suave7 is not only a Theme. It's true Love for iOS.


## Table of Contents

1.	[Sharing the Love](#1-sharing-the-love)
2.	[Requirements](#2-requirements)
3.	[Contents](#3-contents)
4.	[Creating Icons](#4-creating-icons)
5.	[Other noteable Templates](#5-other-noteable-templates)
6.	[Last Words](#6-last-words)
7.	[Greetings](#7-greetings)


## 1. Sharing the Love

This Developer Kit allows you to create new Icons and change the UI-Images from Apps and the entirely iOS based on the Design of Suave7. We would like to share the Love with you&nbsp;: The Themers all over the World. This is what makes Suave7 so beautiful&nbsp;…


## 2. Requirements

If you would like to use this TDK, the first Application you need is [Adobe Photoshop](https://www.adobe.com/de/products/photoshop.html). With Photoshop you can use most of the Templates, but some other Templates and Masks can only be used if you own a Mac and bought the Application [Pixelmator](https://itunes.apple.com/de/app/pixelmator/id407963104?mt=12) from the Mac App Store.

Some Templates require the Font "Myriad Pro", you can get them from [Adobe TypeKit](https://typekit.com/fonts/myriad). You can also sync these Font by opening a Template with Photoshop too.

The last Thing you need is Patience.


## 3. Contents

The TDK currently contains the following Folders&nbsp;:

-  **Defaults**

	These Templates are obsolete. We've added it, because you can use them for some Apps on iOS 7. With iOS 8, Apple introduced a new Way loading Apps : Dynamic Loading Screens, so we can't theme the "Defaults" anymore.

-  **Icons**

	This is the Heart of Suave7. This Folder currently contains more than 5.600 Icons in different Subfolders - categorized by their Creator.

-  **UI&nbsp;(&nbsp;Cydia-Tweaks&nbsp;)**

	The Templates and Masks in this Folder were used for changing the Icons and UI-Images from various Cydia-Tweaks, like Activator, Convergance or Cydia self.

-  **UI&nbsp;(&nbsp;iOS-Apps&nbsp;)**

	If you would like to change the UI from iOS itself, you need the Templates and Masks in this Folder. We've added some Templates for iOS 7 too - like the Calculator, but most of them can be used to theme iOS 9 and above.

-  **UI&nbsp;(&nbsp;iTunes-Apps&nbsp;)**

	This Folder contains all necessary Templates to theme Apps from the App Store, which can be used for other Apps too. The Templates for Facebook Messenger, Twitter and Shazam needs to be updated, to match with the latest UI-Images.

… and the following Photoshop-Templates&nbsp;:

- **Icons&nbsp;(&nbsp;Aeneon, System&nbsp;)**

	The new Template for creating Icons. I've optimized some Things and reduced the Groups and Layers in the Template.

- **Icons&nbsp;(&nbsp;Aeneon, Messages&nbsp;)**

	Based on the new Template, this Template allows you to create Icons for the iMessage Store.

- **Icons&nbsp;(&nbsp;Aeneon, Watch, 120 Pixel&nbsp;)&nbsp;& Icons&nbsp;(&nbsp;Aeneon, Watch, 196 Pixel&nbsp;)**

	Based on the new Template, these Templates allowing you to create Icons for the Apple Watch.

- **Icons&nbsp;(&nbsp;Pat 97.4, System&nbsp;)**

	The classic Template created and used by Pat 97.4 from the good old MacThemes-Forum.


## 4. Creating Icons

How do you create Icons&nbsp;? It's very simple with our small How-To&nbsp;:

1.	Search for the Bundle-ID and the iTunes-Artwork with OffCorner's "[Bundle Id Finder](http://offcornerdev.com/bundleid.html)". If you've got your App, click on the Image showing the iTunes-Artwork and save the Image.

	**Pro Tip&nbsp;:** If you need a High-Res-Image, you can alter the Address of this Artwork by replacing the "512x512" to "1024x1024" at the End of this URL.

	<p align="center"><img src="https://repo.avalon-studios.de/developer/TDK_Creation_HighResArtwork.png" /></p>

	**Note&nbsp;:** Don't close the "Bundle Id Finder" Tab, we need it for the Bundle ID later.

2.	Choose a Template&nbsp;(&nbsp;we will use the new Template for this&nbsp;) and open the downloaded iTunes-Artwork in Photoshop.

3.	Do some Magic&nbsp;…

	<p align="center"><img src="https://repo.avalon-studios.de/developer/TDK_Creation_TheMagic.png" /></p>

4.	Back in our "Bundle Id Finder", copy the "BundleIdentifier", by clicking the second Line&nbsp;…

	<p align="center"><img src="https://repo.avalon-studios.de/developer/TDK_Creation_BundleIdentifier.png" /></p>

5.	And now it's time for saving our newly created Image in Photoshop. Hit "Save as" from the Menu and save the Image as PNG, don't forget to use the copied Bundle-ID as Name and then add a "@2x" *after* this. We need this for all Retina-Devices, like the iPhone 6S, so iOS can choose the correct Image for the corresponding Device-Resolution.

	<p align="center"><img src="https://repo.avalon-studios.de/developer/TDK_Creation_SaveTheMagic.png" /></p>

6.	Now you can close the Template&nbsp;- but we're not at the End !

7.	We need two additional Icons for the App Switcher and Spotlight&nbsp;…

8.	Open up the created Image and reduce the Size of the *Working Area*&nbsp;(&nbsp;not the Image Size&nbsp;!&nbsp;) to 114 x 114 Pixels. The Image should be centered horizontally and vertically.

9.	Now reduce the *Image Size*&nbsp;(&nbsp;not the Working Area&nbsp;) to 80 x 80 Pixels and save the Image with the Addition of "-40" before the "@2x" in the Name.

10.	Do the same with the *Image Size* of 58 x 58 Pixels and the Addition of "-29".

11.	Now you can close Photoshop and enjoy your Icon on your iDevice too&nbsp;😊&nbsp;…


## 5. Other noteable Templates

Additionally to the Templates for the Icons, this TDK contains some other important Templates, to achieve the Suave7-Design&nbsp;:

-  **"Activator&nbsp;(&nbsp;Listeners&nbsp;)" in "UI&nbsp;(&nbsp;Cydia-Tweaks&nbsp;)"**

	This Template is necessary for changing the Listener-Icons in Activator. The Icons made with this Template needs to be resized to 58 x 58 Pixels to show up correctly in Activator.

-  **"Cydia&nbsp;(&nbsp;Sections&nbsp;)" in "UI&nbsp;(&nbsp;Cydia-Tweaks&nbsp;)"**

	This Template is necessary for changing the Sections-Icons in Cydia. There is *no resizing* needed to showing up these Icons in Cydia.

-  **"Button States" in "UI&nbsp;(&nbsp;iOS-Apps&nbsp;)"**

	If you create an UI for an App, this Template is used for all Button States. You can change the Buttons by copying the Style of the Layer. It's possible to alter the Colors for the "Activated"-State by changing Gradients *Hue* to a matching Degree from Colors of the Icon Template.


## 6. Last Words

That's it ! We hope you have Fun with our Theme Developer Kit and you will share the Love with Suave7. If you would like to contribute to this Project, let us know.

If you respect our hard Work, you can help us with a small Donation via [PayPal.me](https://paypal.me/avalonstudios)&nbsp;😃&nbsp;…


## 7. Greetings

We would like to greet all former Members of MacThemes, who had worked on Suave and Suave HD. This Step in the History of Suave won't be possible with your hard Work.

Thank you.

*Thyraz* for Suave Classic. *Pat 97.4* for Suave HD and the Icons you made. *D4RKL0RD198* for Suave HD on iOS 6. *Bli625*, *bwhli*, *DWALLS90*, *Finkle316*, *maxims*, *nienque*, *The Raptor* and *Tundra13* for all the other Icons.
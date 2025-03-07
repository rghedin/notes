---
layout: post
title: "What's the deal with SafetyCore, the weird app that suddenly appeared on Android?"
date: 2025-03-07 06:42 -0300
---
Does your phone run Android? If so, you might have noticed a new app called SafetyCore. Announced by Google [in October 2024](https://security.googleblog.com/2024/10/5-new-protections-on-google-messages.html), the company has been rolling it out recently (at least here, in Brazil).

SafetyCore is designed for devices running Android 9 or later, takes up about 2&nbsp;GB of storage, and according to Google “provides common infrastructure that apps can use to protect users from unwanted content.” [The documentation](https://support.google.com/product-documentation/answer/16001929) also notes that “the classification of content runs exclusively on your device and the results aren’t shared with Google.”

Almost no one reads these docs or even warnings, alerts of an app. What definitely catches your eye is a new icon among your apps that [seems to appear overnight](https://www.forbes.com/sites/zakdoffman/2025/02/28/google-starts-scanning-your-photos-without-any-warning/). Is SafetyCore something to worry about?

[It’s published on the Play Store](https://play.google.com/store/apps/details?id=com.google.android.safetycore) and, like any other app over there, it gets ratings and comments. Its average rating is 3.5, with the highest (5) receiving the most votes overall and the lowest (1) not being insignificant in number. One standout negative comment sums up the problem (in Portuguese, here translated):

>“The app installed on its own and when I tried to open it, it just showed the app info. I’m not sure if it’s legitimate or not, and that worries me and many other consumers, breaking our trust in the security of the operating system. A quick question: if the app is legitimate, is it supposed to have an icon and do something, or is it supposed to be hidden? Like, for example, Google Play Services.”

If I had to sum the issue up even more, I’d say that the way SafetyCore was released is an example of a lack of transparency and a disregard for user autonomy. No matter how good Google’s intentions may be — which, judging by the history of big tech, is far from a guarantee — this isn’t the right approach.

Apple isn’t off the hook either. At the end of December 2024, someone noticed a new option in Apple Photos: “Enhanced Visual Search,” on by default. It identifies the location of photos even when there are no geo location in the metadata, by recognizing landmarks in the images. [The documentation](https://support.apple.com/pt-br/122033) explains that it “works without sending your photos or videos to Apple and without Apple learning about the information in those photos or videos.”

In both cases, trust is lost when features like these are enabled quietly, without giving users the option to opt-out — a practice that remind what malicious parties would adopt if their intention were installing malware on millions, even billions, of devices.

What’s frustrating is that these are promising features that *seem* like good ideas. Scanning for unwanted or malicious content on your device without sending data to Google’s cloud? A real step forward, if true. Improving photo search without handing over your images to a big tech company? Sounds great.

However, note that both promises are extremely difficult to verify since all the code is closed source. That alone is a huge red flag. Enabling these features by default without any notice only worsens the situation.
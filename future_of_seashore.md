# The Future of Seashore

I have decided to deprioritize my work on Seashore in favor of a low-cost commercial replacement
[Seahorse](https://apps.apple.com/us/app/seahorse-image-editor/id6742335288?mt=12) and have created this FAQ to answer common questions.

## Why the change?

For several reasons:

- I've grown weary of the number of Seashore "ripoffs". These go against not just the legality of the open source license, where credit must be given,
 and the resulting source must be available publicly available, but the spirit where changes should be posted back to the original project - not creating forks
 for personal gain. Apple has been very helpful in having these non-compliant ripoffs removed from the App Store but it takes a lot of effort.
- The AI systems have stolen the code without compensation. They make money charging for their services but don't give back to the open source efforts that
  made their systems possible.
- Maintaining backwards compatibility has become more and more difficult - especially the testing.
- The donation model hasn't worked. I appreciate all those that have donated to Seashore and/or left reviews on the App Store, but the revenue versus the hours invested
  has forced me to try a different model.
- I wanted to learn something new - specifically Swift and SwiftUI.
- I wanted to be able to run on an iPad.

## What is happening to Seashore?

Nothing. It will still be on the App Store, and people can chose to use that for free. I will also try and make sure it runs on later OSX versions and
fix critical bugs if they are reported. This is becomming very time consuming, as the latest XCode cannot build for older OSes without a lot of manual
changes.

## Will Seahorse work on my older Mac?

Depends. Seahorse requires OSX 13+ which is compatible with most Macs since 2017. There were just too many complications trying to support OSX versions older than that. Seahorse has a lot of new capabilities that required later OSX versions. This may change if Apple makes some of the newer APIs more backward compatible but that is a longshot.

## Is Seahorse simply a clone of Seashore?

No, not at all. It is a brand new code base written from the ground up in Swift using SwiftUI and GPU native operations. This application should be very 
stable, more performant, and far easier to maintain moving forward - reducing the number of hours I need to spend. It has most of the features of Seashore, 
and has a few more - like the "people selection". It uses a completely dynamic Core Image Filter layer allowing more filters to be added more easily.

## Why isn't Seahorse free?

Honestly, the ageism in tech plus my desire to not be disrespected has brought my career into retirement. This is a way to
hopefully generate some income while keeping myself busy.

## What about the people that already donated to Seashore?

This has been a struggle. I looked into how I could credit those who have already donated but there was no easy way to do so, and for the few people that did
donate __- who I appreciate immensely -__ it wasn't worth the effort. Seahorse is a very low cost application - lower than the price of a fancy coffee.

## Will Seahorse ever be open source?

Possibly. If I generate enough money to have the proper legal structure to enforce its intent I may do so. I believe in the power of open source for education,
but the modern AI systems have perverted this. I believe the code is some of the best I've created in my career. That Seahorse is 3x smaller than Seashore
with greater power and flexibility is a testiment to proper design and the power of Swift and SwiftUI.

## Did you use any AI in developing Seahorse?

A very small bit. It was primarily a test to see how well it worked. We had very early AI code generation at Google -
it was just ramping up when I left - so this was a great opportunity to test various models. I hope to some day write a paper on AI code generation, 
how well it works, how best to use it, the ethics involved - but that day is not today.

## If you used AI aren't you being a hypocrit?

Maybe, but in the end the code was of such low quality or simply didn't work that I needed to write it from scratch anyway.

## Is there an iPad version of Seahorse?

Not yet. I've done some preliminary proof of concept testing but my priority has been getting Seahorse finished for the Mac first. It will probably require an
iPad pro and possibly an external monitor to be truly useful but it's too early to know for certain.

## I tried Seahorse and it's amazing. Do you do consulting on Swift and SwiftUI best practices?

Possibly. Contact me at the email below and let's talk.

## Why is it called Seahorse?

As a tribute to my late father - an octogenarian that love technology. When discussing Seashore he would always seem to call it Seahorse, and the name stuck.

## Where can I get Seahorse?

It is available for [download](https://apps.apple.com/us/app/seahorse-image-editor/id6742335288?mt=12) on the App Store.

## I have some more questions not answered here...

Feel free to send me an email at [seahorse@eolcoder.com](mailto:seahorse@eolcoder.com) - complaints, praises, questions and ideas are welcome - so is simply saying hello.






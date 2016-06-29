---
layout: post
title: Space Is Scalar
date: 2016-06-29
---
Reflections on a geospatial referencing tool.

<!--more-->
![a cropped section of Pieter Bruegel the Elder's Tower of Babel]({{ site.url }}/assets/tower4.jpg)

&#10019; _Suppose you wanted to improve a language by increasing its richness indefinitely. We can get an idea of the enormous number of printed or written words that could be formed by different combinations of phonemes or letters, by envisaging the fact that from an alphabet of 23 letters we could construct 23^8^, i.e. about one hundred thousand million eight letter code words. This should allow us to replace each different sentence ever printed in the English language by different printed word so that this codeword (which would function as a verb) would cover what the sentence asserts. This millionfold enrichment of the English language would completely destroy it; not only because nobody could remember so many words, but for the more important reason that they would be meaningless. For the meaning of a word is formed and manifested by its repeated usage, and the vast majority of our eight-letter code words would be used only once or at any rate too rarely to acquire and express a definite meaning. It follows that a language must be poor enough to allow the same words to be used a sufficient number of times. We may call this the Law of Poverty._  

From [_Personal Knowledge_](https://www.amazon.com/Personal-Knowledge-Towards-Post-Critical-Philosophy/dp/0226672883) by Michael Polanyi

![a cropped section of Pieter Bruegel the Elder's Tower of Babel]({{ site.url }}/assets/tower1.jpg )


&#10019; _The nurse takes your blood pressure. "It's hint.risks over soda.handed." "What was it last time?" you ask. "It was wedge.goad over year.critic." You use a pocket-sized computer, the one you take pictures and read the news with, to translate the code into millimeters of mercury and notice with relief that the second pair of numbers is slightly lower than the first._


![a cropped section of Pieter Bruegel the Elder's Tower of Babel]({{ site.url }}/assets/tower3.jpg )


&#10019; _A police officer pulls you over. "Do you have any idea how fast you were going?" You think back to the words your dashboard was showing you a moment ago. "Definitely no faster than themes.tantrum," you suggest. The police officer whips off a pair of sunglasses and hisses "I clocked you at mini.intervals!" Both of you pause as you use your phone to convert that pair of words into miles per hour, and you slump in chagrin._

![a screenshot of Google Streetview from Ulaanbaatar]({{ site.url }}/assets/yurts.png )

&#10019; _Mongol Post is the country’s largest postal service provider, with 900 employees serving more than 3 million citizens, 30% of whom are nomadic, roaming an area of more than 1.5 million square kilometres. As a rapidly emerging market, Mongolia needs a functioning address system to sustain its economic development and attract investment. what3words is a multi-award winning location reference system based on a global grid of 57 trillion 3 metre x 3 metre squares. Each square has been pre-assigned a fixed and unique 3 word address. The system is available as a mobile app or API integration and works both online and offline. It makes it easy to discover an address, communicate it and deliver to it._

From [Mongol Post Adopts what3words as National Addressing System][3]

Mongol Post, the partially privatized mail system of Mongolia, has adopted [what3words](https://map.what3words.com) as an "addressing platform." What3words is a startup offering a clever spatial index of the entire earth, and word-based lookup codes for every 3m by 3m grid cell. Rob Meyer of _The Atlantic_ [has written about some of the problems this adoption raises,][1] especially with respect to the closed and proprietary nature of what3words.  

According to Mongol Post's announcement, "postal workers will use the 3 word address to navigate directly to the 3mx3m square where they will find the customer’s front door." This is like saying "doctors will use the diagnostic code [ICD-9-CM 540.9](http://www.icd9data.com/2013/Volume1/520-579/540-543/540/540.9.htm) to remove your appendix." Put yourself behind the wheel of a mail truck in Ulaanbaatar. your mailbag includes items addressed to "forest.competing.jaws," "softest.burden.herds," and "tomorrow.texted.treatable." How do you sort these parcels for delivery? If these are frequent recipients, you might remember the door each of the codes corresponds to, and stack the items in order of your route. If you've built an elaborate enough [memory palace][8], you might have already chained the entries by imagining a lurid scene of a predator's [jaws][5] sinking into the hindquarters of some ungulate from the [herds][6] but leaving a wound that is [treatable][7], and you know that these three addresses are a consecutive series of buildings on the south side of a road near the Mongolian State University of Agriculture.

In the absence of such advanced skullware, postal workers will use the what3words app to convert each three letter address to a pair of latitude and longitude coordinates, but knowing where a package should end up is very different from knowing how one should deliver it. The claim that what3words will "make it easy to discover an address, communicate it and deliver to it" is two-thirds true at best. Every what3words address will need to be translated one more time, from its coordinate location to some route-based expression of its position. In other words, the three word code that what3words calls "an address" still needs to be converted to what the rest of us call "an address."

Addressing is an information technology, and a relatively new one. [Only in 1805 did London begin to enforce numbers,][4] which replaced ad-hoc descriptions that mingled districts, nearby landmarks, and physical traits ([more background here](https://regencyredingote.wordpress.com/2012/02/10/on-the-numbering-of-houses/)). Legible addresses don't impose themselves through some emergent process of spontaneous cooperation; they need to be imposed by some central authority, and they typically meet resistance, whether in [nineteenth century France](https://books.google.com/books?id=tD1AupO0vvoC&lpg=PA26&ots=jkXZWtS10d&dq=walter%20benjamin%20house%20numbering%20france&pg=PA26#v=onepage&q&f=false) or in [twenty first century West Virginia](http://www.tandfonline.com/doi/abs/10.1080/00045608.2011.620503).  

Different places have developed different methods of indexing buildings, but none, to my knowledge, has been so rash as to give every spot along the ground a nickname and call it a day. Each addressing system worth the name includes some scalar component: Usually it is the distance along a route (as in the modern U.S. convention) but sometimes it indicates relative sequence of a building's construction. Either way, the number reflects the location's position along some continuous scale, whether space or time. In the system recently adopted by mostly rural West Virginia, the house numbers increment by one every 5.28 feet along the road, or every thousandth of a mile. On St. Croix in the U.S. Virgin Islands, the house numbers increase with distance from the towns of Frederiksted and Christiansted. Japan somehow gets by with addresses that refer to numbered blocks surrounded by unnamed streets, but their addresses at least observe a scaled hierarchy of coarse-to-fine identifiers.

![a Google Maps representation of Tokyo]({{ site.url }}/assets/tokyo.png )

An addressing system is successful insofar as it enables us to execute the suite of cognitive tasks that constitute navigation. Associating a destination with its location on the earth is only one of these chores.

If you have a powerful computer in your pocket, and you want to use your brain to remember and then use your voice or a text message to share a geographic location with someone else who also has a powerful pocket computer, what3words has got you covered. If you want to infer how far that location is from another location, or which roads might connect to it, you are out of luck. Building an addressing system is difficult, expensive work specifically because legitimate addresses embed so many levels of hierarchical categories and scalar proportions for us. Remembering coordinate locations is cognitively burdensome, but the signifiers retain some meaning relative to one another. You can tell the search and rescue team that you've twisted your ankle at [ringleader.kilt.comedians](http://w3w.co/ringleader.kilt.comedians), but as soon as you've moved 3 meters east, you're at [since.duplicates.backswing](http://w3w.co/since.duplicates.backswing), and the technologically-enhanced mnemonic crutch has exhausted its usefulness. Augmenting one cognitive task in a manner that debilitates the constellation of surrounding faculties is not the right way to apply technology to our problems.

The what3words site includes a [gallery of applications](https://what3words.com/industries/), some of which seem like worthwhile accessories to existing spatial systems. The best use cases, though, are not solving an intrinsically spatial problem: They are offering the ability to store and recall one record in a very large data table, with no need to situate that record among its neighbors or observe any security concerns. In the case of what3words, that table happens to be a set of geographic locations. The mnemonic solution that will probably collapse upon contact with postal reality in Mongolia, though, offers some promising opportunities when generalized beyond spatial challenges.

For example, a phone tree might offer continuity in the event of interruption: "If our call is disconnected, please call back and say 'zebra erudite' and we will resume your call." Or your employer's group insurance policy might participate in a lookup service that allows you to tell the receptionist at the doctor's office a three-word policy lookup key instead of showing your card. Both of these examples use information technology to mitigate the complexity it has created, instead of using it to flatten and cripple our pre-computer technologies of place.



[1]: http://www.theatlantic.com/technology/archive/2016/06/the-most-interesting-story-about-postal-addresses-you-have-ever-read/487160/ "The App That Wants to Simplify Postal Addresses"

[2]: http://ardholdings.com/en/ard-financial-group-becomes-a-shareholder-of-mongol-post-jsc/ "Ard Financial Group becomes a shareholder of Mongol Post JSC"

[3]: http://www.mongolpost.mn/more/156 "MONGOL POST ADOPTS WHAT3WORDS AS NATIONAL ADDRESSING SYSTEM"

[4]: http://query.nytimes.com/mem/archive-free/pdf?res=9803EEDB1139E433A25755C1A9619C94699ED7CF "THE NUMBERING OF HOUSES"

[5]: http://w3w.co/forest.competing.jaws "forest.competing.jaws"

[6]: http://w3w.co/softest.burden.herds "softest.burden.herds"

[7]: http://w3w.co/tomorrow.texted.treatable "tomorrow.textable.treatable"

[8]: https://en.wikipedia.org/wiki/Method_of_loci "Method of loci"

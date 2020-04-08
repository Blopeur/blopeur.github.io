---
layout: post
published: true
title: "The never-ending story of X86 patents expiration"
description: "Every couple of years, this story re-emerges, and everybody starts to talk about the upcoming expiry of x86 related patents. They were followed by several stories revolving emulation and the forthcoming flood of third-party implementations of compatible processors. But this never happens. Why?"

picture: intelx86.jpg

label_default: "Intel"
label_primary: "Patent"
label_info: "x86"
---
<!-- Main Container -->
Every couple of years, this story re-emerges, and everybody starts to talk about the upcoming expiry of x86 related patents. They were followed by several stories revolving emulation and the forthcoming flood of third-party implementations of compatible processors. But this never happens. Why?

Intel's patents should have expired you would think. Intel released the 8086 on June 8, 1978. To preserve any available rights under non-U.S. patent law, Tech companies typically file U.S. patent applications just before the first public disclosure of the new technology. Let's assume that they filled it slightly earlier that year. Now, it typically takes two years for that patent application to be issued as a patent, which brings us to  1980. This means that the patent would have expired in 1998 (the earliest filing date plus 20 years).

However, it's not the case. We see some company releasing x86 compatible chip like [Zhaoxin](https://fuse.wikichip.org/news/733/zhaoxin-launches-their-highest-performance-chinese-x86-chips/).
But most of these chips saw the light of day after the FTC forced Intel to allow other companies owning x86 IP to undergo mergers and joint ventures. Hence disseminating, under specific conditions, the capabilities to build x86 compatible chips.

On the other hand, emulation is almost non-existent. Emulation could at least ensure compatibility and help the ARM ecosystem which has seen vast improvements due to a more significant number of implementers: Apple, Huawei, Qualcomm, Nvidia, Samsung, ARM, Applied Micro and Cavium.

Multiple factors are preventing the industry from latching on the x86 bandwagon and start competing with Intel. First, the emulation path is just a non-starter. ARM ISA does not magically confer any performance or efficiency advantage. Yes, ARM processors are more power efficient because they do less work per unit time. They should be operating in roughly the same power envelope once they're as performant as x86. However, it will be difficult to see an ARM processor that's running emulated x86 code will be at anything but a severe performance/watt disadvantage over a comparable x86 part.

Transmeta tried it and failed. Yes, there was some patent war, but the business plan was terrible from the get-go. And that's what killed the company. X86 on ARM emulation could still be a valid business if it were good enough to beat the performance cost ratio compared to equivalent Intel chips. But we are not yet there.

Now, when it comes to actual intellectual property. There is not just ONE patent for x86. There is a multitude of patents that were filed over the year as the architecture evolved and was optimised. Just head up to the [Steam Hardware Survey](https://store.steampowered.com/hwsurvey/Steam-Hardware-Software-Survey-Welcome-to-Steam) , and you can get a glimpse of the still-in-use CPUs. SSE3 is on everything, and CMPXCHG16B, LAHF and SAHF (required by Windows 8.1 and above) are on almost everything. The latter was introduced in March 2005.

Some of the old pieces of the x86 architecture patent already expired. Virtually every chip that's been sold over the last decade or more will include SSE2 support as AMD made SSE2 a mandatory part of its 64-bit AMD64 extension. That's a problem because the SSE family is also new enough—the various SSE extensions were introduced around 2001. Any patents covering SSE2 will still be in force. SSE3 is even more recent. Not to mention the fused multiply and add operation used on by all current OS which has an [Intel patent valid until 2026](https://patents.google.com/patent/US7499962).

As you can see, there is quite a bit of patent protecting the current x86 CPUs which prevent any serious competition from entering the market. Moreover, if you try to implement more modern features, you will have to face Intel's wrath. Intel's approach to x86 historically has been asserting that it's impossible to achieve a clone due to their patents, which they aggressively asserted to keep any competitors out of the market entirely if possible, and restricted to older ISA features if not possible. With the main exception of AMD, which was initially given patent licenses and tolerated to meet 2nd-source requirements. But even AMD they tried to strongarm out of the market later, leading to litigation where AMD eventually won a bunch of continued patent licenses only as part of the lawsuit settlement. Intel has also used patent lawsuits over the past 30 years to attempt to limit competition from Cyrix, Via, NVidia, and Transmeta, among others. Though they did lose or unfavourably settle a number of those lawsuits.

Yes, x86 patents are expiring, but there is a never-ending stream of new one added every year protecting the most recent versions of the highly successful CPU architecture. And by most recent I mean, all the version that span the last 20 years (the lifespan of a patent). Intel has been jealously guarding its crown jewel and is not ready to let it go anytime soon.
<!--End Main Container -->

—-
Layout: post
---

## [Apple Silicon Performance is Astonishing](https://www.anandtech.com/show/16226/apple-silicon-m1-a14-deep-dive)

Anandtech did a deep dive on Apple's A14 Bionic SoC, which features the same high-performance "FireStorm" and low-power "IceStorm" cores as Apple's recently announced M1 SoC. If you've been following Apple's annual cadence in releasing new CPU architectures, then the performance on offer here shouldn't be too much of a surprise.

But if you haven't been following the news, then this chart puts the performance into perspective:

![Performance of AMD, Apple, and Intel chips](https://hirothreading.github.io/thehonourroll//assets/images/applea14perfcharts.png){:height="350px" width="350px"}

Let that sink in for a second. Now, a couple of things to take into account with these performance charts. First, these are all for single core workloads, and they are *not* adjusted for clock speeds and power consumption. That means chips like the AMD Ryzen 9 5950X is able to boost up to 4.90GHz and consume about 45 watts, and the Intel Core i9 10900K can boost to over 5.00GHz and consume ~~150 watts~~ about 50-60 watts. So Apple has plenty of headroom to work with here, and no doubt that future Apple Silicon SoCs clocked north of 3.00 or 4.00GHz can achieve even higher single threaded performance.

The M1 at 10-20 watts is rag dolling Intel and AMD chips in the same power class, so it's exciting to see what Apple can do in the future with greater thermal headroom. An SoC with double or triple the core count and thermal design point (and yes, I am aware that none of these things scale linearly) as the M1 should bring up very impressive performance.

I wonder what Apple has in store for the Mac Pro at about 180-250 watts...

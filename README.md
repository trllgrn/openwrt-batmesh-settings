# openwrt-batmesh-settings
What the heck is this?

I'll answer that question with a story.  Once upon a time, there was small, ambitious startup company (3 unemployed dudes) with a dream of building an amazing product and a successful company.  They saw examples of people building valuable companies by solving interesting problems with transformative technology.  All they needed was a great technology to build on and someone to sell it to.

#The idea:
Wireless networks perform terribly under less than ideal conditions because of the protocol they're based on. TCP/IP was never designed for wireless.  It's a carryover from the days of all wired networking.  So, if there's packet loss in the network, throughput goes in the toilet.  Another small startup company with actual funding had figured this out and was building products to address it.  That company was called QFactor.  Nice guys. Today, if they're still around, they are called Kwicr.

#The dream:
What if we could take what the products that QFactor was building and leverage in a space that we had domain expertise in (military).  We would crush it!  Was there an opportunity?  Hell yeah! There was no more optimal deployment arena for QFactor's product than the military.  A space that relied heavily on network intelligence in areas where there was no infrastructure.  All we had to do was demo it to them, set the price and count the money!


#The reality:
It turns out that if you're going to build demos, you need to have someone to demo them to.  It also turns out that it's not easy to build the demo and find customers at the same time.  It also turns out once you have interested potential customers and a relavent demo to show them, you need money to actually continue to pursue them.  We had none.  And so, sadly...the dream fizzled and laid itself to rest.

#That was a really sad story that was totally not worth it...what is this again?
Oh yeah, so this is a repository of the router configurations we used to run our demos.  We used OpenWRT software to setup custom firmware on portable routers that acted as hops in our network.  Using these nodes, we could simulate a number of different lossy network conditions that convincingly demonstrated the power of the QFactor software.  It was super cool!  We have one claim to fame.  We were the only company in the world to integrate and test a P2P mesh network with QFactor's network coding technology built in, routing on layer 2!  Nobody cares but I'm still claiming it!

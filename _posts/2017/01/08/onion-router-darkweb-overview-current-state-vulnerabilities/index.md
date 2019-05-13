---
The Onion Router and the Darkweb &#8211; An Overview of Current State and Vulnerabilities
---
<article class="post-listing post-17398 post type-post status-publish format-standard has-post-thumbnail hentry category-articles category-deepdot-news tag-current tag-darkweb tag-onion tag-overview tag-router tag-state tag-vulnerabilities">
    <div class="post-inner">
    <p class="post-meta">
    <span>Posted by: <a href="https://www.deepdotweb.com/author/tamersameeh/" title="">Tamer Sameeh </a></span>
    <span>January 8, 2017</span>
    <span>in <a href="https://www.deepdotweb.com/category/articles/" rel="category tag">Articles</a>, <a href="https://www.deepdotweb.com/category/deepdot-news/" rel="category tag">Featured</a></span>
    <span><a href="https://www.deepdotweb.com/2017/01/08/onion-router-darkweb-overview-current-state-vulnerabilities/#comments">6 Comments</a></span>
    </p>
    <div class="clear"></div>
    <div class="entry">
    <p>The Onion Project was created to offer an anonymous way to connect to the internet and the darknet essentially through befuddlement. It has established a network that operates to route connection requests in a way that obfuscates users attempting to access surface websites, in addition to enabling users to build websites, on the darknet , whose hosting servers cannot be traced. Throughout this article we&#8217;ll provide <a href="http://www.cs.tufts.edu/comp/116/archive/fall2016/cjacoby.pdf">an introduction to Tor network and its vulnerabilities</a>.</p>
    <p><img class="wp-image-17405 aligncenter" src="https://www.deepdotweb.com/wp-content/uploads/2017/01/deep-web-jpg.jpeg" alt="deep-web.jpg" width="857" height="449" srcset="https://www.deepdotweb.com/wp-content/uploads/2017/01/deep-web-jpg.jpeg 1268w, https://www.deepdotweb.com/wp-content/uploads/2017/01/deep-web-jpg-300x157.jpeg 300w, https://www.deepdotweb.com/wp-content/uploads/2017/01/deep-web-jpg-1024x536.jpeg 1024w" sizes="(max-width: 857px) 100vw, 857px"/></p>
    <p>Tor provides two forms of services:</p>
    <p>1- An anonymous way to connect to the internet (surface websites).</p>
    <p>2- Hidden services which are anonymous websites whose owners and hosting servers are anonymous . The domain names of these sites end in &#8220;<a href="https://www.deepdotweb.com/how-to-access-onion-sites/">.onion</a>&#8221; instead of &#8220;.com, .org, .info&#8230;&#8230;etc&#8221; that mark surface websites.</p>
    <p>.Onion websites are considered parts of a <a href="https://www.deepdotweb.com/dark-net-market-comparison-chart/">darknet</a> and can be only accessed via Tor. Darknets comprise the dark web, which in turn represents a small part of the deep web. The deep web represents all internet content that can only be accessed via a specific protocol e.g. Tor. This is a rather broad definition, as for example, the content on online databases which belong to governments and universities is protected by means of a &#8220;pay-wall&#8221;; accordingly, these databases are considered parts of the dark web.</p>
    <p><strong>How Does Tor Promote Anonymity for Internet Users?</strong></p>
    <p>Tor enables users to access surface websites anonymously, so their traffic cannot be traced back to them. Although encryption can prevent hackers from seeing what users are sending to and receiving from various websites, it cannot protect them against being traced back using web traffic analysis. To prevent traffic analysis, Tor routes connection requests from each user to multiple relay nodes so that the path from the user to the website, whether on the surface or dark web, is impossible to be traced. Tor relay nodes are connections to thousands of Tor users who have volunteered their bandwidths to Tor to secure the network. Consequently, each and every connection request relays through multiple IPs and the destination website will not be able to trace the user via observing who sent the packet. The complicated nature of this protocol is that any relay node across Tor&#8217;s network cannot trace the origin of any of the connection requests it receives and redirects.</p>
    <p><strong>Hidden Services: Sites on the Deep Web:</strong></p>
    <p>Hidden services are websites on the deep web which have a .onion address that requires a Tor browser to be accessed. This method doesn&#8217;t link the website to a hosting IP address. To guarantee this, the hidden service will connect to nodes on the network using Tor circuits. Firstly, the hidden service will select some introduction nodes and formulate Tor circuits to them which will give introduction nodes the capability to ping back the hidden service without tracing back its location. Secondly, the hidden service will create a descriptor that will allow users to access the service, which will contain its public key and references that point to the introduction nodes. This will be signed by the hidden service&#8217;s private key and then the content of the website will be uploaded to a distributed database hash table i.e. it will be hosted on more than one node while promoting redundancy; in other words, content of the website won&#8217;t be lost if one of the hosting nodes go offline. The address of a website on the deepweb is 16 characters long and is created using the site&#8217;s public key.</p>
    <p><strong>Vulnerabilities of TOR:</strong></p>
    <p>Malicious attacks can occur against Tor users, just like it can happen to users of surface websites. Hidden services that contain corrupted downloads or malicious code can affect users whether or not they are using Tor. Also, hidden services can be also attacked by hackers via SQL injection, cross-site scripting and denial of service attacks.</p>
    <p>De-anonymization can occur to a small percentage of Tor users in some instances. De-anonymization of a user refers to revealing the IP or MAC address, he/she used to connect to the Tor network. This is very hard to accomplish, if not impossible, because it requires the attacker to control all the nodes belonging a user&#8217;s circuit, especially that circuits expire and are replaced by new circuits every few minutes.</p>
    <p><a href="https://www.deepdotweb.com/2015/06/08/the-dark-web-deep-web-and-dark-net-terminology-hell/">Tor and the deep web</a> decentralize the internet and omit the censorship and control that can be imposed by federal governments. Although mainstream media is trying to picture the deep web as a big online store for illegal drugs, the truth is that the deep web is <a href="https://www.deepdotweb.com/2016/11/09/researchers-claim-darknet-legal-sites-illegal-ones/">full of legal websites that might even be more than the illegal ones</a> and can provide the people of the world with an anonymous way to speak their minds out without intimidation.</p>
    </div>
    <span style="display:none"><a href="https://www.deepdotweb.com/tag/current/" rel="tag">current</a> <a href="https://www.deepdotweb.com/tag/darkweb/" rel="tag">darkweb</a> <a href="https://www.deepdotweb.com/tag/onion/" rel="tag">onion</a> <a href="https://www.deepdotweb.com/tag/overview/" rel="tag">overview</a> <a href="https://www.deepdotweb.com/tag/router/" rel="tag">router</a> <a href="https://www.deepdotweb.com/tag/state/" rel="tag">state</a> <a href="https://www.deepdotweb.com/tag/vulnerabilities/" rel="tag">vulnerabilities</a></span> <span style="display:none" class="updated">2017-01-08</span>
    <div style="display:none" class="vcard author" itemprop="author" itemscope itemtype="http://schema.org/Person"><strong class="fn" itemprop="name"><a href="https://www.deepdotweb.com/author/tamersameeh/" title="Posts by Tamer Sameeh" rel="author">Tamer Sameeh</a></strong></div>
    </div>
</article>

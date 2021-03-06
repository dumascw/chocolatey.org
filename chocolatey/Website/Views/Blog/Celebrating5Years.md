Title: Celebrating 5 Years with Chocolatey!
Published: 20160328
Author: Rob Reynolds
Tags: News
Keywords: 5 years, chocolatey, history
Summary: The Chocolatey team remembers the last 5 years with Chocolatey. Did you know that Chocolatey derives its name from NuGet?
---
**Note:** Originally posted at [CodeBetter](http://codebetter.com/robreynolds/2016/03/28/5-years-with-chocolatey/). *Reposted with permission.*

Chocolatey turned [5 years old recently](https://twitter.com/ferventcoder/status/712410862611341312)! I committed the first lines of Chocolatey code on [March 22, 2011](https://github.com/ferventcoder/nugetpackages/commit/d16ed7ac675395b3bb8ecee90fb13efb03d4b619). At that time I never imagined that Chocolatey would grow into a flourishing community and a tool that is widely used by individuals and organizations to help automate the wild world of Windows software. It’s come a long way since I first showed off early versions of Chocolatey to some friends for feedback. Over the last 2 years things have really taken off!

The number of downloads has really increased year over year!

[![Chocolatey usage by downloads over the years 2013-2015](https://pbs.twimg.com/media/CbnRP_CVIAETF3j.jpg:large)](https://twitter.com/ferventcoder/status/700821290303623169)  
**Note:** While not a completely accurate representation of usage and popularity, the number of downloads gives a pretty good context. Going up by 7 million in 2014 and then by almost 30 million downloads in one year really shows a trend!

**Note:** The Chocolatey package has about 1,000 downloads per hour. I shut off the statistics for the install script back in October 2015 due to the extreme load on the site, so the number of Chocolatey package downloads is missing some of the statistics.

### History

Let’s take a little stroll through some of the interesting parts of Chocolatey’s history. The history of Chocolatey really starts when I joined the Nubular (Nu) team in summer 2010.

- July 2010 – [Nu (Package Management for .NET)](https://www.youtube.com/watch?v=IvxAa4XURss) is reintroduced and quickly takes off in popularity (I also [wrote](http://ferventcoder.com/archive/2010/07/15/gems---package-management-for-.net.aspx) [several](http://ferventcoder.com/archive/2010/07/16/how-to---gems-and-.net.aspx) [posts](http://ferventcoder.com/archive/2010/07/17/how-to-ndash-gems-and-.net-ndash-dependencies-references.aspx) [about](http://ferventcoder.com/archive/2010/07/19/gems-for-.net-ndash-community-response.aspx) [it](http://ferventcoder.com/archive/2010/07/26/the-future-of-.net-open-source-software-delivery.aspx)).
- October 6, 2010 – [NuGet is introduced](http://ferventcoder.com/archive/2010/10/06/the-evolution-of-package-management-for-.net.aspx). The Nu team had joined up with Microsoft in late August to work on NuPack (as it was called then).
- February 2011 – Joke with other folks on the NuGet team at MVP summit that if we ever introduced a machine package manager, we’d call it Chocolatey NuGet because it wouldn’t be vanilla NuGet packages.
- March 21, 2011 – First lines of Chocolatey [are committed](https://github.com/ferventcoder/nugetpackages/commit/d16ed7ac675395b3bb8ecee90fb13efb03d4b619). The PowerShell version of Chocolatey represents the first public known use of PowerShell as an application and not just scripts and modules.
- March 23, 2011 – First release of Chocolatey is [0.6.0](https://www.nuget.org/packages/chocolatey/0.6.0). I hope you were not using it that early. ;)
- March 28, 2011 – I started talking about Chocolatey [on the NuGet list](http://nuget.codeplex.com/discussions/251435).
- March 29, 2011 – [Svein Ackenhausen](https://twitter.com/ackenpacken) coins the term “cinst” that would be the main call for choco until 2013.
- April 1, 2011 – [Chris Ortman](https://twitter.com/chriso) writes the [first public blog post](https://chrisortman.wordpress.com/2011/04/01/getting-started-with-chocolatey/) about Chocolatey.
- April 26, 2011 – I [put up a video](https://www.youtube.com/watch?v=N-hWOUL8roU) showing Chocolatey installing 11 pieces of software. Pardon the music, it was swapped out from my original track.
- September 2011 – Community Repository ([https://chocolatey.org](https://chocolatey.org/)) introduced.
- September 7, 2011 – [Christiaan Baes](https://twitter.com/chrissie1) writes a [post about a side project](https://web.archive.org/web/20110926191629/http://blogs.lessthandot.com/index.php/DesktopDev/MSTech/chocolatey-gui) that is known as [Chocolatey GUI](https://github.com/chocolatey/ChocolateyGUI#features).
- October 07, 2011 – A year after NuGet was introduced, I blog about [Chocolatey for the first time](http://ferventcoder.com/archive/2011/10/07/letrsquos-get-chocolatey-kind-of-like-apt-get-for-windows.aspx).
- December 22, 2011 – [Anthony Mastrean](https://twitter.com/anthonymastrean/) [introduces Pester](https://github.com/chocolatey/chocolatey/pull/43) (a [PowerShell BDD testing framework](https://github.com/Pester/Pester)) to Chocolatey.
- March 2012 – Chocolatey is featured in the [Pro Nuget Book](http://www.amazon.com/Pro-NuGet-Experts-Voice-Microsoft/dp/1430241918/).
- April 1, 2012 – [Matt Wrock](https://twitter.com/mwrockx) [commits](https://github.com/mwrock/boxstarter/commit/2d96de030cf5f45b42690c3e01847f632b4e37e6) the first lines of [BoxStarter](http://boxstarter.org/).
- April 23, 2012 – After bouncing ideas off of [Keith Dahlby](https://twitter.com/dahlbyk) and [Aaron Lerch](https://twitter.com/aaronlerch), I figure out how to do [mocking for PowerShell testing](https://github.com/chocolatey/chocolatey/commit/3533d00a835c11aaba9aa3f34ff9d052496ff696#diff-48c72ff2102462265651d53d3d4e374f) (which Matt Wrock later puts into [Pester](https://github.com/pester/Pester) proper). I also determine a proper way to structure a PowerShell application (function per file).
- May 13, 2012 – [Rich Siegel](https://twitter.com/rismoney) starts working on [Puppet integration](https://github.com/chocolatey/puppet-chocolatey/commit/1c5f52ea0f06d109a9c24ba803dbd924f74d66a4).
- September 2012 – Chocolatey is featured on [Lifehacker](http://lifehacker.com/5942417/chocolatey-brings-lightning-quick-linux-style-package-management-to-windows).
- October 4, 2012 – [Guilhem Lettron](https://twitter.com/guilhemlettron) starts working on [Chef integration](https://github.com/chocolatey/chocolatey-cookbook/commit/99e151ca271ba8bf0f1e200a363649ceebf66daa).
- October 19, 2012 – After [putting](https://github.com/pester/Pester/commit/84d5acbab1d809a121378048908dd2a8b2dfefc9) [proper](https://github.com/pester/Pester/commit/ec77ceab7ba99bec93376ad6ca1f6f2d5dfc9d22) [mocking](https://github.com/pester/Pester/commit/4178c343a6574a8a9521be8a77006572fc49e311) [support](https://github.com/pester/Pester/commit/dd7dca288bf5d7258532243687b3f6b6e4936af3) into [Pester](https://github.com/pester/Pester), Matt Wrock [retrofits Chocolatey](https://github.com/chocolatey/chocolatey/commit/654703b9d4388eb385776986ce6d0ee53485a146) to use that.
- January 2013 – [Automatic packaging](https://github.com/chocolatey/choco/wiki/AutomaticPackages) is introduced.
- February 13, 2013 – [Gary Ewan Park](https://twitter.com/gep13) gives [Chocolatey GUI](https://chocolatey.org/packages/ChocolateyGUI) a new home and [takes over project maintenance](https://github.com/chocolatey/ChocolateyGUI/commit/c722821573cafce6bfb50760618a8c1803e76e7f).
- June 2013 – Community repo reaches [1,000 stable packages](http://ferventcoder.com/archive/2013/06/01/chocolatey-official-public-feed-now-has-1000-stable-packages.aspx).
- October 2013 – Community repo surpasses 1 million downloads.
- December 13, 2013 – First lines of the C# Chocolatey rewrite are [committed](https://github.com/chocolatey/choco/commit/b3dbcb851d95e9c0bd7f9f0438b7b087405e7e12).
- February 6, 2014 – [Richard Simpson](https://twitter.com/RichardSimp) joins Gary on [Chocolatey GUI](https://chocolatey.org/packages/ChocolateyGUI) and [commits the initial changes](https://github.com/chocolatey/ChocolateyGUI/commit/2d9bab432f58230f6c15f387608d58657201e536) for the modern version and look.
- March 2014 – Microsoft validates the idea of Chocolatey.
- July 2014 – The Chocolatey package itself surpasses [1 million downloads](https://twitter.com/ferventcoder/status/490992889036419072).
- Sep 2014 – [Introduced Chocolatey Newsletter](http://codebetter.com/robreynolds/2014/09/27/chocolatey-newsletter/).
- September 23, 2014 – I [show](https://www.youtube.com/watch?v=cZl_wKSciVk) the first C# version of Chocolatey at a conference where my [first demo uses choco from non-Windows](https://www.youtube.com/watch?v=cZl_wKSciVk). There are a lot of murmurs in the crowd.
- Oct 2014 – [Kickstarter for Chocolatey](https://www.kickstarter.com/projects/ferventcoder/chocolatey-the-alternative-windows-store-like-yum) started.
- Oct 2014 – [Community Feed Moderation turned on](http://codebetter.com/robreynolds/2014/10/27/chocolatey-now-has-package-moderation/). [Thomas Walter](https://twitter.com/IntrepidPenguin) handles a lion’s share of moderation over 2015 so others can concentrate on the framework.
- November 2014 – Chocolatey version 0.9.8.27 is the first package version alone with more than [1 million downloads](https://chocolatey.org/packages/chocolatey/0.9.8.27). A record that isn’t broken again until October 2015 when [0.9.9.8 has 5.6 million downloads](https://chocolatey.org/packages/chocolatey/0.9.9.8)!
- February 2015 – Community repository hits [10 million downloads](https://twitter.com/ferventcoder/status/568158076093763584).
- March 3, 2015 – First C# Chocolatey version is [released](https://chocolatey.org/packages/chocolatey/0.9.9).
- March 23, 2015 – [dtgm](https://twitter.com/dtgm1594) [modernizes the automatic package](https://github.com/dtgm/chocolatey-packages/commit/fcfa4c140253adc2b21eb2dfb886606e76fa6fdc#diff-5300e33986d291296548da9cd1586aa3) process to achieve high quality automatic packages with checksums.
- October 2015 – CloudFlare and caching are introduced to the community repository to reduce pressure.
- November 2015 – Memcached is introduced to the community repository for a single cache across load balancers.
- December 2015 – Indexing is reintroduced to the community repository.
- Q4 2015 – Introduced the [validator, the verifier, and the cleaner to the community feed](http://codebetter.com/robreynolds/2016/01/16/chocolatey-community-update/) to assist in moderation.
- January 2016 – Moderation backlog is [reduced to near zero](http://codebetter.com/robreynolds/2016/01/16/chocolatey-community-update/) and is now manageable thanks to the automation.
- February 1, 2016 – First Professional Licenses of Chocolatey are shipped to Kickstarters.
- March 21, 2016 – CloudFlare caching tweaks introduced on the community repository to handle the increased pressure that will come from [tab completion for package names](https://www.kickstarter.com/projects/ferventcoder/chocolatey-the-alternative-windows-store-like-yum/posts/1527031).
- March 23, 2016 – Virus scan results shown on the community repository for packages.

This doesn’t represent everything that has happened. I tried to list out and attribute everything I could find and remember. There have been so many amazing package maintainers over the years, there are too many of you to possibly list. You know who you are. You have made the community what it is today and have been instrumental in shaping enhancements in Chocolatey.

### Looking to the Future

The community has been amazing in helping Chocolatey grow and showing that there is a need that it fills. Package maintainers have put in countless and sometimes thankless hours to ensure community growth and consumers have really found the framework useful! Thank you so much! The next version of Chocolatey is coming and it is [going to be amazing](https://github.com/chocolatey/choco/blob/master/CHANGELOG.md). Here’s to the next 5 years, may we change the world of Windows forever!
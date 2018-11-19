# Awesome OpenBSD

*Curated list of resources about OpenBSD* :blowfish:

## Index

* [Official OpenBSD](#official-openbsd)
  * [Related projects](#related-projects)
* [Non-official OpenBSD websites](#non-official-openbsd-websites)
* [OpenBSD-based products](#openbsd-based-products)
  * [OpenBSD-based commercial products](#openbsd-based-commercial-products)
  * [OpenBSD-based opensource products](#openbsd-based-opensource-products)
* [Hosting](#hosting)
  * [donors to OpenBSD Foundation](#donors-to-openbsd-foundation)
  * [KVM-based](#kvm-based)
  * [Other options](#other-options)
  * [Free Shells](#free-shells)
* [Jobs](#jobs)
* [Community](#community)
  * [News](#news)
  * [Conferences](#conferences)
  * [BSD user groups](#bsd-user-groups)
  * [Mailing lists](#mailing-lists)
  * [IRC](#irc)
  * [Twitter](#twitter)
  * [Mastodon](#mastodon-bsdnetwork-instance)
  * [Telegram groups](#telegram-groups)
  * [Interviews](#interviews)
  * [Blogs](#blogs)
* [Selected articles](#selected-articles)
* [Desktop](#desktop)
* [Third party repositories](#third-party-repositories)
* [OpenBSD Provisioning(#openbsd-provisioning)
* [Portable OpenBSD Components](#portable-openbsd-components)

## Official OpenBSD

* [Innovations](https://www.openbsd.org/innovations.html)
* [FAQ](https://openbsd.org/faq/)
* [man pages](http://man.openbsd.org/)
* [PF's users guide](https://www.openbsd.org/faq/pf/)
* [Porter's Handbook](https://www.openbsd.org/faq/ports/)
* [Events & Papers](https://www.openbsd.org/events.html)
* [Donations](https://www.openbsd.org/donations.html)
* [OpenBSD Foundation](http://www.openbsdfoundation.org/) - Funding for OpenBSD and related Projects

### Related projects

* [OpenSSH](http://www.openssh.com/) - the premier connectivity tool for remote login with the SSH protocol
* [LibreSSL](http://www.libressl.org/) - a version of the TLS/crypto stack forked from OpenSSL in 2014, with goals of modernizing the codebase, improving security, and applying best practice development processes
* [OpenNTPD](http://www.openntpd.org/) - free and easy to use implementation of the Network Time Protocol
* [OpenSMTPD](https://www.opensmtpd.org/) - free implementation of the server-side SMTP protocol as defined by RFC 5321, with some additional standard extensions - [OpenSMTPD-extras](https://github.com/OpenSMTPD/OpenSMTPD-extras)
* [OpenBGPD](http://www.openbgpd.org/) - free implementation of the Border Gateway Protocol, Version 4
* [OpenIKED](http://www.openiked.org/) - free implementation of the Internet Key Exchange (IKEv2) protocol
* [mandoc](http://mdocml.bsd.lv/) - free UNIX manpage compiler toolset
* [OpenBSD git mirrors](https://github.com/openbsd/) - OpenBSD CVS repository conversions for public consumpiton (managed by OpenBSD hackers)
* [OpenBSD Testing Infrastructure](http://bluhm.genua.de/) -  infrastructure for semi-automatic testing of source code
changes
* [portroach](https://portroach.openbsd.org/) - OpenBSD Ports Distfile Scanner ([code](https://github.com/jasperla/portroach))

## Non-official OpenBSD websites

* [OpenBSD jumpstart](http://www.openbsdjumpstart.org/) - Learn to tame OpenBSD quickly
* [OpenBSD and you](https://home.nuug.no/~peter/openbsd_and_you/) - How to have fun with the world’s most important free software project (by Peter Hansteen)
* [PF and Networking Tutorial](https://home.nuug.no/~peter/pftutorial/) - on BSDCan 2018 by Peter Hansteen and Massimiliano Stucchi
* [OpenBSD Daily](https://blog.tintagel.pl/2017/06/09/openbsd-daily.html) - [mulander/openbsd-daily](https://github.com/mulander/openbsd-daily) - official repository with all openbsd-daily reading by mulander and duncaen
* [OpenBSD Ports](http://www.openports.se/) - browse the package collection
* [bxr.su OpenGrok](http://bxr.su/) - powerful search on OpenBSD (and other project) code
* [OpenBSD ports](http://ports.su/) - /usr/ports/databases/ports-readmes
* [mdoc.su](http://mdoc.su/) - Deterministic URL shortener for BSD manual pages, written in nginx.conf
* [M:Tier's OpenBSD packages and binpatches](https://stable.mtier.org/) - security updates in both packages and base system
* [OpenBSD stats](http://www.oxide.org/cvs) - CVS commit stats
* [Status of OpenBSD mirrors](http://spacehopper.org/mirmon/top.html) - 150+ sites in 30 regions
* [OpenBSD on Open Hub](https://www.openhub.net/p/openbsd) - more stats about the project
* [Analysis of OpenBSD community](https://github.com/ligurio/openbsd-metrics) with [GrimoireELK](https://github.com/grimoirelab/GrimoireELK)
* [OpenBSD Wikipedia page](https://en.wikipedia.org/wiki/OpenBSD)
* [OpenBSD QA wiki](https://github.com/ligurio/openbsd-tests/wiki)
* [Multicast Proxy for OpenBSD](https://github.com/Esdenera/mcast-proxy) from [Esdenera](https://www.esdenera.com/)
* [A collection of awesome BSD related stuff](https://github.com/DiscoverBSD/awesome-bsd)

## OpenBSD-based products

There are many products based on OpenBSD. Information about these products and the version of OpenBSD they are based on is often difficult to come by, since this fact is not widely publicised.

### OpenBSD-based commercial products

- OpenBSD packet Filter is a part of [Apple Inc.'s OS X and iOS](http://callfortesting.org/macpf/), [Oracle Solaris](https://docs.oracle.com/cd/E53394_01/html/E54829/pfovw-1.html)
- OpenSSH is a part of many commercial products
- [RTMX](http://www.rtmx.com/) sells a version of OpenBSD which has a full complement of POSIX real-time features added to it.
- [genua](https://www.genua.de/) offers sophisticated IT security solutions based on OpenBSD: The two-tier genugate system is the only firewall certified by the German Federal Office for Information Security (BSI) at E3 / high level under the ITSEC international standard.
- [Fox-IT](https://www.fox-it.com/en/) delivers specialist security and intelligence solutions for government bodies and other major organizations throughout the world. Our core business is developing solutions for the protection of state secrets, the investigation of digital crime, audits, managed security services, consulting and training courses. We use OpenBSD as a trusted platform on which the [DataDiode](http://www.datadiode.eu/) is built.
- [Esdenera Networks](https://www.esdenera.com/) Networking and security technology for modern cloud-based, decentralized, mobile and software-defined networks based on OpenBSD.
- [ATMNIS](https://atmnis.com/) - первая и единственная UNIX-подобная защищённая операционная система в Украине, сертифицированная к использованию при создании комплексных систем защиты информации (КСЗИ) классов 2 и 3. See [slides](https://www.atmnis.com/~apelsin/papers/).
- [Calyptix Security](http://www.calyptix.com/products/models/ae800/) - firewall to protect and manage SMB networks. See [slides](http://www.nycbsdcon.org/2010/presentations/lteo-nycbsdcon2010.pdf).
- [M:Tier](http://www.mtier.org/about-us/) - OpenBSD thin client (see [slides](http://www.mtier.org/assets/Uploads/latinoware-2013.pdf)), OpenBSD enterprise desktop for Fortune 500 companies (see [slides](http://www.openbsd.org/papers/opencon07-gnome.pdf) and [article](http://undeadly.org/cgi?action=article&sid=20110420080633)), [Long Term Support subscription](https://stable.mtier.org/subscriptions).
- [Mercedes Benz](http://www4.mercedes-benz.com/manual-cars/ba/foss/content/en/assets/FOSS_licences.pdf)

### OpenBSD-based opensource products

- [flashrd](http://www.nmedia.net/flashrd/)
- [Security Router](http://securityrouter.org/wiki/Main_Page)
- [MirOS](https://www.mirbsd.org/)
- [Bitrig](https://www.bitrig.org/)
- [reflash](https://stable.rcesoftware.com/resflash/)

## OpenBSD-friendly Hosting

### OpenBSD VMM-based

* [OpenBSD Amsterdam](https://openbsd.amsterdam/) - OpenBSD VMs
* [OpenBSD.space](http://openbsd.space/) - Torified OpenBSD VMs

### KVM-based

* [RootBSD](https://www.rootbsd.net/)
* [ARP Networks](https://www.arpnetworks.com/)
* [RamNode](http://ramnode.com/)
* [Digital Ocean](https://www.digitalocean.com)
* [Vultr](https://www.vultr.com/docs/setup-openbsd)
* [Hetzner](https://wiki.hetzner.de/index.php/OpenBSD)
* [BuyVM](https://buyvm.net/operating-systems/bsd-family/)
* [Linode](http://notes.eatonphil.com/2017/3/deploying-freebsd-on-linode-unattended-in-minutes.html)
* [Exoscale](http://exoscale.com/) - based on CloudStack

NOTE: It's possible to run OpenBSD [even hosting providers don't support it](https://jcs.org/notaweblog/2014/09/12/remotely_installing_openbsd_qemu/).

### Other options

* Google Compute Engine [instruction](https://marc.info/?l=openbsd-misc&m=138757967321855&w=2)
* Xen-based: [Amazon EC2](https://gist.github.com/reyk/b372af303eb86bab3fee#file-openbsd-amd64-20160809-aws)
* [Hyper-V-based](https://gist.github.com/reyk/f6d2c7b9567cae7b4270)

### Free shells

- [Devio.us](http://devio.us/)
- [Polarhome](http://www.polarhome.com/)
- [Grex](http://grex.org/)
- [Silenceisdefeat](http://silenceisdefeat.com/)
- [Free Shell Accounts](http://shells.red-pill.eu/)
- [Underlegend Networks](http://yenn.ulegend.net/)
- [obsd.pl](http://obsd.pl/)

## Jobs

- [BSDjobs](https://www.bsdjobs.com/)
- [LinkedIn](https://www.linkedin.com/jobs/openbsd-jobs)
- [StackOverflow](http://stackoverflow.com/jobs?searchTerm=openbsd)
- [jobs@lists.nycbug.org](http://lists.nycbug.org/mailman/listinfo/jobs)

## Community

* [announce@openbsd.org](https://www.openbsd.org/mail.html)
* [misc@openbsd.org](https://www.openbsd.org/mail.html)
* Twitter [@openbsdjournal](https://twitter.com/openbsdjournal)
* [/r/openbsd](https://www.reddit.com/r/openbsd/)
* [Quora](https://www.quora.com/topic/OpenBSD)
* [Google Plus](https://plus.google.com/communities/113634135604793474364)
* [#OpenBSD](http://webchat.freenode.net?channels=%23openbsd) on irc.freenode.net
* [Planet OpenBSD](http://openbsdnow.org/)
* [Gitter](https://gitter.im/BSDs/OpenBSD)
* https://unitedbsd.com/

### News

* [Undeadly](http://undeadly.org/) - OpenBSD Journal
* [Planet OpenBSD](http://openbsdnow.org/) - [src repo](https://github.com/ligurio/openbsdnow.org)
* [Lobsters OpenBSD tag](https://lobste.rs/t/openbsd)
* [reddit community](http://reddit.com/r/openbsd/)
* [Google Plus community](https://plus.google.com/communities/113634135604793474364)
* [UnitedBSD](https://unitedbsd.com/c/openbsd)

### Conferences

- [EuroBSDCon](https://eurobsdcon.org/)
- [NYCBSDCon](http://www.nycbsdcon.org/)
- [MeetBSD](http://meetbsd.org/)
- [AsiaBSDCon](https://asiabsdcon.org)
- vBSDCon
- [OpenKyiv](http://www.uaoug.org.ua/openkyiv/)
- [KyivBSD](http://ru.kyivbsd.org.ua/)
- [BSDTW](https://bsdtw.org/)
- [bhyvecon](http://bhyvecon.org/)
- BSD devroom at FOSDEM ([Twitter](https://twitter.com/fosdembsd)
- [NYCBSDCon](http://www.nycbsdcon.org) ([Twitter](https://twitter.com/nycbsdcon))

### BSD User groups

- http://www.meetup.com/topics/bsd/
- https://www.freebsd.org/usergroups.html
- http://www.openbsd.org/groups.html
- http://www.netbsd.org/community/groups.html

### Mailing lists

* [MARC](https://marc.info/):
  * [openbsd-tech](http://marc.info/?l=openbsd-tech)
  * [openbsd-cvs](http://marc.info/?l=openbsd-cvs)
  * [openbsd-ports](http://marc.info/?l=openbsd-ports)
  * [openbsd-misc](http://marc.info/?l=openbsd-misc)
* [OpenBSD weekly/daily changes list](http://www.squish.net/log/openbsd-source-changes/)

### IRC

* [#OpenBSD](https://webchat.freenode.net/#openbsd) (Freenode)

### Twitter

* [@OpenBSD](https://twitter.com/OpenBSD)
* [@OpenBSD_CVS](https://twitter.com/OpenBSD_CVS) - OpenBSD Commit messages in 140 characters or less. For individual modules, see: [@OpenBSD_src](https://twitter.com/OpenBSD_src), [@OpenBSD_ports](https://twitter.com/OpenBSD_ports), [@OpenBSD_www](https://twitter.com/OpenBSD_www), [@OpenBSD_xenocar](https://twitter.com/OpenBSD_xenocar), [@OpenBSD_stable](https://twitter.com/OpenBSD_stable), [@OpenBSD_sets](https://twitter.com/OpenBSD_sets) (all built by [Andrew Fresh](https://twitter.com/afresh1))
* [@OpenBSDJournal](https://twitter.com/openbsdjournal) - tweets to Undeadly.org stories
* [@OpenSMTPD](https://twitter.com/opensmtpd)
* [@OpenBSDNow](https://twitter.com/openbsdnow) - OpenBSD News & Updates
* [@mpotd_openbsd](https://twitter.com/mpotd_openbsd) - Man Page of The Day

### Mastodon ([bsd.network](https://bsd.network/) instance)

* [@phessler](https://bsd.network/@phessler) - bsd.network's admin
* [@AFresh1](https://bsd.network/@AFresh1)
* [@bcallah](https://bsd.network/@bcallah)
* [@romanzolotarev](https://bsd.network/@romanzolotarev)

### Telegram Groups

* [OpenBSD Jumpstart](https://t.me/joinchat/EzTjLQuG8Mcj89LYcDGKiQ) from the [OpenBSD Jumpstart](http://www.openbsdjumpstart.org/) author
* [OpenBSD Brazil](https://t.me/OpenBSDbr)
* [OpenBSD Spain](https://t.me/OpenBSD_es)

### Interviews with OpenBSD developers

* Theo de Raadt [Yandex](https://events.yandex.ru/lib/talks/1487/), [Linux.com](https://www.linux.com/news/interview-theo-de-raadt-openbsd), [KernelTrap](https://web.archive.org/web/20060421165150/http://kerneltrap.org/node/6)
* Alexander Yurchenko [eax.me](http://eax.me/eaxcast-s02e01/)
* David Gwynne [bsdtalk](http://bsdtalk.blogspot.ru/2006/05/bsdtalk046-interview-with-openbsd.html)
* Stefan Sperling [distrowatch](http://distrowatch.com/weekly.php?issue=20100517#feature), [beastie.pl](http://beastie.pl/deweloperzy-openbsd-stefan-sperling/)
* Bob Beck [bsdtalk](http://bsdtalk.blogspot.ru/2006/09/bsdtalk068-interview-with-openbsd.html)
* [Lobsters](https://lobste.rs/s/ppopah/lobsters_interview_with_ted_unangst)
* Marco Peereboom [bsdtalk](https://archive.org/details/bsdtalk027)
* Daniel Hartmeier [onlamp](http://www.onlamp.com/pub/a/bsd/2004/04/15/pf_developers.html)
* Joris Vink [bsdtalk](https://archive.org/details/bsdtalk050)
* Robert Nagy [The Document Foundation](https://blog.documentfoundation.org/blog/2011/01/21/developer-interview-robert-nagy/)
* Joshua Stein [The Setup](https://usesthis.com/interviews/joshua.stein/), [beastie.pl](http://beastie.pl/deweloperzy-openbsd-joshua-stein/)
* Marc Espie [linuxfr.org](http://linuxfr.org/news/entretien-avec-des-d%C3%A9veloppeurs-francophones-dopenbsd-partie-1)
* Gilles Chehade [bronevichok.ru](https://bronevichok.ru/blog/2014/07/29/testing-of-opensmtpd.html)
* Henning Brauer [IOException.de](http://tmp.marmaro.de/www.ioexception.de/2013/10/16/interview-henning-brauer/index.html)
* Mike Larkin [bsdtalk](http://bsdtalk.blogspot.ru/2010/08/bsdtalk195-mike-larkin.html)
* Anil Madhavapeddy [FOSDEM](https://archive.fosdem.org/2012/interview/anil-madhavapeddy.html)
* Pierre-Yves Ritschard [bsdtalk](http://bsdtalk.blogspot.ru/2007/02/bsdtalk097-openbsd-developer-pierre.html)
* Claudio Jeker [bsdtalk](http://bsdtalk.blogspot.ru/2007/01/bsdtalk095-openbsd-developer-claudio.html)
* Jason Wright [bsdtalk](http://bsdtalk.blogspot.ru/2006/11/bsdtalk082-openbsd-developer-jason.html)
* Marc Balmer [bsdtalk](http://bsdtalk.blogspot.ru/2006/10/bsdtalk076-openbsd-developer-marc.html)
* Matthieu Herrb [bsdtalk](http://bsdtalk.blogspot.ru/2007/04/bsdtalk106-interview-with-matthieu.html), [bronevichok.ru](https://bronevichok.ru/blog/2014/08/06/testing-of-xorg.html)
 
### Blogs

* [Ted Unangst](http://www.tedunangst.com/flak/)
* [Peter Hansteen](https://bsdly.blogspot.com)
* [Joshua Stein](https://jcs.org/)
* [Antoine Jacoutot](https://www.bsdfrog.org/)
* [Adam Wołk](https://blog.tintagel.pl/)
* [Nan Xiao](http://nanxiao.me/en/tag/openbsd/)
* [Roman Zolotarev](https://www.romanzolotarev.com/openbsd/)
* [Daniel Jakots](https://chown.me/)
* [Solène Rapenne](https://dataswamp.org/~solene/)
* [Jeroen a.k.a. h3artbl33d](https://h3artbl33d.nl/blog/)

## Selected articles

* [Keeping Your OpenBSD System In Trim: A Works For Me Guide](http://bsdly.blogspot.com/2012/07/keeping-your-openbsd-system-in-trim.html)
* [OpenBSD Workstation Guide](https://begriffs.com/posts/2017-05-17-openbsd-workstation-guide.html)
* [OpenBSD on a Laptop](https://www.c0ffee.net/blog/openbsd-on-a-laptop/)
* [Installing OpenBSD 6.1 on your laptop is really hard (not)](http://sohcahtoa.org.uk/openbsd.html)
* [OpenBSD 6.3: why and how](https://sivers.org/openbsd)
* [An OpenBSD Workstation](http://eradman.com/posts/openbsd-workstation.html)
* [Enlightenment on OpenBSD](http://enform.haxlab.org/)
* [An awesome OpenBSD 6.1 desktop](https://github.com/WyldePointer/openbsd-desktop) (XFCE)
* [OpenBSD Gaming Resource](http://mrsatterly.com/openbsd_games.html)
* [Screencasting with OpenBSD](http://eradman.com/posts/screencasting.html)
* [OpenBSD's Autoinstall](http://eradman.com/posts/autoinstall-openbsd.html)
* [Fail2ban on OpenBSD 6.0](http://blog.gordonturner.ca/2016/11/20/fail2ban-on-openbsd-6-0/)
* [OpenBSD on PC Engines APU2](https://github.com/elad/openbsd-apu2) - OpenBSD on [PC Engines APU2](http://www.pcengines.ch/apu2.htm)
* [OpenBSD-APU2](https://github.com/northox/openbsd-apu2) - Configuration files to setup PC Engines' APU2 as a WIFI router
* [OpenBSD on Soekris](http://wiki.soekris.info/Installing_OpenBSD)
* [Getting OpenBSD running on Raspberry Pi 3](http://undeadly.org/cgi?action=article&sid=20170409123528)
* [A simple first server](http://blog.hermes-technology.de/openbsd/server/2017/06/06/a-first-server.html) - A series of posts about OpenBSD server configuration for learning purposes
* [OpenBSD manpages reading list](https://gist.github.com/QWxleA/0a3e28f4a3387e5087e8f3608c32fd03)
* [OpenBSD porting workshop, August 11, 2018](https://www.twitch.tv/videos/296003844) - twitch.tv video by bcallah@
* [Debian on OpenBSD vmd (without qemu or another debian system)](http://www.netzbasis.de/openbsd/vmd-debian/)
* [Support of OpenBSD pledge(2) in programming languages](https://gist.github.com/ligurio/f6114bd1df371047dd80ea9b8a55c104)
* [Setup environment in OpenBSD using Ansible playbook](https://github.com/ligurio/openbsd-cookbooks)

## Desktop

- reyk@ [WindowsMaker](https://gist.github.com/reyk/80dca43c8bcfa76d2a7ff147ea64d442) and [Lenovo X1 Carbon](https://gist.github.com/reyk/80dca43c8bcfa76d2a7ff147ea64d442)
- jcs@ [ratpoison](https://github.com/jcs/ratpoison) ([shot](https://www.reddit.com/r/unixporn/comments/454i3p/ratpoison_witty_title_here/), [config](https://github.com/jcs/dotfiles), [desc](https://jcs.org/notaweblog/2009/06/30/my_mac_os_x_setup/)) and [HP Pixel Chromebook](https://jcs.org/talks/2016/09/07/chibug_openbsd_on_the_chromebook_pixel/slides)
- jasper@ cwm? https://twitter.com/jasper_la/status/773080105858007040
- henning@ fvwm https://twitter.com/HenningBrauer/status/771285626612248577
- tedu@ [Lenovo X1 Carbon](http://www.tedunangst.com/flak/post/Thinkpad-Carbon-X1-2015)?

## Third Party repositories

* [Scripts to run an OpenBSD mirror](https://github.com/bluhm/mirror-openbsd)
* [OpenBSD WiP](https://github.com/topics/openbsd-wip)
* [OpenBSD bitbucket mirror](https://bitbucket.org/braindamaged/openbsd-src) - using mercurial
* [snap, an OpenBSD upgrade tool](https://github.com/qbit/snap)
* [upobsd](https://bitbucket.org/semarie/upobsd/) - download, verify and patch bsd.rd image
* [awesome pledge(2)](https://github.com/PeterTonoli/awesome-pledge)
* [AWS-OpenBSD](https://github.com/ajacoutot/aws-openbsd) - AWS playground for OpenBSD kids
* [OpenBSD Flashboot](https://github.com/kirei/flashboot) - suitable for booting of flash devices
* [Execute Rails applications on OpenBSD](https://github.com/wesley974/railsonopenbsd)
* [dotfiles, sweet dotfiles](https://github.com/unbalancedparentheses/dotfiles)
* [fvwm-config-on-openbsd](https://github.com/bfmartin/fvwm-config-on-openbsd) - Configuration files for the FVWM window manager on a modern OpenBSD
* [dyndnsd](https://github.com/mario-campos/dyndnsd) - Dynamic DNS Daemon for OpenBSD
* [OpenMDNS](https://github.com/haesbaert/mdnsd) - [Mdns daemon for OpenBSD](http://www.haesbaert.org/openmdns/)

## OpenBSD Provisioning

* https://github.com/ligurio/openbsd-cookbooks
* http://cvs.x61.com.ar/cgi-bin/cvsweb/ansible-role-mailserver/ 
* https://github.com/martinbaillie/homebrew-openbsd-pcengines-router/
* https://github.com/northox/openbsd-apu2
* https://github.com/elad/openbsd-apu2
* https://github.com/cullum/dank-selfhosted
* https://github.com/codeghar/openbsd-on-erl
* [desktop-openbsd-starter-kit](https://github.com/matthewgraybosch/desktop-openbsd-starter-kit) - Dotfiles and config files for use with OpenBSD on a desktop or laptop
* [vedetta](https://github.com/vedetta-com/vedetta) - OpenBSD Router Boilerplate
* [caesonia](https://github.com/vedetta-com/caesonia) - OpenBSD Email Service (there's also a [Playbook for Caesonia](https://github.com/vedetta-com/ansible-role-caesonia))
* [Automated solution for hosting email, web, DNS, XMPP, and ZNC on OpenBSD](https://github.com/cullum/dank-selfhosted)

## Portable OpenBSD Components

* [OpenSMTPD](https://github.com/opensmtpd)
* [OpenIKED](https://github.com/reyk/openiked)
* [LibreSSL](https://github.com/libressl-portable/portable)
* [cwm(1)](https://github.com/chneukirchen/cwm) - portable version of OpenBSD's cwm(1) window manager
* [doas](https://github.com/Duncaen/OpenDoas)
* ksh(1): [ibara/oksh](https://github.com/ibara/oksh), [dimkr/ksh](https://github.com/dimkr/loksh)
* [file(1)](https://github.com/brynet/file)

----
Please [donate](http://www.openbsd.org/donations.html) to the OpenBSD project.

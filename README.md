# Awesome OpenBSD

*Curated list of resources about OpenBSD* :blowfish:

## Index

* [Official OpenBSD](#official-openbsd)
  * [Inside projects](#inside-projects)
* [Non-official OpenBSD websites](#non-official-openbsd-websites)
* [OpenBSD-based products](#openbsd-based-products)
  * [OpenBSD-based commercial products](#openbsd-based-commercial-products)
  * [OpenBSD-based opensource products](#openbsd-based-opensource-products)
* [Hosting](#hosting)
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
  * [Interviews with OpenBSD developers](#interviews-with-OpenBSD-developers)
  * [Blogs](#blogs)
* [Selected articles](#selected-articles)
* [Third party repositories](#third-party-repositories)
* [OpenBSD Provisioning](#openbsd-provisioning)
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

### Inside projects

* [OpenSSH](http://www.openssh.com/) - the premier connectivity tool for remote login with the SSH protocol
* [LibreSSL](http://www.libressl.org/) - a version of the TLS/crypto stack forked from OpenSSL in 2014, with goals of modernizing the codebase, improving security, and applying best practice development processes
* [OpenNTPD](http://www.openntpd.org/) - free and easy to use implementation of the Network Time Protocol
* [OpenSMTPD](https://www.opensmtpd.org/) - free implementation of the server-side SMTP protocol as defined by RFC 5321, with some additional standard extensions - [OpenSMTPD-extras](https://github.com/OpenSMTPD/OpenSMTPD-extras)
* [OpenBGPD](http://www.openbgpd.org/) - free implementation of the Border Gateway Protocol, Version 4
* [OpenIKED](http://www.openiked.org/) - free implementation of the Internet Key Exchange (IKEv2) protocol
* [mandoc](http://mdocml.bsd.lv/) - free UNIX manpage compiler toolset
* [Game of Trees](http://gameoftrees.org/) - version control system which prioritizes ease of use and simplicity over flexibility

## OpenBSD Ports

* [OpenBSD WIP](https://github.com/topics/openbsd-wip)
* [OpenBSD Ports](http://www.openports.se/) - browse the package collection
* [OpenBSD ports](http://ports.su/) - /usr/ports/databases/ports-readmes
* [M:Tier's OpenBSD packages and binpatches](https://stable.mtier.org/) - security updates in both packages and base system
* [portroach](https://portroach.openbsd.org/) - OpenBSD Ports Distfile Scanner

## Helpful Sites

* [OpenBSD GIT mirrors](https://github.com/openbsd/) - OpenBSD CVS repository conversions for public consumpiton (managed by OpenBSD hackers)
* [OpenBSD Testing Infrastructure](http://bluhm.genua.de/) -  infrastructure for semi-automatic testing of source code changes
* [OpenBSD QA wiki](https://github.com/ligurio/openbsd-tests/wiki)
* [mdoc.su](http://mdoc.su/) - URL shortener for BSD manual pages
* [bxr.su OpenGrok](http://bxr.su/) - powerful search on OpenBSD (and other project) code
* [Status of OpenBSD mirrors](http://spacehopper.org/mirmon/top.html) - 150+ sites in 30 regions
* [OpenBSD Wikipedia page](https://en.wikipedia.org/wiki/OpenBSD)
* [Multicast Proxy for OpenBSD](https://github.com/Esdenera/mcast-proxy)
* [A collection of awesome BSD related stuff](https://github.com/DiscoverBSD/awesome-bsd)
* [OpenBSD JumpStart](http://www.openbsdjumpstart.org/) - Learn to tame OpenBSD quickly
* [OpenBSD and you](https://home.nuug.no/~peter/openbsd_and_you/) - How to have fun with the world’s most important free software project (by Peter Hansteen)
* [PF and Networking Tutorial](https://home.nuug.no/~peter/pftutorial/) - on BSDCan 2018 by Peter Hansteen and Massimiliano Stucchi
* [OpenBSD Daily](https://blog.tintagel.pl/2017/06/09/openbsd-daily.html) - [mulander/openbsd-daily](https://github.com/mulander/openbsd-daily) - official repository with all openbsd-daily reading by mulander and duncaen

## OpenBSD stats

* [OpenBSD stats](http://www.oxide.org/cvs) - CVS commit stats
* [OpenBSD community metrics](https://github.com/ligurio/notebooks/tree/master/oss-metrics/OpenBSD)

## OpenBSD-based products

There are many products based on OpenBSD. Information about these products and
the version of OpenBSD they are based on is often difficult to come by, since
this fact is not widely publicised.

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

### OpenBSD-based opensource products

- [Security Router](http://securityrouter.org/wiki/Main_Page)
- [MirOS](https://www.mirbsd.org/) (Not in active development)
- [Bitrig](https://www.bitrig.org/)
- [reflash](https://stable.rcesoftware.com/resflash/)

## Hosting

* `vmm` [OpenBSD Amsterdam](https://openbsd.amsterdam/)
* `kvm` [RootBSD](https://www.rootbsd.net/)
* `kvm` [ARP Networks](https://www.arpnetworks.com/)
* `kvm` [RamNode](http://ramnode.com/)
* `kvm` [Digital Ocean](https://www.digitalocean.com)
* `kvm` [Vultr](https://www.vultr.com/docs/setup-openbsd)
* `kvm` [Hetzner](https://wiki.hetzner.de/index.php/OpenBSD)
* `kvm` [BuyVM](https://buyvm.net/operating-systems/bsd-family/)
* `kvm` [Exoscale](http://exoscale.com/)
* `kvm` [Google Compute Engine](https://marc.info/?l=openbsd-misc&m=138757967321855&w=2)
* `xen` [Amazon EC2](https://gist.github.com/reyk/b372af303eb86bab3fee#file-openbsd-amd64-20160809-aws)
* `hyper-v` [Azure Devops](https://gist.github.com/reyk/f6d2c7b9567cae7b4270)
* `shell` [Devio.us](http://devio.us/)
* `shell` [Polarhome](http://www.polarhome.com/)
* `shell` [Grex](http://grex.org/)
* `shell` [Free Shell Accounts](http://shells.red-pill.eu/)
* `shell` [tilde.institute](https://tilde.institute/) of OpenBSD Education

## Jobs

- [StackOverflow](http://stackoverflow.com/jobs?searchTerm=openbsd)
- [jobs@lists.nycbug.org](http://lists.nycbug.org/mailman/listinfo/jobs)

## Community

* [Quora](https://www.quora.com/topic/OpenBSD)
* [StackOverflow](https://stackoverflow.com/questions/tagged/openbsd)
* https://unitedbsd.com/

### News

* [Undeadly](http://undeadly.org/) - OpenBSD Journal
* [Planet OpenBSD](https://bronevichok.ru/openbsdnow/) - [src repo](https://github.com/ligurio/openbsdnow.org)
* [Lobsters OpenBSD tag](https://lobste.rs/t/openbsd)
* [Reddit /r/openbsd](http://reddit.com/r/openbsd/)

### Conferences

- [EuroBSDCon](https://eurobsdcon.org/)
- [NYCBSDCon](http://www.nycbsdcon.org/)
- [AsiaBSDCon](https://asiabsdcon.org)
- [vBSDCon](https://www.verisign.com/en_US/internet-technology-news/verisign-events/vbsdcon/index.xhtml)
- [OpenKyiv](http://www.uaoug.org.ua/openkyiv/)
- [BSDTW](https://bsdtw.org/)
- [bhyvecon](http://bhyvecon.org/)
- BSD devroom at FOSDEM ([Twitter](https://twitter.com/fosdembsd))
- [NYCBSDCon](http://www.nycbsdcon.org) ([Twitter](https://twitter.com/nycbsdcon))

### BSD User groups

- http://www.meetup.com/topics/bsd/
- https://www.freebsd.org/usergroups.html
- http://www.openbsd.org/groups.html
- http://www.netbsd.org/community/groups.html

### Mailing lists

* https://www.openbsd.org/mail.html
* [MARC](https://marc.info/):
  * [openbsd-tech](http://marc.info/?l=openbsd-tech)
  * [openbsd-cvs](http://marc.info/?l=openbsd-cvs)
  * [openbsd-ports](http://marc.info/?l=openbsd-ports)
  * [openbsd-misc](http://marc.info/?l=openbsd-misc)

### Chats

* `gitter` https://gitter.im/BSDs/OpenBSD
* `irc` [#OpenBSD](http://webchat.freenode.net?channels=%23openbsd) on irc.freenode.net
* `telegram` [OpenBSD Jumpstart](https://t.me/joinchat/EzTjLQuG8Mcj89LYcDGKiQ)
* `telegram` [OpenBSD Brazil](https://t.me/OpenBSDbr)
* `telegram` [OpenBSD Spain](https://t.me/OpenBSD_es)

### Twitter

* [@OpenBSD](https://twitter.com/OpenBSD)
* [@OpenBSD_CVS](https://twitter.com/OpenBSD_CVS) - OpenBSD Commit messages in 140 characters or less. For individual modules, see: [@OpenBSD_src](https://twitter.com/OpenBSD_src), [@OpenBSD_ports](https://twitter.com/OpenBSD_ports), [@OpenBSD_www](https://twitter.com/OpenBSD_www), [@OpenBSD_xenocar](https://twitter.com/OpenBSD_xenocar), [@OpenBSD_stable](https://twitter.com/OpenBSD_stable), [@OpenBSD_sets](https://twitter.com/OpenBSD_sets) (all built by [Andrew Fresh](https://twitter.com/afresh1))
* [@OpenBSDJournal](https://twitter.com/openbsdjournal) - tweets to Undeadly.org stories
* [@OpenSMTPD](https://twitter.com/opensmtpd)
* [@OpenBSDNow](https://twitter.com/openbsdnow) - OpenBSD News & Updates
* [@mpotd_openbsd](https://twitter.com/mpotd_openbsd) - Man Page of The Day

### Mastodon

* [bsd.network](https://bsd.network/)
* [@phessler](https://bsd.network/@phessler) - bsd.network's admin
* [@AFresh1](https://bsd.network/@AFresh1)
* [@bcallah](https://bsd.network/@bcallah)
* [@romanzolotarev](https://bsd.network/@romanzolotarev)
* [@akpoff](https://bsd.network/@akpoff)
* [@brynet](https://bsd.network/@brynet)
* [@h3artbl33d](https://bsd.network/@h3artbl33d)
* [@OpenBSDAms](https://bsd.network/@OpenBSDAms)
* [@openbsdnow](https://bsd.network/@openbsdnow)
* [@polishdub](https://bsd.network/@polishdub)

### Interviews with OpenBSD developers

* Bryan Steele (brynet@) [beastie.pl](https://web.archive.org/web/20160328131143/http://beastie.pl/deweloperzy-openbsd-bryan-steele/)
* Theo de Raadt [Yandex](https://events.yandex.ru/lib/talks/1487/), [Linux.com](https://www.linux.com/news/interview-theo-de-raadt-openbsd), [KernelTrap](https://web.archive.org/web/20060421165150/http://kerneltrap.org/node/6)
* Alexander Yurchenko [eax.me](http://eax.me/eaxcast-s02e01/)
* David Gwynne [bsdtalk](http://bsdtalk.blogspot.ru/2006/05/bsdtalk046-interview-with-openbsd.html)
* Stefan Sperling [distrowatch](http://distrowatch.com/weekly.php?issue=20100517#feature)
* Bob Beck [bsdtalk](http://bsdtalk.blogspot.ru/2006/09/bsdtalk068-interview-with-openbsd.html)
* Marco Peereboom [bsdtalk](https://archive.org/details/bsdtalk027)
* Daniel Hartmeier [onlamp](http://www.onlamp.com/pub/a/bsd/2004/04/15/pf_developers.html)
* Joris Vink [bsdtalk](https://archive.org/details/bsdtalk050)
* Robert Nagy [The Document Foundation](https://blog.documentfoundation.org/blog/2011/01/21/developer-interview-robert-nagy/)
* Joshua Stein [The Setup](https://usesthis.com/interviews/joshua.stein/), [beastie.pl]( https://web.archive.org/web/20160304043723/http://beastie.pl/deweloperzy-openbsd-joshua-stein/)
* Marc Espie [linuxfr.org](http://linuxfr.org/news/entretien-avec-des-d%C3%A9veloppeurs-francophones-dopenbsd-partie-1), [beastie.pl](https://web.archive.org/web/20160404154248/http://beastie.pl/deweloperzy-openbsd-marc-espie/)
* Gilles Chehade [bronevichok.ru](https://bronevichok.ru/blog/2014/07/29/testing-of-opensmtpd.html), [beastie.pl](https://web.archive.org/web/20160304040101/http://beastie.pl/deweloperzy-openbsd-gilles-chehade/ )
* Henning Brauer [IOException.de](http://tmp.marmaro.de/www.ioexception.de/2013/10/16/interview-henning-brauer/index.html), [beastie.pl](https://web.archive.org/web/20160304040842/http://beastie.pl/deweloperzy-openbsd-henning-brauer/)
* Mike Larkin [bsdtalk](http://bsdtalk.blogspot.ru/2010/08/bsdtalk195-mike-larkin.html)
* Anil Madhavapeddy [FOSDEM](https://archive.fosdem.org/2012/interview/anil-madhavapeddy.html)
* Pierre-Yves Ritschard [bsdtalk](http://bsdtalk.blogspot.ru/2007/02/bsdtalk097-openbsd-developer-pierre.html)
* Claudio Jeker [bsdtalk](http://bsdtalk.blogspot.ru/2007/01/bsdtalk095-openbsd-developer-claudio.html)
* Jason Wright [bsdtalk](http://bsdtalk.blogspot.ru/2006/11/bsdtalk082-openbsd-developer-jason.html)
* Marc Balmer [bsdtalk](http://bsdtalk.blogspot.ru/2006/10/bsdtalk076-openbsd-developer-marc.html)
* Matthieu Herrb [bsdtalk](http://bsdtalk.blogspot.ru/2007/04/bsdtalk106-interview-with-matthieu.html), [bronevichok.ru](https://bronevichok.ru/blog/2014/08/06/testing-of-xorg.html)
* Ingo Schwarze (schwarze@) [beastie.pl](https://web.archive.org/web/20160404205317/http://beastie.pl/deweloperzy-openbsd-ingo-schwarze/)
* Vadim Zhukov (zhuk@) [beastie.pl](https://web.archive.org/web/20160304045614/http://beastie.pl/deweloperzy-openbsd-vadim-zhukov/)
* Dmitrij Czarkoff (czarkoff@) [beastie.pl](https://web.archive.org/web/20160304041801/http://beastie.pl/deweloperzy-openbsd-dmitrij-d-czarkoff/)
* Landry Breuil (landry@) [beastie.pl](https://web.archive.org/web/20160304044831/http://beastie.pl/deweloperzy-openbsd-landry-breuil/)
* Ted Unangst (tedu@) [beastie.pl](https://web.archive.org/web/20160304045544/http://beastie.pl/deweloperzy-openbsd-ted-unangst/), [Lobsters](https://lobste.rs/s/ppopah/lobsters_interview_with_ted_unangst)
* Brandon Mercer (bmercer@) [beastie.pl](https://web.archive.org/web/20160304051407/http://beastie.pl/deweloperzy-openbsd-brandon-mercer/)
* Antoine Jacoutot (ajacoutot@) [beastie.pl](https://web.archive.org/web/20160304052709/http://beastie.pl/deweloperzy-openbsd-antoine-jacoutot/)
* Stefan Sperling (stsp@) [beastie.pl](https://web.archive.org/web/20160304044753/http://beastie.pl/deweloperzy-openbsd-stefan-sperling/)

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
* [Configuring SNMP v3 on OpenBSD 6.4](https://thefreecountry.wordpress.com/2018/11/27/configuring-snmp-v3-on-openbsd-6-4/)
* [An OpenBSD Workstation](http://eradman.com/posts/openbsd-workstation.html)
* [Enlightenment on OpenBSD](http://enform.haxlab.org/)
* [An awesome OpenBSD 6.1 desktop](https://github.com/WyldePointer/openbsd-desktop) (XFCE)
* [OpenBSD Gaming Resource](http://mrsatterly.com/openbsd_games.html)
* [Screencasting with OpenBSD](http://eradman.com/posts/screencasting.html)
* [OpenBSD's Autoinstall](http://eradman.com/posts/autoinstall-openbsd.html)
* [Fail2ban on OpenBSD 6.0](http://blog.gordonturner.ca/2016/11/20/fail2ban-on-openbsd-6-0/)
* [OpenBSD on Soekris](http://wiki.soekris.info/Installing_OpenBSD)
* [Getting OpenBSD running on Raspberry Pi 3](http://undeadly.org/cgi?action=article&sid=20170409123528)
* [A simple first server](http://blog.hermes-technology.de/openbsd/server/2017/06/06/a-first-server.html) - A series of posts about OpenBSD server configuration for learning purposes
* [OpenBSD manpages reading list](https://gist.github.com/QWxleA/0a3e28f4a3387e5087e8f3608c32fd03)
* [OpenBSD porting workshop, August 11, 2018](https://www.twitch.tv/videos/296003844) - twitch.tv video by bcallah@
* [Debian on OpenBSD vmd (without qemu or another debian system)](http://www.netzbasis.de/openbsd/vmd-debian/)
* [Support of OpenBSD pledge(2) in programming languages](https://gist.github.com/ligurio/f6114bd1df371047dd80ea9b8a55c104)

## Third Party repositories

* [Scripts to run an OpenBSD mirror](https://github.com/bluhm/mirror-openbsd)
* [snap, an OpenBSD upgrade tool](https://github.com/qbit/snap)
* [upobsd](https://bitbucket.org/semarie/upobsd/) - download, verify and patch bsd.rd image
* [awesome pledge(2)](https://github.com/PeterTonoli/awesome-pledge)
* [AWS-OpenBSD](https://github.com/ajacoutot/aws-openbsd) - AWS playground for OpenBSD kids
* [OpenBSD Flashboot](https://github.com/kirei/flashboot) - suitable for booting of flash devices
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

## Portable OpenBSD Components

* [OpenSMTPD](https://github.com/opensmtpd)
* [OpenIKED](https://github.com/reyk/openiked)
* [LibreSSL](https://github.com/libressl-portable/portable)
* [cwm(1)](https://github.com/chneukirchen/cwm) - portable version of OpenBSD's cwm(1) window manager
* [doas](https://github.com/Duncaen/OpenDoas)
* ksh(1): [ibara/oksh](https://github.com/ibara/oksh), [dimkr/ksh](https://github.com/dimkr/loksh)
* [file(1)](https://github.com/brynet/file)

----
Please [donate](https://www.openbsd.org/donations.html) to the OpenBSD project.

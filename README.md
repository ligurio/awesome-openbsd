# Awesome OpenBSD

*Curated list of resources about OpenBSD* :blowfish:

## Index

* [Official OpenBSD](#official-openbsd)
* [Projects around OpenBSD](#projects-around-openbsd)
* [OpenBSD Stats](#openbsd-stats)
* [OpenBSD-based projects](#openbsd-based-projects)
* [Hosting](#hosting)
* [Virtualization](#virtualization)
* [CI](#ci)
* [Jobs](#jobs)
* [Community](#community)
  * [News](#news)
  * [Conferences](#conferences)
  * [BSD user groups](#bsd-user-groups)
  * [Mailing lists](#mailing-lists)
  * [Chats](#chats)
  * [Twitter](#twitter)
  * [Mastodon](#mastodon)
  * [Interviews with OpenBSD developers](#interviews-with-OpenBSD-developers)
  * [Blogs](#blogs)
  * [OpenBSD Countries Communities](#openbsd-countries-communities)
* [Selected articles](#selected-articles)
* [Videos](#videos)
* [Third party repositories](#third-party-repositories)
* [OpenBSD Provisioning](#openbsd-provisioning)
* [Portable OpenBSD Components](#portable-openbsd-components)
* [OpenBSD Developers](#openbsd-developers)

## Official OpenBSD

* [OpenBSD Project](https://www.openbsd.org/)
* [OpenBSD Foundation](https://www.openbsdfoundation.org/)
* OpenBSD Umbrella:
  * [OpenSSH](https://www.openssh.com/) - the premier connectivity tool for remote login with the SSH protocol
  * [LibreSSL](https://www.libressl.org/) - a version of the TLS/crypto stack forked from OpenSSL in 2014, with goals of modernizing the codebase, improving security, and applying best practice development processes
  * [OpenNTPD](http://www.openntpd.org/) - free and easy to use implementation of the Network Time Protocol
  * [OpenSMTPD](https://www.opensmtpd.org/) - free implementation of the server-side SMTP protocol as defined by RFC 5321
  * [OpenBGPD](http://www.openbgpd.org/) - free implementation of the Border Gateway Protocol, Version 4
  * [rpki-client](https://www.rpki-client.org/) - free and easy-to-use implementation of the RPKI for Relying Parties (RP) to facilitate validation of the Route Origin of a BGP announcement
  * [mandoc](http://mdocml.bsd.lv/) - free UNIX manpage compiler toolset
  * [Game of Trees](http://gameoftrees.org/) - version control system which prioritizes ease of use and simplicity over flexibility

## Projects around OpenBSD

* [OpenBSD GIT mirrors](https://github.com/openbsd/) - OpenBSD CVS repository conversions for public consumpiton (managed by OpenBSD hackers)
* [OpenBSD Testing Infrastructure](http://bluhm.genua.de/) -  infrastructure for semi-automatic testing of source code changes
* [OpenBSD Kernel fuzzer](https://syzkaller.appspot.com/openbsd) - kernel fuzzer, syzkaller, uses declarative description of syscall interfaces to manipulate programs (sequences of syscalls).
* [OpenBSD dmesg collection](https://dmesgd.nycbug.org/index.cgi?do=index&fts=OpenBSD) - user-submitted repository of OpenBSD dmesgs.
* [Hardware for OpenBSD](https://bsd-hardware.info/?d=OpenBSD) - anonymously collect hardware details of BSD-powered computers.
* [Unofficial OpenBSD Testing](https://github.com/ligurio/openbsd-tests/)
* [mdoc.su](http://mdoc.su/) - URL shortener for BSD manual pages
* [bxr.su](https://bxr.su/) - powerful search on OpenBSD, NetBSD and FreeBSD (and other project) code bases
* [Status of OpenBSD mirrors](https://spacehopper.org/mirmon/top.html)
* [OpenBSD WIP](https://github.com/topics/openbsd-wip) - unofficial OpenBSD ports
* [OpenBSD ports](http://ports.su/) - `/usr/ports/databases/ports-readmes`
* [OpenBSD Ports Readme](https://openports.pl/) - [maintained by @solene](https://dataswamp.org/~solene/2022-10-21-openports.pl.html)
* [OpenBSD.app package search](https://openbsd.app/) - also maintained by @solene
* [M:Tier's OpenBSD packages and binpatches](https://stable.mtier.org/) - security updates in both packages and base system
* [portroach](https://portroach.openbsd.org/) - OpenBSD Ports Distfile Scanner
* [Why OpenBSD rocks - The facts](https://why-openbsd.rocks/)
* [OpenBSD Handbook](https://www.openbsdhandbook.com/)
* [OpenBSD Howto](https://www.bsdhowto.ch/)
* [OpenBSD Router Guide](https://openbsdrouterguide.net/)

## OpenBSD stats

* [OpenBSD stats](http://www.oxide.org/cvs) - CVS commit stats
* [OpenBSD community metrics](https://github.com/ligurio/notebooks/tree/master/oss-metrics/OpenBSD)

## OpenBSD-based projects

- `closed-source` [genua](https://www.genua.de/) offers sophisticated IT security solutions based on OpenBSD: The two-tier genugate system is the only firewall certified by the German Federal Office for Information Security (BSI) at E3 / high level under the ITSEC international standard.
- `closed-source` [Calyptix Security](https://www.calyptix.com/products/models/) - firewall to protect and manage SMB networks. See [slides](http://www.nycbsdcon.org/2010/presentations/lteo-nycbsdcon2010.pdf).
- `closed-source` [M:Tier](https://www.mtier.org/about-us/): OpenBSD thin client ([slides](http://www.mtier.org/assets/Uploads/latinoware-2013.pdf)), OpenBSD enterprise desktop for Fortune 500 companies ([slides](http://www.openbsd.org/papers/opencon07-gnome.pdf) and [article](http://undeadly.org/cgi?action=article&sid=20110420080633)), [Long Term Support subscription](https://stable.mtier.org/subscriptions).
- `opensource` [reflash](https://stable.rcesoftware.com/resflash/)
- `opensource` [FuguIta](http://fuguita.org/) is a live system based on OpenBSD that is designed to run from removable media. Note a portion of documentation is only available in Japanese.

## Hosting

* `vmm` [OpenBSD Amsterdam](https://openbsd.amsterdam/)
* `kvm` [RootBSD](https://www.rootbsd.net/)
* `kvm` [ARP Networks](https://www.arpnetworks.com/)
* `kvm` [RamNode](https://ramnode.com/)
* `kvm` [Digital Ocean](https://www.digitalocean.com) ([How-To](https://www.going-flying.com/blog/openbsd-on-digitalocean.html))
* `kvm` [Vultr](https://www.vultr.com/docs/setup-openbsd)
* `kvm` [Hetzner](https://wiki.hetzner.de/index.php/OpenBSD)
* `kvm` [BuyVM](https://buyvm.net/operating-systems/bsd-family/)
* `kvm` [Exoscale](http://exoscale.com/)
* `kvm` [Google Compute Engine](https://marc.info/?l=openbsd-misc&m=138757967321855&w=2)
* `kvm` [Data Center Light](https://twitter.com/reykfloeter/status/1146714795552509952)
* `xen` [Amazon EC2](https://gist.github.com/reyk/b372af303eb86bab3fee#file-openbsd-amd64-20160809-aws)
* `xen` [AWS-OpenBSD](https://github.com/ajacoutot/aws-openbsd) - AWS playground for OpenBSD kids
* `xen` [TornadoVPS](https://tornadovps.com/) ([How-To Setup](https://tornadovps.com/documentation/openbsd))(formerly prgmr.com)
* `hyper-v` [Azure Devops](https://gist.github.com/reyk/f6d2c7b9567cae7b4270)
* `shell` [Devio.us](https://devio.us/)
* `shell` [Polarhome](https://www.polarhome.com/)
* `shell` [Free Shell Accounts](https://shells.red-pill.eu/)
* `shell` [tilde.institute](https://tilde.institute/) of OpenBSD Education
* `bhyve` [bhyve.cloud](https://bhyve.cloud/)

## Virtualization

* [Vagrant support](https://github.com/double-p/vagrant-openbsd)
* [Packer support](https://github.com/double-p/packer-builder-openbsd-vmm)

## CI

- [Appveyor](https://github.com/appveyor/ci/issues/2844) (In progress)
- [Cirrus CI](https://cirrus-ci.org/features/) - [FreeBSD support](https://cirrus-ci.org/guide/supported-computing-services/), [OpenBSD support WIP](https://github.com/cirruslabs/cirrus-ci-docs/issues/311)
- [Sourcehut](https://man.sr.ht/builds.sr.ht/compatibility.md#openbsd) - OpenBSD, FreeBSD and NetBSD support
- GitLab ([HowTo](https://frankgroeneveld.nl/2016/04/06/using-gitlab-ci-multi-runner-on-openbsd/)), [sysutils/gitlab-runner](http://openbsd-archive.7691.n7.nabble.com/new-sysutils-gitlab-runner-td365939.html#a365948)
- Travis CI ([Running FreeBSD in Travis-CI](https://erouault.blogspot.com/2016/09/running-freebsd-in-travis-ci.html))
- MinCI https://github.com/kristapsdz/minci

## Jobs

- [StackOverflow](https://stackoverflow.com/jobs?searchTerm=openbsd)
- [jobs@lists.nycbug.org](https://lists.nycbug.org/mailman/listinfo/jobs)

## Community

* [Quora](https://www.quora.com/topic/OpenBSD)
* [StackOverflow](https://stackoverflow.com/questions/tagged/openbsd)

### News

* [Undeadly](https://undeadly.org/) - OpenBSD Journal
* [OpenBSD Webzine](https://webzine.puffy.cafe/)
* [Planet OpenBSD](https://bronevichok.ru/openbsdnow/) - [src repo](https://github.com/ligurio/openbsdnow.org)
* [Lobsters OpenBSD tag](https://lobste.rs/t/openbsd)
* [Reddit /r/openbsd](https://reddit.com/r/openbsd/)

### Conferences

- [EuroBSDCon](https://eurobsdcon.org/)
- [NYCBSDCon](https://www.nycbsdcon.org/)
- [AsiaBSDCon](https://asiabsdcon.org)
- [BSDCan](https://www.bsdcan.org/)
- [vBSDCon](https://www.verisign.com/en_US/internet-technology-news/verisign-events/vbsdcon/index.xhtml)
- [OpenKyiv](https://www.uaoug.org.ua/openkyiv/)
- [BSDTW](https://bsdtw.org/)
- [bhyvecon](https://bhyvecon.org/)
- BSD devroom at FOSDEM ([Twitter](https://twitter.com/fosdembsd))
- [NYCBSDCon](https://www.nycbsdcon.org) ([Twitter](https://twitter.com/nycbsdcon))

### BSD User groups

- https://www.meetup.com/topics/bsd/
- https://www.freebsd.org/usergroups.html
- https://www.openbsd.org/groups.html
- https://www.netbsd.org/community/groups.html

### Mailing lists

* https://www.openbsd.org/mail.html
* [MARC](https://marc.info/):
  * [openbsd-tech](https://marc.info/?l=openbsd-tech)
  * [openbsd-cvs](https://marc.info/?l=openbsd-cvs)
  * [openbsd-ports](https://marc.info/?l=openbsd-ports)
  * [openbsd-misc](https://marc.info/?l=openbsd-misc)

### Chats

* `gitter` https://gitter.im/BSDs/OpenBSD
* `irc` [#OpenBSD](https://web.libera.chat/?channels=#openbsd) on irc.libera.chat
* `irc` [#OpenBSD-Russian](http://webchat.freenode.net?channels=%23openbsd-russian) on irc.freenode.net
* `matrix` [OpenBSD](https://matrix.to/#/%23openbsd%3Amatrix.org)
* `telegram` [OpenBSD Jumpstart](https://t.me/joinchat/EzTjLQuG8MdUSVqFS1xA4w)
* `telegram` [OpenBSD English](https://t.me/openbsd_en)
* `telegram` [OpenBSD Russian](https://t.me/openbsd_ru)
* `telegram` [OpenBSD Chinese](https://t.me/openbsd_zh)
* `telegram` [OpenBSD Brazil](https://t.me/OpenBSDbr)
* `telegram` [OpenBSD Spain](https://t.me/OpenBSD_es)
* `telegram` [BSDar Argentina](https://t.me/BSDar)

### Twitter

* [@OpenBSD](https://twitter.com/OpenBSD)
* [OpenBSD Commits To Twitter](https://github.com/afresh1/openbsd-commits-to-twitter) (maintained by [Andrew Fresh](https://twitter.com/afresh1))
* [@OpenBSDJournal](https://twitter.com/openbsdjournal) - tweets to Undeadly.org stories
* [@OpenSMTPD](https://twitter.com/opensmtpd)
* [@OpenBSDNow](https://twitter.com/openbsdnow) - OpenBSD News & Updates
* [@mpotd_openbsd](https://twitter.com/mpotd_openbsd) - Man Page of The Day

### Mastodon

* [OpenBSD Commits To Mastodon](https://github.com/danieljakots/openbsd-commits-to-mastodon)
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
* Alexander Yurchenko [eax.me](https://eax.me/eaxcast-s02e01/)
* David Gwynne [bsdtalk](https://bsdtalk.blogspot.ru/2006/05/bsdtalk046-interview-with-openbsd.html)
* Stefan Sperling [distrowatch](https://distrowatch.com/weekly.php?issue=20100517#feature)
* Bob Beck [bsdtalk](https://bsdtalk.blogspot.ru/2006/09/bsdtalk068-interview-with-openbsd.html)
* Marco Peereboom [bsdtalk](https://archive.org/details/bsdtalk027)
* Daniel Hartmeier [onlamp](https://www.onlamp.com/pub/a/bsd/2004/04/15/pf_developers.html)
* Joris Vink [bsdtalk](https://archive.org/details/bsdtalk050)
* Robert Nagy [The Document Foundation](https://blog.documentfoundation.org/blog/2011/01/21/developer-interview-robert-nagy/)
* Joshua Stein [The Setup](https://usesthis.com/interviews/joshua.stein/), [beastie.pl]( https://web.archive.org/web/20160304043723/http://beastie.pl/deweloperzy-openbsd-joshua-stein/)
* Marc Espie [linuxfr.org](https://linuxfr.org/news/entretien-avec-des-d%C3%A9veloppeurs-francophones-dopenbsd-partie-1), [beastie.pl](https://web.archive.org/web/20160404154248/http://beastie.pl/deweloperzy-openbsd-marc-espie/)
* Gilles Chehade [bronevichok.ru](https://bronevichok.ru/blog/2014/07/29/testing-of-opensmtpd.html), [beastie.pl](https://web.archive.org/web/20160304040101/http://beastie.pl/deweloperzy-openbsd-gilles-chehade/ )
* Henning Brauer [IOException.de](https://tmp.marmaro.de/www.ioexception.de/2013/10/16/interview-henning-brauer/index.html), [beastie.pl](https://web.archive.org/web/20160304040842/http://beastie.pl/deweloperzy-openbsd-henning-brauer/)
* Mike Larkin [bsdtalk](https://bsdtalk.blogspot.ru/2010/08/bsdtalk195-mike-larkin.html)
* Anil Madhavapeddy [FOSDEM](https://archive.fosdem.org/2012/interview/anil-madhavapeddy.html)
* Pierre-Yves Ritschard [bsdtalk](http://bsdtalk.blogspot.ru/2007/02/bsdtalk097-openbsd-developer-pierre.html)
* Claudio Jeker [bsdtalk](https://bsdtalk.blogspot.ru/2007/01/bsdtalk095-openbsd-developer-claudio.html)
* Jason Wright [bsdtalk](https://bsdtalk.blogspot.ru/2006/11/bsdtalk082-openbsd-developer-jason.html)
* Marc Balmer [bsdtalk](https://bsdtalk.blogspot.ru/2006/10/bsdtalk076-openbsd-developer-marc.html)
* Matthieu Herrb [bsdtalk](http://bsdtalk.blogspot.ru/2007/04/bsdtalk106-interview-with-matthieu.html), [bronevichok.ru](https://bronevichok.ru/blog/2014/08/06/testing-of-xorg.html)
* Ingo Schwarze (schwarze@) [beastie.pl](https://web.archive.org/web/20160404205317/http://beastie.pl/deweloperzy-openbsd-ingo-schwarze/)
* Vadim Zhukov (zhuk@) [beastie.pl](https://web.archive.org/web/20160304045614/http://beastie.pl/deweloperzy-openbsd-vadim-zhukov/)
* Dmitrij Czarkoff (czarkoff@) [beastie.pl](https://web.archive.org/web/20160304041801/http://beastie.pl/deweloperzy-openbsd-dmitrij-d-czarkoff/)
* Landry Breuil (landry@) [beastie.pl](https://web.archive.org/web/20160304044831/http://beastie.pl/deweloperzy-openbsd-landry-breuil/)
* Ted Unangst (tedu@) [beastie.pl](https://web.archive.org/web/20160304045544/http://beastie.pl/deweloperzy-openbsd-ted-unangst/), [Lobsters](https://lobste.rs/s/ppopah/lobsters_interview_with_ted_unangst)
* Brandon Mercer (bmercer@) [beastie.pl](https://web.archive.org/web/20160304051407/http://beastie.pl/deweloperzy-openbsd-brandon-mercer/)
* Antoine Jacoutot (ajacoutot@) [beastie.pl](https://web.archive.org/web/20160304052709/http://beastie.pl/deweloperzy-openbsd-antoine-jacoutot/)
* Stefan Sperling (stsp@) [beastie.pl](https://web.archive.org/web/20160304044753/http://beastie.pl/deweloperzy-openbsd-stefan-sperling/)

## OpenBSD Countries Communities

* [OpenBSD Brazil](https://openbsd-br.org)
* [OpenBSD Pour Tous (France)](https://openbsd.fr.eu.org/)

## Selected articles

* [Keeping Your OpenBSD System In Trim: A Works For Me Guide](https://bsdly.blogspot.com/2012/07/keeping-your-openbsd-system-in-trim.html)
* [OpenBSD Workstation Guide](https://begriffs.com/posts/2017-05-17-openbsd-workstation-guide.html)
* [OpenBSD on a Laptop](https://www.c0ffee.net/blog/openbsd-on-a-laptop/)
* [Installing OpenBSD 6.1 on your laptop is really hard (not)](https://sohcahtoa.org.uk/openbsd.html)
* [OpenBSD 6.3: why and how](https://sivers.org/openbsd)
* [Configuring SNMP v3 on OpenBSD 6.4](https://thefreecountry.wordpress.com/2018/11/27/configuring-snmp-v3-on-openbsd-6-4/)
* [An OpenBSD Workstation](https://eradman.com/posts/openbsd-workstation.html)
* [Enlightenment on OpenBSD](https://enform.haxlab.org/)
* [An awesome OpenBSD 6.1 desktop](https://github.com/WyldePointer/openbsd-desktop) (XFCE)
* [OpenBSD Gaming Resource](https://mrsatterly.com/openbsd_games.html)
* [Screencasting with OpenBSD](https://eradman.com/posts/screencasting.html)
* [OpenBSD's Autoinstall](https://eradman.com/posts/autoinstall-openbsd.html)
* [Fail2ban on OpenBSD 6.0](https://blog.gordonturner.ca/2016/11/20/fail2ban-on-openbsd-6-0/)
* [Getting OpenBSD running on Raspberry Pi 3](https://undeadly.org/cgi?action=article&sid=20170409123528)
* [A simple first server](https://blog.hermes-technology.de/openbsd/server/2017/06/06/a-first-server.html) - A series of posts about OpenBSD server configuration for learning purposes
* [OpenBSD manpages reading list](https://gist.github.com/QWxleA/0a3e28f4a3387e5087e8f3608c32fd03)
* [OpenBSD porting workshop, August 11, 2018](https://www.twitch.tv/videos/296003844) - twitch.tv video by bcallah@
* [Debian on OpenBSD vmd (without qemu or another debian system)](https://www.netzbasis.de/openbsd/vmd-debian/)
* [Nextcloud with OpenBSD](https://docs.nextcloud.com/server/latest/admin_manual/installation/example_openbsd.html)
* [Dendrite (Matrix server) with OpenBSD](https://x61.sh/log/2022/10/20221021T153746-dendrite.html)
* [Backups with Bupstash on OpenBSD](https://x61.sh/log/2022/01/20220117T191751-backups.html)
* [Wireguard on OpenBSD](https://x61.sh/log/2022/01/20220104T122904-wireguard.html)
* [GoT on OpenBSD](https://x61.sh/log/2022/01/20220127T190458-got.html)
* [K3s cluster over vmm on OpenBSD](https://x61.sh/log/2022/09/20220926T143151-openbsd_alpine_k3s_cluster.html)
* [Rspamd dashboard with Relayd](https://x61.sh/log/2022/10/20221027T115439-rspamd-dashboard.html)

## Videos

* [An Introduction to OpenBSD](https://www.youtube.com/watch?v=EkDVKthufAM)
* [OpenBSD talks, interviews and guides](https://www.youtube.com/playlist?list=PLbET-7keUM8qdq16cDrx-dw2SVXBLH4hk)
* [The OpenBSD guy channel](https://www.youtube.com/@TheOpenBSDguy)

## Third Party repositories

* [Scripts to run an OpenBSD mirror](https://github.com/bluhm/mirror-openbsd)
* [snap, an OpenBSD upgrade tool](https://github.com/qbit/snap)
* [upobsd](https://bitbucket.org/semarie/upobsd/) - download, verify and patch bsd.rd image
* [dyndnsd](https://github.com/mario-campos/dyndnsd) - Dynamic DNS Daemon for OpenBSD
* [OpenMDNS](https://github.com/haesbaert/mdnsd) - [Mdns daemon for OpenBSD](http://www.haesbaert.org/openmdns/)
* [awesome pledge(2)](https://github.com/PeterTonoli/awesome-pledge)
* [Support of OpenBSD pledge(2) in programming languages](https://gist.github.com/ligurio/f6114bd1df371047dd80ea9b8a55c104)
* [A collection of awesome BSD related stuff](https://github.com/DiscoverBSD/awesome-bsd)
* [OpenBSD JumpStart](https://www.openbsdjumpstart.org/) - Learn to tame OpenBSD quickly
* [OpenBSD and you](https://home.nuug.no/~peter/openbsd_and_you/) - How to have fun with the world’s most important free software project (by Peter Hansteen)
* [PF and Networking Tutorial](https://home.nuug.no/~peter/pftutorial/) - on BSDCan 2018 by Peter Hansteen and Massimiliano Stucchi
* [OpenBSD Daily](https://blog.tintagel.pl/2017/06/09/openbsd-daily.html) - [mulander/openbsd-daily](https://github.com/mulander/openbsd-daily) - official repository with all openbsd-daily reading by mulander and duncaen

## OpenBSD Provisioning

* https://github.com/ligurio/openbsd-cookbooks
* https://git.sr.ht/~gonzalo/ansible-role-mailserver
* https://git.sr.ht/~gonzalo/apu2_setup
* https://git.sr.ht/~gonzalo/vmm_setup
* https://github.com/martinbaillie/homebrew-openbsd-pcengines-router/
* https://github.com/northox/openbsd-apu2
* https://github.com/elad/openbsd-apu2
* https://github.com/cullum/dank-selfhosted
* https://github.com/codeghar/openbsd-on-erl
* [vedetta](https://github.com/vedetta-com/vedetta) - OpenBSD Router Boilerplate
* [caesonia](https://github.com/vedetta-com/caesonia) - OpenBSD Email Service (there's also a [Playbook for Caesonia](https://github.com/vedetta-com/ansible-role-caesonia))
* [dotfiles, sweet dotfiles](https://github.com/unbalancedparentheses/dotfiles)
* [fvwm-config-on-openbsd](https://github.com/bfmartin/fvwm-config-on-openbsd) - Configuration files for the FVWM window manager on a modern OpenBSD
* [ohmyksh](https://github.com/qbit/ohmyksh) - A framework for OpenBSD's ksh
* [openbsd.run](https://openbsd.run/) - An OpenBSD-focused Ansible playbook embedded in type-annotated Python

## Portable OpenBSD Components

* [OpenSMTPD](https://github.com/opensmtpd)
* [OpenIKED](https://github.com/reyk/openiked)
* [LibreSSL](https://github.com/libressl-portable/portable)
* [cwm(1)](https://github.com/chneukirchen/cwm) - portable version of OpenBSD's cwm(1) window manager
* [doas](https://github.com/Duncaen/OpenDoas)
* ksh(1): [ibara/oksh](https://github.com/ibara/oksh), [dimkr/ksh](https://github.com/dimkr/loksh)
* [file(1)](https://github.com/brynet/file)

## OpenBSD Developers

- https://github.com/fcambus
- https://github.com/mbelop
- https://github.com/omoerbeek
- jcs@ https://github.com/jcs
- djm@ https://github.com/djmdjm
- bluhm@ https://github.com/bluhm
- https://github.com/pirofti
- https://github.com/kristapsdz
- https://github.com/semarie
- https://github.com/jasperla
- https://github.com/ajacoutot
- https://github.com/bob-beck
- https://github.com/afresh1
- https://github.com/yasuoka
- https://github.com/reyk
- https://github.com/shadchin
- https://github.com/vext01
- https://github.com/tedu
- https://github.com/grayed
- https://github.com/nicm
- https://github.com/mfriedl
- https://github.com/hallexander
- https://github.com/ratchov
- https://github.com/ischwarze
- https://github.com/qbit
- https://github.com/cjeker
- https://github.com/rnagy
- https://github.com/millert
- https://github.com/poolpOrg
- https://github.com/busterb
- https://github.com/marcespie
- https://github.com/bsdkurt

----
Please [donate](https://www.openbsd.org/donations.html) to the OpenBSD project.

# Chevereto

> 🔔 [Subscribe](https://newsletter.chevereto.com/subscription?f=PmL892XuTdfErVq763PCycJQrvZ8PYc9JbsVUttqiPV1zXt6DDtf7lhepEStqE8LhGs8922ZYmGT7CYjMH5uSx23pL6Q) to don't miss any update regarding Chevereto.

![Chevereto](LOGO.svg)

[![Discord](https://img.shields.io/discord/759137550312407050?style=flat-square)](https://chv.to/discord)

Chevereto is a multi-user, full-featured media sharing solution. It's your services. Your rules, your eyes. Say goodbye to closures, restrictions and data mining on your media.

In a nutshell, Chevereto is:

- 👨🏾‍💻 An indie developed [mature project](#history)
- ❤ A large [Community](https://chevereto.com/community/)
- 🤯 Used everywhere, including at [high scale](#-powered-by-chevereto)
- 🔌 Extensible, configurable and pluggable
- ⚖ Open Source Software

## Technical Overview

This is the repository for the Chevereto V4 application project skeleton, which orchestrates the whole thing. In Chevereto, [API](https://github.com/Chevereto/api) provides all the I/O for user instructions which are driven by the application. The administration for the user application content is provided by [API Admin](https://github.com/Chevereto/api-admin).

On the other hand, [Peafowl](https://github.com/Chevereto/peafowl) and [Dashboard](https://github.com/Chevereto/dashboard) are the default web clients for API and API Admin. The concept of "default" is very important here because Chevereto is _built_ to be plugged to _any_ given interface, is not limited to just the defaults, and hopefully it will get _many_ cool user interfaces.

Chevereto also provides an OAuth2 server supporting third-party login providers, which handles account access, sessions and credentials. That way, Chevereto API-client users connect to the same login experience regardless of the user interface being used. In this context, the given user interface appears to the user as an application authorized to the account.

## 🚀 Powered by Chevereto

There are many Chevereto installations out there, probably you have already use it without even knowing it. Chevereto installations vary, each one hosting from zero up to _n_ million images. The following [notable public websites](https://chevereto.top/) are using Chevereto (any release).

| Website                                   | Images |
| ----------------------------------------- | ------ |
| [add.pics](https://add.pics/)             | 44K    |
| [comss.pics](https://comss.pics/)         | 56k    |
| [Forumbilder](https://forumbilder.com/)   | 1M     |
| [Freeimage.host](https://freeimage.host/) | 100K   |
| [Gifyu](https://gifyu.com/)               | 3M     |
| [ImageRide](https://imageride.com/)       | 170K   |
| [ImgBB](https://imgbb.com/)               | 1M+    |
| [imgchr](https://imgchr.com/)             | 5M     |
| [imghub.io](https://imghub.io/)           | 15k    |
| [imgyukle](https://imgyukle.com/)         | ??     |
| [ipev.ru](https://ipev.ru/)               | 250K   |
| [Jerking](https://jerking.empornium.ph/)  | ??     |
| [lensdump](https://lensdump.com/)         | ??     |
| [nickpic](https://nickpic.host/)          | 2M     |
| [qpix](https://qpix.com/)                 | 520K   |
| [UPLD.IM](https://upld.im/)               | 174K   |

## Contribution

Developers (and those wanting to become) are welcome! Join our [Discord](https://chv.to/discord) channel for more into this.

❤ You can also [donate](https://paypal.me/RodolfoBerrios) to support my work. I thank **very much** all my [donors](DONORS.md).

## Donate

Development of this software is a life project that has consumed many years of my time. **I don't work for any company**, I'm not backed by anyone else except users of this software.

## History

Chevereto project began in 2007 as a self-hosted alternative to ImageShack when they blocked the images on my forum and it started as a simple one-click web uploader. It got good reception, and it became an Open Source project. I started this on college and I made my career around it.

During all these years many things have happened, licensing has changed a couple of times and to keep it short on August 2016 a fork, named [Chevereto-Free](https://github.com/chevereto/chevereto-free), was released to kickstart the process of turning all Chevereto into Open Source.

### Major Releases

| Version                                            | Date       | Licensing (release) | Licensing (actual) |
| -------------------------------------------------- | ---------- | ------------------- | ------------------ |
| [V1](https://code.google.com/archive/p/chevereto/) | 2009-02-26 | MIT License         | MIT License        |
| [V2](https://github.com/chevereto/chevereto-2)     | 2011-06-15 | Proprietary         | MIT License        |
| [V3](https://chevereto.com/releases)               | 2014-04-05 | Proprietary         | Proprietary (*)    |
| [V4](https://github.com/chevereto/chevereto)       | TBD        | MIT License         | MIT License        |

(*) V3 will eventually merge with Chevereto-Free into MIT license.

## Funding

Funding core concepts are pending release (is a quite hard task to monetize Open Source). For now, you can read [Thoughts on monetizing Chevereto installations](https://rodolfo.is/2021/01/20/thoughts-on-monetize-chevereto-installations/) which outlines my way of think and the business that I hope you can spawn with Chevereto.

## License

Copyright [Rodolfo Berrios A.](https://rodolfoberrios.com/) Chevereto is licensed under the [MIT license](LICENSE).

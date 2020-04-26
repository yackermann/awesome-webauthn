# WebAuthn Awesome [![Awesome](https://github.com/sindresorhus/awesome/blob/master/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome WebAuthn/FIDO2 resources

- [WebAuthn Awesome](#WebAuthn-Awesome)
  - [Demos](#demos)
  - [Server Libs](#server-libs)
  - [Client Libs](#client-libs)
  - [Software Authenticators](#software-authenticators)
  - [Hardware Authenticators](#hardware-authenticators)

- [Resources](#resources)
  - [Tutorials](#tutorials)
  - [Articles](#articles)
  - [Slides](#slides)
  - [Books](#books)

- [FAQ](#faq)
- [Contributions guidelines](./CONTRIBUTIONS.md)
- [License](#license)

## Demos
 - [FIDO: WebAuthn Demo](https://github.com/fido-alliance/webauthn-demo) - FIDO Alliance WebAuthn Demo
 - [DUO: WebAuthn Demo](https://github.com/duo-labs/webauthn.io) - A Demonstration of the WebAuthn Specification https://webauthn.io/
 - [Mastercard: WebAuthn Demo](https://github.com/Mastercard/fido2-rp-spring) - Webauthn/FIDO2 Relying Party Reference Implementation
 - [Adam Powers: WebAuthn Demo](https://github.com/apowers313/fido2-server-demo) - A set of FIDO2 / WebAuthn demo servers. Live: https://webauthn.org
 - [Anders Åberg: .NET library for FIDO2 Demo](https://github.com/abergs/fido2-net-lib) - A working implementation library + demo for FIDO2 and WebAuthn using .NET. https://fido2.azurewebsites.net/
 - [Auth0: WebAuthn Demo](https://webauthn.me/) - Probably the best WebAuthn flow demo
 - [Google: WebAuthn Demo](https://github.com/google/webauthndemo) - An example Java Relying Party implementation of the WebAuthn specification. [https://webauthndemo.appspot.com](https://webauthndemo.appspot.com)
 - [Yubico: WebAuthn Demo](https://demo.yubico.com/webauthn) - Provides technical details of WebAuthn data flow and includes a playground to test a U2F/FIDO2 key as a second factor or passwordless key.
 - [jcjones: WebAuthn.bin.coffee DEMO](https://github.com/jcjones/webauthn.bin.coffee) - A simple site for testing Web Authentication https://webauthn.bin.coffee/
 - [FIDO Alliance: Interop WebApp](https://github.com/fido-alliance/fido2-interop-webapp) - As simple test app for FIDO2 servers
 - [Spomky-Labs: Webauthn Demo](http://webauthn.spomky-labs.com) - a demo based on Symfony and the PHP framework [web-auth/webauthn-framework](https://github.com/web-auth/webauthn-framework)
 - [Yuriy Ackermann: FIDO2 Demos](https://github.com/herrjemand/FIDO2WebAuthnSeries) - A set of demos for ["Introduction to WebAuthn API"](https://medium.com/@herrjemand/introduction-to-webauthn-api-5fd1fb46c285)
 - [Shane Weeden: FIDO2 Viewer](https://github.com/sbweeden/fido2viewer) - This is a free, simple, standalone-in-the-browser viewer for FIDO2 attestation and assertion payload inspection.

## Server Libs
 - `FIDO CERTIFIED™` [Strong Key: FIDO2 Server](https://github.com/StrongKey/fido2) - Open-source FIDO server, featuring the FIDO2 standard.
 - `FIDO CONFORMANT` [Anders Åberg: .NET library for FIDO2](https://github.com/abergs/fido2-net-lib) - A working implementation library + demo for fido2 and WebAuthn using .NET
 - `FIDO CONFORMANT` [WebAuthn4J Project: WebAuthn4J](https://github.com/webauthn4j/webauthn4j) - A portable Java library for WebAuthn server side verification 
 - `FIDO CONFORMANT` [DUO: WebAuthn Go library](https://github.com/duo-labs/webauthn) - WebAuthn library written in Go.
 - [DUO: A WebAuthn Python module](https://github.com/duo-labs/py_webauthn) - PyWebAuthn is a Python module which can be used to handle WebAuthn registration and assertion. 
 - [Yubico: Java WebAuthn Server](https://github.com/Yubico/java-webauthn-server) - Server-side Web Authentication library for Java. 
 - [Adam Powers: FIDO2 lib](https://github.com/apowers313/fido2-lib)
 - [Nov Matake: Ruby WebAuthn Lib](https://github.com/nov/web_authn) - W3C Web Authentication API (a.k.a. WebAuthN / FIDO 2.0) RP library in Ruby
 - [Yubico: python-fido2](https://github.com/Yubico/python-fido2) - FIDO2 Client and Server lib
 - [cedarcode: WebAuthn Ruby](https://github.com/cedarcode/webauthn-ruby) - Ruby implementation of a WebAuthn Relying Party
 - [Tangui: Wax](https://github.com/tanguilp/wax) - Elixir implementation of WebAuthn
 - [Suby Raman: redux-webauthn](https://github.com/subyraman/redux-webauthn) - Redux middleware for registering and authenticating users with the Web Authentication API (FIDO2).
 - [Firstyear: WebAuthn-RS](https://github.com/Firstyear/webauthn-rs) - An implementation of webauthn components for Rustlang servers
 - [Koesie10: WebAuthn](https://github.com/koesie10/webauthn) - Go/JS WebAuthn Library for easy Server/Client integation
 - [SharpLab: Spring-Security-WebAuthn](https://github.com/sharplab/spring-security-webauthn) - Unofficial WebAuthn module for the Spring Security project
 - [Spomky-Labs: WebAuthn Framework](https://github.com/web-auth/webauthn-framework) - This framework contains PHP libraries and Symfony bundle to allow developpers to integrate FIDO2 authentication mechanism into their web applications.
- [Wallix: @webauthn/server](https://github.com/wallix/webauthn) - A NodeJS library containing easy-to-use helpers to integrate FIDO2. Works in pair with [@webauthn/client](https://github.com/wallix/webauthn).
- [asbiin: laravel-webauthn](https://github.com/asbiin/laravel-webauthn) - A Laravel adapter for the WebAuthn Framework (from Spomky-Labs).
- [e3b0c442: warp](https://github.com/e3b0c442/warp) - A framework-independent Relying Party implemnetation for Go

## Client Libs
 - [Yubico: python-fido2](https://github.com/Yubico/python-fido2) - Client Lib to talk to a hardware authenticators over USB HID
 - [Yubico: libfido2](https://github.com/Yubico/libfido2) - C client library and command-line tools to communicate with a FIDO device over USB, and to verify attestation and assertion signatures.
 - [keys.pub: go-libfido2](https://github.com/keys-pub/go-libfido2) - Go client library (wraps Yubico: libfido2)
 - [Lyo Kato: iOS Webauthn Kit](https://github.com/lyokato/WebAuthnKit) - This library provides you a way to handle W3C Web Authentication API (a.k.a. WebAuthN / FIDO 2.0) easily.
 - [Radoslav Bodó: soft-webauthn](https://github.com/bodik/soft-webauthn) - Python software webauthn token
 - [Yubico: Mobile iOS SDK (YubiKit)](https://github.com/Yubico/yubikit-ios) - YubiKit is an iOS library provided by Yubico to interact with YubiKeys on iOS devices. Works with other FIDO2 devices as well
 - [Mozilla: authenticator-rs](https://github.com/mozilla/authenticator-rs/) - Rust library to interact with Security Keys, used by Firefox
 
## Software Authenticators
 - [Damian Czaja: android-webauthn-token](https://github.com/Trojan295/android-webauthn-token) - A FIDO2 WebAuthn BLE Android phone token
 - [Fabian Henneke: WearAuthn](https://github.com/FabianHenneke/WearAuthn) - FIDO2 Bluetooth HID/NFC soft token for Wear OS watches with support for resident keys
 
## Hardware Authenticators
- `FIDO CERTIFIED™` [SoloKeys](https://github.com/solokeys) - Solo is an open source FIDO2 security key, and you can get one at solokeys.com
- `FIDO CONFORMANT` [Conor Patrick: U2F Zero](https://github.com/conorpp/u2f-zero) - U2F Zero is an open source U2F token for 2 factor authentication.
- [Trezor](https://github.com/trezor/trezor-core/tree/master/src/apps/webauthn) - Trezor is an open source hardware wallet with FIDO/U2F and FIDO2/WebAuthn functionality.
- [Google: OpenSK](https://github.com/google/OpenSK) - OpenSK is an open-source implementation for security keys written in Rust that supports both FIDO U2F and FIDO2 standards.

# Resources
## Tutorials
 - [Introduction to WebAuthn API](https://medium.com/@herrjemand/introduction-to-webauthn-api-5fd1fb46c285)
 - [FIDO WebAuthn Workshop](https://slides.com/fidoalliance/jan-2018-fido-seminar-webauthn-tutorial)
 - [WebAuthn Guide: DUOSEC](https://webauthn.guide/)
 - [Yubico: Securing a Website with Passwordless Authentication](https://github.com/YubicoLabs/java-webauthn-passwordless-workshop)
 - [Google: Your First WebAuthn](https://codelabs.developers.google.com/codelabs/webauthn-reauth/#0) - An awesome WebAuthn introduction by Eiji Kitamura @ Google
## Articles
 - [Yuriy Ackermann: WebAuthn/FIDO2 Blog](https://medium.com/@herrjemand)
 - [Auth0: Introduction to Web Authentication](https://auth0.com/blog/introduction-to-web-authentication/)
 - [Watahani のブログ](https://blog.haniyama.com/) - 技術メモとか料理ネタとか
 - [Eiji Kitamura: Credential Management API and best practices](https://medium.com/dev-channel/sign-in-on-the-web-credential-management-api-and-best-practices-d21aed14b6fe)
 - [FIDO блог Юрия Аккерманна на Хабре](https://habr.com/users/herrjemand/posts/) - Статьи о FIDO на русском
 - [Ken¥d のブログ](https://ken5scal.hatenablog.com/) - セキュリティ, Android, Cloud Nativeについてまとめるブログです
 - [gebo: CTAP2 お勉強メモ ブログ](https://qiita.com/gebo)
 - [上野博司/super_reader: Yahoo! JAPANでの生体認証の取り組み（FIDO2サーバーの仕組みについて](https://techblog.yahoo.co.jp/advent-calendar-2018/webauthn/)
 - [パスワードレス認証WebAuthnの勘所と対応状況](https://gihyo.jp/dev/column/newyear/2019/webauthn)
 - [パスワードの不要な世界はいかにして実現されるのか - FIDO2 と WebAuthn の基本を知る](https://blog.agektmr.com/2019/03/fido-webauthn.html)
 - [Damien Bod: ASP.NET CORE IDENTITY WITH FIDO2 WEBAUTHN MFA](https://damienbod.com/2019/08/06/asp-net-core-identity-with-fido2-webauthn-mfa/) - This article shows how Fido2 WebAuthn could be used as 2FA and integrated into an ASP.NET Core Identity application.
 - [Paul Stamatiou: Getting started with security keys](https://paulstamatiou.com/getting-started-with-security-keys/) - How to stay safe online and prevent phishing with FIDO2, WebAuthn and security keys. (Less technical but a very usefull article)
 - [Adam Powers FIDO Alliance: The Truth about Attestation ](https://fidoalliance.org/fido-technotes-the-truth-about-attestation/) - A woundeful tech article about attestations
 - [Henrik Loeser (data-henrik): FIDO2-related blog articles](https://blog.4loeser.net/search/label/FIDO2) - FIDO2 keys on Linux and for cloud services
## Slides
 - [FIDO Alliance: WebAuthn Overview](https://slides.com/fidoalliance/webauthn-overview)
 - [Implementing FIDO on Android Side using com.google.android.gms.fido.fido2](https://speakerdeck.com/ken5scal/deep-dive-to-com-dot-google-dot-android-dot-gms-dot-fido-dot-fido2)

## Books
 - [Getting started with WebAuthn](https://my-transistor.booth.pm/items/1157260) - コミックマーケット95で頒布した同人誌「Getting started with WebAuthn」の電子版(PDF)です。
 
 ## Other
 - [Adam Powers: WebAuthn Logos](https://github.com/apowers313/webauthn-logos) - An awesome logos by Adam Powers

## FAQ


 - **What is `FIDO CERTIFIED™`?**

`FIDO CERTIFIED` means that implementation has passed FIDO conformance tools, passed interoperability even, and has achieved official FIDO Alliance certification. A registered FIDO Alliance Trademark.

 - **What is `FIDO CONFORMANT`?**

`FIDO CONFORMANT` means that implementation has passed FIDO conformance tools (as reported by the author), thus can claim that it is conformant with FIDO2 specifications. If you want to get access to the conformance tools, you can do it here https://fidoalliance.org/certification/functional-certification/conformance/. If you have passed conformance tools, send me a DM or a tweet [@herrjemand](https://twitter.com) with a screenshot of passing the tests.
 
 - **FIDO2 or WebAuthn?**

FIDO2 is the name of the standard. WebAuthn is just browser JS API to talk to the authenticators. So correct way to call your server is "FIDO2 Server" and to say "Authentication with FIDO2".

 - **I would like to advertise my company product here!**

Please don't. The advertisement you can get is by writing a good, deep, technical article, or open sourcing your server or/and tools is much better for you, than cheap show off. People will buy your company product if you show them that you know what you are doing.

Otherwise we have strict no ads policy. We will only link to open source repos and actual articles. No company websites.

## License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

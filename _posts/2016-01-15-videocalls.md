---
layout: post
title: "Videocalls state"
permalink: /videocalls-state/
---

TLDR: commonly not accessible XMPP feature. Badly maintained or just absent in client implementations.

Tried to make calls with Jitsi, Gajim, Pidgin, webapps Jappix and JSXC - nothing worked in this domain setup.

But I am obsessed with an idea to bring this feature to decent.im users. Decent.im is supposed to be ass-kicking!

For your information, I am working on implementing Jingle calls in Conversations, please join to [Bountysource campaign](https://www.bountysource.com/issues/18153806-support-audio-video-calls-encryption/backers) to appreciate me (and/or competitors).

Still cannot get Jappix or JSXC webapps to work with calls on this server, despite my numerous attempts.

But a kind person Philipp Hancke from operators@xmpp.org ML pointed to [this brilliant test page](https://legastero.github.io/jingle-interop-demos/stanzaio/), which just works without any issue! This testing page is by far the most accessible and convenient way to make calls with Jabber! :) Also works the same good way in both Chrome and Firefox, which feels exceptional.

In other words, you can go on and make your calls using that test page! Just be sure to enter full JID (with resource part) into participant JID input. The full JID of the connection made by this page shows up on the page itself. WebSocket URL is wss://decent.im:5281/xmpp-websocket


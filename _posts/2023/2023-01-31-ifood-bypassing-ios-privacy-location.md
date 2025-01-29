---
layout: post
title: "Was this Brazilian major app bypassing Apple's location privacy on iOS?"
date: 2023-01-31 11:30:00 -0300
--- 
One of the biggest Brazilian apps/startups, [iFood](https://www.ifood.com.br/), was peeking at iOS users location when it should've not.

A reader of _Manual do Usuário_ (my Portuguese-written blog) noticed the glitch/bug while using iOS 16.2.

iFood, Brazilian largest food delivering app evaluated at [USD 5.4 billion](https://www.bloomberglinea.com/english/ifood-hits-54b-valuation-surpasses-colombian-rival-rappi/), was accessing his location when not open/in use, bypassing an iOS setting that restrict an app's access to certain phone's features. Even when the reader completely denied location access to it, iFood's app continued to access his phone's location.

![Two screenshots showing iFood accessing iPhone location even when denied to do so.](/assets/2023/ifood-bypassing-ios-privacy-location/ifood-bypassing-ios-location-privacy.jpg)

We got intrigued: how was iFood getting away with this?

An educated guess was revealed by [iOS 16.3 release notes](https://support.apple.com/en-us/HT213606), launched on January 23th. Apple mentions a security issue in Maps in that “an app may be able to bypass Privacy preferences”. It's [CVE-2023-23503](https://www.cve.org/CVERecord?id=CVE-2023-23503), submitted by an anonymous researcher and, so far, “reserved” in CVE's system — which means details are pending to be published.

The reader who noticed iFood's misbehavior said that afterwards, he reseted his iPhone and that apparently solved the issue. He promptly updated to iOS 16.3 as soon it was released. So far, he haven't notice anything unusual.

I contacted iFood's press team to get a word about this issue. They received my request, asked for more details, but haven't provided a statement so far. When they reply, I'll update this post.

**Update (February 1st, 17h35):** iFood just sent a statement. Here it goes (my translation):

>iFood reinforces that data security is a priority in its business and in the relationship with consumers, deliverers, and restaurants. The data collected is used only for the purposes set out in our [Privacy Statement](https://institucional.ifood.com.br/abrindo-a-cozinha/declaracao-privacidade-clientes/#capitulo-4).
>
>In this case, after careful analysis by the technology team, no code was identified in the iFood application that allows access to the user's location without authorization, but even so, the company remains available to clarify any questions on the subject or any alleged failure, in order to contribute to bringing more security to the platform. 
>
>Present in over 1,700 cities in Brazil and a reference in online delivery, iFood constantly invests in security, technology and monitoring to identify and correct possible flaws and continuous improvement of the application.
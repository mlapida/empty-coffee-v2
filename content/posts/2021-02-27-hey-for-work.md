---
title: "HEY for Work: Getting Personal"
date: 2021-02-27
description: Sharing the experience of using HEY for Work for a personal, custom domain name.
slug: /hey-for-work-personal/
author:
  name: "Mike Lapidakis"
  image: "https://empty.coffee/cdn-cgi/imagedelivery/3iqqzuCu4mz697Mt3VX2wA/69194722-6f88-4268-402b-a24f5c3daf00/tiny"
  twitter: "@MikeLapidakis"
thumbnail: "https://empty.coffee/cdn-cgi/imagedelivery/3iqqzuCu4mz697Mt3VX2wA/6b18f08a-db5c-4f57-c040-6d7003534200/thumbnail"
image: "https://empty.coffee/cdn-cgi/imagedelivery/3iqqzuCu4mz697Mt3VX2wA/6b18f08a-db5c-4f57-c040-6d7003534200/hero"
categories: [Services, Apps, Email, HEY, Fastmail]
---

Last summer I [wrote up some of my initial thoughts about HEY](/on-hey-email/), a new email service from the creators of Basecamp. I concluded that, while I enjoyed the interface and workflow, I didn’t love that I had to forward in emails from a custom domain provider or switch to their @hey.com email address. At the time, the HEY team promised custom domain support within a year.

Six months later and the team launched [HEY for Work](https://hey.com/work/), a variant of HEY intended for professional use with the ability to use a custom domain. I received an invitation to try out HEY for Work in January and have since completely migrated my custom domain from Fastmail.

I’m using HEY for Work for personal use as the ability to use a custom domain was a significant driver. HEY for Work costs nearly 50% more than standard HEY ($144/year vs $99/year), though you pay monthly rather than annually and there are a handful of additional features included. In this post, I’ll cover the setup, the new features, and observations while using HEY for Work for personal domains.

As a note, changing email services that use a custom domain can be nerve-racking. There’s a period of time when changes aren’t fully propagated, and you’ll receive emails to both services. Having confidence that your emails are still getting through and not ending up in the spam folder can also be a concern. I don’t take switching email providers lightly.

## Setup

![HEY for Work Setup](https://empty.coffee/cdn-cgi/imagedelivery/3iqqzuCu4mz697Mt3VX2wA/6f0eba27-d6d3-4853-db94-d1a8e178e500/post)

Setting up HEY for Work is straightforward, assuming you know your way around configuring domain names. You first sign up, specifying a domain name and backup email. Then you must verify ownership of the domain by adding a small text record to the root of your domain. The setup wizard does a fantastic job of reading existing records and coaching you through the process.

![HEY for Work Domain Configuration](https://empty.coffee/cdn-cgi/imagedelivery/3iqqzuCu4mz697Mt3VX2wA/2483297a-0b31-4566-eb67-e73ea8ed7100/post)

After ownership is confirmed, you’ll be prompted to add user accounts and configure billing. Finally, the wizard will ask you to adjust the DKIM, DMARC, and MX records, making it clear that once complete, emails will begin to flow into HEY. The most glaring missing feature is the ability to migrate mail into the service. I’m not sure how a company of a reasonable size would feel comfortable moving to HEY without the ability to import old emails.

For personal use, with one user, this setup was a breeze. The HEY for Work wizard confirms the correct entries at each step, reducing concerns around misconfigurations that may lead to lost email.

## Features

HEY for Work has all the marquee features of HEY, including the unique workflow, the fantastic search, the screener, and more. It also adds a few nice-to-have collaboration features such as “collections”, a place to share groups of emails with others and extensions, the ability to set up addresses beyond the user accounts (i.e. support@devops.shoes).

HEY has implemented the ability to [link multiple accounts together](https://hey.com/link-multiple-accounts/). For me, I linked my original @hey.com account with my new HEY for Work hosted custom domain. This provides a unified experience with visual indicators in the form of shapes dictating which address received the email. HEY has also made it easy for this configuration to extend beyond a single client; each place I’m logged in shares the linked accounts and matching shapes. It’s one of the better multi-account integrations I’ve come across.

![HEY for Work Deliverability](https://empty.coffee/cdn-cgi/imagedelivery/3iqqzuCu4mz697Mt3VX2wA/e6643b8b-2b56-4f5a-4495-7f2b147e1300/post)

On deliverability, one of the areas that concerns me the most when hosting email for a custom domain, HEY for Work knocks it out of the park. In my initial testing, HEY for Work successfully delivers my emails to the recipients’ inbox every time, avoiding the dreaded spam folder. When running a deliverability test, my HEY for Work email scores perfectly.

## Impressions

For hosting a personal domain, HEY for Work is nearly perfect. All of HEY’s marquee features translate over, and some new and improved features have been added including "extensions". Since switching over a month ago, I haven’t experienced a single issue sending or receiving emails. If you’ve tried and enjoyed HEY, and were holding out for custom email support to completely dive in, now’s the time.

The experience isn’t without some shortcomings. HEY for Work only support one domain name, which is a real bummer. Paying for a bunch of HEY for Work accounts to use with other domains I own isn’t a reasonable option. I’m also disappointed with HEY’s approach to portability. While I understand their version of email is unique and import/export of emails would be challenging, I do think it’s a required feature for a service as critical as email. Not being able to import old emails, and concerns on the ability to search and archive emails exported form HEY, is the biggest issue I have for my ongoing use of HEY for Work. I hope they reconsider this decision.

## Conclusion

Wrapping up, if you own a domain that acts as your primary personal email address today, and have found HEY’s email workflow compelling, it’s worth giving HEY for Work a try. At $12 per user/month, it’s definitely not the cheapest way to host your email. After using HEY for six months, I can say the feature set is enough to keep me hooked, as it has improved the signal-to-noise ratio of modern email. I also appreciate their robust [privacy](https://hey.com/spy-trackers/) and [security](https://hey.com/security/) features. Overall, I’ve enjoyed HEY's reinvention of email, and I’m pleased that I can now use my email domain with the service. I’m also looking forward to experiencing where the HEY team takes email next.

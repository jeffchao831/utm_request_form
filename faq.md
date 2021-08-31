# UTM Builder Library  <!-- omit in toc -->

## Table of Contents <!-- omit in toc -->
- [Medium Definition & Usage Scenario](#medium-definition--usage-scenario)
  - [Paid Search](#paid-search)
  - [Paid Social](#paid-social)
  - [Social](#social)
  - [Display](#display)
  - [Text](#text)
  - [Email](#email)
  - [Video](#video)
  - [QRCode](#qrcode)
- [FAQ](#faq)
  - [I got two links that have same medium and same source. How to divide the traffic in this case?](#i-got-two-links-that-have-same-medium-and-same-source-how-to-divide-the-traffic-in-this-case)
  - [I use banner link and text link in the email. What kind of utm_medium should I choose?](#i-use-banner-link-and-text-link-in-the-email-what-kind-of-utm_medium-should-i-choose)
  - [Something](#something)

## Medium Definition & Usage Scenario

### Paid Search
- The link is displayed as cpc in search engine.

### Paid Social
- The link is displayed as any type of AD in the social media platform.

### Social
- The link is posted in the organic social post.
- The link is posted by channel partner in their social account. 

### Display
- The link is displayed as banner or image in common website.

### Text
- The link is displayed as text in common website.

### Email
- The link is displayed as any type of format in an email.

### Video
- The link is posted in the video platform, e.g., Youtube, Youku and etc.

### QRCode
- The link is displayed as QR Code in physical material.

## FAQ

### I got two links that have same medium and same source. How to divide the traffic in this case?

You can use "utm_content" to add additional information, then you can base on utm_content to divide the traffic.

Multiple AD type in the LinkedIn's paid social.

| utm_medium  | utm_source | utm_content |
| ----------- | ---------- | ----------- |
| paid-social | LinkedIn   | ad-im       |
| paid-social | LinkedIn   | ad-image    |

Multiple email material from a channel partner.

| utm_medium | utm_source     | utm_content  |
| ---------- | -------------- | ------------ |
| email      | ChannelPartner | newsletter_1 |
| email      | ChannelPartner | newsletter_2 |

### I use banner link and text link in the email. What kind of utm_medium should I choose?

If the user will see the link in an email.
- No matter how link be displayed, choose "Email" as utm_medium.

If the user will see the link in a common website.
- The link is displayed as banner/image, then choose "Display" as utm_medium.
- The link is displayed as text, then choose "Text" as utm_medium.

### Something
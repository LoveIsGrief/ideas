# Why

[Firefox's official forums](https://www.mozilla.org/en-US/about/forums/#extension-development) are a mailing list \(mozillazine isn't affiliated to them and additionally isn't using SSL/TLS!\).

I never was a fan of mailing lists as it needed my email and the display isn't too nice. Quite frankly, the interface is quite lacking.

# Goal

A forum or reddit-like interface.

# How

Mailing list software has [archives](https://mail.mozilla.org/pipermail/dev-addons/) from which are easily accessible. It would be a matter of writing a parser \(or using an existing one if that does exist\) and displaying it correctly.

In order to contribute \(write\) to the mail list, it would need to have access to an email address and be sure that access was granted to the mailing list.

## Web

Access to the email would need to be done most likely over OAuth, so only a few sites would be possible.

## Gui

It could possibly be intergrated as an extension for thunderbird, since it already has access to the email account.


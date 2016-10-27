
# AME2016: Automatic Mail Encryption unconf + hackathon

It's high time we get emails end-to-end encrypted for massively more users than today.  The AME2016 meetup at the Onion Offices in Berlin is where we want to discuss how to achieve that.  The gathering is meant to be a meetup of mail client developers, crypto researchers and people involved with standardization, useability and other cross-cutting concerns.  It's an unconference meaning that everybody can just-in-time bring ideas for sessions, prototypes and whatnots.  Some people will already meet a few days earlier for hacking and prototyping.

## dates and location

**hackathon/hangout starts: Wednesday 14th Dec 2016.**

**unconference: Friday evening Dec 16th until Dec 18th sunday afternoon.**

We will meetup during the whole time at the [Onion office](http://www.openstreetmap.org/node/3237956432#map=19/52.55048/13.36968) which is located at:

    ExRotaprint-Gelaende
    Gottschedstrasse 4 (Aufgang 4)
    13357 Berlin

## participation, registration

Participation itself carries no fees but please pre-register and possibly help organize food and accomodations for everyone.   AME2016 is a self-organized event without sponsoring.  If you would like to but can't come due to missing money please indicate it when sending your registration mail.

For registration or questions please send mail (if possible encrypted via [this key](https://sks-keyservers.net/pks/lookup?op=get&fingerprint=on&search=0x8E3B03A279B772D6)) to holger at merlinux dot eu and provide the following:

    Name/Handle 
    background/interest/project
    estimated arrival and departure time
    if it's ok to publish your handle/name on the web page
    if you'd like to share accomodation but have none
    if you can provide accomodation for someone
    if possible please attach PGP Key if not discoverable from your mail

Moreover, please subscribe to this mailing list:

    https://lists.mayfirst.org/mailman/listinfo/ame2016

We are going to pre-discuss there and discuss logistcal questions.

## major topic: in-band opportunistic mail encryption

One hot topic arose from discussions about automatic mail encryption at OpenPGPConf and PGPSummit 2016 and is currently headlined "in-band opportunistic mail encryption".  This scheme follows ideas from [Opportunistic Security](https://tools.ietf.org/html/rfc7435), particularly focuses first on protecting against passive network/provider attacks and in particular aims to:

- liberate users from having to manually manage encryption/decryption keys

- manage key discovery through mails people send each other (no
  keyservers, no dependency on extra services)

- be easy to standardize probably through an IETF draft.

- implement multi-device sharing of secrets through "self-sent mails"

Many of the involved topics have a history of discussion and reasoning behind them.  dkg and holger aim to write things up in November 2016 and also prototype in-band opportunistic mail encryption and will keep the above "ame2016" Mailing list updated about it.

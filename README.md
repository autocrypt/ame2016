
# AME2016: Automatic Mail Encryption unconf + hackathon

Email has been declared dead many times but refuses to die. It remains the largest open federated identity and messaging system, anchors the web and mobile phones and continues to relay sensitive information between citizens and organisations.  However, bringing pervasive end-to-end encryption to this infrastructure has failed so far.  The "automatic mail encryption" AME2016 gathering at the Onion Offices in Berlin is the next meetup where we want to discuss how to unfail.  

"We" are a group of mail-program developers and researchers from different projects and backgrounds who got together at the PGPSummit and OpenPGPConf in 2016.  The gathering is meant for fellow mail client developers, crypto researchers and people involved with standardization, useability and other cross-cutting concerns in mail encryption.  It's an unconference meaning that everybody can just-in-time bring ideas for sessions, prototypes and whatnots. 


## dates and location

**hackathon/hangout starts: Wednesday 14th Dec 2016.**

**unconference: Friday evening Dec 16th until Dec 18th sunday afternoon.**

We will meetup during the whole time at the [Onion office](http://www.openstreetmap.org/node/3237956432#map=19/52.55048/13.36968) which is located at:

    ExRotaprint-Gelaende
    Gottschedstrasse 4 (Aufgang 4)
    13357 Berlin

## Current state of Scheduling

Official start time each day is around 9AM.  Very likely some will be there much earlier and have breakfast.

**Wednesday, 14th: arrivals** holger and azul to pick up key and arrive around 10am at the onion space or possibly earlier. Around 6-10 other arrivals are expected that day. We'll start chatting, scout the area for food and drinks, figure out networking, connect the projector.  IOW, hackathon and hanging out together starts.

**Thursday, 15th: hackathon + federated messaging session** the first of us are to be at the space around 9AM.  At 10AM we do a little plenary session to organize the day. Around 2pm in the afternoon there is a session dedicated to federated/decentralized low-latency messaging with Matthew from https://matrix.org, Dominic from https://scuttlebot.io, Marios from University of London and dkg/holger/vincent from INBOME as things tand.

**Friday, 16th: hackathon, more arrivals** 10AM plenary session, splitting into groups etc. just a regular hacking and chatting day but more fun because you don't get to hang out with this set of people usually.

**Saturday, 17th: unconference on diverse automatic mail encryption related topics.** Currently registered are roughly 20 people engaged in diverse mail clients and enryption R&D contexts. We'll have some talks and do group sessions to discuss particular shared topics of interest.

**Sunday, 18th: breakfast hackathon and closing sessions, wrap up early afternoon**

## participation, registration

There is no fancy webform to register and no social media strategy to promote the meeting. We can only accomodate 20-30 people in the Onion Space anyway and are already like 15-20 people and growing. If you know someone else who might be interested to attend, then by all means ask them!  We'd like to have diverse set of people who share the goal of making pervasive e2e mail encryption a thing.

AME2016 is a hands-on self-organized low-cost event without much sponsoring. If you would like to but can't come due to missing money please indicate it when sending your registration mail and we'll look out for sponsoring. It's getting late to organize that, though.

For registration and pre-discussion please [subscribe to our mailing list](https://lists.mayfirst.org/mailman/listinfo/ame2016).

And please be so kind to send mail to holger at merlinux.eu and provide the following:

    Name/Handle 
    background/interest/project
    estimated arrival and departure time
    if it's ok to publish your handle/name on the web page
    if you'd like to share accomodation but have none
    if you can provide accomodation for someone
    if possible please attach PGP Key if not discoverable from your mail


## code of conduct

The gathering follows the same ideas/rules as the [Python Community Code of Conduct](https://github.com/python/pycon-code-of-conduct/blob/master/code_of_conduct.md), in very short: Our gathering is dedicated to providing a harassment-free experience for everyone, regardless of gender, sexual orientation, disability, physical appearance, body size, race, or religion. 

## major topic: in-band opportunistic mail encryption

Some of currently engage in [spec-drafting and prototyping "in-band opportunistic mail encryption"](https://inbome.readthedocs.org).  The topic and idea arose from discussions about automatic mail encryption at OpenPGPConf and PGPSummit 2016.  It follows ideas from the post-snowden [RFC7435 Opportunistic Security](https://tools.ietf.org/html/rfc7435), particularly focuses first on protecting against passive network/provider attacks and in particular aims to:

- liberate users from having to manually manage encryption/decryption keys

- manage key discovery through mails people send each other (no
  keyservers, no dependency on extra services)

- be easy to standardize probably through an IETF draft.

- implement multi-device sharing of secrets through "self-sent mails"

Many of the involved topics have a history of discussion and reasoning behind them.  See here and at the [ame2016 Mailing list](https://lists.mayfirst.org/mailman/listinfo/ame2016) about it.

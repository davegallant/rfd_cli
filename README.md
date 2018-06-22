# RFD CLI

Hot Deals on the command line.

[![Build Status](https://travis-ci.org/davegallant/rfd_cli.svg?branch=master)](https://travis-ci.org/davegallant/rfd_cli)

[![PyPI version](https://badge.fury.io/py/rfd.svg)](https://badge.fury.io/py/rfd)

## Installation

```bash
pip install rfd
```

## Usage

```bash
rfd threads <topic-id> [--count 10]
```

### Display first 5 threads from hot deals

![screenshot](https://user-images.githubusercontent.com/4519234/37319853-3a03fb9c-2647-11e8-806e-17156541cf43.png)

### tail a post:

```bash
▶ rfd posts https://forums.redflagdeals.com/koodo-targeted-public-mobile-12-120-koodo-6gb-40-no-referrals-2176935/ --tail 4

--------------------------------------------------------------------------
    - [0] For those worried about credit ratings, according to Boworell, my credit score rose by 44 points since last month.  I did absolutely nothing except open 3 Koodo lines all with medium tabs and I paid off 1 in full the very next day (Shaner)

--------------------------------------------------------------------------
    - [0] If we want to keep our PM plan but use the code to set up a spouse on the plan is that still okay?
I've read that the port can only be used once now, but does it matter which phone number is ported in? (kid_icarus)

--------------------------------------------------------------------------
    - [0] blackboxvr6 wrote: ↑Mar 12th, 2018 2:13 pm
Legit 1st line on Wednesday, no shipping email yet...


Tuesday before noon and still waiting. (gardener28)

--------------------------------------------------------------------------
    - [0] Ordered a SIM last Wednesday, haven't heard a peep from Koodo since the initial order confirmation e-mail. (DaJinx)

--------------------------------------------------------------------------
```
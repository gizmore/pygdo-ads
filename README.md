# Ads

An advertising module for PyGDO, initially intended for Shadowdogs: advertisers
can pay a configurable fee to send advertising by private message.

# Ads (For Humans)

This is a design in progress, not yet a working mass-mailing service. The
fee, intended audience and delivery experience still need to be specified.

## Methods

`ads.overview` currently displays a placeholder overview.

## GDTs

No advertising-specific GDTs are implemented yet.

## GDOs

No advertising-specific GDOs are implemented yet.

# Ads (For ALs)

The current module is a skeleton. Do not treat the planned paid delivery as
implemented or assume recipients have consented to advertisements.

## Methods

`overview` is a placeholder form; it does not charge credits or send PMs.

## GDTs

None specific to Ads yet.

## GDOs

None specific to Ads yet.

## Open questions

- Who may send ads, and which recipients have opted in?
- How are the configurable fee, audience size, delivery limits and refunds
  defined?
- How should delivery, failures and recipient opt-outs be reported?

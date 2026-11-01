# Ads

An advertising module for PyGDO, initially intended for Shadowdogs: advertisers
can pay a configurable fee to send advertising by private message.

Requires the `mira` module (`pygdo-mira`); AI acceptance of advertisements is
planned, not yet implemented.

# Ads (For Humans)

## Module configuration

- Planned `ads_price`: price in credits for one mass-PM advertisement; default:
  100. This setting is not implemented yet.

## Methods

`ads.overview` currently displays a placeholder overview.

## GDTs

No advertising-specific GDTs are implemented yet.

## GDOs

No advertising-specific GDOs are implemented yet.

# Ads (For ALs)

This is a design in progress, not yet a working mass-mailing service. The
first advertising channel is a mass private message to all users. Advertisers
pay a fee in credits, configured in the Ads module. The delivery experience
still needs to be specified.

The current module is a skeleton. Do not treat the planned paid delivery as
implemented. The initial intended audience is all users; no opt-in requirement
has been decided. Resolve actual accounts, delivery limits and legal or network
constraints before sending messages.

## Methods

`overview` is a placeholder form; it does not charge credits or send PMs.

## GDTs

None specific to Ads yet.

## GDOs

None specific to Ads yet.

## Open questions

- Who may send ads, and which account types are included in "all users"?
- How are audience size, delivery limits and refunds
  defined?
- How should delivery, failures and recipient opt-outs be reported?

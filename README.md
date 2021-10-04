# Buidl Dao

Draft of a semi-automated founder friendly fund

## Structure

### GP Dao

Has the tools for things like verification and assigning hash, creation of LP DAO.

### LP Dao

Strictly owns one thing and is as automated as possible. Including creation, ongoing maintenance, dissolution, annual taxes, etc.

## Pitch to founders

We thought of the ideal investor and tried to create it:

- cash-backed offer
- only 1 round to confirm valuation
  - (that could be skipped v1?)
- always back founders / approve founder requests
- sign any and all docs within 1 business day
- check size at least [25k? ideally $100k min]

## Initial funding flow

Assuming an interested investor is set up and in the system.

### Initial interest

- A potential investor writes down an amount for a company, optional cap.
- GP Dao contacts other potential investors?
- GP Dao contacts founder: possible investment up to [sum_amounts], if interested pls reply with terms

### Terms

- Founder replies with terms
- GP (automatically?) confirms amounts with interested investors, requests capital (within 12 hrs).
- (If GP does not fund, demerit); capital held 'in escrow' (potentially stake for opex)
- GP presents final amount, legal entity (i.e. proposed LP Dao name) to founder for confirmation and docs; potentially this is all cash in hand
- Founder confirms and sends docs
- GP shows 'cash' and confirms intent to fund upon LLC creation

### Create LP DAO

- Set aside funds to operate for [7] years. (Stake these and use any interest to extend life.)
- Ownership % determined by funds.
- Signer / owner is GP DAO.
- GP transfers capital to LP Dao

### Execute docs and fund

- New LP DAO signs documents with founder
- Send funds, ideally on-chain

### On-going

- Founder updates shared only to LP members (using Signal-like new key for each?)
- Anything needing signature is quickly signed;
  - Can this be set up in advance? There are only so many types; or give 'power of attny' to founder?

### Good outcome

- Sale or acquisition before fund lifetime
- Distribute funds to members per %
- Dissolve
- Distribute any remaining funds per % (i.e. unused annual fees)

### Not good outcomes

#### No liquidity event before fund times out

- vote on continue (and fund), shut down and dissolve
- other ideas: pass back to GP, sell to 3rd party (i.e. EquityZen, another investor, founder)

#### Company dissolves

- Dissolve
- Give clear tax event
- Distribute any remaining funds per % (i.e. unused annual fees)

### Initial setup for investor

A way to verify membership of [yc_alumni], accredited, wallet, contact info.

Maybe all potential investors must be members of GP DAO.

Potentially, for helping with maintenance tasks (i.e. signing documents), they can earn coins/reduce fees.

## Standard events

### Annual K-1s

- Ideally automate since percentages, current balance, liquidity events, owners (hash?) are known

### Signing corporate things

- Automate
- Someone authorized signs
- Signer earns 'coins' for handling

### Company updates

- special email?
- distributed (encrypted) to LPs

### Founder requests

- ?

### Create DAO

### Dissolve DAO

### Distribute funds from DAO

### Authenticate DAO member

- accreditation
- member of group (i.e. YC alumni)

## Outstanding questions

- How to deal with questions?
- Forget the valuation roundtrip and accept 'current val'? Add MFN?

### YC Specific

Not much info on demo day (i.e. possibly no revenue or unclear definition)

## Misc notes

- Start with YC alumni on Demo Day
- Over time build reputation, figure out how to deal with diligence
- General DAO has various verification and whatever stuff; provide the hash or the wallet, so the inv DAOs are pseudo anonymous

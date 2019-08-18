# Heating

*This is an opinionated guide for heating automation. Links to buy are pointing to european platforms to start with.*

tl;dr:

- [HomeMatic Radiator Valves](https://rover.ebay.com/rover/0/0/0?mpre=https%3A%2F%2Fwww.ebay.de%2Fulk%2Fitm%2F202482181196)
- HomeMatic Gateway
  - *this is just one out of many options*
  - [CUL USB stick](http://busware.de/tiki-index.php?page=CUL)
- [FHEM](https://fhem.de)
  - Most feature-rich application for managing heating with HM components

More details:

Heating is one of the easiest topics to start with and, at the same time, has a good return of invest over time. If you live in a climate with cold winters, and in a building that is isolated well, you can save about 5% of heating energy per degree celcius when you lower the temperature while, for example, being at work.

Looking at security, performance and signal reach, HomeMatic BidCoS radiator valves have proven their price-point of about 35 euro per piece for the self-assembly kit (no soldering required). Plus a single-time investment to get a sender/receiver device.

Operating at 868 MHz, 128bit AES encrypted, both signal reach and security are ahead of other products in the segment.

## Why FHEM is Recommended

- Supports multiple sender/receiver devices for high availability
- Third-party window/door sensors can be peered
- Third-party thermostats can be peered

This enables makers to create custom, and often cheaper, solutions for sensory components while having a very reliable raditor operation component at hand.

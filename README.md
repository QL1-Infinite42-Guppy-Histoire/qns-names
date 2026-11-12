# QNS Names — .qom directory (QL1)

A read-only directory of every registered QNS (.qom) name on QL1, plus a direct
on-chain check for whether a name is taken.

- List source: the QL1 explorer (Blockscout) index of the QNS registrar
  (`0xDCbF4614152a22D1883Ba3929c668B978A3be548`, QL1 chain id 766)
- Availability check: reads the registrar contract directly in the browser
  (token id = keccak256 of the label; ownerOf / nameExpires)
- Order: names starting with a digit first, then alphabetical
- Search: substring match
- Length filter: 1–4 characters individually, 5+ grouped
- New QNS registrations have ended; an unregistered name cannot be newly
  registered at present (stated on the page as well)

Site: https://ql1-infinite42-guppy-histoire.github.io/qns-names/

Developed by the community. MIT license.

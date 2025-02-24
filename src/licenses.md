# US

## Amateur
We are all about the ham radio here, which offers the most flexibility of all on certain axes.

Band 40 is the best bet. 

The lower 50MHz of legacy LTE band 42 also
appears to be usable under part 97 per footnote
[US103](https://www.law.cornell.edu/cfr/text/47/2.106). This may not
last for long, but deployments under ham privileges could convert to
CBRS rules if the current state changes.

With carrier aggregation, it *might* be possible to hack together
spectrum from all over the space, which might make portions of band 8
(900MHz) usable, or possibly other bands such as the uplink portion of band 30.

We haven't fully mapped the overlap between privileges and bands in this context.


> In Release-11, the potential of carrier aggregation with HSDPA is extended to up to 8 carriers
> with a potential use of 40 MHz aggregate within one UE. There is no need for the carrier to be
> adjacent, and it is possible to aggregate them from more than one frequency band
> The downlink and uplink can be configured completely independently, with only the limitation
> that the number of uplink carriers cannot exceed the number of downlink carriers.
[LTE-Advanced carrier aggregation. Release 11, paragraph 1](https://dataedge.ie/wp-content/uploads/2013/07/Network-Testing-Understanding-Carrier-Aggregation-web.pdf)

This use of CA is an open question and we'd love help resolving it!

## Unlicensed
https://en.wikipedia.org/wiki/LTE_in_unlicensed_spectrum

US hams generally have the ability to use at least some portion of common
unlicensed spectrum under part 97 rules, so this may offer some support
off the shelf while freeing us from part 15 or ISM constraints.

Finding UE with support for these bands can be very difficult.

## CBRS
Mostly license-free, but not literally so. CBRS is probably the easiest
way to come to grips with LTE stuff but requires use of a SAS, and
many useful deployments would require installation by a certified
installed. Certification costs ~$600.

## STA
Not really a license, but a permission slip. This may be one way to get
temporary operating authority on bands that are not currently used in
your area. We should search to find existing applications.

## Lab
With everything turned to low power and through attenuators, or in a
nice metal box, you may be able to test without a license.

## non-RF
srsran supports zmq, meaning it simulates the RF side and does not actually require hardware at all.

# UK

## Amateur
Looks like Band 40 might work here:
https://www.hflink.com/bandplans/UK_bandplan.pdf
## Shared Access licensing
https://librecellular.org/user/spectrum

# NO
## Amateur
Band 40 should work nicely.
https://lovdata.no/dokument/SF/forskrift/2009-11-05-1340

# ES
## Amateur
Band 40 will work:
https://www.fediea.org/hamradio/inspain/qrg.php?lang=en

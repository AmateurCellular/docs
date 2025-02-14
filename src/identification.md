## Identification requirements

`97.309a4` makes clear that if an unlisted digital code's technical
characteristics are documented publicly, it counts as a specified digital
code. Under `97.119b3`, that makes us eligible to handle identification
entirely through that digital code in some publicly specified way.

We might still choose to use CW or some other kind of more-obvious
beacon to stay within the bounds of amateur radio _culture_ as well as
the regulations. After all, if someone is just browsing around the band
and stumbles across our signal, we'd like them to be able to join us!

Here's how we might do that.

* CW or FM beacon - solves all problems. Hard to do except in case of SDR transmitters we own. Doesn't solve UE identification requirements.
* Broadcast packets on the IP layer with callsigns. That suggests a
user-space application sending link-local packets with some specified
payload including the operator's callsign. 
* The above might even be automatable
on the eNB/gNB side by recognizing keys, but I'd have to take a closer
look at part 97 to see if that would really be permissible.

All are plenty possible.


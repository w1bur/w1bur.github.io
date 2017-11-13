---
title: W1BUR repeater range tests
excerpt: Notes on which repeaters W1BUR VHF/UHF control station could reach from Boston University.
categories: antenna
---

This is for a record of which repeaters could be reached using the omnidirectional J-pole antenna ~ 40 meters elevation.
Distances are estimated using the RepeaterBook app.
Test done with [Yaesu FT-5100](http://www.eham.net/reviews/detail/2031), which is an ailing old radio subject to intermod due to receiver overload. 
It's an old design that needs to be replaced.

Although range is strongly a function of terrain and repeater elevation, using numerous repeaters to verify "not working" gives an idea of system performance.

Currently (Nov 2017), the maximum range to repeaters from W1BUR omni J-pole VHF/UHF antenna is approximately:

70cm: 10 miles
2m: 5 miles

This seems to be very limited range.
I tried to segment receiver issues from transmit issues.
I think the Yaesu receiver is not bad (though it's not too good either).
This points to a coax or antenna problem.

Further diagnosis would require wattmeter & dummy load at antenna to test.

## Working

freq (MHz) | callsign | distance (mi) | notes
---------|----------|---------------|-------
145.23   | W1BOS    | 2.7   | very strong, Boston, MA
145.43   | W1MRA    | 4.9   | very strong, Belmont, MA
147.03   | W1TKZ    | 5.3   | strong, Newton, MA  50 watt kerchunk
146.64   | W1MHL    | 6.9   | moderate, Waltham, MA
146.67   | W1BRI    | 8.5   | moderate, Quincy, MA  50 Watt kerchunk




freq (MHz) | callsign | distance (mi) | notes
---------|----------|---------------|-------
449.725  | W1XM     | 1.2   | very strong
446.325  | W1CLA    | 1.4   | very strong
444.7    | W1KRU    | 2.4   | strong
444.6    | W1TKZ    | 5.3   | weak, fluttery, kerchunk @ 35 watts
449.075  | W1MHL    | 6.9   | moderate signal, 5 watts
442.7    | W1MRA    | 10.1  | very weak, kerchunk @ 5 watts
442.5    | AE1TH    | 11.1  | very weak, kerchunk @ 35 watts


GMRS repeaters were also tested.

freq (MHz) | location | distance (mi) | notes
---------|----------|---------------|-------
462.625  | Fenway | 1 | 
462.625  | Cambridge | 3 | 


## Not working
These repeaters were not reachable even at full power.
When I get time I'll try to verify with HT at top floor (in case repeater was just off-air or not reachable due to terrain or interference.).

freq (MHz) | callsign | distance (mi) | notes
---------|----------|---------------|-------
147.36   | W1LJO    | 5.3   | Newton, MA
146.91   | K1SVP     | 9.4  | Saugus, MA
146.79   | N1BE     | 10.1  | Weston, MA
147.015  | W1DVG    | 11.4  | Lynn, MA
146.715  | KC1US    | 11.7  | N. Reading, MA
147.12   | W1DC     | 16.7  | Billerica, MA

freq (MHz) | callsign | distance (mi) | notes
---------|----------|---------------|-------
442.75  | WA1GPO | 5.3  | Newton, MA
443.05  | KC2LT  | 6.9  | Waltham, MA
449.825 | N1OMJ  | 9.3  | Woburn, MA
447.025 | W1CLA  | 11.7 | Burlington, MA
446.775 | W1DYJ  | 11.7 | Burlington, MA
446.525 | WA1RHN | 12.2 | Reading, MA
449.125 | W1CLA  | 13.3 | Natick, MA
449.425 | K1BFD  | 13.3 | Canton, MA
441.9   | K1KZP  | 14.2 | Wilmington, MA
443.975 | W1ZSA  | 16.1 | Walpole, MA


freq (MHz) | location | distance (mi) | notes
---------|----------|---------------|-------
462.55   | Quincy    | 8 |

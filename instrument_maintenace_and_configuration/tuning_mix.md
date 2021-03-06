# The bottles on the front of the qTOF

The Agilent 6545 qTOF has two calibrant/tuning solutions that sit in bottles connected directly to the instrument.  Bottle B is the "tuning mix" and is essentially used only prior to analysis runs, for mass calibration and instrument "tuning".  Bottle A is optionally used to continuously infuse a smaller number of compounds into the instrument during every sample run, providing a "lock" mass for ensuring continued mass accuracy during analysis runs.

This document describes recipes for both calibrants.  It is adapted from the **Agilent 6500 Series Q-TOF LC/MS Maintenance Guide**, not available on Agilent's web site but found on:
* `http://phct.ru/assets/files/G2581-90065_Q-TOF_Maintenance.pdf`
* `http://sim-gmbh.de/en/support/downloads/153-6500-series-accurate-mass-quadrupole-time-of-flight-q-tof-lc-ms-maintanance/file.html`
* USB sticks that came with our instrument.

## Bottle B: The tuning mix / mass calibrant

The proper tuning mix depends on the ion source.  

### dual-AJS ion source

| Component                         | ID          | Volume | notes                                                                                                                                               |
|-----------------------------------|-------------|-------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| ESI-L tuning mix                  | G1969-85000 | 5 mL        | **DO NOT USE MMI-L tuning mix**                                                                                                                                                    |
| acetonitrile                      | -           | 44.25 mL       | it is OK to use<br />MeCN w/ 0.1% formic acid                                                                                                            |
| water                             | -           | 0.75 mL        | it is OK to use<br />water w/ 0.1% formic acid                                                                                                           |
| 0.1 mM HP-0321<br />solution from vial | G1969-85003 | 2 &mu;L       | This solution contains the +322.0492 m/z standard; <br />it contains hexamethoxyphosphazene. <br /> I don't know why this additional component is required. |

* Add the components in the order listed.
* The component at an _m_/_z_ of 118.0874 is glycine betaine / trimethylglycine.  This signal degrades more quickly than the others.  It's intensity is strongly affected by the volume fraction of water in the mix.  You can add more water up to 5% v/v, in an effort to rescue this signal.  You could also add a few &mu;L of glycine betaine solution in HPLC-grade water to the calibrant solution to rescue it.
* Components of the tuning mix are available in this link: `https://www.agilent.com/cs/library/certificateofanalysis/G1969-85000cofa872022-U-LB86189.pdf`
	* most of the high-MW components are fluorinated phosphazenes or alkyl triazines.


### MMI ion source

| Component                         | ID          | Volume (mL) | notes                                                                                                                                               |
|-----------------------------------|-------------|-------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| MMI-L tuning mix                  | G1969-85020 | 25          |      **DO NOT USE ESI-L tuning mix**                                                                                                                                               |
| acetonitrile                      | -           | 71.25        | it is unknown if using<br />MeCN w/ 0.1% formic acid<br />is OK                                                                                                     |
| water                             | -           | 3.75         | it is unknown if using<br />water w/ 0.1% formic acid<br />is OK                                                                                                          |

* The component at an _m_/_z_ of 121.0520 is purine; this signal seems to decay faster than the others.  It might be possible to rescue bad calibrant by adding a few &mu;L of dilute solutions of purine in HPLC-grade water to the calibrant.  (This is untested as of October 2016).
* Ideal calibrant abundances while tuning are between 50k and 700k.  
* Components of the tuning mix are available in this link: `https://www.agilent.com/cs/library/certificateofanalysis/G1969-85020cofaG1969-85020-lb88758.pdf`
	* the only marked difference between this and the ESI-L tuning mix appears to be (a) use of purine instead of glycine betaine, and (b) higher amounts of trifluoroacetate salts.
	
\pagebreak

## Bottle A: the reference mass solution

The same bottle can be used regardless of ion source.

**The components listed below should be added to 1.0 L of solution of 950:50 v:v acetonitrile:water!**  After mixing, this one-liter batch can be stored at 4 &deg;C in a nalgene bottle.  When the 100-mL bottles on the instrument empty, you don't need to make more calibrant, you can just refill the bottle on the instrument from the 1-L nalgene bottle in the fridge.

| Component                         | ID          | Volume (mL) | notes                                                                                                                                               |
|-----------------------------------|-------------|-------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| 5 mM purine<br /> in 90:10 MeCN:water                | G1969-85001 | 0.4          |                                                                                                                                                     |
| 2.5 mM HP-0921<br /> in 90:10 MeCN:water                      | -           | 1        |     This solution contains the +922.0109 m/z standard; <br />it contains hexakis(1H,1H,3H-perfluoropropoxy)phosphazene.                                                                                                |


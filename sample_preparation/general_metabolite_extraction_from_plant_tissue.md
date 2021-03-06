# Overview

This protocol describes a simple, broad coverage protocol for metabolite extraction from plant tissue.

# Equipment

### PPE
Safety glasses and nitrile gloves are required for this protocol.

### Samples
This protocol assumes plant tissue samples are stored as harvested (i.e. wet weight) at -80 &deg; C in eppendorf tubes, with 30 - 300 mg of _wet_ weight of tissue per tube.  The most common sample type is excised leaf.  Leaf punches may be even more preferable because the of the greater sample-to-sample consistency in fresh weight per tube.	

### Equipment


0. Eppendorf [Safe-Lock tubes](https://online-shop.eppendorf.com/OC-en/Laboratory-Consumables-44512/Tubes-44515/Eppendorf-Safe-Lock-Tubes-PF-8863.html), 1.5 mL or 2 mL in capacity, colorless
1. -80 &deg; C Freezer
2. Lyophilizer (e.g. [LABCONCO Freezone 6plus](https://www.labconco.com/product/freezone-plus-6-liter-console-freeze-dry-system/281) )
3. Ball-mill homogenizer (e.g. [Retch MM 400](https://www.retsch.com/products/milling/ball-mills/mm-400/function-features/))
4. Syringeless filter vials (e.g. Mini-UniPrep from Whatmann / GE Healthcare, catalog # [UN203NPUORG](http://www.capitolscientific.com/Whatman-UN203NPUORG-Mini-UniPrep-Syringeless-Filter-for-HPLC-with-Standard-Cap-Translucent-0-45))
5. Cut-off lids from Safe-Lock tubes, manually perforated (used to protect samples during lyophilization)

### Reagents

1. Methanol:water 80:20 v/v mixture.  
	* TODO: an internal standard should be added to this mixture.  A probably good internal standard is blue Sharpie, but as of now no internal standards are used.
	* Methanol and water can both be reactive solvents, a fact rarely noted or appreciated in the thousands of published studies that use them as extraction media for metabolites.  For example [Rajniak et al. 2015](http://dx.doi.org/10.1038/nature14907) found that extraction of plants with water/methanol mixtures led to hydrolytic and methanolytic destruction of 4-hydroxyindole-3-carbonyl nitrile.  100% DMSO can be an alternative in such cases.
	* Plant metabolites can often be glycosylated.  This protocol assumes you want to observe the intact glycosides.  If you'd prefer to see aglycones, enzyme-based deglycosylation protocols are available.


# Procedure
1. Lyophilize the samples.
	1. Remove Eppendorf tubes containing frozen wet plant tissue samples from the -80 &deg;C and place on dry ice.
	2. Uncap the tubes.
	3. Cap the tubes with a separately prepared, perforated Eppendorf tube lid.
		* This protects your samples during lyophilization; in the event of an accidental sudden (de)pressurization, chunks of your sample made get propelled out of the tube if the top was open completely.  Protecting them with a separate lid (perforated so lyophilization can work) guards against this.
	4. Place the samples in a lyophilization jar / chamber that you have pre-chilled on dry ice.
	5. Carrying the samples on dry ice, proceed to the lyophilizer.
	6. Follow the directions on the lyophilizer (directions below assume you are using the [LABCONCO Freezone 6plus](https://www.labconco.com/product/freezone-plus-6-liter-console-freeze-dry-system/281) in Shriram Center.
		1. BEFORE ADDING YOUR SAMPLES, CLOSE OFF AND ISOLATE ANY CURRENTLY LYOPHILIZING SAMPLES.
			* This step prevents sudden depressurization of your labmates' samples and thus also prevents their severe ire.
			* To isolate a chamber, rotate the recessed part of the gray valve handle for the chamber so that it faces 90&deg; to the left or to the right of the black "spout" for the chamber.
		2. Add your chamber to the lyophilizer.
			* If you are worried about photolability in the metabolites you care about, cover your lyophilization jar thoroughly with aluminum foil.
		3. Rotate the gray valve for your own lyophilizer chamber approx. 180&deg; so that the recessed part of the gray handle faces down (relative to the black "spout"), thus opening up your samples to the lyophilizer pump.
		4. Wait for the lyophylizer to partially evacuate your sample chamber:
			* Let temperature and pressure indicator bars reach "_five dots_".
		5. RETURN THE VALVES FOR YOUR LABMATES' CHAMBERS TO THE "DOWN" POSITION SO THEIR SAMPLES KEEP LYOPHILIZING!
			* Failure to do this step results in ire, as described above.
		6. Allow your samples to lyophilize until dry.
			* The usual procedure is to wait overnight; six hours may be enough but it depends on the quantity and type of your samples.
		7. Remove your chamber from the lyophilizer.
			* Rotate the gray handle _slowly_ until that the recessed part faces "UP".  
		8. Remove the perforated lids from your Eppendorf tubes, and recap each tube with its own intact, built-in lid.
		9. Store samples at -80 &deg;C until homogenization.
			* Ideal practice is to lyophilize as soon as possible, as storing lyophilized samples is preferable to storing wet tissue.
2. Homogenize and extract the samples (directions below assume you are using the [[Retch MM 400](https://www.retsch.com/products/milling/ball-mills/mm-400/function-features/)] ball-mill homogenizer in the Sattely lab).
	1. Remove samples from frozen storage and work on dry ice.
	2. Add one (1) steel ball, 5 mm diameter, to each Eppendorf tube.
	3. Place the Eppendorf tubes in the white Teflon homogenizer rack.
		* Each rack holds 10 samples; there are two racks.  For more samples you will have to work in batches.
	4. Tighten the homogenizer holder clamps to lock the racks in place.  
		* Do not overtighten the clamps.  (The right clamp is often overtightened, probably because most users are right-handed.)
	5. Homogenize at room temperature for 2 minutes and 25 Hz.
		* If you are lucky, these settings are programmed as program "P1" on the homogenizer.
	6. Remove the samples from the homogenizer.
		* You do not need to remove the steel ball from each sample now.  Wait until later.
	7. Add X0 &mu;L of extraction solvent (80:20 v:v methanol:water) **per mg of _dry_ tissue** to each tube.
		* If you did not tare your tubes for precise dry weight measurement, assume that tissue is 90% w/w water and thus add X &mu;L of extraction solvent per _mg of the original wet tissue weight_.  
		* The value of X depends on the plant and tissue you are using.  Some rough guidelines:  
			* For tomato leaf, X = 6; i.e., add 60 &mu;L of solvent per mg of dry tissue.
			* For _Arabidopsis_ leaf, X = 8; i.e., add 80 &mu;L of solvent per mg of dry tissue.
			* For tobacco leaf, X = 2; i.e., add 20 &mu;L of solvent per mg of dry tissue.
	8. Vortex strongly for ~10 seconds.
	9. Optional: Heat at 65 &deg; C for 10 minutes.
		* The utility of this step needs to be assessed for your metabolites and sample types.  It is a tradeoff between metabolite stability and extraction yield.
		* If you do heat, vortex briefly after heating.
	10. Centrifuge at up to 21,000 _g_ on a benchtop centrifuge for 5 minutes at 4 &deg;C.
		* Even at 21,000 _g_ or higher (essentially the highest setting of most benchtop microcentrifuges), the steel ball will not damage SafeLock tubes
	11. Decant the supernatant into the bottom part of a Whatmann filter vial.  
		* Make sure not to accidentally decant the steel ball at this stage.
	12. Filter the samples using the Whatmann vial filter top by manually plunging the top completely down 
		* Some force will be required.
	13. Analyze samples immediately or store at freezer temperatures until analysis.
		* Stability of samples stored in the freezer will depend on metabolites of interest.  (80% methanol does not freeze, even at - 80 &deg;C temperatures.)  It is best to analyze samples as soon as possible after extraction.  Storing lyophilized unextracted samples is preferable to storing extracted samples.
	14. Remove the steel balls from all sample tubes and clean them before returning them to the container of steel balls labeled "clean".
		* TODO: write protocol for cleaning steel balls.
	
#### Notes

Based on [Jeon et al. 2018](https://www.biorxiv.org/content/biorxiv/suppl/2018/09/04/408518.DC1/408518-1.pdf)'s writeup of longstanding Sattely lab practice.  Thanks to Ryan N., Ricardo d.l.P., & Niraj M. for feedback.

CF / cf
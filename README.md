# ROSAT All-Sky Survey (X-ray) Recreation

![](https://heasarc.gsfc.nasa.gov/Images/rosat/slide_gifs/misc_rass.gif)

In this python notebook, we will reproduce the image above. It's a colorized composite of data from the ROSAT All-Sky Survey available from NASA here: https://heasarc.gsfc.nasa.gov/docs/rosat/gallery/misc_allsky1.html. The ROSAT was launched 30 years ago on the day of this writing. Its observations were completed in 1990-1991 and were composited at a low resolution. The [high resolution TIF format version](https://heasarc.gsfc.nasa.gov/Images/rosat/slide_gifs/misc_rass.tif) is only 1633x815 pixels.

The image we're trying to replicate was published in _[M.J.Freyberg, R.Egger (1999), "ROSAT PSPC All-Sky Survey maps completed", in Proceedings of the Symposium "Highlights in X-ray Astronomy in honour of Joachim Trümper's 65th birthday", eds. B.Aschenbach & M.J.Freyberg, MPE Report 272, p.278-281, Fig.4.](http://articles.adsabs.harvard.edu/cgi-bin/nph-iarticle_query?bibcode=1999hxra.conf..278F&db_key=AST&page_ind=3&data_type=GIF&type=SCREEN_VIEW&classic=YES)_

The image is labeled `red: 0.1-0.4 keV green: 0.5-0.9 keV blue: 0.9-2.0 keV` and it's caption reads:

> "3-colour composite image of a 100° x 100° region centered on l = 0°, b = 0° created from the completed maps. The 1/4keV band emission is coded red, green denotes 3/4keV band emission, and blue represents the hard 1.5keV band. Prominent features are Sco X-1 (the hard source in the upper third of the image) and its bright X-ray scattering halo (note, that the central ~30' remained still unobserved)."

# Galaxy clusters detection in Planck data using thermal Sunyaev-Zeldovich emission.

Work from Marilou Medawar (ObsPM, Paris) and Marine Prunier (ObsPM, Paris).
Under the supervision of Dr. Marian Douspis (IAS, Orsay)

## Abstract

Context: The European Space Agency PLANCK Satellite observed the Cosmic Microwave Background (CMB) at a high angular resolution and sensitivity measuring the temperature variations across this microwave background and providing a strong database for a better understanding of the anisotropies. In addition, PLANCK has also been designed to detect the signature of the Sunyaev-Zeldovich (SZ) effect corresponding to the spectral distortion of the CMB through inverse Compton scattering of the CMB photons by high-energy electrons present in distant galaxy clusters.

Goal: Our aim in this work is to detect candidate galaxy clusters with the Sunyaev-Zeldovich effect component and compare them to the Planck 2nd Sunyaev-Zeldovich Source Catalog.

Method: We extract the emission of thermal SZ from the Planck maps using a component separation method so-called Internal Linear Combination (ILC) Constrained to build clean All Sky SZ maps. Then, we develop a routine to detect the candidate galaxy clusters on a portion of the map.

Results: We detect 8 candidate cluster on a 10° by 10° portion of our SZ map. We match most of the detected candidates with clusters cataloged in the Planck 2nd Sunyaev-Zeldovich Source Catalog with small relative errors.



This repository contains:

-Implementation of simple ILC Constrained (Internal Linear Combination) method (see (1), (2), (3)).

-Visualization using HEALPix (Hierarchical Equal Area isoLatitude Pixelation of a sphere) python package (see (6))

-Galaxy cluster detection on an image routine. 

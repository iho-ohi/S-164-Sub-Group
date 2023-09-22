GOOD BASE CELLS

This directory contains a set of five base cells. One
is in the approach band while the remaining four are in
the harbour band.

EDITION and ISSUE DATES:

gb4x0000.000 EDTN 2, UPDN 0, UADT 20010409, ISDT 20010409
gb5x01ne.000 EDTN 1, UPDN 0, UADT 20010406, ISDT 20010406
gb5x01nw.000 EDTN 2, UPDN 0, UADT 20010406, ISDT 20010406
gb5x01se.000 EDTN 1, UPDN 0, UADT 20010406, ISDT 20010406
gb5x01sw.000 EDTN 1, UPDN 0, UADT 20010408, ISDT 20010408
gb5x02se.000 EDTN 1, UPDN 0, UADT 20010407, ISDT 20010407

SCALES:

The five harbour cells all have compilation scales (CSCL)
of 25000.
The approach cell has a compilation scale (CSCL) of 52000.
The approach cell also has an area at a different
compilation scale (M_CSCL). This area is at a scale of
45000 and lies to the north west of the cell. The area on
the sea is bounded by the north border and a line between:
	32 19.77S, 61 01.20E and
	32 21.58S, 60 56.13E.
The area continues over the land as a thin strip. The
larger scale area is that part of the cell covered by
Furania rather than Jussland.

SCAMIN:

The four harbour cells have SCAMIN set to 40000 for the
soundings.

The approach cell has SCAMIN set to 80000 for all soundings
with the exception of two groups:

    within the 10m contour around Bow Reef centred about
    32 34.6S, 60 58.5E and the other 
    within the 10m contour around Pillar Shoal centred about
    32 37.0S, 61 00.0E; 

which have SCAMIN set to 104000.

AREA OF NO DATA:

The cell gb4x0000.000 has an area of no data surrounding
the entire data set.

CELL GB5X02SE.000:

This cell adjoins to the south east of cell CELL GB5X01SE.000. It is an example which contains gaps and overlaps of data between the coverage areas of two cells. When two hydrographic offices' data shares a common boundary, it is found that there is often a small discrepency between the two limits. Although not the subject of any test, it was considered useful to provide OEMs with an example of such discrepencies. 

TEXT FILES:

Three text files (gbchains.txt, gbdevare.txt and gbiectmp.txt) are
contained in the goodb1 directory. The first two are not for any
specific test but are referred to within cell gb4x0000.000.
The third is an example of a Temporary Notice to Mariners and is attributed to a CTNARE (caution area) centred within cell gb4x0000.000 at about
32 34.73S, 61 08.83E.

PICTURE FILES:

A black and white 1 bit tiff file (gbx4000t.tif) containing a Rise and Fall of Tide diagram is attributed to a M_NPUB object covering Micklefirth Sound within cell gb4x0000.000.
	
A series of picture files which include Greyscale 8 bit, Palette 8 bit and RGB 24 bit and compressed versions can be found in the directory PICREP.
The LNDMRK object at 32 33.9S 60 54.3E in cell GB$X0000.000 is attributed with PICREP and a value GBTESTPC.TIF.
The intention is that the various images held in the PICREP directory can be renamed GBTESTPC.TIF and copied to the appropriate ENC_ROOT directory as required.
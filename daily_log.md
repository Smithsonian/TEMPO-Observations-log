# TEMPO Daily Log during Nominal Operation
#   (10/17/2023-present)

Last updated on 07/23/2025

For Commissioning period Daily log, (6/2023-10/16/23), see [CommissioningLog](TEMPO_Daily_Log_during_Commissioning.md)

For Current week's predicted overpass times at certain sites, see [OverPass](https://tempo.si.edu/OverpassPrediction)

For acronyms, see the TEMPO [glossary](glossary.md)

|Date | Log |
|:-| ----|
| 10/17/2023| **SDPC v4.1** operational processing started (9 hrs)
| 10/18/2023| Frequent data dropouts (missing data), INR might fail and no subsequent data products
|10/19/2023 | **Solar cal Working Diffuser (WD)** <br> Frequent data dropouts (missing data), INR might fail and no subsequent data products
|10/20/2023 | Frequent data dropouts (missing data), INR might fail and no subsequent data products
|10/21/2023 |Frequent data dropouts (missing data), INR might fail and no subsequent data products
|10/23/2023| Some data dropout
|10/26/2023| **Solar cal WD** 
|10/29/2023| Bad INR almost all day (**no L2 data products**) (R2.3.8 restart issue), will be reprocessed later with SDPC v4.2.
|10/30/2023| Data dropout, Scan 2 (S002) scan mirror stopped advancing midway through scan (12:21:57Z - 13:01:43Z). Kept imaging of the same location. Scan 2 was still processed. Scan 3 back to normal.
|11/02/2023| **Solar cal WD** <br>
|11/08/2023| bad INR for scans 1-7 (R2.3.8 restart issue). Scans 8-9 are ok, CSM interrupted after s009. L2 data products available for scans 1-9.
|11/09/2023| **Solar cal WD**<br> Intelsat anc_gps dropout 16:50-20:03Z, affecting scans 7-11. Manually restart for scan 12, ok after that. Missing data can be reprocessed. 
|11/16/2023| **Solar cal WD**
|11/18/2023| **SDPC v4.2** operational processing started (INR improvement), boresight correction slightly changes solar observation time, scanning plan was updated with an option to make sure that overpass time within the hour for a particular location is more or less predictable (did not use this option in the science planning).
|11/22/2023|Data Drop out. Scan 6 not at ASDC. INR crashed and then restarted. Major slowdown Internet GS copying starting about 21:30Z. Scans 11,12,13 not at ASDC. Scan 14 and 15 there at ASDC.
|11/23/2023| **Solar cal WD (pre boresight correction)**
|11/24/2023| **Solar cal WD (post boresight correction)**, no obvious difference from 11/23 as BTDF different is taken into account
|11/29/2023| 1 data drop out, inr crashed. Scan 5 not processed, not at ASDC.
|11/30/2023| **Solar cal WD** <br> Scan 3 (S003) scan mirror stopped advancing midway through scan. Kept imaging of the same location. Scan 3 was processed. Scan 4 back to normal.
|12/1/2023| Intelsat encrypted downlink data -- change to GS. Got some corrupted telemetry data starting about 2:13pm EST, apid 150 --scan mechanism telemetry like cma_pos (cal mechanism resolver position) and sma_last_x_pos. Back to normal around 4pm EST. Occurred about 19:13Z to 21:00Z; Scan 9 (18:57:33Z-19:57:14Z) and Scan 10 (19:57:33Z-20:57:14Z), and the beginning of Scan 11 (20:57:33Z-21:37:19Z) may be affected.
|12/7/2023| **Solar cal WD**
|12/10/2023| Data dropout. inr crashed. Scan 5 not processed, not at ASDC.
|12/14/2023| **Solar cal WD**
|12/21/2023| **Solar cal WD** <br> Incorrect packaging of morning dark granules; city lights dark frames stored in the same file with radiance dark frames.
|12/22/2023| **Solar cal Reference Diffuser (RD)** <br> Citylight measurements (West & East Coast, 88s exposure)
|12/23/2023| **Solar cal WD** <br> Citylight measurements (West & East Coast, 88s exposure)
|12/24-27/2023| Citylight measurements (West & East Coast, 88s exposure)
|12/28/2023| **Solar cal WD**
|1/4/2024| **Solar cal WD**
|1/11/2024| **Solar cal WD**<br> Citylight measurements (West & East Coast, 44s exposure)
|1/11-17/2024| Citylight measurements (West & East Coast, 44s exposure)
|1/18/2024| **Solar cal WD**<br> Citylight measurements (West & East Coast, 44s exposure)
|1/19-24/2024| Citylight measurements (West & East Coast, 44s exposure)
|1/22/2024| GOES-16 CMI product outage from 1720Z on 1/22 until 0040Z on 1/23. Effect on INR quality appears minor.
|1/24/2024| **TEMPO in safe mode** due to spacecraft GPSR and pointing error
|1/25/2024| **TEMPO brought out of safe mode, but TEMPO clock lost sync with spacecraft clock, GPSR problem remain, not ready for operation until 2/1/2024**
|2/1/2024| **TEMPO operations resume (but GPSR still not used for control, INR degrades but can still meet the INR requirement).** <br> **Solar Cal WD** <br> Citylight measurements (Chicago and Houston, 44s exposure)
|2/2/2024| No GEOS-CF forecast update <br> Citylight measurements (Chicago and Houston, 44s exposure)
|2/3-6/2024| Citylight measurements (Chicago and Houston, 44s exposure)
|2/7/2024| Citylight measurements (Chicago and Houston, 44s exposure) <br> Scan 2 (S002) scan mirror stopped advancing near the end of a scan. Kept imaging of the same location. Scan 2 was processed. Scan 3 back to normal.
|2/8/2024| **Solar Cal WD** <br> Citylight measurements (Full FOR coverage, ~12.7s exposure)|2/9-11/2024| Citylight measurements (Full FOR coverage, ~12.7s exposure)
|2/15/2024| **Solar Cal WD** <br> Citylight measurements (Partial FOR coverage due to reduced measurement time related to gradual season change, ~12.7s exposure)
|2/16-2/21/2024| Citylight measurements (Partial FOR coverage due to reduced measurement time related to gradual season change, ~12.7s exposure)
|2/22/2024| **Solar Cal WD** <br> Citylight measurements (Partial FOR coverage due to reduced measurement time related to gradual season change, ~12.7s) <br> tilted northward to measure Aurora
|2/22-2/28/2024| Citylight measurements (~12.7s), tilted northward to measure Aurora
|2/26/2024| **SDPCv4.3 (V02 data products)** operational processing started.
|2/29/2024| **Solar Cal WD** <br> Same Citylight measurements as last week
|3/1-3/6/2024| Citylight measurements (~12.7s), tilted northward to measure Aurora
|3/7/2024| **Solar Cal WD** <br> Citylight measurements (Las Vegas, Chicago, LA, Houston, DFW regions) with ~120s exposure time with 19 coadds, tilted northward to measure Aurora
|3/8-13/2024| Citylight measurements (~120s exposure time with 19 coadds) tilted northward to measure Aurora
|3/14/2024| **Solar Cal WD** <br> Citylight measurements for full field of regard with ~6.3s (1 coadd) exposure time, no tilting north
|3/14-3/20/2024| Citylight measurements for full field of regard with ~6.3s (1 coadd) exposure time
|3/21/2024| **Solar Cal WD** <br> Citylight measurements for full field of regard with ~6.3s (1 coadd) exposure time, no tilting north <br> At 2024-03-21T15:36:31Z, @rawtol0@ **started reporting frequent data corruption**, duplicated and late packets, which is related to planned maintenance activities at Riverside (from10Am-10PM EST). Three scans (006, 009, 014 could not be processed due to INR failure).
|3/22/2024| **Solar Cal RD** <br> Citylight measurements for full field of regard with ~6.3s (1 coadd) exposure time, no tilting north
|3/23/2024| **Solar Cal WD** <br> Citylight measurements for full field of regard with ~6.3s (1 coadd) exposure time, no tilting north
|3/24-3/27/2024| Citylight measurements for full field of regard with ~6.3s (1 coadd)exposure time, no tilting north
|3/28/2024| **Solar Cal WD**
|3/31/2024|  During twilight (RADT) Scan 002, scan mirror stopped advancing at 2024-03-31T11:03:18Z near beginning of scan.
|3/28-4/03/2024| Citylight measurements for full field of regard with ~6.3s (1 coadd)exposure time, no tilting north 
|4/4/2024| **Solar Cal WD**
|4/4-4/10/2024| Citylight measurements for full field of regard with ~3s (1 coadd)exposure time, no tilting north
|4/11/2024| **Solar Cal WD**
|4/11-4/17/2024| Citylight measurements for full field of regard with ~3s (1 coadd)exposure time, no tilting north
|4/18/2024| **Solar Cal WD**
|4/18-4/24/2024| Citylight measurements for full field of regard with ~3s (1 coadd)exposure time, no tilting north
|4/25/2024| **Solar Cal WD**
|5/2/2024| **Solar Cal WD**
|5/9/2024| **Solar Cal WD**
|5/13/2024| **SDPCv4.4 (V03 data products)** operational processing started <br> Scan mirror stopped advancing near end of scan 12 (S012) at 21:00:18Z. Scan 12 covers 20:01:28Z-21:01:09Z.
|5/16/2024| **Solar Cal WD**
|5/17/2024| Scan 15 Granule 5 (S015G05) missing (data dropout led to processing issue)
|5/23/2024| **Solar Cal WD**
|5/23/2024 - 5/27/2024| The retrievals are done with GEOS-CF climatology instead of GEOS-CF data from 2024-5-23 S014 through the end of 2024-5-27.  
|5/28/2024| Data dropout. Scans 7,8,9 not at ASDC.
|5/30/2024| **Solar Cal WD** Scan 8 missing (data dropout led to processing issue)
|5/31/2024| Scan mirror stopped advancing shortly after Scan 1 (S001) began at 10:33:11Z. Scan 2 resumed as normal.
|6/6/2024| **Solar Cal WD**
|6/13/2024|**Solar Cal WD** <br> **Special Observations**: Calibration campaign, scans S012,S013,S014 starting 20:40:31Z total duration 1 hour
|6/14/2024| **Special Observations**: Calibration campaign, scans S012,S013,S014 starting 20:40Z total duration 1 hour
|6/16/2024| **Special Observations**: Calibration campaign, scans S012,S013,S014 starting 20:10:55Z total duration 1 hour
|6/20/2024| **Solar Cal WD**
|6/21/2024| **Solar Cal RD**
|6/22/2024| **Solar Cal WD**
|6/27/2024| **Solar Cal WD**
|6/28/2024-7/08/2024| The June 28 IMS ice/snow cover product was used in SDPC processing for the period June 28-July 8 due to download issue.
|7/03/2024| Scan mirror stopped advancing about midway through Scan 2 (S002) at 11:37:07Z. Scan 3 resumed as normal.
|7/04/2024| **Solar Cal WD**
|7/11/2024| **Solar Cal WD**
|7/18/2024| **Solar Cal WD**
|7/21/2024| Low level data corruption, impacted INR. Scan 9 (S009) not at ASDC.
|7/24/2024| **Unplanned S/C maintenance. No Observations taken for the day.** Resumed observations as usual 7/25.
|7/25/2024| **Solar Cal WD**
|8/01/2024| **Solar Cal WD**
|8/08/2024| **Solar Cal WD** Technical issues. **No radiance scan observations taken for the day.**
|8/09/2024| Technical issues. **No radiance scan observations taken.**
|8/10/2024-8/21/2024| Technical issues. **No radiance scan observations taken.**
|8/22/2024| **Solar Cal WD**  <br> **Observations resume** <br> **8/22-29** GEOS-CF forecast download failed causing CLDO4, HCHO, and NO2 retrievals to use climatology. Scan 14 (S014) on 8-22 to scan 16 (S016) 8/29.
|8/23/2024| **Solar Cal RD** <br> 
|8/24/2024| **Solar Cal WD**
|8/29/2024| **Solar Cal WD**
|8/30/2024| GEOS-CF forecast back to operational at start of day (affects CLD04,HCHO and NO2 products).
|9/05/2024| **Solar Cal WD** <br> Citylights measurements, ~6 (6.3) sec exposure, 9/05-9/11
|9/12/2024| **Solar Cal WD** <br> Citylights measurements, 3.0 and 6.0 sec exposure 9/12-9/18
|9/19/2024| **Solar Cal WD** <br> Citylights measurements, 6.3 sec exposure, 9/19-9/25
|9/20/2024| **Solar Cal RD**
|9/21/2024| **Solar Cal WD**
|9/23/2024| Brief data dropout for Scan 14 (S014) around 23:04Z  (Scan 14 covers 22:30:16Z to 23:10:22Z) <br>Scan mirror stopped advancing near end of scan 15 (S015) at ~23:40Z for about 10 minutes. End of scan 15 is 23:50:27Z.
|9/26/2024| **Solar Cal WD** <br> Citylights measurements, 6.3 sec exposure, tilt South FoR (dy=4400), 9/26-10/3
|10/03/2024| **Solar Cal WD (different parameters, shorter int time)** <br> Citilights measurements, 6.3 sec exposure area scans alternate with aurora scans (tilt FoR north, 120 sec. exposure), 10/03-10/09 <br> earth darks at ~06:15:45Z
|10/09/2024| Evening city lights scan (S016) not processed due to data loss during first granule.
|10/10/2024| **Solar Cal WD** (shorter int time will be default going forward) <br> Citilights measurements, area scans (~6.3 sec) plus moonlight illumination scans (~12 sec),10/10-10/16
|10/17/2024| **Solar Cal WD** <br> Citilights measurements, Morning city lights scans target a 200-step wide window including California (~6 sec), while evening city lights scans cover the eastern half of the field of regard (11.72 sec). 10/17-10/23
|10/24/2024| **Solar Cal WD** <br> Citilights measurements, area scans (12 sec, 2 coadds), 10/24-10/30
|10/25/2024| **Unplanned S/C maintenance. No Observations taken for the day.** Resumed observations as usual 10/26.
|10/31/2024| **Solar Cal WD** <br> Citilights measurements, area scans (12 sec, 2 coadds), 10/31-11/06
|11/07/2024| **Solar Cal WD** <br> Citilights measurements, area scans (12 sec, 2 coadds), 11/07-11/13
|11/14/2024| **Solar Cal WD** <br> Citilights measurements, area scans (12 sec, 2 coadds), 11/14-11/20
|11/19/2024| S/C maintenance required two East/West maneuvers. 8 scans: S001-S008 (less than usual number of daily scans)
|11/21/2024| **Solar Cal WD** <br> Citilights measurements, area scans (12.6 sec, 2 coadds), 11/21-11/27
|11/28/2024| **Solar Cal WD** <br> Citilights measurements, east-coast twilight scans are 6.27 sec exposures and will cover only the region from just eastward of Cape Cod to just westward of Chicago, yielding 4 scans per session.  The west-coast twilight scans are ~12.6 sec (2 coadds), 11/28-12/04
|12/05/2024| **Solar Cal WD** <br>  Citilights measurements, area scans (12.6 sec, 2 coadds),12/05-12/11
|12/12/2024| **Solar Cal WD** <br> Citilights measurements, east-coast twilight scans are 6.27 sec exposures and will cover only the region from just eastward of Cape Cod to just westward of Chicago, yielding 4 scans per session.  The west-coast twilight scans are ~12.6 sec (2 coadds), 12/12-12/18.
|12/18/2024| **Solar Cal WD**
|12/19/2024| **Solar Cal RD** <br> Citilights measurements, east-coast twilight scans are 6.27 sec exposures and will cover only the region from just eastward of Cape Cod to just westward of Chicago, yielding 4 scans per session.  The west-coast twilight scans are ~12.6 sec (2 coadds), 12/19-12/25.
|12/20/2024| **Solar Cal WD**
|12/26/2024| **Solar Cal WD** <br> Citilights measurements, east-coast twilight scans are 6.27 sec exposures and will cover only the region from just eastward of Cape Cod to just westward of Chicago, yielding 4 scans per session.  The west-coast twilight scans are ~12.6 sec (2 coadds), 12/26-01/01.
|01/02/2025| **Solar Cal WD** <br> Citilights measurements, east-coast twilight scans are 6.27 sec exposures and will cover only the region from just eastward of Cape Cod to just westward of Chicago, yielding 4 scans per session.  The west-coast twilight scans are ~12.6 sec (2 coadds), 01/02-01/08.
|01/07/2025| City lights scan (RADT product): Scan mirror stopped advancing near start of scan 1 (S001), at 2025-01-07 10:07:27Z. End of scan at 12:26:59Z.
|01/09/2025| **Solar Cal WD** <br> Citilights measurements, east-coast twilight scans are 6.27 sec exposures and will cover only the region from just eastward of Cape Cod to just westward of Chicago, yielding 4 scans per session.  The west-coast twilight scans are ~12.6 sec (2 coadds), 01/09-01/15.
|01/13/2025| Citilights (RADT) S017G03,S018 delayed/reprocessing required.
|01/15/2025| Citilights (RADT) S017G03,S018 delayed/reprocessing required.
|01/16/2025| **Solar Cal WD** <br> Citilights measurements, east-coast twilight scans are 6.27 sec exposures and will cover only the region from just eastward of Cape Cod to just westward of Chicago, yielding 4 scans per session.  The west-coast twilight scans are ~12.6 sec (2 coadds), 01/16-01/22.
|01/16-01/19/2025| **Special obs:** 10-min scans of the LA region on 16-19 Jan (Thu-Sun). alternating hourly with FoR scans.
|01/23/2025| **Solar Cal WD** <br> Citilights measurements, area scans (~12 sec, 2 coadds), 01/23-01/29.
|01/30/2025| **Solar Cal WD** <br> Citilights measurements, area scans (~12 sec, 2 coadds), 01/30-02/05.
|02/06/2025| **Solar Cal WD** <br> **Unplanned S/C maintenance. No radiance observations taken until 21:22Z, starting with S011.** Observations resumed as usual for rest of the day. Scans S001-S010 do not exist. <br> Citilights measurements, area scans (~12 sec, 2 coadds), 02/06-02/12.
|02/07/2025| **Unplanned S/C maintenance. No radiance observations taken until 17:22Z, starting with S007.** Observations resumed as usual for rest of the day. Scans S001-S006 do not exist.
|02/13/2025| **Solar Cal WD** <br> Citilights measurements, area scans (~12 sec, 2 coadds), 02/13-02/19.
|02/20/2025| **Solar Cal WD** <br> Citilights measurements, area scans (~12 sec, 2 coadds), 02/20-02/26.
|02/22/2025| Scans S002-S008 now available (S002-S008 were delayed, due to GOES-18 data outage/gap.) Processing resumed as normal with scan S009.
|02/27/2025| **Solar Cal WD** <br> Citilights measurements, area scans (~12 sec, 2 coadds), 02/27-03/05.
|03/02-03/05/2025| Because IMS snow and ice cover updates were not available March 2-5, TEMPO data collected during this period were processed using IMS data from March 1. IMS updates resumed on March 6.
|03/06/2025| **Solar Cal WD** <br> Citilights measurements, area scans (~6 sec, 1 coadd), 03/06-03/12.
|03/07,08,09/2025| Because IMS snow and ice cover updates were not available March 7-9, TEMPO data collected during this period were processed using IMS data from March 6. IMS updates resumed March 10.
|03/12/2025| GEOS-CF forecast was unavailable for part of March 12 due to system maintenance. Climatology was used as input for CLDO4,HCHO and NO2 retrievals for S013,S014.
|03/13/2025| **Solar Cal WD** <br> Citilights measurements, area scans (~6 sec, 1 coadd), 03/13-03/19. <br>  GEOS-CF forecast was unavailable March 13 due to system maintenance.  Climatology was used as input for CLDO4,HCHO and NO2 retrievals S002 to S014.
|03/19/2025| **Solar Cal WD**
|03/20/2025| **Solar Cal RD** <br> Citilights measurements, area scans (~6 sec, 1 coadd), 03/20-03/26.
|03/21/2025| **Solar Cal WD**
|03/25/2025| Scan mirror stopped advancing near end of Scan 12 (S012) starting at 21:45:40Z. S012 goes from 21:14:47Z-21:57:11Z. Next scan resumed as normal.
|03/27/2025| **Solar Cal WD** <br> **Special Obs:** Perform 12 min. scans covering Geneva State Forest Alabama (prescribed burn) and NYC alternating hourly with FoR scans <br> Citilights measurements, area scans (~6 sec, 1 coadd), 03/27-04/02.
|03/28/2025| **Special Obs:** Perform 12 min. scans covering Geneva State Forest Alabama (prescribed burn) and NYC alternating hourly with FoR scans.
|04/03/2025| **Solar Cal WD** <br> Citilights measurements, area scans (~6 sec, 1 coadd), 04/03-04/09.
|04/07/2025| Scan mirror stopped advancing at 21:28:38Z, in middle of Scan 12 (S012) 21:10:56Z - 22:10:37Z. Next scan resumed as normal.
|04/09/2025| **Special Obs**: S006 and S007 (scans 6 and 7). Otherwise nominal scan pattern.
|04/10/2025| **Solar Cal WD** <br> Citilights measurements, area scans (~6 sec, 1 coadd), 04/10-04/16.
|04/17/2025| **Solar Cal WD** <br> **Special Obs:** April 17: interleaved 10 minute scans to observe the prescribed burn experiment in the Fort Stewart, GA area. <br> Citilights measurements, area scans (~6 sec, 1 coadd), 04/17-04/23.
|04/24/2025| **Solar Cal WD** <br> Citilights measurements, area scans (~6 sec, 1 coadd), 04/24-04/30.
|05/01/2025| **Solar Cal WD** <br> No citilights measurements. End of citilights season.
|05/06/2025| Scan 1 (S001) could not be processed due to short telemetry gap. <br> **SDPCv4.5** operational processing started.
|05/08/2025| **Solar Cal WD** <br> Scan 15 (S015) could not be processed due to telemetry gap. 
|05/15/2025| **Solar Cal WD**
|05/22/2025| **Solar Cal WD**
|05/29/2025| **Solar Cal WD**
|05/31/2025| **Special obs. scans**: S011, S012, S013 for calibration starting at 20:51:12Z (1 hr total).
|06/01/2025| **Special obs. scans**: S013, S014, S015 starting at 20:40Z (1 hr total).
|06/02/2025| **Special obs. scans**: S013, S014, S015, starting at 20:20Z (1 hr total).
|06/03/2025| **Special obs. scans**: S013, S014, S015, starting at 20:30Z (1 hr total).
|06/03/2025-06/06/2025| The June 3rd IMS ice/snow cover product was used in SDPC processing for June 3-June 6 due to no IMS update since June 3.
|06/05/2025| **Solar Cal WD** <br> **Special obs scans**: S012, S013, S014, starting at 20:20Z (1 hr total).
|06/09/2025| **SDPCv4.6** operational processing started.
|06/12/2025| **Solar Cal WD**
|06/19/2025| **Solar Cal WD** <br> **Special obs.** scans (10 min.), 83W to 93W, Scans 12-28 (S012-S028) from 20:06Z to 23:06Z.
|06/20/2025| **Solar Cal RD**
|06/21/2025| **Solar Cal WD**
|06/26/2025| **Solar Cal WD**
|07/03/2025| **Solar Cal WD**
|07/10/2025| **Solar Cal WD**
|07/17/2025| **Solar Cal WD**
|07/22/2025| **Unplanned S/C maintenance** No radiance measurements taken for most of the day. Only S001 (granules G01-G04) and S013,S014 scans exist.


For Current week's predicted overpass times at certain sites, see [OverPass](https://tempo.si.edu/OverpassPrediction)

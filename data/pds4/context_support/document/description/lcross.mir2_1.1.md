
 
  Instrument Overview
  ===================
 
  The LCROSS mid-infrared camera #2 (MIR2) is vanadium oxide (VOx)
  microbolometer model ThermoVision Micron from Flir Systems/Indigo
  Operations.  MIR2's focal plane uncooled microbolometer sensor has a
  164 [H] x 128 [V] pixel resolution and is digitized at 14-bit resolution.
 
  MIR2 is one of two mid-infrared (7.5-13.5 micron) cameras carried by
  LCROSS. MIR2 is filter-less while MIR1 contains a 6-10 micrometer bandpass
   filter. This is the primary difference between the cameras. There are
   other differences due to the fact that MIR1 is manufactured by
   Thermoteknix, repackaged in a Argon-filled environment to improve
   temperature stability and has been set to different factory defaults.
 
  MIR2 has a 30 mm, f/1.6 lens providing a 15.0 deg [H] x 11.0 deg
  [V] (18.6 deg [Diagonal]) field-of-view.
 
  Although the camera's native format is 164 [H] x 128 [V] 14-bit images,
  the images are converted by the DHU GSEOS software to 160 [H] x 120 [V]
  14-bit images.
 
  Internal to both MIR modules is an instrumented-motorized shutter
  to provide a reference for temperature measurements.  The camera's
  peak power during operation is 1.3 W.  The gain, which determines the
  sensitivity to temperature scenes, is configurable with a command sent
  to the camera.
 
  Unlike MIR1, MIR2 is not backfilled with dry gas.
 
  Scientific Objectives
  =====================
 
  The main science objectives for the mid infrared cameras (MIR1 & MIR2)
  is to provide pre- and post-impact thermal images of the impact terrain
  and identify the location of the Centaur impact-created crater. In
  addition, these cameras will obtain thermal evolution of the ejecta plume
  (which is dependent on the water content) and observe the ejecta blanket
  and freshly exposed regolith at mid-infrared wavelengths.
 
 
  Calibration
  ===========
 
  Conversion from raw data values [DN] to a scene temperature (degree C)
  is described in the LCROSS Instrument Response and Calibration Report
  in the CALIB directory of this archive.  The relationship is gain
  dependent. High sensitivity/High Gain (low scene temperature) is used for
  the majority of the mission data. The relationship is also sensor
  temperature dependent. Pre-flight DN to scene temperature was only
  performed at room temperature (+17 to +21 C) during requirement
  validation, mainly at atmosphere with very limited vacuum testing.
  A calibration for the flight mid-infrared camera images is provided using
  a high-fidelity thermal model of the moon's south pole at the time of
  impact from the LRO Diviner team to map raw data values [DN] to
  temperature (degrees C).
 
  In addition, the MIR camera units are programmed to perform a
  flat field correction (FFC) every 2 minutes. Flat Field Correction
  (also known as NUC or single point correction) is the process of measuring
  the output and creating an offset for every pixel so that the output becomes
  totally uniform (Flat). Internal to both MIR modules is an
  instrumented-motorized shutter to provide a reference for this FFC.
 
  The MIR cameras both experience settling time effects that asymptote
  away approximately 10 minutes after instrument power on. Calibrations
  for these instruments are valid for only this steady state condition.
 
  In addition MIR2 performance in-flight was subject to another time-
  dependent transient that is calibrated out using thermal vacuum test
  data and in-orbit performance. Details are documented in the LCROSS
  Instrument Response and Calibration Report.
 
  The gain settings are documented with each image.
 
 
  Operational Modes
  =================
 
  The LCROSS mid-infrared cameras have a single mode change parameter - high
  vs. low gain.  The majority of the mission data is taken in high
  sensitivity or high gain. This gain setting is best suited for low scene
  temperatures (temperature < +150 deg C). The low temperature floor
  sensitivity for this mode was measured to be ~-50 C. The other setting,
  low sensitivity or low gain is better suited for high scene temperatures
  (+150 C < temperature < +500 C).  Only quicklook-29k data toggles between
  the two gain settings as a part of a health and status checkout.

        
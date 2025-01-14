
              Online Reference: http://wundow.wustl.edu/clbin/clsearch.pl

 
  Instrument Overview
  ===================
   The High Resolution Imaging (HIRES) camera combines a lightweight
   beryllium telescope with an image intensifier-coupled frame
   transfer charge couple device (CCD) imager.  Image shuttering is
   accomplished through voltage gating of the image intensifier.
 
   Maximum integration time is 733 milliseconds with 10.67 microsecond
   increments.  Spectral response is limited in the system by the S-2
   photo cathode between 0.4 and 0.8 microns. Five spectral bands can
   be selected from a filter wheel which is controlled through the
   serial-addressable synchronous interface (SASI).  A sixth filter
   position is allocated to an opaque filter for the protection of the
   photocathode and image intensifier.
 
   The post-FPA electronics circuitry is identical to that used in the
   UVVIS camera.  Images of the dayside of the moon used intensifier
   gate times with relatively low gain settings on the order of 1
   millisecond.
 
   Lifetime concerns about the photocathode and micro channel plates
   in the intensifier unit drove operational settings to low
   exposures.  This resulted in photon shot noise contributing
   significantly to the overall noise in the HIRES sensor.
 
   Additionally, the image intensifier imposed a nonuniformity on
   images. This yielded images that did not compress well using the
   MATRA optimized rms algorithm. For this reason, JPEG compression,
   which discards high spatial frequency detail, was employed on the
   Hires images.
 
   The Hires performance specifications are provided below.
 
   Scientific Objectives
   =====================
   The HIRES camera was used primarily to photograph the lunar poles
   at very high resolutions ranging from 10 to 15 meters/pixel
   (effective resolution of 40 to 60 meters when taking into account
   the 4 pixel point spread function of the instrument).  Polar
   observations were made primarily with the 750nm spectral filter
   (filter wheel position D).  Because of the narrow field-of-view of
   the HIRES camera overlapping coverage of the HIRES imaging was not
   possible between -80 to 80 degrees latitude.
 
   The HIRES camera was also used to make high-resolution color
   observations of special targets such as the Apollo landing sites
   and Earth seen from lunar orbit.
 
 
   Calibration
   ===========
   The radiometric calibration converts the digitized signal received
   from the camera (DN value) into a quantity that is proportional to
   the radiance reaching the sensor.  The sensitivity of the CCD focal
   plane array varies across the field of view but appears to be time
   invariant during the two month lunar observation period.  The HIRES
   camera was calibrated before launch.  Laboratory observations of a
   flat field under various operating temperatures and camera
   operation modes provides information about the sensitivity of the
   camera under expected spaceflight conditions.  During inflight
   operations, a variety of calibration observations were made
   including images of stars with known radiance (Vega) and the Apollo
   Landing sites where laboratory spectra of returned lunar samples
   have been measured.
 
   Geometric calibration removes optical distortions of the imaging
   system.  The geometric distortion of the HIRES camera has been
   shown to be minimal (maximum optical distortion does not exceed 0.1
   pixels) and can be satisfactorily modeled by a 2nd order
   polynomial.
 
   In regards to the HiRes 750nm Strip Mosaics Archive (DATA_SET_ID =
   CLEM1-L-H-5-DIM-MOSAIC-V1.0, PDS volumes CL_6001 through
   CL_6022), the Hires geometric and photometric calibrations were
   referenced to the UVVIS Basemap Mosaic.  The geometric calibration
   was achieved through a constrained registration of map-projected,
   nadir-pointed Hires images against the UVVIS Basemap Mosaic, which
   is the de facto lunar control network. An approximate photometric
   calibration was performed on Hires mosaic tiles of sufficiently
   limited extent (1.75 degrees of latitude) that the photometric
   response was approximately constant.  Then, the linear stretch
   which matches the underlying UVVIS Baseline Mosaic approximates the
   photometric calibration of the Hires tile.
 
   For additional information on the geometric and radiometric
   calibration of the Clementine imaging systems, contact the PDS
   Imaging Node.
 
 
   Operational Considerations
   ==========================
   Lifetime concerns about the photocathode and micro channel plates
   on the HIRES camera led to several decisions on the operation of
   the camera during the lunar mapping phase of the mission.  The
   primary objective of the HIRES camera was to have been high-
   resolution color imaging of the asteroid Geographos; lunar
   observations were of secondary importance.  The Geographos fly-by
   was abandoned due to a spacecraft malfunction that caused a spin up
   of the spacecraft and loss of attitude control on May 7, 1994.  The
   HIRES camera was essentially 'turned off' during the lunar
   observations between the latitude ranges -50 to 50 degrees, thereby
   preserving the life of the instrument.  The imaging system remained
   active at this time due to the electronic coupling with the LIDAR
   altimeter but the camera was set so that no real imaging was
   acquired.  The result is that most HIRES images acquired at mid-
   latitudes are not usable.
 
   The unusable HIRES imaging was included in the archive of EDR data
   products in order to form a complete set of all data returned by
   the spacecraft.  At high latitudes low camera settings were used to
   ensure the HIRES camera would be undamaged for the Geographos
   encounter.  Thus, the signal/noise ratio of the HIRES imaging data
   during the lunar mapping phase is less than ideal.  Photon shot
   noise and the 'honey comb' noise pattern of the intensifier is
   evident in most of the lunar images.
 
   The pole-to-pole lunar observations provided scenes with a broad
   range of viewing conditions, ranging from bright observations near
   zero phase angle at the equator to very low light-level
   observations at the poles.  In order to properly record an
   observation with an optimal signal-to-noise ratio it is important
   to adequately fill the 8-bit (255 levels) dynamic range of the A/D
   camera output.  The integration time (exposure time) and the gain
   and offset settings of the instrument were adjusted to properly
   record each image.  During the systematic mapping, the gain state
   of the camera was normally set to lower values for the mid-latitude
   observations and set to higher levels (thereby increasing the
   sensitivity of the A/D converter) at the higher latitudes.
   Integration times were rarely increased as observations approached
   the poles, nominally being set to 1.067 ms.  Lunar observations
   were broken into 10 latitude bins.  Each latitude bin nominally
   contained fixed gain and offset modes and integration times for
   each camera/filter combination, although occasional offlooking
   slews that fell within a bin other than that corresponding to the
   subspacecraft point resulted in images with differing acquisition
   settings.
 
   The Clementine orbit was designed to provide overlapping coverage
   in both the down-track (~15% overlap) and cross-track (~10% overlap
   at the equator) directions.  The image overlap is necessary to
   geometrically control images in cartographic applications.
 
 
   Operational Modes
   =================
   The HIRES camera had four operating modes:
 
   1. Programmable integration time.  (up to 733 milliseconds in 10.67
   millisecond steps)
 
   2. A/D Gain Mode. The gain mode represents the multiplicative
   constant applied to the image data passing through the A/D
   converter. Three gain state settings were available (1,2,4).
 
   3. A/D Offset Mode. The offset mode represents the additive
   constant applied to the image data passing through the A/D
   converter. There were 14 offset mode settings (1-14).
 
   4. Microchannel Plate Gain Mode. The mode provided gain control on
   the microchannel plate. (8-bit, 255 step gain control).
 
   Camera Specifications
   =====================
 
     Detectors
     ---------
    Focal Plane Array -
    Type            :  Si Charge Coupled Device
                       Thomson TH7863-CRU (Not UV enhanced)
    Pixel format    :  288x384
    Pixel size      :  23x23 microns
    Readout rate    :  4MHz
    Image intensifier -
    Image intensifier module      : General Atomics 0131-Z12-2-009
    Useful photocathode diameter  : 12 mm
    Luminous gain                 : 1000 fL/fC
    Limiting resolution           : 40 lp/mm
    Gain control                  : 8 bits
    Power                         : 9.5 W
    Properties FPA and joined intensifier -
    Wavelength        0.4 to 0.8 microns
    Field of view     0.4 deg. x 0.3 deg.
    Pixel IFOV        18 microradians
    Point spread      4 pixels
 
 
  Electronics
  -----------
    A/D resolution   : 8 bits
    Frame rate       : 10 Hz
    Readout time     : 27.4 ms
    Integration time : 0.2-733 ms
    Digitization gain: 150,350,1000 electrons
    Offset control   : 248 gray levels
    Power            : 4.5 W
 
 
  Filters
  -------
    Filter
    Wheel         Spectral
    Position      Band
    -----------------------------------------------
    A      : 415 nm cw (plus-or-minus 20 nm bw)
    B      : 560 nm cw (plus-or-minus 5)
    C      : 650 nm cw (plus-or-minus 5)
    D      : 750 nm cw (plus-or-minus 10)
    E      : 400 to 800 nm broad band
    F      : opaque filter (no light transmittance)
 
 
  Optics
  ------
    Clear aperture :    131 nm
    Speed          :   F/9.5
 
 
  Mechanical
  ----------
    Mass           : 1120 grams
    Size           : 17.0 cm x 18.1 cm x 36.4 cm

        
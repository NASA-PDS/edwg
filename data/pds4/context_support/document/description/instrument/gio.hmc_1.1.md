
 
      Instrument Overview
      ===================
        The HMC utilizes a 16-cm modified Ritchey-Chretien telescope
        with a 1.00-m focal length to image the sky onto a set of
        linear-array detectors.  The telescope is mounted with its axis
        perpendicular to the rotational axis of the spacecraft.  A 45-
        degree mirror in front of the telescope, which rotates together
        with the entire telescope assembly, allows the telescope to view
        any direction from parallel to the spacecraft's axis of spin to
        perpendicular to that axis.  Thus, depending on the rotational
        orientation of the telescope, the spin of the spacecraft causes
        the linear field of view of the camera to sweep out a circle on
        the sky (when pointed nearly parallel to the axis of spin), or
        an annulus on the sky (when pointed at intermediate directions),
        or a rectangular strip (when pointed perpendicular to the axis
        of spin).  A reticon detector with two rows of 936 pixels (30 by
        375 microns each) has a linear field of view of 1.6 degrees and
        was used primarily to search for the comet before the encounter.
        Two CCDs (22.35 micron square pixels; 584 lines of 390 pixels)
        were masked to provide two linear detectors on each CCD.  Each
        linear detector was several pixels high and the readouts were
        clocked to move the charge from line to line synchronized with
        the effective motion of the image across the detector.  Three
        detectors were fitted with fixed filters (red, blue, and clear)
        and the third was fitted with a filter wheel containing a
        variety of narrow-band filters.  In some modes, on-chip binning
        was used to improve the signal-to-noise ratio at the expense of
        reduced spatial resolution.  On-board electronics located the
        brightest portion of each image and transmitted a region
        centered on that point, discarding the periphery of each image.
 
      Science Objectives
      ==================
        The technical goals of the experiment were first to obtain high-
        quality images of the cometary nucleus in four colors with two
        polarizations and secondarily to obtain images of the cometary
        coma in a variety of narrow bandpasses.  The primary scientific
        goal to be addressed with these images was to determine the
        basic properties of the nucleus including the size and shape,
        the morphology and topography of the surface, the photometric
        properties of the surface, the rotational state, the degree of
        heterogeneity in the outgassing, and the energy balance at the
        surface.  The secondary scientific goal was to study the
        properties of the inner coma including the production and
        evolution of gas and dust, the scales of the relevant physical
        processes, the size distribution of the dust, the chemistry of
        the inner coma, and the temporal variability in the inner coma.
 
      Calibration Description
      =======================
        Flat-fielding, or determining the responsivity matrix for each
        pixel, was carried out using pre-flight exposures on the ground.
        These were all taken without on-chip binning (i.e.  in SPF-0,
        Super Pixel Format 0).  Because the detectors are one-
        dimensional, defects in the responsivity matrix show up as
        vertical lines in an image.  For detector C, the most frequently
        used detector, the encounter data in both SDM and MDM were used,
        by integrating parallel to the tracking, to locate vertical
        lines in the images and the responsivity matrix was adjusted to
        make these integrated brightnesses vary smoothly along the
        window. Detectors B and D were strongly affected by blooming of
        the charge in the pre-flight calibration exposures so only faint
        exposures could be used and these required fitting of a
        polynomial to the illumination.  The gain switch, used to reduce
        the gain by a nominal factor 4 during non SPF-0 SDM
        observations, was calibrated by comparing images of Jupiter
        taken in SDM at both gains.  The ratio was 4.115, in good
        agreement with ground-based tests prior to launch.  The absolute
        calibration was carried out by observing bright stars, Jupiter,
        and Venus while enroute to the comet.  The absolute fluxes from
        the stars were obtained from published sources and, when not
        available from these sources, by fitting black-body curves to
        the known fluxes.  Observations of Venus and Jupiter were also
        used together with published fluxes, taking into account the
        variation with phase.  The final overall calibration is thought
        to be accurate to about 5%.  See Thomas and Keller, 1990,
        Applied Optics, 29, 1503-1519 fur further details.
 
      Operational Considerations
      ==========================
        The instrument operated at a much higher temperature than
        planned, resulting in a much higher dark current than expected.
        Because the clocking of the CCD was synchronized with the
        rotation of the spacecraft as projected on the sky, the
        effective exposure time varies with the orientation of the
        telescope and its periscopic 45-degree mirror with the shortest
        effective exposure times occurring at closest approach (viewing
        perpendicular to the axis of spin). Because of the periscopic
        approach to scanning, the shape of the field of view is a
        function of the rotation of the telescope and its 45-degree
        periscopic mirror.  Geometric rectification was carried out
        after the image was transmitted back to Earth.
 
        Instrument Manufacturer    :
                        MAX-PLANCK-INSTITUT-FUER-AERONOMIE
 
      Detectors
      =========
 
        Detector A
        ----------
          Detector type                 : RETICON
          Nominal Operating Temperature : 253.
          Model CP 1001 Reticon with two rows of 936 pixels each with no
          dead area between pixels. Individual pixels are 30 by 375
          microns. Coincidence between the two rows was used to
          discriminate against cosmic rays.  Two clocking speeds were
          used to allow for different brightness levels of the target.
 
        Detector B
        ----------
          Detector type                 : CCD
          Minimum Wavelength            : 0.30
          Maximum Wavelength            : 1.05
          Nominal Operating Temperature : 253.
          This detector is one of two windows in the mask on CCD number
          1.  The CCD is a virtual-phase device by Texas Instruments
          with two independent sections of 390 by 292 pixels and the two
          windows are at the 'leading' edge of each section.  Pixel size
          is 22.35 microns square.  The window in the mask is the full
          width of 390 pixels by several pixels and the clocking is
          varied to synchronize with the apparent motion of the image
          across the detector window.  The output is thus a line of 390
          pixels for each of many different positions in the image.
          This window is always viewing through a red filter and is the
          first of the four imaging detectors to 'see' an object as the
          field of view of the telescope sweeps across the sky.
 
          Sensitivity Description: See response curve for CCD given in
          Schmidt et al.  (1986), Figure 9 and the reflectivity of the
          mirror given in Figure 7 of the same reference.  See also the
          characteristics of Filter B in the appropriate template or in
          Table I of the same reference.
 
        Detector C
        ----------
          Detector type                 : CCD
          Minimum Wavelength            : 0.30
          Maximum Wavelength            : 1.05
          Nominal Operating Temperature : 253.
          This detector is one of two windows in the mask on CCD number
          1.  The CCD is a virtual-phase device by Texas Instruments
          with two independent sections of 390 by 292 pixels and the two
          windows are at the 'leading' edge of each section.  Pixel size
          is 22.35 microns square.  The window in the mask is the full
          width of 390 pixels by several pixels and the clocking is
          varied to synchronize with the apparent motion of the image
          across the detector window.  The output is thus a line of 390
          pixels for each of many different positions in the image.
          This window views through the filter wheel containing a series
          of polarizers and narrow-band filters.  It is the second of
          the four imaging detectors to 'see' an object as the field of
          view of the telescope sweeps across the sky.
 
          Sensitivity Description: See response curve for CCD given in
          Schmidt et al.  (1986), Figure 9 and the reflectivity of the
          mirror given in Figure 7 of the same reference.  See also the
          characteristics of Filters Cn in the appropriate templates or
          in Table I of the same reference.
 
        Detector D
        ----------
          Detector type                     : CCD
          Minimum Wavelength                : 0.30
          Maximum Wavelength                : 1.05
          Nominal Operating Temperature     : 253.
          This detector is one of two windows in the mask on CCD number
          2.  The CCD is a virtual-phase device by Texas Instruments
          with two independent sections of 390 by 292 pixels and the two
          windows are at the 'leading' edge of each section.  Pixel size
          is 22.35 microns square.  The window in the mask is the full
          width of 390 pixels by several pixels and the clocking is
          varied to synchronize with the apparent motion of the image
          across the detector window.  The output is thus a line of 390
          pixels for each of many different positions in the image.
          This window is always viewing through a blue filter and is the
          third of the four imaging detectors to 'see' an object as the
          field of view of the telescope sweeps across the sky.
 
          Sensitivity Description: See response curve for CCD given in
          Schmidt et al.  (1986), Figure 9 and the reflectivity of the
          mirror given in Figure 7 of the same reference.  See also the
          characteristics of Filter D in the appropriate template or in
          Table I of the same reference.
 
        Detector E
        ----------
          Detector type                 : CCD
          Minimum Wavelength            : 0.30
          Maximum Wavelength            : 1.05
          Nominal Operating Temperature : 253.
          This detector is one of two windows in the mask on CCD number
          2.  The CCD is a virtual-phase device by Texas Instruments
          with two independent sections of 390 by 292 pixels and the two
          windows are at the 'leading' edge of each section.  Pixel size
          is 22.35 microns square.  The window in the mask is the full
          width of 390 pixels by several pixels and the clocking is
          varied to synchronize with the apparent motion of the image
          across the detector window.  The output is thus a line of 390
          pixels for each of many different positions in the image.
          This window is always open to white light without a filter and
          is the last of the four imaging detectors to 'see' an object
          as the field of view of the telescope sweeps across the sky.
 
          Sensitivity Description: See response curve for CCD given in
          Schmidt et al.  (1986), Figure 9 and the reflectivity of the
          mirror given in Figure 7 of the same reference.  See also the
          characteristics of Filter E in the appropriate template or in
          Table I of the same reference.
 
      Electronics
      ===========
        The CCDs are read out using a Correlated Double Sampling
        technique to minimize noise and are then digitized with a 12-bit
        ADC.  A 4-to-1 gain switch in front of the ADC effectively
        provides a 14-bit ADC.  Super-pixels are created in various
        formats by binning the charge from multiple pixels on the
        charge-sensing node of the output gate of the CCD. Formats for
        binning are: SPF-0 = 1 x 1; SPF-1 = 2 x 2; SPF-2 = 4 x 4; SPF-3
        = 8 x 8; SPF-4 = 16 x 16; and SPF-5 = 4 x 3.  Noise of 75
        electrons (rms) has been achieved in flight but there appears to
        have been some interference from other experiments or other
        parts of this experiment.  The two CCDs are read out in parallel
        in MDM.  The two lines of the reticon are each read out on two
        video lines alternately.  There are two readout speeds, a slow
        speed using both lines of pixels for acquiring the comet
        initially, and a high speed used with a single line of pixels to
        evaluate the position of the comet prior to the arrival of that
        part of the image at the first CCD detector.  An acquisition
        preprocessor converts the reticon signals into the minimum
        number of bytes needed to specify the passage of a bright object
        across the field of view of the reticon.  A tracking
        preprocessor determines the actual location of the bright object
        relative to the spacecraft for use in acquisition and in
        controlling the clocking of the CCD readout.  A mass memory unit
        can store the full readout from all four detectors during a
        single spin of the spacecraft.  The digital processing unit uses
        an algorithm to select portions of the images for telemetry
        since the maximum data rate can not accommodate transmission of
        the full images.
 
      Filters
      =======
 
        Filter 1
        --------
          Filter Name                   : C1
          Filter Type                   : OPAQUE SHUTTER
 
        Filter 2
        --------
          Filter Name                   : C2
          Filter Type                   : CLEAR
 
        Filter 2A
        ---------
          Filter Name                   : E
          Filter Type                   : CLEAR
 
        Filter 3
        --------
          Filter Name                   : C3
          Filter Type                   : WIDE-BAND RED
          Minimum Wavelength            : 0.700
          Minimum wavelength is for 500f peak
          transmission and has a tolerance of 0.005
          microns.  Filter transmits to wavelengths longer
          than the response of the CCD.
 
        Filter 3A
        ---------
          Filter Name                   : B
          Filter Type                   : WIDE-BAND RED
          Minimum Wavelength            : 0.700
          Minimum wavelength is for 500f peak transmission
          and has a tolerance of 0.005 microns.  Filter transmits
          to wavelengths longer than the response of the CCD.
 
          Filter 4
          --------
          Filter Name : C4 Filter Type : WIDE-BAND ORANGE
          Minimum Wavelength           : 0.580
          Center Filter                0.700
          Maximum and minimum wavelengths refer to points
          with 500f peak transmission.  Both have tolerances
          of 0.005 microns.
 
          Filter 5
          --------
          Maximum Wavelength : 0.490
          Maximum wavelength refers to point with 500f peak
          transmission and has a tolerance of 0.005 microns.
          Filter extends with transmission greater than 900f
          peak to wavelengths less than 0.360 microns.
 
          Filter 5A
          ---------
          Maximum Wavelength : 0.490
          Maximum wavelength refers to point with 500f peak
          transmission and has a tolerance of 0.005 microns.
          Filter extends with transmission greater than 900f
          peak to wavelengths less than 0.360 microns.
 
          Filter 6
          --------
          Filter Name : C6
          Filter Type : PARALLEL POLARIZER
          Polarizer is oriented to transmit electric vector
          parallel to line of image in sky.  Polarizer transmits
          with >900f  peak transmission at all wavelengths at
          which the CCD responds, from <0.300 to >1.100 microns.
 
          Filter 7
          --------
          POLARIZER
          Polarizer is oriented to transmit electric vector
          parallel to line of image in sky.  Polarizer transmits
          with >900f  peak transmission at all wavelengths at
          which the CCD responds, from <0.300 to >1.100 microns.
 
          Filter 8
          --------
          Filter Name : C8
          Filter Type : NARROW-BAND FOR VIOLET CONT
          Minimum Wavelength : 0.440
          Wavelength : 0.456
          Maximum and minimum wavelengths refer to points
          with 500f peak transmission.  Both have
          tolerances of 0.002 microns.
 
          Filter 9
          --------
          Filter Name : C9
          Filter Type : NARROW-BAND RED CONTINUUM
          Minimum Wavelength : 0.716
          Center Filter Wavelength : 0.729
          Maximum Wavelength : 0.742
          Maximum and minimum wavelengths refer to points
          with 500f peak transmission.  Both have
          tolerances of 0.002 microns.
 
        Filter 10
        ---------
          Filter Name                   : C10
          Filter Type                   : NARROW-BAND FOR OH RADICAL
          Minimum Wavelength            : 0.302
          Center Filter Wavelength      : 0.311
          Maximum Wavelength            : 0.320
          Maximum and minimum wavelengths refer to points
          with 500f peak transmission.  Both have
          tolerances of 0.002 microns.
 
        Filter 11
        ---------
          Filter Name                   : C11
          Filter Type                   : NARROW-BAND FOR C3 RADICAL
          Minimum Wavelength            : 0.398
          Center Filter Wavelength      : 0.407
          Maximum Wavelength            : 0.416
          Maximum and minimum wavelengths refer to points
          with 500f peak transmission.  Both have
          tolerances of 0.002 microns.
 
        Filter 12
        ---------
          Filter Name                   : C12
          Filter Type                   : NARROW BAND FOR C2 RADICAL
          Minimum Wavelength            : 0.500
          Center Filter Wavelength      : 0.510
          Maximum Wavelength            : 0.520
          Maximum and minimum wavelengths refer to points
          with 500f peak transmission and they have
          tolerances of 0.002 microns.
 
      Optics
      ======
        The basic telescope is a modified Ritchey-Chretien with a
        correcting field lens at the focal plane. The primary has a
        clear aperture of 166 mm.  The primary and secondary are
        separated by 246 mm.  The unvignetted field of view has a
        diameter of 1.4 located near the entrance pupil of the
        telescope.
        Telescope ID                  : HMC
        Telescope Focal Length        : 0.998
        Telescope Diameter            : 0.160
        Telescope F Number            : 6.24
        Telescope Resolution          : 0.000044
        Telescope T Number            : 7.7
 
        Instrument Mounting Description
        ===============================
        The HMC is mounted inside the body of the Giotto spacecraft,
        looking out the side, perpendicular to the axis of spin of the
        spacecraft.  The 45-degree diagonal mirror at the entrance pupil
        of the telescope extends beyond the body of the spacecraft to
        enable viewing in all directions.
 
      Instrument Section/Operating Mode Descriptions
      ==============================================
        Data Rate          : 20058 bit/sec
        Sample Bits : 8
        FOV Shape : RECTANGULAR
        Instrument Parameter Name : PIXEL
        Sampling Parameter Name : PIXEL
 
        ACQ Mode
        --------
          ACQ, or Acquisition Mode, was used prior to encounter to
          search a 4.4- by 4.6-degree field centered on the spacecraft's
          axis of spin.  The searching is accomplished by a combination
          of the spin and tilting the 45-degree, periscopic mirror.  The
          reticon was used in a coincidence mode to locate the brightest
          object in the field of view.  After a sufficient number of
          detections, the instrument's DPU calculated the position of
          the comet relative to the spacecraft and predicted the
          pointing of the camera for the transmitted to Earth.
          Data Path Type: INTERNAL TO INSTRUMENT ONLY
 
        SDM Mode
        --------
          Single Detector Mode, or Coma Mode, was used for most
          observations far from the time of closest approach when the
          annular field of view swept out by the detectors had such a
          small radius of curvature that the motion of the field could
          be orthogonal to only one of the linear detectors. Detector C
          was used to locate the center of brightness which was then fed
          back, once every second spin of the spacecraft, to the
          controlling electronics.  These then adjusted the periscopic
          mirror to make the motion orthogonal to detector C and
          adjusted the clocking rate of the detector to match the motion
          of the field of view.  A sub-mode of this mode, known as
          'Photometer Mode', involved stopping the clocking of the CCD
          so that it integrated across the entire coma.
 
        MDM Mode
        --------
          Multi Detector Mode, or Nucleus Mode, was used for imaging
          near the time of closest approach (when the radius of the
          annular field swept out was greater than 1.6 degrees),
          starting roughly 5 minutes before closest approach.  In this
          mode, the spacecraft and all four detectors were used.
          Data Path Type:
                   REAL-TIME TELEMETRY OF SUBSET OF PIXELS
 
        OBS Mode
        --------
          Observatory Mode was intended for observations of stars during
          cruise phase, primarily for calibration of the camera.  The
          camera did not track in this mode and fast sequences of
          filters were used.

        
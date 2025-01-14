
 
 
    Scientific Objectives
    =====================
      Krehbiel, J.P., L.H.  Brace, R.F.  Theis, J.R.  Cutler, W.H.
      Pinkus, and R.B.  Kaplan, 'Pioneer Venus Orbiter Electron
      Temperature Probe', IEEE Transactions on Geoscience and Remote
      Sensing, January 1980. [KREHBIELETAL1980].
 
      ABSTRACT - The Orbiter Electron Temperature Probe (OETP)
      instrumentation and measurement technique has been designed to
      perform in-situ measurements of electron temperature and
      electron and ion density in the ionosphere of Venus.  Adaptive
      sweep voltage circuitry continuously tracks the changing
      electron temperature and spacecraft potential while
      auto-ranging electrometers adjust their gain in response to the
      changing plasma density.  Control signals used in the
      instrument to achieve this automatic tracking provide a
      continuous monitor of the ionospheric parameters without
      telemetering each volt-ampere curve.  Internal data storage
      permits high data rate sampling of selected raw characteristic
      curves for low rate transmission to Earth.  These curves are
      used to verify or correct the inflight processed data.  Sample
      in orbit measurements are presented to demonstrate instrument
      performance.
 
      I.  INTRODUCTION
 
      THE PIONEER VENUS Orbiter Electron Temperature Probe (OETP) is
      one of several instruments used on the orbiter to perform
      in-situ measurements of the ionospheric plasma of Venus.  The
      instrument employs cylindrical Langmuir probes to measure the
      electron temperature, Te, the electron and ion densities, Ne
      and Ni, and the spacecraft potential, Vs.  To provide high
      spatial resolution of these parameters the instrument takes
      several hundred volt-ampere curves during each brief passage
      through the ionosphere.  Owing to the limited telemetry rate
      available to each instrument, circuitry was included for
      inflight processing of the volt- ampere curves.  Onboard
      storage of raw data from selected curves was provided to permit
      ground confirmation of the inflight processing method.  Prior
      to launch, the instrument design was outlined briefly by Brace
      in a paper edited by Colin and Hunten (1977) [BRACE1977].  The
      purpose of this paper is to present a a more detailed account
      of the instrument and some of the data acquired at Venus to
      illustrate how the instrument performs and how the ground data
      analysis is used to verify the flight measurements.  Early
      results from this experiment have been reported.
      [BRACEETAL1979A] [BRACEETAL1979B] [BRACEETAL1979C]
 
      II.  THEORY OF THE METHOD
 
      The OETP is the latest spaceflight version of cylindrical
      electrostatic probe of Langmuir probe instrumentation. I.
      Langmuir and H.  Mott-Smith, Jr., first reported use of the
      electrostatic probe in a laboratory plasma in 1924
      [LANGMUIRETAL1924].  The cylindrical probe technique has been
      used extensively to characterize the Earth's ionosphere
      [BRACE1970], most recently on board the Atmosphere Explorer
      (AE) satellites [BRACEETAL1973].  The three AE instruments with
      their adaptive control circuitry and auto ranging electrometer
      provided the basis for the OETP instrument.
 
      Langmuir probe theory and application has been widely reported
      in the literature [BRACE1977] [BRACEETAL1979A] [BRACEETAL1979B]
      [BRACEETAL1979C] [LANGMUIRETAL1924] [BRACE1970] [BRACEETAL1973]
      [HOEGYETAL1973].  Here it will suffice to provide a brief
      description of the technique and to remind the reader of the
      theoretical volt-ampere curve produced by a Langmuir probe in a
      plasma as shown in Fig.  1 [KREHBIELETAL1980].  The curve
      begins in the ion saturation region with the probe potential
      sufficiently negative to prohibit plasma electrons from
      reaching the probe.  At this point, current to the probe is due
      only to ions.  In the retardation region where the probe
      potential is less negative, the more energetic electrons
      overcome the retarding potential, and produce an exponentially
      increasing current.  The electron temperature Te determines the
      power of the exponential with lower Te yielding a narrower
      retarding region.  In the electron saturation region, the probe
      is positive with respect to the plasma and therefore attracts
      additional electrons from the plasma.  Equations appropriate to
      the three regions of the curve are given below.
 
      In the ion saturation region at 90 degree angle of attack
      [HOEGYETAL1973]
 
      Ii = ANiew/pi(1 + kTi/miw2 + 2eV/miw2)1/2 (1)
 
 
      In the electron retardation region [BRACEETAL1979A]
 
 
      Ie = ANee(kTe/2pime)1/2 exp(eV/kTe0.  (2)
 
 
      In the electron saturation region [MOTTSMITHETAL1926]
      [SPENCERETAL1965]
 
 
      Ie = (ANee/pi)(2eV/me)1/2 (3) where
 
      Ne electron density Ni ion density Te electron temperature Ti
      ion temperature A collector surface area w collector speed with
      respect to plasma k Boltzmann constant mi mean ion mass me
      electron mass V collector voltage with respect to the plasma e
      electron charge.
 
      OETP measurements are made with respect to spacecraft ground.
      This causes the voltage applied to the probe VA to be
      translated by the spacecraft potential Vs, as illustrated in
      Fig.  1 [KREHBIELETAL1980].  Special steps must be taken to
      account for this and to assure a stable spacecraft potential.
      This will be described later.
 
    Instrument Overview
    ===================
      III.  THE EXPERIMENTAL ARRANGEMENT
 
      The OETP instrumentation system consists of two cylindrical
      sensors and a central electronics unit. Fig.  2
      [KREHBIELETAL1980] illustrates the relative position of the
      sensors and the larger appendages of the spacecraft.  The
      radial sensor is mounted at the end of a 1-m boom which was
      folded against the solar array and deployed after Venus orbit
      insertion so as to be perpendicular to the spacecraft spin
      axis.  The axial sensor is mounted on a fixed boom which places
      it 0.4 m away from the spacecraft forward surface.  Because the
      axis of the axial sensor is parallel to the spin axis it
      maintains a relatively constant angle of attack to the incident
      plasma and is therefore not subject to spin modulation.
 
      To provide an adequate path for return current to the plasma,
      the spacecraft provides 1.73 m2 of exposed conducting area
      which is spacecraft ground.  This area consists of a metal band
      around the solar array, a metal mesh over the outer kapton
      surface of the forward thermal blanket, and the outer surface
      of the magnetometer boom.  Silicone rubber was applied to all
      solar cell edges and exposed electrical conductors making up
      the solar array to insulate these positive potential areas from
      the plasma and thus minimize the electron current they would
      otherwise collect producing a concomitant change in spacecraft
      potential.
 
      A.  The Central Electronics
 
      The OETP central electronics unit contains independent
      electrometer amplifiers and adaptive sweep voltage circuitry to
      service each probe. Fig.  3 [KREHBIELETAL1980] is a simplified
      functional block diagram of the system.  Each amplifier feeds
      its output into the common A/D converter and data handling
      circuitry.  The autoranging electrometer and adaptive sweep
      voltage circuits are identical to that employed in the three AE
      missions [BRACEETAL1973].  The signal multiplexing (Mux), A/D
      conversion, data formatting, and First-In/First-Out memory
      (FIFO) are new features to permit the inflight processing and
      recovery of data, a capability required by the lower data rate
      available from the orbiter.  The radial probe electrometer has
      a sensitivity range of 1 x 10 to the neg.  10 power to 1 x 10
      to the neg.  6 power A/V, while the axial probe electrometer
      has a sensitivity range of 1 x 10 to the neg.  nine power to 1
      x 10 to the neg.  5 power A/V.  Electrometer sensitivity is
      automatically adjusted to one of 1024 possible values.
      Electrical power is provided by a common dc/dc converter having
      separate floating outputs for each of the two electrometers.
 
      Adaptive circuitry is provided to adjust the sweep voltage to
      resolve that region of the volt-ampere curve needed to derive
      Ni, Ne, Te, and Vs and to track changes in Te and Vs
      encountered along the orbit.  The adaptive process provides a
      more continuous monitor of these plasma parameters than could
      be obtained if we were to rely solely on ground-based analysis
      of volt-ampere curves produced by the instrument, given the
      available data rate.  The VA generator converges on the proper
      starting value VA Start, and the proper rate of change VA Slope
      through an iterative process involving the auto-ranging
      electrometer and the adaptive VA circuitry.  When the adaptive
      process is completed, usually within two sweeps, the curves are
      properly framed to maximize the resolution of the measured
      parameters.  Once proper framing had been achieved, it is
      maintained by slight adjustments in VA Start, VA Slope, and
      electrometer gain which track the changes in electron
      temperature, density, and spacecraft potential.
 
      An idealized 1/2-s instrument measurement cycle of applied
      voltage, and the resulting electrometer output for a properly
      framed curve are shown in Fig.  4 [KREHBIELETAL1980].  Also
      shown are the parameters used to carry out the adaptive process
      and to achieve the inflight analysis.  The cycle begins at time
      T0 by setting VA equal to VA Start as determined from
      parameters measured during the previous curve.  After a
      settling time the electrometer auto-ranging algorithm is
      initiated to adjust the electrometer gain as needed to drive
      its output to the -3.30-Vthreshold.  Current to the sensor at
      this time is entirely ion current and is used to determine Ni.
      At time T1 the VA is increased linearly at a rate also
      determined from the previous curve.  The VA and electrometer
      outputs are monitored by level detectors.  When the
      electrometer output reaches +1.41 V a level detector starts a
      counter and the value of VA at T2 is measured.  When the
      electrometer output reaches +9.50 V, a second level detector
      stops the counter and the value of VA at T3 is measured.  At T3
      the electrometer downranges by one decade and displays the rest
      of the volt-ampere curve until the linear sweep is stopped at
      T4.  At T4 a fixed 2-V step is added to drive the sensor into
      the electron saturation region.  The electrometer then
      downranges until its output is on scale and a reading of output
      voltage and gain are taken and used to determine Ne.
 
      In each 1/2-s instrument cycle we are thus able to determine,
      from each electrometer, Ni from the gain and electrometer
      output just prior to T1, Te from the change in VA which
      produced a factor of e change in electrometer output, and Ne
      from the gain and electrometer output during the Ne sample
      time.  The curve framing process continues by automatically
      computing new values of VA Slope and VA Start.  VA Slope is
      computed from our definition of a properly framed curve which
      requires that the full amplitude of VA be ten times the value
      of the change in VA from T2 to T3 when the 1.41- and 9.50-V
      thresholds are reached.  VA Start is computed using (4) which
      places the exponential electron retardation region such that
      the 9.50-V threshold is reached at 86 percent of the sweep
      interval.
 
      VA Start = 8.6 VA at T2 - 7.6 VA at T3.  (4)
 
      If the VA at T1 does not provide a net ion current to the
      collector or if the electrometer fails to reach the +9.50-V
      output, called the T3 threshold, the VA generator will preset
      to the 'fault' condition for the next sweep causing VA to start
      at -7 V and sweep up to +5V.  The fault sweep amplitude is
      sufficient to locate the operating region of the volt-ampere
      curve and to permit the convergence algorithm to repeat at the
      beginning of the following sweep.
 
      As a safeguard against unforeseen difficulties which might
      cause our adaptive approach to fail, a fixed amplitude sweep
      mode can be selected by ground command in which a sequence of
      high and low voltage sweeps are applied to either or both
      sensors.  The high VA was -7 to +5 V and the low VA was -2 to
      +1 V.  In this mode a bias voltage of +/- 1 V can be added to
      account for Vs uncertainties.  The fixed sweep mode is not
      normally used because the adaptive mode yields better resolved
      stored curves.
 
      B.  The Sensors and Booms
 
      A sensor with its guard electrode and a portion of the boom are
      schematically shown in Fig.  5 [KREHBIELETAL1980].  The guard
      electrode, driven at VA, is the exposed inner shield of a rigid
      triaxial boom fabricated with titanium and teflon.  The outer
      triaxial shield is held at spacecraft ground potential.  A
      special white conductive paint, GSFC Code No.  NS43C
      [SHAI1978], was applied to the outer surface of the booms to
      provide thermal control.  Flight sensors were screwed onto the
      boom center conductor and held in place with a high temperature
      silicone (Dow Corning X 12561, silver filled for electrical
      conductivity) to assure that the sensors remained in place
      during the launch vibration.
 
      The accuracy of the temperature measurements is affected by the
      characteristics of the sensor surface [SMITH1972].  In
      particular, the work function of different crystal surfaces can
      vary by as much as several tenths of a volt and thus introduce
      an uncertainty in the value of V in (1) - (3).  To reduce this
      error the collectors were fabricated using a chemical vapor
      deposition (CVD) process.  Studies of the CVD Rhenium show that
      Rhenium deposited by the pyrolyctic decomposition of Rhenium
      pentachloride (ReCl5) show a very high degree of crystal
      orientation.  Rhenium deposited in this manner exhibits a
      (0001) preferred orientation [YANG1972] perpendicular to the
      plane of growth.  Cylindrical tubes of this type have yielded
      uniform vacuum work functions of 5.1 eV.  Molybdenum deposited
      from MoCl6 also shows a very high degree of crystal
      orientation.  Thus both materials become candidates for sensor
      materials.
 
      Fig.  6 [KREHBIELETAL1980] shows part of a cross section of a
      collector having a CVD Rhenium surface deposited on a
      polycrystalline substrate.  Flight collectors were selected on
      the basis of examining similar cross sections cut from one end
      of the collector and from volt-ampere curves taken in
      laboratory plasmas.  The radial collector surface is Rhemium
      and the axial is Molybdenum.
 
      C.  Measurements Format
 
      The orbiter is able to operate in several data formats and at
      spacecraft data rates from 16 to 2048 b/s.  The OETP is
      designed for optimum operation when its output data rates are
      80, 128, or 160 b/s, one of which is normally used during a
      periapsis pass.  Various instrument data formats can be
      selected by command to provide for more or less dense coverage
      depending on such factors as spacecraft bit rate and whether
      the OETP data system is dedicated to one sensor or shared by
      both of them.
 
      IV.  Verification of Inflight Analysis
 
      To permit ground calibration of the values of Ni, Ne, and Te
      determined by the inflight processing, the instrument
      periodically samples volt-ampere curves from either or both
      electrometers.  The electrometer output is measured at 50
      equally spaced points between T1 and T4.  The FIFO memory is
      used to store the fifty measurements , made at 1132 b/s, for
      later readout at the lower spacecraft telemetry rate. Fig.  7
      [KREHBIELETAL1980] illustrates the ground analysis of such a
      stored curve taken from orbit 112.  The solid line represents a
      least squares fit of a straight line (ion current) and
      exponential (electron current) to the actual data points within
      the electron retardation region.
 
      V.  Illustration of Operation at Venus
 
      Fig.  8 [KREHBIELETAL1980] is a computer plot of the values of
      Te and Ne taken from a single pass of the orbiter through the
      nightside ionosphere.  The line segments connect the inflight
      values and reveal the small-scale spatial structure which is
      often present.  The asterisks represent the values of Te and Ne
      derived later by computer fitting stored volt-ampere curves of
      the type illustrated in Fig.  7 [KREHBIELETAL1980].  Values
      derived from the stored curves are used to normalize the
      inflight processed data.  Thus through the use of on-board
      processing of curves, high spatial resolution is achieved
      without sacrificing the accuracy provided by ground computer
      fitting of raw volt-ampere curves.  As of this writing more
      than 250 passes through the ionosphere of Venus have been
      completed and the instrument continues to operate well.
 
      ACKNOWLEDGEMENT
 
      The authors gratefully acknowledge the aid of L.R.O.  Storey in
      the testing of candidate collectors in the low temperature
      plasma chamber at the Centre de Recherches en Physique de
      L'Environment Terrestre en Planetaire in Orleans, France.
 
      REFERENCES
 
      L.H.  Brace, 'Orbiter electron temperature Probe', L.  Colin
      and D.M.  Hunten, Eds.  Space Sci.  Rev., vol.  20, no.  4,
      p.454, June 1977.  [BRACE1977]
 
      L.H.  Brace, R.F.  Theis, J.P.  Krehbiel, A.F.  Nagy, T.M.
      Donahue, M.E.  McElroy, and A.  Pedersen, 'Electron
      temperatures and densities in the Venus ionosphere', Science,
      vol.  203, p.  763, Feb.  23, 1979.  [BRACEETAL1979A]
 
      L.H.  Brace, H.A.  Taylor Jr., P.A.  Cloutier, R.E.  Daniell
      Jr., and A.F.  Nagy, 'On the configuration of the nightside
      Venus ionopause', Geophys. Res.  Lett., vol.  6, p.  345, 1979.
      [BRACEETAL1979B]
 
      L.H.  Brace, R.F.  Theis, H.B.  Niemann, H.G.  Mccayr, W.R.
      Hoegy, and A.F.  Nagy, 'Empirical models of the electron
      temperature and density in the nightside Venus ionosphere',
      Science, vol.  205, p.  102, 1979.  [BRACEETAL1979C]
 
      I.  Langmuir, and H.  Mott-Smith, Jr., 'Studies of the electric
      discharges in gases at low pressures', Gen. Elec.  Rev., p.
      616, Sept. 1924.  [LANGMUIRETAL1924]
 
      L.H.  Brace, 'Global structure of ionosphere temperature', in
      Space Research X.  Amsterdam, The Netherlands: North-Holland,
      p.  633, 1970.  [BRACE1970]
 
      L.H.  Brace, R.F.  Theis, and A.  Dalgarno, 'The cylindrical
      electrostatic probes for atmosphere explorer -C, -D, -E',
      Science, vol.  8, no.  4, p.  341, Apr. 1973.  [BRACEETAL1973]
 
      W.R.  Hoegy and L.E.  Wharton, 'Current to moving spherical and
      cylindrical electrostatic probes', J. Appl.  Phys., vol.  44,
      no.  12, p.  5365-5371, 1973.  [HOEGYETAL1973]
 
      H.  Mott-Smith and I.  Langmuir, 'The theory of collectors in
      gaseous discharges', Phys.  Rev., vol.  28, pp.  727-763, 1926.
      [MOTTSMITHETAL1926]
 
      N.W.  Spencer, L.H.  Brace, G.R.  Carignan, D.R.  Taeusch, and
      H.B.  Niemann, 'Electron and molecular nitrogen temperature and
      density in the thermosphere', J. Geophys.  Res., vol.  70, pp.
      2665-2698, 1965.  [SPENCERETAL1965]
 
      M.C.  Shai, 'Formulation of electrically conductive thermal-
      control coatings ', NASA Tech.  Paper 1218, Apr. 1978.
      [SHAI1978]
 
      D.  Smith, 'The application of Langmuir probes to the
      measurement of very low electron temperatures', Planet.  Space
      Sci., vol.  20, p.  1721, 1972.  [SMITH1972]
 
      L.  Yang, 'Preparation & evaluation of CVD rhenium thermionic
      emitters', in The Third Annual Conference on Chemical Vapor
      Deposition, F.A.  Glaski, Ed., American Nuclear Society, 1972.
      [YANG1972]
 
 
    Calibration
    ===========
      To permit ground calibration of the values of Ni, Ne, and Te
      determined by the inflight processing, the instrument
      periodically samples volt-ampere curves from either or both
      electrometers.  The electrometer output is measured at 50
      equally spaced points between T1 and T4.  The FIFO memory is
      used to store the fifty measurements , made at 1132 b/s, for
      later readout at the lower spacecraft telemetry rate. Fig.  7
      [KREHBIELETAL1980] illustrates the ground analysis of such a
      stored curve taken from orbit 112.  The solid line represents a
      least squares fit of a straight line (ion current) and
      exponential (electron current) to the actual data points within
      the electron retardation region.
 
      The Sensors and Booms
 
      A sensor with its guard electrode and a portion of the boom are
      schematically shown in Fig. 5.  [KREHBIELETAL1980] The guard
      electrode, driven at VA, is the exposed inner shield of a rigid
      triaxial boom fabricated with titanium and teflon.  The outer
      triaxial shield is held at spacecraft ground potential.  A
      special white conductive paint, GSFC Code No.  NS43C
      [SHAI1978], was applied to the outer surface of the booms to
      provide thermal control.  Flight sensors were screwed onto the
      boom center conductor and held in place with a high temperature
      silicone (Dow Corning X 12561, silver filled for electrical
      conductivity) to assure that the sensors remained in place
      during the launch vibration.
 
      The accuracy of the temperature measurements is affected by the
      characteristics of the sensor surface [SMITH1972].  In
      particular, the work function of different crystal surfaces can
      vary by as much as several tenths of a volt and thus introduce
      an uncertainty in the value of V in (1) - (3).  To reduce this
      error the collectors were fabricated using a chemical vapor
      deposition (CVD) process.  Studies of the CVD Rhenium show that
      Rhenium deposited by the pyrolytic decomposition of Rhenium
      pentachloride (ReCl5) show a very high degree of crystal
      orientation.  Rhenium deposited in this manner exhibits a
      (0001) preferred orientation [YANG1972] perpendicular to the
      plane of growth.  Cylindrical tubes of this type have yielded
      uniform vacuum work functions of 5.1 eV.  Molybdenum deposited
      from MoCl6 also shows a very high degree of crystal
      orientation.  Thus both materials become candidates for sensor
      materials.
 
      Fig.  6 [KREHBIELETAL1980] shows part of a cross section of a
      collector having a CVD Rhenium surface deposited on a
      polycrystalline subtrate.  Flight collectors were selected on
      the basis of examining similar cross sections cut from one end
      of the collector and from volt-ampere curves taken in
      laboratory plasmas.  The radial collector surface is Rhemium
      and the axial is Molybdenum.
 
 
    Instrument Electronics
    ======================
      A.  The Central Electronics
 
      The OETP central electronics unit contains independent
      electrometer amplifiers and adaptive sweep voltage circuitry to
      service each probe. Fig.  3 [KREHBIELETAL1980] is a simplified
      functional block diagram of the system.  Each amplifier feeds
      its output into the common A/D converter and data handling
      circuitry.  The autoranging electrometer and adaptive sweep
      voltage circuits are identical to that employed in the three AE
      missions [BRACEETAL1973].  The signal multiplexing (Mux), A/D
      conversion, data formatting, and First-In/First-Out memory
      (FIFO) are new features to permit the inflight processing and
      recovery of data, a capability required by the lower data rate
      available from the orbiter.  The radial probe electrometer has
      a sensitivity range of 1 x 10 to the neg.  10 power to 1 x 10
      to the neg.  6 power A/V, while the axial probe electrometer
      has a sensitivity range of 1 x 10 to the neg.  nine power to 1
      x 10 to the neg.  5 power A/V.  Electrometer sensitivity is
      automatically adjusted to one of 1024 possible values.
      Electrical power is provided by a common dc/dc converter having
      separate floating outputs for each of the two electrometers.
 
      Adaptive circuitry is provided to adjust the sweep voltage to
      resolve that region of the volt-ampere curve needed to derive
      Ni, Ne, Te, and Vs and to track changes in Te and Vs
      encountered along the orbit.  The adaptive process provides a
      more continuous monitor of these plasma parameters than could
      be obtained if we were to rely solely on ground-based analysis
      of volt-ampere curves produced by the instrument, given the
      available data rate.  The VA generator converges on the proper
      starting value VA Start, and the proper rate of change VA Slope
      through an iterative process involving the auto-ranging
      electrometer and the adaptive VA circuitry.  When the adaptive
      process is completed, usually within two sweeps, the curves are
      properly framed to maximize the resolution of the measured
      parameters.  Once proper framing had been achieved, it is
      maintained by slight adjustments in VA Start, VA Slope, and
      electrometer gain which track the changes in electron
      temperature, density, and spacecraft potential.
 
      An idealized 1/2-s instrument measurement cycle of applied
      voltage, and the resulting electrometer output for a properly
      framed curve are shown in Fig.  4 [KREHBIELETAL1980].  Also
      shown are the parameters used to carry out the adaptive process
      and to achieve the inflight analysis.  The cycle begins at time
      T0 by setting VA equal to VA Start as determined from
      parameters measured during the previous curve.  After a
      settling time the electrometer auto-ranging algorithm is
      initiated to adjust the electrometer gain as needed to drive
      its output to the -3.30-V threshold.  Current to the sensor at
      this time is entirely ion current and is used to determine Ni.
      At time T1 the VA is increased linearly at a rate also
      determined from the previous curve.  The VA and electrometer
      outputs are monitored by level detectors.  When the
      electrometer output reaches +1.41 V a level detector starts a
      counter and the value of VA at T2 is measured.  When the
      electrometer output reaches +9.50 V, a second level detector
      stops the counter and the value of VA at T3 is measured.  At T3
      the electrometer downranges by one decade and displays the rest
      of the volt-ampere curve until the linear sweep is stopped at
      T4.  At T4 a fixed 2-V step is added to drive the sensor into
      the electron saturation region.  The electrometer then
      downranges until its output is on scale and a reading of output
      voltage and gain are taken and used to determine Ne.
 
      In each 1/2-s instrument cycle we are thus able to determine,
      from each electrometer, Ni from the gain and electrometer
      output just prior to T1, Te from the change in VA which
      produced a factor of e change in electrometer output, and Ne
      from the gain and electrometer output during the Ne sample
      time.  The curve framing process continues by automatically
      computing new values of VA Slope and VA Start.  VA Slope is
      computed from our definition of a properly framed curve which
      requires that the full amplitude of VA be ten times the value
      of the change in VA from T2 to T3 when the 1.41- and 9.50-V
      thresholds are reached.  VA Start is computed using (4) which
      places the exponential electron retardation region such that
      the 9.50-V threshold is reached at 86 percent of the sweep
      interval.
 
      VA Start = 8.6 VA at T2 - 7.6 VA at T3.  (4)
 
      If the VA at T1 does not provide a net ion current to the
      collector or if the electrometer fails to reach the +9.50-V
      output, called the T3 threshold, the VA generator will preset
      to the 'fault' condition for the next sweep causing VA to start
      at -7 V and sweep up to +5V.  The fault sweep amplitude is
      sufficient to locate the operating region of the volt-ampere
      curve and to permit the convergence algorithm to repeat at the
      beginning of the following sweep.
 
      As a safeguard against unforeseen difficulties which might
      cause our adaptive approach to fail, a fixed amplitude sweep
      mode can be selected by ground command in which a sequence of
      high and low voltage sweeps are applied to either or both
      sensors.  The high VA was -7 to +5 V and the low VA was -2 to
      +1 V.  In this mode a bias voltage of +/- 1 V can be added to
      account for Vs uncertainties.  The fixed sweep mode is not
      normally used because the adaptive mode yields better resolved
      stored curves.
 
 
    Detectors
    =========
      The OETP instrumentation system consists of two cylindrical
      sensors and a central electronics unit. Fig.  2
      [KREHBIELETAL1980] illustrates the relative position of the
      sensors and the larger appendages of the spacecraft.  The
      radial sensor is mounted at the end of a 1-m boom which was
      folded against the solar array and deployed after Venus orbit
      insertion so as to be perpendicular to the spacecraft spin
      axis.  The axial sensor is mounted on a fixed boom which places
      it 0.4 m away from the spacecraft forward surface.  Because the
      axis of the axial sensor is parallel to the spin axis it
      maintains a relatively constant angle of attack to the incident
      plasma and is therefore not subject to spin modulation.
 

        
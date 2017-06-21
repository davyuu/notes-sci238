# Gravity

- Chandra/X-ray
- Hubble/visible
- Spitzer/IR

Space around eletric charges is filled with a electric field; its strength and direction are indicated by electric field lines

Space around electric currents is filled with a magnetic field; its strength and direction are indicated by magnetic field lines

A changing magnetic field creates and electric field and vice verse, generating an electromagnetic wave
- At any point in space, the amplitudes of the electric & magnetic fields oscillate with frequency ƒ
- At any instant of time, the field amplitudes form a sinusoidal wave parttern (along a line through the source) of wavelength ƛ
- The sinusoidal wave pattern moves forward a distance ƛ in a time T = 1/f (the period of the wave)
- The speed of the wave:

	c = distance / time = ƛ / (1/f) = ƛf = 3.0 * 10^8 m/s

	higher frequency -> shorter wavelength
	lower frequency -> longer wavelength

#### Electromagnetic Spectrum
- The range of ƛ and f of electromagnetic waves is infinite:
	- from gamma rays (very short wavelength & very high frequency) to radio waves (very long wavelength & very low frequency)
	- the human eye can see only a very narrow band of electromagnetic waves called visible light

The quantum nature of our universe demands taht electromagnetic waves (electromagnetic radiation) is really a shower of quantum particles called phtons, which have both wave-like and particle-like properties
- Electromagnetic radio of wavelength ƛ and frequency f is composed of photons with (h = Plancks constant)
	- Energy E = hf = hc/ƛ
	- Momentum p = E/c = h/ƛ

- Photons have wavelength, frequency and energy
- 1 eV = 1.602 x 10^-19 joules
	- the kinetic energy an electron acquires in accelerating through a 1 V potential difference

	Range of ƛ and E allows us to probe the same range of physical scales: size ~ƛ and energy ~E

- Electric & magnetic fields exert forces on charged particles causing them to accelerate
	- Electric fields can change the speed of motion and the energy of charged particles (eg particle accelerator)
	- Magnetic fields change the direction of motion but not the speed or energy of charged particles
	- Electric and magnetic fields are often present together
- Conversly, the source of all electromagnetic radiation is accelerated elctric charge

#### Thermal Radiation
Matter is made of atoms in random thermal motion. The kinetic energy stored in this motion is called thermal energy.

THe hotter the matter, the more thermal energy is stored.

Temperature T ∝ the average thermal energy per atom.

Atoms, in tern are made of charged particles.
When atoms collide the charged particles jiggle around (accelerate) emitting a type of random electromagnetic radiation caleld thermal radiation

An object's thermal radiation spectrum depends on only one property: its temperature

The hotter the object is brightest at a shoter wavelength (or higher frequency, or higher energy):

	ƛ_max(nm) = 2,900,000 / T(K)  -> (Wien's Law)

The hotter object emits more thermal power (energy per second per square meter, added up over all wavelengths):

	F(W/m^2) = σT^4   -> (Stefan - Boltzmann Law)
		σ = 5.67 * 10^-8 W/m^2K^4

Example 1
- Consider four sources with temp:
	- 50,000K, 5,000K, 500K, 50K
- What is wavelength at which each is brightest?

	ƛ_max(nm) = 2,900,000 / T(K)

- From Wien's Law, ƛ_max = 58 nm (UV), 580 nm (visible), 5800 nm = 5.8 µm (IR), 0.058 mm (mm)
- Different types of objects in space are brightest at different wavelengths. Telescopes and detectors are designed to operate in diff wavelength ranges
- Viewing same object in diff wavelength ranges reveals new info

Example 2
- Two stars have same temp, but one is observed to emit energy at 10,000 times the rate of the other. How can we explain diff?

	F(W/m^2) = σT^4

- F = energy/second/area = σT^4, so diff must be total surface area (A = 4piR^2) of the two stars.
- Energy/second = area * σT^4

	10,000 = (area(A) * σT^4) / (area(B) * σT^4) = 4piR(A)^2 / 4piR(B)^2
	R(A) / R(B) = sqrt(10,000) = 100

=> the more luminous star has a radius of 100 times larger

Example 3
- Two stars have same temp & size, one appears 10,000 times bright than other?

- Apparent brightness depends on absolute brightness and distance. Absolute brightness is called luminosity (W).

	Apparent brightness  = Luminosift / 4pid^2
	Apparent brightness decreases as distance ^2

- Since two stars have same temp (surface brightness) and size (surface area), they have same luminosity. Diff must be distance.

=> one star is 100 times more distant than other

### Phase Changes in Matter
- Ionization: stripping of electrons, changing atoms into plasma
- Dissociation: breaking molecules into atoms
- Sublimation: breaking of rigid chemical bonds, changing solid into gas
- Evaporation: breaking of flexible chamical bonds, changing liquid into solid
- Melting: breaking of rigit chemical bonds, changing solid into liquid

Quantum: Electrons in atoms are restricted to certain discrete states, with correspondig discrete energies (E = KE + PE).

The only allowed changes in the energy of the atom are those corresponding to a transition between discrete energy level via emission or absorption of photons

Each type of atom has a eunique set of allowed energy level transitions - spectral fingerprint
Each transition corresponds to a unique photon energy, freq and wavelength

	E = hf = hc/ƛ = h|f_f - f_i| = hc|1/ƛ_f - 1/ƛ_i|

Molecules have additional energy levels because they can vibrate and rotate. These are also quantized

#### Molecular Radiation
- Large numbers of vibrational and rotational energy levels can make the spectra of molecules very complicated.
- Many of these molecular transitions are in the infrared part of the spectrum

Any hot object emits thermal radiation with a continuous spectum

Line or low-density cloud of gas emits electromagnetic radiation only at specific wavelengths that depend on its composition, producing a spectrum with bright emission lines.

**Thermal broadening** (due to Doppler effect) of the lines also allows a measure of temp of the gas

A cloud of gas between us and a source of thermal radiation can absorb light of specific wavelengths, reradiate it in a random direction, leaving dark absorption lines in the spectrum

A precision spectrum contains a great deal of info on the temp and composition of an object

#### Synchrotron Radiation
- Charged particles spiral around magnetic field lines
- The accelerated electrons emit synchrotron radiation
	- a continuous spectrum distinct from thermal radiation

##### Measuring speed of objects using light
- When source and detector are in relative motion, the wavelength detected differs from the wavelength emitted
- This effect can be used to measure the radial velocity of objects in the Universe, toward or away from us

The *Doppler shift* can be very accurately measured by observing shifts in the wavelengths of spectral lines

#### Example: Measuring Earth's Motion

	v << c => v_radial / c ~ Δƛ / ƛ_rest, where Δƛ = ƛ_obs - ƛ_rest
		Δƛ > 0 => redshift (receding)
		Δƛ < 0 => blueshift (approaching)

	Given:
		ƛ_rest - 486.13nm
		ƛ_obs_1 = 486.27nm
		ƛ_obs_2 = 486.17nm

	Find:
		v_E

	(v_s + v_E) / c = (ƛ_obs_1 - ƛ_rest) / ƛ_rest
	(v_s - v_E) / c = (ƛ_obs_2 - ƛ_rest) / ƛ_rest
	2v_E / c / c = (ƛ_obs_1 - ƛ_obs_2) / ƛ_rest
	v_E ~ 30km/s

##### Measuring rotation of objects using light
- Spectral lines are wider when an object rotates faster
- Use this Doppler broadening to determine rotation speeds of planets, stars and galaxies

### Telescopes
**Bigger is better**

- the larger the aperture, the more photons/second are captured:
	- Reduces light-collecting time
	- Can see more structure in objects
	- Allows detection of fainter objects

	Light-collecting area = (1/4)pi*D^2  (D = diameter)

- The Hubble Deep Field
- Exposure time ~ 35 hours at each of several wavelengths

#### Angular Resolution
- the large the aperture, the greater the resolving pwoer (ability to separate objects that are close to each other, or to ditinguiush fine detail)
	- Fundamental limitation of all optics due to diffraction of light (spreading after apssing through an aperature)
	- nearby objects can overlap because of speading
	- ϑ_min = 1.22 ƛ / D

#### Refracting Telescope
- Focuses light with lenses
- Disadvantages:
	- Chromatic aberration: nede long, heavy telescopes
	- Requires precise machining of two surfaces
	- Absorption; cannot have internal imperfections; can only be supoorted around the edge

#### Reflecting Telescope
- Focuses light with mirrors
- Advantages:
	- No chromatic aberration
	- Requires only one precisly machined surface
	- Mirror can be supported on entire back-side

#### Telescopes Today
- Visible Light: Reflectors ~10m aperature
- Location: Calm, high, dark, dry

Virtually all observation are done with instruments

### What astronomers do with telescopes:
- Imaging: taknig pictures of the sky
- Spectroscopy: Breaking light into spectra
- Time Monitoring: measuring how light output varies with time

#### Imaging
- Most sensitive CCDs are black and white
- Astronomical detectors generally record only one wavelength of light at a time (using filters)
- Several images must be combined to make full-color pictures
- Astronomical detectors can record wavelengths of light our eyes can't see
- False color is sometimes used to represent non-visible wavelengths

#### Spectroscopy
- separates the different wavelengths of light befoer they hit the CCD detector

#### Time Monitoring
- light intensity (flux) curve represents a series of brightness measurements made over a period of time

### Telescopes and the Atmosphere
- only radio waves and visible light pass easily through Earth's atmosphere
- need telescopes in space to observe other wavelengths in the electromagnetic specturm

##### Adaptive Optics
Trubulent air flow in Earth's atmosphere distorts view, causing stars to appear to twinkle

##### Interferometers
achieving the angular resolution of a large telescope using two small telescopes at some distance apart, but linked to allow simultaneous detection

does not ahve the sensitivity of the large telescope

easiest to do with radio telescopes

Now possible also with infrared and visible light telescopes

## Properties of Stars
- distance to stars
	- parallax
- brightness vs luminosity
	- magnitude scale
	- effect of distance on magnitude & brightness
- temp of stars
	- colrs of stars
	- class ification os stellar sepctra
- HR diagram
	- CM diagram
	- main-sequence, giant, supergiant, white dwarf

## Parallax
Fundamental distance determination is from stellar parallax
- motion of Earth around Sun causes apparent motion of nearby stars again more distance backgorund stars
- this motion is a small loop
- angular diameter of loop is measrue of stellar parallax
- nearest stars have largest parallax
	- still small < one second of arc = 1 arcsec = 1''
- define a unit of distance:
	- __parsec__: objects wit parallax = 1 arcsec are at distance of 1 parsec

	d_parsec = 1 / p''
	p'' = 1 / d_parsec

	1 parsec = 1 pc = 206265 AU = 3.086 * 10^16 m = 3.26 light years

## Example
p ~ 0.286 arcsec
	d = 1 / p
	  = 1 / 0.286''
	  = 3.50 pc
	  = 11.4 ly

d ~ 4.24 ly = 1.30 pc
	p = 1 / d
	  = 1 / 1.30 pc
	  = 0.769 arcsec < 1''

## Apparent Brightness
depends on both distance and luminosity

Luminosity = Total amount of power (at all wavelengths) a star radiates (energy per second = watt)
	= L
	= 4*pi*R^2 * σ*T^4

	...intrinsic brightness
	like light bulb wattage

light spreads out over a large area as it travels further from its source
therefore, energy of light falling on any one square is less for squares further from source

Apparent Brightness = Intensity of starlight with reaches Earth (energy/second/square meter = W/m^2)
	= b
	= L / 4*pi*d^2

	can be reduced by anything along line of sight that blocks (absorbs or scatters) some starlight

can determine star's luminosity if we can measures its distance and apparent brightness

	L = 4*pi*d^2 x b

## Magnitude System
- scale set for naked-eye stars
	- brightness are first magnitude
	- faintest are sixth magnitudde
	- larger number = fainter
- first magnitude = 100 times brighter than sixth magnitude
- if m_1 - m_2 = 5 then b_2/b_1 = 100
- m = apparent magnitude
- b = apparent brightness
- log scale reflects how eye responds
	- converts ratio of actual intensity (b_2/b_1) into interval of perceived intensity (m_1-m_2)

if Δm = m_1 - m_2 = 5 => b_2/b_1 = 100
then Δm = 1 => b_2/b_1 = 100^(1/5) = 2.512

for two stars wit mag m1 and m2 and brightness b1 and b2

	b2/b1 = 100^((m1-m2)/5) => log(b2/b1) = (m1-m2)*log100 / 5
	m1 - m2 = 2.5 log(b2/b1) = -2.5*log(b1/b2)

	note: log_10

## Example
- star A is 5 times brighter than star Β.
- how many mags brighter is star A
	- mA - mB = -2.5*log(bA/bB) = -2.5*log(5) = -1.4 mag
	- star A is 1.4 mag brighter than star B
	- eg. if mB = 2.4 mag, then mA = 1.0 mag
	- note: smaller number corresponds to brighter star
- star C is a third mag star (mC = 3.0 mag) and mD = 4.8 mag
- how much brighter is C than D
	- mC - mD = -1.8 = -2.5*log(bC/bD)
	- bC/bD = 10^(-1.8/-2.5) = 10^0.72 = 5.25
	- => diff of 1.8 mag corresponds to brightness ratio 5.25

- 20 identical stars are close together, appear to be one star
- if each has brightness of 5.0 mag
- what is brightness in magnitude that observed for group

	m20 - m1 = -2.5*log(20star/1star)
	m20 - 5.0 = -2.5*log(20) = -2.5*1.30 = -3.25
	m20 = 1.75 mag

## Absolute Magnitude
M = absolute magnitude
  = apparent magnitude if star were at standard distance of 10 pc = 32.6 ly

  	m1-m2 = -2.5*log(b1/b2)
	b = L / 4*pi*d^2
	m-M = -2.5*log( d^2 / (10*p*c)^2 )
		= 5*log( d[pc] / 10 )

	d = 10pc -> m - M = 0
	d > 10pc -> m - M > 0 -> dimmer than at 10pc
	d < 10pc -> m - M < 0 -> brighter than at 10pc

M is related to L

	M1 - M2 = -2.5 * log( (b1 at 10pc) / (b2 at 10pc) )
	b_i = L_i / 4*pi*d_i^2
	M1 - M2 = -2.5 * log (L1/L2)

## Magnitude Summary
- magnitude scale relates apparent brightness (linear) and apparent magnitude (log)

	m1 - m2 = -2.5 * log( b1 / b2)

- distance formula relates apparent magnitude, absolute magnitude, and distance (in parsecs)

	m - M = 5 * log( d[pc] / 10 )

- can relate absolute magnitude and luminosity as for brightness and apparent magnitude

	M1 - M2 = -2.5 * log( L1 / L2 )

## Measuring Stellar Temperature
- Two methods
	- Color (backbody curve)
	- Spectrum (level of stellar atmosphere ionization)

	Note: human eye is not very sensitive to color at low light

## Color
- star's color is direct measure of temp
	- red stars cooler than blue stars
	- reddest/coolest stars ~ few * 1000 K
	- bluest/hottest stars ~ few * 10,000 Κ

- problem: interstellar dust can redden starlight
- measure ratio of apparent brightness at two diff wavelengths to determine T
	- measure that is independent of star's distance

## Spectrum
- level of ionization reveals star's temp
	- elements in cooler outer layers of star's atmosphere produce distinctive absortion spectrum
	- temp affects level of ionization of these elements (num & strength of lines)
		- higher T -> higher ionization

- Classificaton by spectral type:
- letters correspond to T ranges:
	- (hottest) O B A F G K M (coolest)
- spectra of hotter stars dominated by H & He lines
- cooler stars dominated by metals & molecules

- Subtypes
	- B0 (hottest B), B1, ..., B9 (coolest B)
- subtle diff in widths of spectral lines found to relate to luminosity/radius of stars
	- (narrowest) I, II, III, IV, V (widest)
	- I = high luminosity supergiant stars
	- III = medium luminosity giant stars
	- V = lower luminosity main-sequence stars (like Sun)
	- Sun = G2 V

## Extended Spectral Classification
- Brown Dward Stars:
	- mass between heaviest gas giants and lightest stars (~ 13-80 M_J)
	- too low mass for H fusion
		- maybe fuse deuterium or lithium
	- cooler than M9 stars
	- L dwarfs have strong lines/bands of metal hydrides (FeH, CaH, CrH)
	- T dwarfs are even cooler (T < 1400K)
		- dominated by lines/bands of water and methane

## Hertzsprung-Russell Diagram
- HR diagram is magnitude-color (CM) diagram ~= luminosity-temperature

- most stars lie along main sequence (MS)
- MS is a mass sequence
- other major regions
	- giant, supergiant, white dwarfs
	- evolutionary stages of MS stars with wide range of masses
- Mainsequence stars fuse H -> h2 in cores
- more luminous MS stars are hot (blue)
- less luminous MS stars are coolor (yellow/red)
- stars wit same T but higher L than MS, have larger radii
	-> giants and supergiants
- stars wit same T but lower L than MS, have smaller radii
	-> white dwarfs

## Binary Stars
Binary star systems are common (~50%)
- possible binary cases:
	- visual binary
		- both stars visibly orbiting each other
	- astrometric binary
		- only one star visible
		- moves around sky in loop
	- spectroscopic binary
		- only one star visible
		- shows no visible motion but from spectrum, can see regular periodic motion from Doppler shifts
		- sometimes only brighter star's sepectrum seen
	- eclipsing binary
		- one star passes infront of other, blocking some light

## Visual Binary
eg. period P ~ 45 y
	Kepler's 3rd Law: (m1 + m2) * P^2 ~ a^3

need to know distance (via parallax)
	d ~ 13 ly to get a ~9.5 AU
	-> m1 + m2 ~ 0.45 * M_sun
determine mass ratio from orbital radii ratio
	m1 ~ 0.27 M_sun
	m2 ~ 0.18 M_sun

## Spectroscopic Binary
cant see two separate stars but observe one or both star's spectra

motion -> periodic Doppler shifts of spectra
- timescale -> orbital period, P
- amplitude -> orbital speed -> orbital size, a -> sum of masses
- amplitude ratio -> mass ratio
- (edge-on -> true masses)

	m1/m2 = a2/a1 = v2/v1

## Example
- assume
	- seeing orbit edge-on (eclipsing binary)
	- orbits are circular, wit radii a1, a2 and a = a1 + a2
measure
	P = 0.1 y = 3.156 * 10^6 s (period of Doppler shift)
measrue
	v1 = 26 km/s, v2 = 40 km/s (amplitudes of Doppler shift)
calculate
	v1 = 2*pi*a1 / P
	=> a1 = P*v1 / 2pi
		= 1.306 * 10^10 m
	   	= 0.0873 AU
    v2 = 2*pi*a2 / P
	=> a2 = P*v2 / 2pi
	 	= 2.009 * 10^ 10 m
		= 0.1343 AU
calculate
	a = a1 + a2
		= 0.2216 AU
		= 3.315 * 10^10 m
calculate
	P^2 = 4*pi^2*a^3 / G*(m1+m2)
	=> m1+m2 = 2.165 * 10^30 kg = 1.089 M_sun
calculate
	m1/m2 = v2/v1 = 40/26
	=> m1 = 0.660 M_sun
	=> m2 = 0.429 M_sun

## Eclipsing Binary System
- eclipse => periodic changes brightness
- timescale => orbital period
- eclipse timing => ratio of stellar radii
- eclipse depth + radius => temp and luminosity ratio
- if spectroscopic => true radii + masses => avg densities

stellar mass data
	=> star's MS location determined by mass
	=> relations
		- mass & temp
		- mass & luminosity

### Mass-Luminosity Relation

	L ~ M^3.5
	M -> 2M
	L -> 11L

stellar lifetimes depend on:
1) amount of fuel (mass)
2) rate of burn (luminosity)

higher mass
- higher core P
- higher T, n
- higher fusion rate
- higher luminosity

	 Lifetime ~ Mass / Luminosity ~ M / M^3.5 = 1 / M^2.5
	 Lifetime = 10^10 years / (M / M_sun)^2.5

 ### Example
 M = 10 M_sun
 -> Lifetime = Life_sun / 10^2.5
 			 = 0.003 Life_sun

 M = 0.1 M_sun
 -> Lifetime = Life_sun / 0.1^2.5
 			 = 300 Life_sun

 ## Giants, Supergiants, White Dward
 Stellar properties depend on mass and age:
 	finished fusing H -> H2 in core leaves MS

All stars beecome larger and redder after exhausting core hydrogen
	-> giants and supergiants

Most stars end up small and white after fusion ceased
	-> white dwarfs

## Star Clusters
- Open cluster
	- few thousand loosely packed stars, bound together by gravity
- Globular cluster
	- up to a million or more stars in dense ball bound together by gravity

- cluster: group of stars, held together by mutual gravity
- all stars in cluster are summed to be roughtly same age

## HR diagram ofr Pleiades open cluster
- mass-lum relation => massive blue stars die first -> white, yellow, orange, red
- in Pleiades, all stars wit life expectancy less than ~10^8 y died
- ML-prediction: Pleiades ~100 million yrs old

## Variable Stars
- many stars vary in brightness far various reaons
- most common intrinsic caused is pulsation
	- star increases then decreases in radius
	- usually surface temp also varies
	- lum also depends on radius and temp -> result in variet of light curves

### Main types
- pulsating variables: common types
	- Cepheid: periods of 3-50 days
		- vary by ~0.2 mag
		- absolute mag -1.5 to -5 (very bright)
	- RR Lyrae: periods of less than a day
		- absolute mag of ~-1.0
		- Not as birhgt as Cepheids
	- long-period or Mira: periods of 80-600 days
		- large range in brightness
- eruptive variables: flare stars, novae, supernovae

## Variable star light curves
- plot of brightness of light at diff times
- many diff shapes of light curves
- shape tells about kind of variations in radius and surface temp
- most pulsating variable stars inhabit in instability strip on HR diagram
- models tell that stars cannot achieve proper balance between pwoer weling up from core and power radiated from surface
- Contract -> He ionization near surface -> opaque -> expand -> cools -> contracts -> variable brightness

Most luminous pulsating variables are Cepheid variables
very simple Period-Luminosity relation -> Standard Candle

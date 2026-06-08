# Virtual Armillary Sphere

A teaching-first, fully interactive 3D model of the celestial sphere — the rings
of the sky (horizon, meridian, equator, ecliptic, tropics, polar circles,
colures, polar axis) you can tilt to any latitude, run through the year, spin
through the day, and view from outside or from the ground in a first-person
planetarium. It also projects the real stars and constellation figures, lets you
scrub the year to watch precession drift the equinox through the zodiac, and can
highlight the Big Dipper and the southern Pointers as guides to the celestial
poles.

**Live:** https://whitehatnetizen.github.io/armillary-sphere/

Everything is in the single static file `index.html` (Three.js from a CDN — no
build step). Open it through any web server, or visit the live link above.

## Credits & licences

- Star and constellation-line data: [d3-celestial](https://github.com/ofrohn/d3-celestial) — MIT.
- Constellation figure artwork: [Stellarium](https://stellarium.org/) "modern" skyculture, by Johan Meuris — **Free Art License** (attribution and share-alike on redistribution).
- Capital-city coordinates: [REST Countries](https://restcountries.com/).
- Earth daymap: NASA Blue Marble (public domain), via the three.js examples.

## Accuracy note

A schematic teaching model, not an ephemeris. The Sun's position uses the
equation of centre (solstices land at ±23.44°, equinoxes ~0°, accurate to ~0.3°);
star positions are J2000 with uniform precession. True to the phenomena, not to
the arcsecond.

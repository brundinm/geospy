### *** geospy repository ***

*MRB: Tue 07-Jul-2026*

Purpose: This repository contains the GeoSpy game as well as the Ruffle Flash
Player emulator.

Description: This repository contains the GeoSpy game (also known as the 
GeoSpy Agency game), which was an interactive, educational online geography
game created by the National Geographic's Education Foundation in collaboration
with Maggie's Earth Adventure. GeoSpy was released sometime in the mid-2000s
and retired in 2020. It was a browser-based client-side application that was
programmed primarily in Adobe Flash, with ActionScript 3.0 code compiled into
.swf files that were hosted on the National Geographic Kids portal until Flash
was retired in December 2020.

Players are recruited to act as GeoSpy agents to help identify continents,
countries, and states or provinces (the states or provinces are for the countries
of Canada, Mexico, and the United States) on a map in a certain specified amount
of time. If a user guesses incorrectly, the game provides the correct answer
before giving them another location to find.

This repository also contains Ruffle, which is a free, open-source Adobe Flash
Player (also known as Shockwave Flash) emulator. Ruffle allows users to play
legacy Flash games and animations directly in modern web browsers, without
requiring the official (and discontinued) Flash Player plugin. It translates
Flash .swf files into modern web technologies (HTML5, WebAssembly, and WebGL) on
the fly. In this GeoSpy wrapper index.html file, the JavaScript ruffle.js file
automatically detects embedded Flash content and seamlessly replaces it with the
Ruffle player.

To play the game, you can click the website link at the top right of this page in
the About section to launch the Ruffle player and the embedded GeoSpy game, or you
can go to the website at <a href="https://brundinm.github.io/geospy/" target="_blank" 
rel="nofollow noopener noreferrer">https://brundinm.github.io/geospy/</a>.

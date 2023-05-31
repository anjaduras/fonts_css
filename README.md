####### MY FIRST FONTS LIBRARY #######

Hi friends! So basically the idea of this was me trying to simplify my future work.

1. In html, there are (for now) 28 p tags with same text line and font name. I also give them all custom id-s to link them to css. 
2. CSS contains 28 @font-face methods where i made custom font-family names and linked the font files I downloaded earlier. 
3. Then I simply wrote a specific font-family for each id.

The problem I faced is that is seems like TTF fonts are a bit old now? 
Meaning they take much longer to load then web-fonts like Google ones. Still need th research what to do. Soo it`s definetely not the best way, still works though!


####### QUOTING w3school: #######

TrueType Fonts (TTF)
TrueType is a font standard developed in the late 1980s, by Apple and Microsoft. TrueType is the most common font format for both the Mac OS and Microsoft Windows operating systems.

OpenType Fonts (OTF)
OpenType is a format for scalable computer fonts. It was built on TrueType, and is a registered trademark of Microsoft. OpenType fonts are used commonly today on the major computer platforms.

The Web Open Font Format (WOFF)
WOFF is a font format for use in web pages. It was developed in 2009, and is now a W3C Recommendation. WOFF is essentially OpenType or TrueType with compression and additional metadata. The goal is to support font distribution from a server to a client over a network with bandwidth constraints.

The Web Open Font Format (WOFF 2.0)
TrueType/OpenType font that provides better compression than WOFF 1.0.

SVG Fonts/Shapes
SVG fonts allow SVG to be used as glyphs when displaying text. The SVG 1.1 specification define a font module that allows the creation of fonts within an SVG document. You can also apply CSS to SVG documents, and the @font-face rule can be applied to text in SVG documents.

Embedded OpenType Fonts (EOT)
EOT fonts are a compact form of OpenType fonts designed by Microsoft for use as embedded fonts on web pages.


# lib-spectrum-next
#### ZX Spectrum Next Library Routines
A suite of Z80 modules for the ZX Spectrum Next with routines for:
- Reading the mouse
- Vector graphics (fast line, circle, and plot routines)
- Filled vector graphics with simple flat texturing (triangle, quadrilateral and circle)
- DMA
- Maths (taking advantage of the extended Z80N opcodes)

##### Build the demos
- The code is written to cross-assemble in sjasmplus on PC, Mac or Linux
- Visual Studio Code files included in .vscode folder for build and debug
- Demo files in the /Demo directory included to give you a quick-start

##### NB
- The DMA library routine is adapted from [one in this article written by Jim Bagley](https://www.specnext.com/the-zxndma/)
- The Kempston Mouse library routine is adapted from [this one written by Ben Versteeg](http://www.benophetinternet.nl/hobby/kmt.htm)

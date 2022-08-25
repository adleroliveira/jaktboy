# JaktBoy GameBoy emulator in Jakt
I decided to take the Jakt [Programming Language](https://github.com/SerenityOS/jakt) for a spin and was very inspired by JT's YouTube series building a Nes Emulator in Jakt, so I decided to do the same with a GameBoy emulator.

## References
- http://www.devrs.com/gb/files/docs.html
- http://bgb.bircd.org/pandocs.htm
- https://gbdev.io/
- http://www.akkit.org/info/gbatek.htm
- https://www.pastraiser.com/cpu/gameboy/gameboy_opcodes.html
- https://gbdev.gg8.se/wiki/articles/Pan_Docs
- https://gbdev.gg8.se/files/roms/blargg-gb-tests/
- http://marc.rawer.de/Gameboy/Docs/GBCPUman.pdf
- http://www.devrs.com/gb/files/docs.html
- http://imrannazar.com/GameBoy-Emulation-in-JavaScript
- http://www.codeslinger.co.uk/pages/projects/gameboy.html
- https://www.chibiakumas.com/z80/Gameboy.php
- https://ia803208.us.archive.org/9/items/GameBoyProgManVer1.1/GameBoyProgManVer1.1.pdf


## Blargg Tests Passing

### CPU
- [x] 01-special
- [x] 02-interrupts
- [x] 03-op sp,hl
- [x] 04-op r,imm
- [x] 05-op rp
- [x] 06-ld r,r
- [ ] 07-jr,jp,call,ret,rst
- [x] 08-misc instrs
- [ ] 09-op r,r
- [ ] 10-bit ops
- [ ] 11-op a,(hl)

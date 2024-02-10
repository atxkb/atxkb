### ATXKB resources

### 512/Console:

* Bumpons: 6x2mm
* Gasket: 1mm x 76mm x 5mm (any cushioned adhesive strip will do, but the original was silicon)
* PCB: any standard 60% pcb
* Plates:
  - [wkl](plates/512_wkl_plate_v7.dxf)
  - [wk](plates/512_wk_plate_v10.dxf)

### Moontower/Moontower V2/Moontower V3:

* [O-ring](https://www.theoringstore.com/store/index.php?main_page=product_info&products_id=879)
* Additional O-ring source: graveshift
* Bumpons: 8x2mm
* PCB: Hiney H60
* Clip-in GMK or TX stabs (there have been some reports of [filing down screw-in stabs](https://cdn.discordapp.com/attachments/758797111486971976/937809309314715648/unknown.png), but I haven't tried myself)
* [Easy Plate removal technique](https://youtube.com/shorts/fSTPTv5prkE)
* [Plate](plates/moontower_plate_v8.dxf)
  - also compatible with standard 60% plates

### 1894 PCB Instructions:

* Download the atxkb/1894 via hex [here](https://caniusevia.com/docs/download_firmware/)
* Download and install qmk toolbox [here](https://github.com/qmk/qmk_toolbox)
* Download VIA [here](https://www.github.com/the-via/releases/releases/latest) 
* Plug in your pcb and daughterboard
* Press the reset button on the bottom of the pcb
* Flash the atxkb/1894 via hex to the pcb using qmk toolbox
* Customize the pcb layout/lighting/etc with via

### H60 PCB Instructions:

* Same as 1894, but you'll need to use [this](firmware/hineybush_h60_via.hex) hex file instead

### Live Oak:

* Gaskets: 53mm x 3mm x 1.5mm
  - the ones included in the kit are custom, but you can find foam gaskets that can work as a replacement on amazon you just may need to cut them to fit
* Bumpons: 8x2mm

### Live Oak Build Instructions:

* Set aside pcb, pcb screws, daughterboard, domes, springs, sliders, and switches from your hhkb
  - Disassembly vid [here](https://www.youtube.com/watch?v=kdqqHSKyfyI) (there are others on youtube as well)
* Install the daughterboard into the Live Oak case using the three screws already in the case
* I recommend lubing the sliders themselves and/or the contact points on the plate where the sliders will touch the plate
  - You can put a slider into the plate to see where the legs of the sliders will contact the plate if you're unsure
* Flip the Live Oak plate upside down and place sliders and stabilizers into place
* Lube the stabilizers, the stabilizer wires, and the two stabilizer wire covers
* Secure the stabilizer wires into place with the two covers and screws included with your kit
* Add the spacebar stabilizers to the plate
  - The area surrounding the spacebar stabilizers is very thin so support the plate when pressing them in and press slowly, but firmly until they click.
  - [There was a report of the plate cracking during this process so be careful!](https://imgur.com/a/sVJymYy)
* Either hold the plate in one hand or find two objects of equal height to suspend the plate so the sliders are fully extended
* Place the domes onto the sliders
  - The domes on the stabilizer stabs can be a bit of a pain but will eventually line up
* Place the pcb onto the plate assembly and secure using the screws from your hhkb
  - I recommend starting with the outside screws and working inward making sure they line up
* Place the gaskets included with your kit on the plate or on the case depending on your preference
  - You'll be using all 12 gaskets so both the top and underside of the plate are isolated from the case
* Connect the ribbon cable between the pcb and the daughterboard
* Place the plate assembly into the case
* Position the top piece of the case into place
* Flip the board and secure the top and bottom pieces together using the included screws
  - You may want to screw them in lightly in case you need to center the plate before screwing them in the rest of the way
* Enjoy! Also let me know if I missed anything here and I'll add it

### Live Oak halp from the community:

* If you notice any ticking/clack on the enter or shift and normal lubing doesn't seem to be helping you might want to give [these](https://unrealkeyboards.com/products/o-rings-for-keycaps) orings a shot

### Live Oak alternate plate:

* [Live Oak Housingless Plate](plates/live_oak_housingless_plate.dxf)
* Required Screws: 18 m2x8mm
* Requires donor housings from a realforce or deskeys

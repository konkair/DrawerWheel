<h1 align="center">Before You Begin</h1>
 
<p align="center">
  Models related to the steering wheel (paddle shift, wheel encoder) are designed for this steering wheel:
  <br><br>
 <img width="449" height="441" alt="621088206-c9d27bfe-b4da-4281-bfc6-63039ef5ae99-Photoroom" src="https://github.com/user-attachments/assets/16e96729-bf80-4541-9500-fc57965cf35f" />
  <img width="200" height="441" alt="image2" src="https://github.com/user-attachments/assets/a815cc70-40b7-4f56-a009-1150a662146c" style="vertical-align: middle; margin: 10px;" />
</p>
<p align="center">
  (You can buy it secondhand; that's what I did.)
   </p>

# Full Build
<img width="1920" height="722" alt="zz" src="https://github.com/user-attachments/assets/e65df026-e9fd-4b08-9398-76ff06f114d8" />


<img width="1520" height="722" alt="Screenshot 2026-07-12 151130" src="https://github.com/user-attachments/assets/32c54c19-cdda-4622-9fa2-860ee5fee710" />


<img width="1520" height="722" alt="2e02f5b3-c47f-4aac-a90a-409e35e45135" src="https://github.com/user-attachments/assets/e9d0ab70-481c-40e9-94ac-123a34f56987" />

*You can take detailed measurements yourself using the full-build model.*



# Why Im Building This?

I'm building this project because I want a steering wheel, but they're expensive and you can actually make better than the ones on the market for cheaper (I mean, I guess?). and at the same time this project will teach you (and me) a lot.
and you might be wondering why I didn't use a 3D printer or buy new materials to make a case;

this drawer is useless. Why wouldn't I use it? (and stronger than 3D printed cases)

# 3D Part Guide

### Desk clamp

In the 76th layer, there is a stop. In this layer, you need to insert the M12 hex nut into this place:
<img width="856" height="465" alt="image" src="https://github.com/user-attachments/assets/dea53b1a-8956-484b-ac72-fca09810fd0a" />

Then resume printing.


### Thumb Screw Knob

Just print it as normal, then glue the M12 hex-headed screw into this spot.

<img width="290" height="257" alt="image" src="https://github.com/user-attachments/assets/2c407114-d339-4f69-a5b6-8d5c67d961ce" />



*There is nothing special about the other parts, but you need to use the 3MF file that I uploaded to GitHub because the settings for each part are different.*

# Build Guide

You can figure out how to build this project by reviewing the fullbuild model; I'm thinking of putting together a short guide after I build the project, but I'm not sure yet.


This is the schematic for this project
<div align="center">
<img src="https://github.com/user-attachments/assets/4edd468b-7f72-474d-85c8-245d2e56b416" width="1600">
 <p>(This schematic is not final and may change as the project progresses. And this is actually my first schematic.)</p>
</div>

The Arduino Leonardo will be sufficient for a project of this power, I'm not using the ESP32-3S or STM32 because the softwares made for these microcontrollers is usually for direct drive, but this project is not direct drive, so it does not require a lot processing power and there is a software for the Arduino Leonardo that is specifically designed for these modules and project purpose: https://github.com/ranenbg/Arduino-FFB-wheel This is the software and the original wiring diagram can be found at that link.

<div align="center">
 <p></p>


# Markdown Billl of Materials

(These links lead to local sellers in Turkiye.)
| Part | QTY | Link |
| :--- | :---: | :--- |
| Rotary Encoder E6B2-CWZ6C 1000 Pulse | 1 | https://www.direnc.net/rotary-encoder-e6b2-cwz6c-1000-pulse |
| Arduino Leonardo R3 Klon | 1 | https://www.voltaj.net/arduino-leonardo-r3-klon-usb-kablo-pmu1486 |
| 12V 30A Power Supply | 1 | https://www.robolinkmarket.com/12v-30a-metal-kasa-adaptor |
| 14 AWG Silicone Cable (black) | 1 | https://www.robolinkmarket.com/14-awg-silikon-kablo-1-metre-siyah |
| 14 AWG Silicone Cable (red) | 1 | https://www.robolinkmarket.com/14-awg-silikon-kablo-1-metre-kirmizi |
| GT2 Closed-End Belt - 280mm (Buy 240mm if found) | 1 | https://www.robo90.com/gt2-6mm-kapali-zamanlama-kayisi-280mm-uzunluk |
| BTS7960B 40-Amp Motor Driver Board | 1 | https://www.voltaj.net/43a-5-27v-cift-bts7960b-h-kopru-yuksek-guc-motor-surucu-modulu-pmu1135 |
| 20-Tooth GT2-6mm Pulley - 5mm Shaft Diameter | 1 | https://www.robolinkmarket.com/20-dis-gt2-6mm-kasnak-5mm-saft-capi |
| GT2 6mm Toothless Pulley with Bearings - 5mm Shaft Diameter | 1 | https://www.robolinkmarket.com/gt2-6mm-dissiz-rulmanli-5mm-kasnak-siyah |
| KP000 Bearing (10 mm) - P000 | 2 | https://www.robolinkmarket.com/kp000-rulman-10mm |
| RS 775 DC Motor - 12V - 3000 RPM - Drill Motor | 1 | https://www.robo90.com/rs-775-dc-motor-12v-3000-rpm-matkap-motoru |
| 10mm Chrome-Plated Induction Shaft - 300mm | 1 | https://www.robo90.com/10mm-krom-kapli-induksiyonlu-mil-300mm |
| Insert Nut M5 | 20 | https://www.rhino3dprinter.com/urun/insert-somun-m5 |
| M6 Locknut | 4 | https://www.hirdavatim.com.tr/urun/fiberli-somun-celik-m5-m39-m5 |
| M5 Locknut | 6 | https://www.hirdavatim.com.tr/urun/fiberli-somun-celik-m5-m39-m5 |
| M3 Hex Nut | 14 | https://www.hirdavatim.com.tr/urun/metrik-normal-celik-somun-m3-m48-m5 |
| M12 Hex Nut | 2 | https://www.hirdavatim.com.tr/urun/metrik-normal-celik-somun-m3-m48-m5 |
| M5 Hex Nut | 2 | https://www.hirdavatim.com.tr/urun/metrik-normal-celik-somun-m3-m48-m5 |
| M6 40mm Allen Screw | 4 | https://www.hirdavatim.com.tr/urun/m6-imbus-civatalar-8-8-kalite-m6-40-mm |
| M3 20mm Pan Head Screw | 2 | N/A |
| M3 30mm Pan Head Screw | 4 | N/A |
| M3 50mm Pan Head Screw | 4 | N/A |
| M3 12mm Pan Head Screw | 4 | N/A |
| M5 30mm Allen Screw | 3 | https://www.hirdavatim.com.tr/urun/m6-imbus-civatalar-8-8-kalite-m6-40-mm |
| M12 50mm Hex Head Screw | 2 | https://www.hirdavatim.com.tr/urun/m12-anahtar-basli-celik-civatalar-8-8-kalite-m12x50-mm |
| M5 12mm Allen Screw | 1 | https://www.hirdavatim.com.tr/urun/m6-imbus-civatalar-8-8-kalite-m6-40-mm |
| M5 20mm Allen Screw | 1 | https://www.hirdavatim.com.tr/urun/m6-imbus-civatalar-8-8-kalite-m6-40-mm |
| 3.5X50mm Wood Screw (Pack of 20 - Min order) | 6 | https://www.hepsiburada.com/meridyen-3-5x18-mm-sunta-vidasi-50-adet-p-HBV00000JIT71 |
| 3.20mmX18.5 Wood Screw | 8 | N/A |
| M5 Washer | 14 | https://www.hirdavatim.com.tr/urun/metrik-demir-pul-cesitleri-05-mm |
| M6 Washer | 4 | https://www.hirdavatim.com.tr/urun/metrik-demir-pul-cesitleri-05-mm |
| Estimated Total Price (~$70 - $90) | | |

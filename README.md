# CAD

CAD model of the Centauri Carbon

Live Viewer available here on the [Opencentauri Docs](https://docs.opencentauri.cc/hardware/CC1/) an F3Z version of the CAD with joints can be downloaded there or through [printables](https://www.printables.com/model/1355933-elegoo-centauri-carbon-opencentauri-community-cad)



https://github.com/user-attachments/assets/0ed5f8c5-8805-440e-aed6-0f10b0649171

## FDM-optimized printable replacement parts

<img width="1638" height="1440" alt="image" src="https://github.com/user-attachments/assets/64fae27e-0e5d-4e6f-8c66-ba423bc33c1a" />

Built in support has not been added to all models where it is required. further improvements may need to be done on some of these models- these are not tested designs and if you run into problems or want to contribute changes reach out on the opencentauri discord or make a pull request on the OC CAD github. The following parts are included:
- carriage part
- Extruder parts
- Front idler mounts
- Motor mounts
- bed mounts
- Z belt tensioner
- top rod/leadscrew mounts

Additionally not all models are particularly well suited for direct FDM optimization and better scratch designs from the community are available. In particular this applies to:
- XY Bearing blocks:  [clogged_nozzl3's bearing blocks](https://www.printables.com/model/1535090-centauri-carbon-runice-toothed-idler-blocks) are strongly reccomended over the rough optimized version included here
- Toolhead cowling/shell: There are numerous toolhead cowling options that are more suitable for FDM printing including the following:
    - [clogged_nozzl3's ACCTC cowling](https://www.printables.com/model/1575497-another-centauri-carbon-toolhead-cover) heavily modified low mass gamma-variant
    - [layer.shifted's cowling](https://www.printables.com/model/1511606-centauri-carbon-lightweight-cowling) which offers a close to stock styling
    - [Robert Samples' gamma cowling](https://www.printables.com/model/1410999-g-gamma-toolhead-cover-for-elegoo-centauri-carbon) which offers a high strenght low mass magnetic version
    - [Synthetic Electron 3D's cowling](https://www.printables.com/model/1399340-se3d-elegoo-centauri-carbon-toolhead-cover) the first printable design with numerous remixes

### Printing and use instructions:

ABS/ASA minimum recommended. Counterbore bridging was used to eliminate support requirements where possible but in other places built in supports (in green) are part of the printable base models as discrete objects, they are optimized for printing with 0.2 mm layer height. DO NOT ADD EXTRA SUPPORT. orientation for printing should be fairly obvious, all built in supports contact the bed. The Z tensioner is split into two halves which are printed seperately and screwed together. You will need m3x5x4mm heatset inserts for this, as well some m2.5 heatsets ones for the carriage. They must be the following style and not injection molding type inserts.

<img width="109" height="92" alt="image" src="https://github.com/user-attachments/assets/07366bb9-a0ec-450a-a6ec-873003bb98f1" />




## **Credits**

Elegoo: Provided official models for Z axis, X axis, and toolhead plastic parts

Discord user anna\_devminer: model of mainboard and and toolhead PCB

Discord user thijskunst added beta opencentauri board model

Benjamin Butschell: Midcowling revisions

Printables/Discord user CornFlakes\_494568: Front Idler mount revisions

Printables/Discord clogged\_nozzl3: XY motor tensioner

Felix Oberfeld: XY block revisions

HeartForge/Devin: accurate rear bed mount

Discord user lamarc4102: Huge redesign of the toolhead cowling and improved toolhead PCB model, accurate purge shoot model.

GitHub MakingStuffandThings: spool holder

Printables/Discord userMINUS\_Stl: main cable chain links

Printables user indi001 (https://www.artstation.com/werner-kaffl): toolhead cable chain link

Robert Samples: Main geometry and integration, FDM-part optimization

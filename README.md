# PlasticPET Selected Plots  

- *Some plots have very poor statistics, but I haven't yet had a chance to regenerate them... 
- If you would like to use those, please tell me, and I will generate them ASAP (will take a day or two, since simulation is fairly slow).
- The upper-right green `code` dropdown offers an option to download as ZIP.


## SETUP

### Geometry

- I am assuming Mr. Proga has supplied this to satisfaction...  

### Cross-Section & Material Definition

- EJ208 & SiPM Response

![](0-CrossSection/EJ208.png) ![](0-CrossSection/SiPM.jpg)

- Geant4 Implementation of Polyvinyltoulene (PVT) against NIST standards:  

![](0-CrossSection/PVT_G4_VS_NIST_CS.png) ![](0-CrossSection/PVT_G4_VS_NIST_L.png)  

- Geant4 Implementation of EJ208 (addition of Pb) against NIST standards:  

![](0-CrossSection/PVT_G4_W_Pb_CS.png) ![](0-CrossSection/PVT_G4_W_Pb_L.png)  

### Primitives

- Example Creation/Production & Detection Plots; to motivate looking at sum histograms.

![](1-Primitives/Creation.png) ![](1-Primitives/Detection.png)  

### Surface Treatment*

#### Light Yield across Varying Plastic Roughness | Motivate using Polished Crystal

- VK_sigmaalpha = 12 degrees, EJ_sigmaalpha = `[2deg, 12deg]` respectively. These values are from a previous G4 paper that used them to discriminate between rough and polished surfaces.

![](2-Surfaces/EJVK-2-12.png) ![](2-Surfaces/EJVK-12-12.png) 

- VK_sigmaalpha = 0.0001, EJ_sigmaalpha = `[0.0001,1.3deg,4deg,6deg,8deg,12deg,30deg]` respectively. All with 200 events. Note EJ208 is set at 100% reflectivity specially for these tests! VK reflectivity is as measured.  

<details>
<summary>Images</summary>

![](2-Surfaces/EJVK-0.0001.png) ![](2-Surfaces/EJVK-1.3-0.0001.png) 

![](2-Surfaces/EJVK-4-0.0001.png) ![](2-Surfaces/EJVK-6-0.0001.png) 

![](2-Surfaces/EJVK-8-0.0001.png) ![](2-Surfaces/EJVK-12-0.0001.png)  

![](2-Surfaces/EJVK-30-0.0001.png)  

- EJ & VK_sigmaalpha = `[1.3deg, 12deg]`, respectively.  

![](2-Surfaces/EJVK-1.3.png) ![](2-Surfaces/EJVK-12.png)  

</details>





# PlasticPET Selected Plots  

- *Some plots have very poor statistics, but I haven't yet had a chance to regenerate them... 
- If you would like to use those, please tell me, and I will generate them ASAP (will take a day or two, since simulation is fairly slow).
- Some images are hidden by a dropdown, since they are not directly relevant, but are needed to show full progression.  

<a href="https://github.com/akhilsadam/PlasticPET-graphicx/archive/refs/heads/main.zip">Download as ZIP</a>
<link type="text/css" rel="stylesheet" src="https://raw.githubusercontent.com/akhilsadam/PlasticPET-graphicx/gh-pages/styles.css"/>

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


![](2-Surfaces/EJVK-0.0001.png)

![](2-Surfaces/EJVK-1.3-0.0001.png)  

![](2-Surfaces/EJVK-4-0.0001.png)

![](2-Surfaces/EJVK-6-0.0001.png)  

![](2-Surfaces/EJVK-8-0.0001.png)

![](2-Surfaces/EJVK-12-0.0001.png)   

![](2-Surfaces/EJVK-30-0.0001.png)    
 

</details>

- EJ & VK_sigmaalpha = `[1.3deg, 12deg]`, respectively.  

<details>
<summary>Images</summary>  


![](2-Surfaces/EJVK-1.3.png)

![](2-Surfaces/EJVK-12.png)  



</details>

#### Reflection Suite

<details>
<summary>Images</summary> 



# TODO



</details>





<svg fill="none" viewBox="0 0 800 400" width="800" height="400" xmlns="http://www.w3.org/2000/svg">
	<foreignObject width="100%" height="100%">
		<div xmlns="http://www.w3.org/1999/xhtml">
			<style>
* {
    font-variant-ligatures: none;
}

img{
    width: 25%;
}

:root {
    --kotoba: Kiona, Aron Grotesque Light, Montserrat Regular;
    --aijiro: rgba(235, 246, 247, 1);
    --sukaitsuri-iro: rgb(220, 240, 250);
    /* skytree white not accurate */
    --mashiro: rgb(255, 255, 255);
    --zoge-iro: rgb(255, 255, 240);
    --hakushi: rgb(249, 251, 255);
    --mizu-iro: rgb(134, 171, 165);
    --gunjo-iro: rgb(93, 140, 174);
    --sora-iro: rgb(77, 143, 172);
    --chigusa-iro: rgb(49, 117, 137);
    --benimidori: rgb(120, 119, 155);
    --rurikon: rgb(27, 41, 75);
    --rurikon-alph: rgba(27, 41, 75, 0.15);
    --omeshi-onando: rgb(61, 76, 81);
    --tetsuonando: rgb(43, 55, 54);
    --sakuranezumi: rgb(172, 129, 118);
    --ginshu: rgb(188, 45, 41);
    --azuki-iro: rgb(103, 36, 34);
}

body,
html {
    height: 100%!important;
    margin: 0;
    padding: 0;
    background: var(--aijiro) !important;
    /*#e7ecf7!important;*/
    font-family: var(--kotoba);
}

.row .col {
    padding: 0!important;
}

header {
    position: relative;
    width: 100%;
    padding: 30px 0!important;
    background: var(--mashiro)!important;
    box-shadow: 0 0 5px var(--hakushi);
    font-family: var(--kotoba);
}

header .nav-wrapper {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 1000px;
    max-width: 90%;
    margin: auto;
}

header .nav-wrapper nav {
    display: flex;
}

header .nav-wrapper .logo {
    display: inline-block;
    width: 40px;
}

header .nav-wrapper a {
    color: var(--chigusa-iro);
    font-size: 1em;
    text-decoration: none;
    transition: all .3s ease-out;
}
			</style>
			<div class="container">
				<h1>Made with HTML &amp; CSS<br/>not an animated GIF</h1>
				<p>Click to see the source</p>
			</div>
		</div>
	</foreignObject>
</svg>

---
# title:
# author: Hadi Asemi
# date:
# <!-- header-includes:
#   - \hypersetup{colorlinks=True,
#       allbordercolors={0 0 0},
#       pdfborderstyle={/S/U/W 1}
#     } --> -->


urlcolor: blue
geometry: "left=2cm,right=2cm,top=2cm,bottom=2cm"
fontsize: 12pt

header-includes:

- \usepackage{fancyhdr}
- \pagestyle{fancy}
- \fancyfoot{}
- \fancyhead{}
- \fancyfoot[R]{\thepage\ }
- \renewcommand{\headrulewidth}{2pt}
- \renewcommand{\footrulewidth}{2pt}
- \fancyhead[L]{Review papers}
- \fancyhead[R]{Hadi Asemi}
- \fancyhead[C]{}
- \newlength\FHoffset
- \setlength\FHoffset{1cm}
- \usepackage{setspace}
- \onehalfspacing

---


\begin{titlepage}
	\begin{center}
		\line(1,0){300}\\
		[0.25in]
		\huge{\bfseries Research}\\
		[2mm]
		\line(1,0){300}\\
		[1.5cm]
		\textsc{\LARGE Review papers}\\
		[10.5cm]

		\textsc{\Large }\\
		[4cm]

	\end{center}
	\begin{flushright}
		\textsc{\large Hadi Asemi\\
		Jul 27,2020\\}
	\end{flushright}
\end{titlepage}
\tableofcontents
\thispagestyle{empty}
\cleardoublepage
\newpage
\setcounter{page}{1}
\thispagestyle{fancy}

# **Review of Fiber Optic Diagnostic Techniques for Power Transformers:**

It is important constantly monitor transformers because when the age of power grid increase, the failure will increase. Normally, we use the electrical sensors to monitor the transformers; however, due to the high electromagnetic interface, it is difficult to   monitor in the real time. As result, to overcome this problem we use fiber optic sensor to overcome this barrier. We can use fiber sensors to measure optical absorption, fluorescence refractive index, pressure, and strain.
In this paper a variety and assessment of different fiber optic-based diagnostic techniques for monitoring power transformers are discussed.

 Fiber optic sensors are classified:

 		 1. Phase-modulated senosors:
		 2. Intensity-modulated sensors:
		 3. Wavelength-modulated sensors:
		 4. Scattering-based sensors:
		 5. Polarization-based sensors:


## Fiber Optic Sensor for Electrical Parameters Assessment:

### Partial discharges:

Partial discharges(PDs) are electrical breakdown in weak region of an electrical
insulation System.

		1. PDs of the corona type: this will occur in the gas bubbles suspended oil.
		2. PDs of the sparking type: this will happen in the liquid(oil) or solid(paper)
		   phase
		3. PDs of the surface type: this will occur in discharges on the outer
		   surface of solid insulation.

The fiber optic interferometers have high sensitivitys and large flat response range, but it is hard to multiplex.

**Chen et al.** made an extrinsic fiber Fabry-Parot (FP) sensor for detecting
PD acoustic emission. As a result, he could measure PD acoustic emission
for both wide-band and narrowband mode.This emission, had the high amplitude
between **50-170kHz** frequency range.

**Wang et al.** made an optical fiber sensing probe to detect the ultrasonic signals of PD based  on linear Sagnac optical interferometry. The time-domain amplitude was 0.8-1.9V, and frequency response was 58kHz with 10kV voltage.

**Zhou et al.** mentioned that in the Michelson ultrasonic sensor the sensitivity increased when the fiber coil get smaller to the range between 80-200kHz. The detection limit was 0.26Pa and distance between sensor's head and the ultrasonic sensor was 300mm in the oil.

The important result of their experiment shows that phase-shifted fiber Bragg gratings(PS_FBG) has the higher frequency response (8.46db) compare to the ultrasonic sensor. The PD detection demonstrate that PS-FBG immersed in oil has sensitivity 17.5 times higher than zirconate titanate (PZT) sensor.  
 They developed the fiber acoustic sensors array and installed into a real 35kV transformer. They also found out by PD localization they can get less than 5cm error in their design.

### Electrical Breakdown Assessment:

They developed fiber optic sensors based on setp index multimode polymer for monitoring transformer oil breakdown. The refractive index for a service age oil is higher than new oil and when the oil degrades the breakdown voltage decrease, and refractive index increase. By measuring the output voltage of optical fiber(immersed in oil) and level of oil contamination, they indicate the oil is new or old.

### Current and Voltage Monitoring:

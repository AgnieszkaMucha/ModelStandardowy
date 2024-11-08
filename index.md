{% include cool_header.html %}
### AGH University of Kraków
### Wydział Fizyki i Informatyki Stosowanej


# Wstęp do Modelu Standardowego (FT1 2024) 

## WYKŁADY
- O czym tu będzie, czyli wstęp do wstępu [slajdy](/Files/WMS_1.pdf)
- Relatywistyka [slajdy cz.2 Pole elm ](/Files/WMS_Pola.pdf)
- Lagranżiany 
- Obroty i grupa U(1) [slajdy](/Files/WMS_3.pdf)
- Oddziaływania elektromagnetyczne
- Równanie Diraca
- Neutrina
- Przekrój czynny,   

## ĆWICZENIA
- Relatywistyka i pola [Zadania](Files/Rel_pola.pdf)
- Rozważania o spinie i izospinie [Zadania](Files/Spiny_MS3.pdf)


## Literatura:
- W. N. Cottingham,  D. A. Greenwood "An Introduction to the Standard Model of Particle Physics",
- David Griffiths "Introduction to Elementary Particles", John Wiley & Sons 1987
- Mark Thomson "Modern Particle Physics", University of Cambridge, 2013 [online resources](https://www.hep.phy.cam.ac.uk/~thomson/MPP/ModernParticlePhysics.html)
- B.R. Martin G.Shaw "Particle Physics", 3rd Ed, Wiley 2008
- Sylvie Braibant, Giorgio Giacomelli, Maurizio Spurio "Particles and Fundamental Interactions: An Introduction to Particle Physics" 2011
- Martinus Veltman "Facts and Mysteries in Elementary Particle Physics" World Scientific Publishing Co. Pte. Ltd. 2003
- Matthew D. Schwartz "Quantum Field Theory and the Standard Model",
- Luis Alvarez-Gaume, Miguel A. Vazquez-Mozo "Lectures on Field Theory and the Standard Model: A Symmetry-Oriented Approach",
- Alessandro Bettini “Introduction to Elementary Particle Physics”  Cambridge University Press, 2014

## PROJEKT


# Model Standardowy (FT2 2024)

## WYKŁADY
- Czym różni się kurs *Model Standardowy* od kursu *Oddziaływania cząstek elementarnych*? [slajdy](/Files/FT2_MS_1.pdf)
- Grupy i symetrie w fizyce (zwłaszcza cząstek elementarnych) [slajdy](/Files/FT2_MS_2.pdf)
- Relatywistyka 
- Lagrangiany i zasada najmniejszego działania [slajdy](/Files/FT2_MS_4.pdf)
- Równanie Diraca [slajdy](/Files/FT2_MS_5.pdf)
- Oddziaływania elektromagnetyczne [slajdy](/Files/FT2_MS_6.pdf)
- Oscylacje zapachu [slajdy](/Files/FT2_MS_7.pdf)
- Oddziaływania silne [slajdy](/Files/MS_QCD-notes.pdf)
- Oddziaływania elektrosłabe [slajdy](/Files/FT2_MS_9.pdf)
- Spontaniczne łamanie symetrii i bozon Higgsa
- Precyzyjne pomiary Modelu Standardowego

  
## Literatura:
- W. N. Cottingham,  D. A. Greenwood "An Introduction to the Standard Model of Particle Physics",
- David Griffiths "Introduction to Elementary Particles", John Wiley & Sons 1987
- Mark Thomson "Modern Particle Physics", University of Cambridge, 2013 [online resources](https://www.hep.phy.cam.ac.uk/~thomson/MPP/ModernParticlePhysics.html)
- B.R. Martin G.Shaw "Particle Physics", 3rd Ed, Wiley 2008
- Sylvie Braibant, Giorgio Giacomelli, Maurizio Spurio "Particles and Fundamental Interactions: An Introduction to Particle Physics" 2011
- Martinus Veltman "Facts and Mysteries in Elementary Particle Physics" World Scientific Publishing Co. Pte. Ltd. 2003
- Matthew D. Schwartz "Quantum Field Theory and the Standard Model",
- Luis Alvarez-Gaume, Miguel A. Vazquez-Mozo "Lectures on Field Theory and the Standard Model: A Symmetry-Oriented Approach",
- Alessandro Bettini “Introduction to Elementary Particle Physics”  Cambridge University Press, 2014

## Laboratorium
- Oscylacje flavouru [program Pawła](/Files/Oscilation.zip)
- Narzedzia statystyczne - ROOFit [manual](https://root.cern/download/roofit-strasbourg-v10.pdf)
- Pakiet do analizy - zFit [tutorial](https://zfit-tutorials.readthedocs.io/en/latest/)   lub wstęp [tutaj](https://github.com/zfit/zfit) lub [artykuł](https://arxiv.org/abs/1910.13429)
- O minimalizacji Minuitem poczytaj [tutaj](https://indico.cern.ch/event/833895/contributions/3577808/attachments/1927550/3191336/iminuit_intro.html)

<!--
# Składzik z narzędziami

### ROOT 
 You can find a plethora of ROOT tutorials:
 - Very recent [Manual](https://root.cern/manual/basics/)
 - Very clear and quite new tutorial with C++ and Python [here](https://www.nevis.columbia.edu/~seligman/root-class/RootClass2021.pdf)
 - Examples with DataFrame [here](https://root.cern/doc/master/classROOT_1_1RDataFrame.html)
 - PyROOT Workshop z 2022, [zobacz](https://indico.cern.ch/event/882824/contributions/3929999/)
 
### Working environment 
HEP analyses usually require [ROOT framework](https://root.cern/). 
> You can use ROOT on Windows but I strongly discourage you from doing this. 
> You can either:
- zainstalować VM z preinstalowanym ROOTem i condą (**podejście rekomendowane**), zobacz i pobierz [tutaj](https://figshare.com/s/2fd8f8072f9b7e50cf4d), kilka wskazówek praktycznych jest [tutaj](Files/notatki_VM_Root.pdf)
- use your personal computer with VM and install ROOT, see [here](https://root.cern/install/),
- używać ROOTa poprzez Google Collab: konfiguracja środowiska pracy podczas pracy w laboratorium WFiIS jest tutaj: [instrukcja](Files/WorkingEnv)
- używać ROOTAa na swoim lokalnym komputerze po zajęciach logując się na komputer w 204, instrukcja jest [tutaj](https://agile.fis.agh.edu.pl/confluence/pages/viewpage.action?pageId=28837229)


### How to start with Jupyter Notebook
- start with reading [this](https://www.dataquest.io/blog/jupyter-notebook-tutorial/)
- everything you need to know is [here](https://hsf-training.github.io/analysis-essentials/python/01basics.html#Jupyter)


### Python 
- practical course of Python, see [here](https://hsf-training.github.io/analysis-essentials/python/README.html)


### C++ or Py? This is the question...
> Well, why not trying both? Below you can find example of the same analysis in ROOT in C++ and Python scenario [3]:
   - [ROOT C++](Files/Tutorial-ROOT.pdf)
   - [PyROOT](Files/Tutorial-PyROOT_2018.pdf)
- Have a look at [PyROOT](https://root.cern/manual/python/) webpage.




## PROJEKT
- Skąd się biorą cząstki w pliku z danymi? [Reconstruction](Files/LAB_reconstruction.pptx)
- Identyfikacja cząstek w eksperymencie LHCb [Identyfikacja](Files/Identyfikacja.pdf)
- Materia-antymateria (łamanie CP) [OPIS](Files/projekt_2022.pdf)
- Zadanie projektowe [notatnik](https://github.com/lhcb/opendata-project/blob/master/LHCb_Open_Data_Project.ipynb)

- Kwarki [Zadania](Files/zadania_3.pdf)



## Particle Physics projects for AGH UST FPACS students
- Materia-antymateria (łamanie CP) [OPIS](Files/projekt_2021.pdf)

## HOT NEWS!
- Evidence of new physics (Measurement of the Positive Muon Anomalous Magnetic Moment) [web page](https://news.fnal.gov/2021/04/first-results-from-fermilabs-muon-g-2-experiment-strengthen-evidence-of-new-physics/) [article](Paper/muong2.pdf)
- Violation of lepton universality (Strengthened hints for a violation of lepton universality in B decays) [article](https://arxiv.org/abs/2103.11769)




<!--


## Goals of the course:
   I. Introduction to experimental particle physics. <br>
   II. Study of charm or beauty meson decays in the LHCb experiment with the use of real or simulated data. <br>
   III. Environment for daily work

### LHCb Experiment 
The LHCb (Large Hadron Collider beauty) experiment is one of the four main experiments that operate at the Large Hadron Collider (LHC) at CERN. The experiment is designed to study CP violation, observation of rare decays of beauty and charm particles, and search for New Physics (NP) evidences using indirect measurements. Whereas ATLAS and CMS are general-purpose detector with a broad physics programme spanning from the Standard Model (SM) though supersymmetry (SUSY) to extra dimensions, the LHCb detector is a single-arm forward spectrometer dedicated for studying flavour physics at the LHC. The LHCb programme is thus highly complementary to the direct searches performed at ATLAS and CMS. 

### D meson
D mesons contain charm quark. The lighter D<sup>+</sup> meson contains also one of the lightest quarks (up or down) whereas D<sub>s</sub><sup>+</sup> has a heavier strange quark. Decays of charm mesons involve the change of quark flavour through weak interaction. 

### Project 1: 3-body decay of D meson (real data)

### Project 2: D meson decays to three hadrons (simulated data)
1. Introduction:
   - study the channels of [D<sup>+</sup>](https://pdglive.lbl.gov/Particle.action?init=0&node=S031&home=MXXX035#decayclump_F) and [D<sub>s</sub><sup>+</sup>](https://pdglive.lbl.gov/Particle.action?init=0&node=S034&home=MXXX040#decayclump_A) decays and chose one that contains charge kaons or pions. 
   - draw Feynman diagram of your process and note whereas it is a common or rare decay (we call it favoured or suppressed decay). What type of interaction is responsible for this decay?
   - what information you need to obtain from experiment to observe your process?
2. Data anaysis:
   - study the data set (from AGH cloud, [check access to this site](https://dysk.agh.edu.pl/s/cQ6wLsdCxRjFpa4) ) <br> 
   It contains 160 000 simulated events of D<sup>+</sup> and D<sub>s</sub><sup>+</sup> decays to three hadrons (kaons and pions). 
   - Choose one mode of D meson decay, select candidates,
   - plot distribution of mass and life-time,
   - make fits and compare parameters with theory.

[1] LHCb Detector Performance, LHCb Collaboration, Roel Aaij et al. (Dec 19, 2014) [Int.J.Mod.Phys.A 30 (2015) 07, 1530022](https://arxiv.org/abs/1412.6352) <br>
[2] Hadron Collider Physics Summer School - [HASCO](http://hasco.uni-goettingen.de/)
-->  

# phys205-music-generation
PHYS205 Computational Physics Music Generation from Machine Learning Project
How to load libraries and other specifics to run the jupyter notebook:
- Open up anadonda powershell and use the "pip install" command to open the following libraries:
  - pyFluidSynth (Not "fluidsynth" this is a different library that will take priority over pyFluidSynth)
  - glob
  - seaborn
  - tensorflow
  - sklearn
  - keras
- You will also need to install the .dll file in this GitHub called "libfluidsynth.dll". This needs to go in your system32 folder (I know this sounds a little dodgy but it's required for the pyfluidsynth module to work properly.)
After this, the notebook should function.

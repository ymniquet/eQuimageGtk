### eQuimageGtk is a python tool (with a Gtk GUI) to postprocess astronomical images from Unistellar telescopes

Author: Yann-Michel Niquet (https://astro.ymniquet.fr)

### Note

***eQuimageGtk is not developed any more. See eQuimage for a general purpose module to postprocess astronomical images, and eQuimageLab for a Jupyter Notebook interface to eQuimage.***

### Installation

eQuimageGtk is developed in Python 3 with a GTK3 graphical user interface. Python 3 and the GTK3 library are available in all Linux distributions; on Windows, follow https://www.gtk.org/docs/installations/windows/ for GTK3. To install the latest version of eQuimageGtk, open a linux terminal/windows command prompt and run:

  `pip install --user eQuimageGtk`

pip will automatically download eQuimageGtk and the missing python modules if necessary (matplotlib, etc...). You can then launch eQuimageGtk by typing:

  `eQuimageGtk`

in this same terminal. You can also create a link to eQuimageGtk from your desktop; an icon is distributed for this purpose with the python package.

### Usage

This code has no claim and only offers elementary operations compared to other more advanced image processing or astrophotography software (GIMP, SIRIL, PixInsight, etc...). Among its specific features, eQuimageGtk can
  - highlight the pixels "blackened" or saturated by the treatments (in each R/G/B channel),
  - leave the frame of the Unistellar images unprocessed (option only implemented to date for the eQuinox 1 telescope, but feel free to contribute or send me sample images from other telescopes !),
  - compare different treatments to help choose the best options,
  - keep track (in a log file) of all operations applied to a given image.

There is no documentation yet, but you should find your way around easily if you have used image processing software before. The python code itself is documented in English.

### Known bugs


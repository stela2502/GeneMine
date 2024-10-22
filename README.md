# GeneMine is a Apptainer image definition

The image installs the iReads https://github.com/genemine/iread scripts.

# Build

To build that image yourself you can clone this repo and use the Makefile to build the image.

```
git clone https://github.com/stela2502/GeneMine.git
make -C GeneMine
```

You also could download the definition file and build you image using Apptainer.

# Usage on COSMOS-SENS

The image is currently installed on COSMOS-SENS and you can load it like that:


```
ml GeneMine/1.0
```

If that does not work you might need to activate the gr01 specific module path:

```
module use /scale/gr01/shared/common/modules
```

Best would be to add that to your .bashrc.

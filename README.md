# Fast Adaptive Blue Noise on Polygonal Surfaces

Research software by Esdras Medeiros, Lis Ingrid, Sinésio Pesco, and Claudio Silva, accompanying the Graphical Models (2014) paper.

- [Read the paper](paper/fastAdaptiveBlueNoise.pdf)
- [Download the original Linux distribution](https://github.com/esdrasmedeiros/fastAdaptiveBlueNoise/raw/refs/heads/main/downloads/fastAdaptiveBlueNoise.zip)
- [Watch the supplementary videos](videos/README.md)

## What is included

This repository preserves the original **Linux binary distribution**, sample surface, importance sampling data, and test script. The supplied archive did not contain the implementation’s source code.

- `main`: original precompiled Linux executable (14.04 LTS, according to the original Readme).
- `script_test`: original example script.
- `genus3.ply`: example surface.
- `genus3.obj.curveq.txt`: importance sampling data.
- `data/`: output directory structure expected by the script.
- `downloads/`: unchanged original ZIP archive.
- `videos/`: the two supplementary MP4 demonstrations.

## Original usage

From the repository root on a compatible Linux system:

```sh
./script_test
```

The script writes sampling results into `data/`. See the [original Readme](Readme) and the paper for parameter details. Compatibility with current systems has not been verified.

## Publication

Esdras Medeiros, Lis Ingrid, Sinésio Pesco, Claudio Silva. **Fast Adaptive Blue Noise on Polygonal Surfaces.** Graphical Models, 76(1), 17–29, 2014.

## Distribution notes

Files were migrated from the author’s academic website. No new license is assigned; the original archive did not include an explicit license file.

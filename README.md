# Experimental-data-from-the-anechoic-water-tank-at-Northwestern-Polytechnical-University-January-2025

NPU Anechoic Water Tank Dataset (January 2025)

Overview

This repository provides experimental underwater acoustic array data collected in January 2025 at the anechoic water tank of Northwestern Polytechnical University (NPU). The dataset was acquired for research on underwater acoustic signal processing, array processing, and direction-of-arrival (DOA) estimation.

Experimental Environment

The experiments were conducted in the anechoic water tank at Northwestern Polytechnical University. The tank dimensions are 20 m × 8 m × 7 m (length × width × height), with a water depth of 6.8 m. The facility is a vertical-wall reinforced concrete structure specifically designed for underwater acoustic experiments. To suppress acoustic reflections and approximate a free-field underwater environment, all six interior surfaces of the tank are uniformly covered with conical rubber wedge acoustic absorbing units.

Experimental Equipment

A sound source emitting a 3 kHz continuous-wave (CW) acoustic signal was employed during the experiments. The received signals were acquired using a 10-element piezoelectric uniform linear array (ULA) with an inter-element spacing of 0.25 m. The sampling frequency was set to 8 kHz.
Photographs of the experimental apparatus are provided in the Experimental Apparatus Images folder of this repository.
Dataset Description
During the experiments, the selected 10-element ULA was mounted on a moving platform and rapidly rotated, resulting in continuous variations of the target azimuth angle relative to the receiving array.
This repository contains three processed experimental datasets:
1. ExpArrayReceivedData_min07Degreeto10Degree.mat
The target azimuth angle varies continuously from −7° to 10°.
2. ExpArrayReceivedData_35Degreeto28Degree.mat
The target azimuth angle varies continuously from 35° to 28°.
3. ExpArrayReceivedData_min45Degreetomin35Degree.mat
The target azimuth angle varies continuously from −45° to −35°.
Each MATLAB data file contains processed array measurements with dimensions of 10 × 80000, where:
each row corresponds to one array element;
each column corresponds to one sampled time point.
The duration of each recorded dataset is 10 seconds.

File Format

All datasets are provided in MATLAB .mat format for convenient use in signal processing and array processing research.

Citation

If you use this dataset in your research, publications, or analyses, please cite the relevant papers published by the authors.

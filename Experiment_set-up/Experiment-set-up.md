## Sample Preparation

To prepare for the experiment, the alloys had to be cut and mounted. The V44 and V1515 samples came pre-made as buttons.
All preparation for the samples was performed in the Materials Micropreparation Laboratory at the University of Sheffield. 
The first V44 samples for Experiment 1 and Experiment 2 were halved on the Secotom 50 cutting machine, the V1515 sample, was cut on the Isomet 5000. 
All samples were mounted in conductive bakelite on the Simplimet Mounting Press 1000. 
They were then ground using standard micropreparation steps on the Automet 250, the final grinding value was to 1200 grit. 

## Design of Experiments (DOE)

To design an experiment which explores a range of the two variables, laser power and laser speed, a design of experiment (DOE) was employed. 
Using statistical software, Minitab 20, a DOE was created by inputting a maximum and minimum value for the laser speed and powers, in mm/s and Watts respectively. 
There are two main designs for the DOE, these are Box-Behnken and Central Composite designs. 
Central Composite design was employed as only two parameters were being varied. 
On the Minitab software, Central Composite was selected using a quadratic design with axial input of maximum and minimum values. 
The maximum and minimum input values for Minitab of the laser speed and power for the experiments are displayed below.

| Experiments   | Condition | Laser Speed (mm/s) | Laser Power (W) |
|---------------|-----------|--------------------|-----------------|
| Experiment 1  | Max       | 2000               | 390             |
|               | Min       | 500                | 150             |
| Experiment 2  | Max       | 1750               | 235             |
|               | Min       | 500                | 65              |
| Experiment 3  | Max       | 2000               | 390             |
|               | Min       | 500                | 150             |

## DOE Experiment 1 V44 alloy

The values for the DOE are based on the maximum and minimum operating values of the LPBF machine. 
This is the first experiment of its sort to be tested with the alloys, V44 and V1515, it is important to initially test a wide range of values to understand how the alloys are affected by the parameters.
The values created by the DOE for the initial experiment can be seen in [Design of Experiment with Power and Speed variables for Experiment 1 with V44 alloy](Melt_track_DoE_Experiment_1.png). 

## DOE Experiment 2 V44 alloy

Experiment 1 on V44 showed that the higher performance results were those of sample 1-9, which had a speed of 1250 mm/s and a power of 150 W, discussed further in [results](image_url). 
Experiment 2 was influenced by the higher performance outcomes observed in Experiment 1, the central values of Experiment 2 closely aligned with the optimal values identified in Experiment 1. 
For Experiment 2, two DOE's were created, one consisting of a larger range and another having a smaller range of values to hone in on the optimum conditions seen in Experiment 1. 
Both DOE's were centered around 150 W power and a 1125 mm/s speed. 
The DOE can be seen in [Design of Experiment with Power and Speed variables for Experiment 2 with V44 alloy](Melt_track_DoE_Experiment_2.png).

## DOE Experiment 3 V1515 alloy

Experiment 3 was designed with a smaller range, again influenced by the higher performance outcomes of Experiment 1. 
Experiment 3 tested the V1515 alloy, hence a larger range of values were used, similar to the initial values in Experiment 1 to test a higher range, with centre values of 270 W for laser power and 1250 mm/s for laser speed. 
An additional DOE was created with a smaller range, centered around the higher performance values derived from Experiment 1, with centre values of 185 W for laser power and 1125 mm/s for laser speed.
This is due to the likelihood that the V1515 alloy would yield similar outcomes to those of the V44 alloy in Experiment 1. 
The DOE can be seen in [Design of Experiment with Power and Speed variables for Experiment 3 with V44 alloy](Melt_track_DoE_Experiment_3.png).

## Experimental Procedure

The setup for each experiment remained consistent, with the primary difference being the adjustment of laser speed and power, as well as the testing of the V1515 alloy in Experiment 3, compared to the V44 alloy tested in Experiments 1 and 2. The hatch spacing, set to 0.3 mm.
For Experiment 1, both single and hatch melt tracks were tested. Given the early stage of the testing and lack of data on vanadium alloy melt tracks, both approaches were tested to gain comprehensive data and to determine the most suitable technique for understanding the effect of laser parameters on the alloys. 
The orientation of the melt tracks can be seen [Melt track orientation with single tracks and hatch sections, with d showing the distance between sections and w showing the section width.]()

The fixed parameters are detailed below:

| Fixed Parameters                 | Value   |
|----------------------------------|---------|
| Number of track tests            | 20      |
| Track Type                       | Single, Hatch |
| **Single track**                 |         |
| Track length (mm)                | 5       |
| Distance between tracks (mm)     | 0.85    |
| Number of tracks                 | 10      |
| Number of centre repeats         | 1       |
| **Hatching**                     |         |
| Hatch length (mm)                | 5       |
| Hatch spacing (mm)               | 0.03    |
| Hatch section width, w (mm)      | 0.75    |
| Distance between sections, d (mm)| 0.85    |
| Hatches per section              | 25      |
| Number of sections               | 10      |
| Number of centre repeats         | 1       |

When mounting the V44 sample in the Aconity machine, the sample was secured onto the base plate using tack, and levelled with a spirit level. A dry run was completed to visually assess where the laser track would fall on the sample using the laser guide, this was to ensure that the laser did not hit the bakelite and remained on the alloy. The chamber was flushed with Argon to create an inert gas environment and reduce possible oxidation. The standard practice for this Aconity machine is to start at 1000 ppm Oxygen, however vanadium is a highly oxidative material, hence the experiment did not begin until the Oxygen concentration in the chamber was below 500 ppm.

The test parameters for Experiment 1 are shown below:

| Single track ref | Hatching ref | Power (W) | Speed (mm/s) |
|------------------|--------------|-----------|--------------|
| line 1           | 1            | 185.1471863 | 1780.330086 |
| line 2           | 2            | 270       | 1250         |
| line 2.2         | 2            | 270       | 1250         |
| line 3           | 3            | 185.1471863 | 719.6699141 |
| line 4           | 4            | 270       | 2000         |
| line 5           | 5            | 354.8528137 | 1780.330086 |
| line 6           | 6            | 354.8528137 | 719.6699141 |
| line 7           | 7            | 390       | 1250         |
| line 8           | 8            | 270       | 500          |
| line 9           | 9            | 150       | 1250         |


## Experiment 2 and 3

The setup methodology for Experiment 2 and 3 closely resembled that of Experiment 1, with slight variations in fixed parameters. Notably, only hatching tracks were tested, as single tracks gave insignificant results from Experiment 1.
To optimise time and machine efficiency, Experiment 2 and Experiment 3 were performed at the same time on the LPBF machine. Both the V44 and V1515 samples for Experiment 2 and 3 had two available samples to use. An operational glitch occurred during the initial run and performed the melt tracks twice for the V1515 alloy and a misalignment occurred leading to the melting of the bakelite during the V44 alloy run. Consequently, the second sample set for these alloys was used.

The fixed parameters are detailed below:

|                            | Experiment 2 | Experiment 3 |
|----------------------------|--------------|--------------|
| **Fixed Parameters**       | **Value**    | **Value**    |
|----------------------------|--------------|--------------|
| Number of track tests      | 17           | 18           |
| Track Type                 | Hatch        | Hatch        |
| **Hatching**               |              |              |
| Hatch length (mm)          | 5            | 5            |
| Hatch spacing (mm)         | 0.03         | 0.03         |
| Hatch section width, w (mm)| 0.75         | 0.75         |
| Distance between sections, d (mm) | 0.35  | 0.3          |
| Hatches per section        | 25           | 25           |
| Number of sections         | 17           | 18           |
| Number of centre repeats   | 0            | 0            |

The test parameters for Experiment 2 are shown below: 

| Track Ref number | Power (W) | Speed (mm/s) |
|------------------|-----------|--------------|
| "2-1"            | 65        | 1125         |
| "2-2"            | 90        | 683          |
| "2-3"            | 90        | 1567         |
| "2-4"            | 90        | 1125         |
| "2-5"            | 108       | 1390         |
| "2-6"            | 108       | 860          |
| "2-7"            | 150       | 500          |
| "2-8"            | 150       | 750          |
| "2-9"            | 150       | 1125         |
| "2-10"           | 150       | 1750         |
| "2-11"           | 150       | 1500         |
| "2-12"           | 192       | 860          |
| "2-13"           | 192       | 1390         |
| "2-14"           | 210       | 683          |
| "2-15"           | 210       | 1567         |
| "2-16"           | 210       | 1125         |
| "2-17"           | 235       | 1125         |

The test parameters for Experiment 3 are shown below: 

| Track Ref number | Power (W) | Speed (mm/s) |
|------------------|-----------|--------------|
| "3-1"            | 100       | 1125         |
| "3-2"            | 125       | 1567         |
| "3-3"            | 125       | 683          |
| "3-4"            | 150       | 1250         |
| "3-5"            | 185       | 500          |
| "3-6"            | 185       | 1125         |
| "3-7"            | 185       | 1750         |
| "3-8"            | 185       | 1780         |
| "3-9"            | 185       | 720          |
| "3-10"           | 245       | 683          |
| "3-11"           | 245       | 1567         |
| "3-12"           | 270       | 1250         |
| "3-13"           | 270       | 500          |
| "3-14"           | 270       | 1125         |
| "3-15"           | 270       | 2000         |
| "3-16"           | 355       | 1780         |
| "3-17"           | 355       | 720          |
| "3-18"           | 390       | 1250         |


## Preparation for Analysis

After completing the experiments, the samples required preparation for optical imaging and Scanning Electron Microscopy (SEM) analysis. Top-view optical imaging could be performed immediately following the melt track experiments, requiring no additional preparation. However, for cross-sectional views of the melt tracks, the samples were bisected along the center of the melt tracks using the Isomet 5000. They were then removed from the previous bakelite mount and re-mounted in conductive bakelite, with the top of the sample as the cross-section using the Simplimet Mounting Press 1000. \\

To correlate the sample surface with their respective melt tracks, each half of the bisected samples was mounted together in a PAC-man configuration. The samples were then subjected to grinding and polishing on the Automet 250 using standard micropreparation practices, with a surface finish of 0.05 μm Colloidal Silica.

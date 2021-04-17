
Edit this file to describe how to retrieve the data set. Except for very small data files, it's not recommended to check data into version control.

Mouse LGN Orientation Selectivity

These files contain the spiking responses of LGN neurons in the mouse to drifting gratings.  Each file contains the spiking responses and stimulus specifications for a single neuron.

These files are in the Matlab format.  Loading one in MatLab will bring a structure called mlgn into MatLab's memory.  The structure has two elements:

spktimes: MxNxT size array, where M is the stimulus number, N is the repeat number and T is time in milliseconds.  Value of 1 in the array indicates a spike.  Value of 0 indicates no spike.  The order of the presentation of the stimulus repeats is not provided.

stim:	M size array, where M is the number of stimulus conditions.
stim for this dataset indicates the contrast used, spatial frequency, temporal frequency, stimulus duration (in seconds), prestimulus duration, poststimulus duration, the original scanrate, orientation, and whether muscimol was present in V1.

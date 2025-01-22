# BCI_Tools
A repository for tools in BCI research.

## EEG_Preprocessor

Currently, this produces a list of MNE raw objects from a range of file types. This includes gdf, fif and .mat files, but .mat files must have conventionally named titles e.g. "channel names", "sampling frequency", "channel types". Some leeway is given using regular expressions.

Next, you can select to add a bandpass filter to your desired EEG files.

To view a processed signal, you can select an EEG file from a dropdown menu and run the plot cell.

To use it, create a folder "eeg_data", or run the corresponding block. Next, add your chosen EEG files into the folder and run the code, following the notebooks instructions.

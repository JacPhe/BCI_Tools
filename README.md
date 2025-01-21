# BCI_Tools
A repository for tools in BCI research.

EEG_Preprocessor:

Currently, this produces a list of MNE raw objects from a range of file types. This includes gdf, fif and .mat files, but .mat files must have conventionally named titles e.g. "channel names", "sampling frequency", "channel types". Some leeway is given using regular expressions.

# processed
Folder for processed data files.
## flu_csv
folder to contain zipped files of influenza_outbreak_dataset.mat to csv; aside from format conversion, no further processing has taken place on these files.


## state_data.zip
some further processing of influenza_outbreak_long.csv, completed by Lachlan Fox: data is broken up by state and 'location', 'split' and 'time_index' columns are removed.

## ak_flucsv_combined.zip
Small amount of further processing of data contained within ak_flucsv.zip, completed by Amelia King: data is fully separated by original test and train split; all features within X-matrices (from influenza_outbreak_dataset.mat) are kept.

# Useful Scripts: OPC data handling

Version of this script: v07 (last update: 25 November 2020)

Author: Nuno Canha

# Goal of the script:
This script aims to calculate the particle's concentration from their number concentration. Original file is a database with particle counts (obtained from an optical particle count - OPC, namely, N2 from Alphasense - in the Black & Bloom campaign in 2016), with 16 different bins of particle's sizes.

The output of script provides:
- Plot of particle number concentrations in different bins
- Plot of particle number concentrations considering 6 integrated bins
- Plot of particle mass concentrations considering 6 integrated bins
- Plot of particle mass concentration for particles with diameter equal to 2.55 micrometers (as an example)
- database with all the data (averaged to 1 hour frequency) for number and mass concentrations - csv file
- database with hourly data for the 6 integrated bins

Remarks: This script focus on the data treatment of OPC data from 2016 (B&B) and it provides an update for stacked bar plot (or area plot, in this case).

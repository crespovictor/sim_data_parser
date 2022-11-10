# sim_data_parser
Python Script to parse the data from LGSVL simulation

## How to run data_parser
1. Copy `data_parser.py` to the `/simulation` folder in the outputs directory of AV-Fuzzer and/or random_testing. Example: `random_testing/outputs/ds_1_v2-at-11-08-2022-15-58-42/simulation`
2. In `data_parser.py` modify the number of scenarios to the number of objects in each of the subfolders in `/simulation`
3. Run `python3 data_parser.py`

## Known issues:
- Acceleration is not realistic: Will probably need to take a look at how it is calculated, and come up with a different way of calculating it.
- The script could automatically look at the number of objects present in each subdirectory without the need for manually specifying it.
- The number and name of features could be expanded

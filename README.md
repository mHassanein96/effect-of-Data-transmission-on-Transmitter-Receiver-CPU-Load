# Hardware Testing Project: Effect of Data transmission on both Transmitter and Receiver CPU Load
We made experiment by transmit artificial data between two points with distance of 100m and applied many transmission settings manually over several time periods (each period represent different settings) details of transmission settings can be found in the settings.json file

We extracted CPU usage and throughput and datetime metrics from transmission points pcap tracefile with tcpstat of 1 second sampling rate

We are going to do analysis and generate 3 plots from the throughput and 2x cpu load time series data, that are stacked over each and do show a Box-Whisker over time with 10s or 20s datapoints binned together. with vertical lines indicates different settings time periods.

### Built With
+ **R**
+ **ggplot2** - a system for declaratively creating graphics, based on The Grammar of Graphics.
+ **reshape2** -  allows us to easily transform our data into whatever structure we may need, can work on matrix/array, so that corresponds to a single participant and each column corresponds to a variable.
+ **rjson** - A C based JSON parser for R.

## Effect of Data transmission on both Transmitter and Receiver CPU Load Analysis Project:
### access [Full project HERE!](https://github.com/mHassanein96/effect-of-Data-transmission-on-Transmitter-Receiver-CPU-Load/blob/4ac42219a098e192d4bc41e18e31588483e5b077/IT_TxRx_Analysis.ipynb)

![image](https://github.com/mHassanein96/effect-of-Data-transmission-on-Transmitter-Receiver-CPU-Load/assets/133708970/64bb1abf-5776-4b93-8dc7-146bad97081c)


#### Credits
Experiment (Installing, operating, Providing PCAP tracefile) parts done by: Nordhausen Applied University **Prof. Dr.-Ing. Thomas Hühn**

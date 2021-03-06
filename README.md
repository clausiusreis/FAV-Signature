# FAV-Signature
[Implementation](https://github.com/clausiusreis/FAV-Signature/tree/master/Code) of the FAV and DEMON Signatures for boat detection, comparison code and [samples](https://github.com/clausiusreis/FAV-Signature/tree/master/Code/samples) used on the paper can be found on [Code folder](https://github.com/clausiusreis/FAV-Signature/tree/master/Code).

## 24h Spectrogram of analysed period (2015.02.19)
![alt text](https://github.com/clausiusreis/FAV-Signature/blob/master/24hSpectrogram/SpecPeriod_2015.02.19.png?raw=true)

[24H Spectrogram from 2015-02-19 00:01:22 to 2015-02-20 00:06:56](https://github.com/clausiusreis/FAV-Signature/blob/master/24hSpectrogram/SpecPeriod_2015.02.19.png) showing only frequencies up to 1kHz. 

## Sample analysis
[Images for each of the 1440 sample analysis](https://github.com/clausiusreis/FAV-Signature/tree/master/DetectionImg) of the 24h Spectrogram, showing only frequencies up to 1kHz. The original audio files for the 1440 samples are located on the [Dataset_2015.02.19 folder](https://github.com/clausiusreis/FAV-Signature/tree/master/Dataset_2015.02.19)

The name pattern for the files is: **year.month.day_hour.minute.second_M0.png** where **M0** is the minute of the file (M0 = minute 0, M1 = minute 1, ...). 

For example: The image bellow of the file **2015.02.19_00.01.22_M10.png.png** corresponds to February 19, 2015, where the recording (Minute 10) started at 00:11:22 and ended at 00:12:22, corresponding to file time 00:01:22 plus 10 and 11 minutes respectively.

![alt text](https://github.com/clausiusreis/FAV-Signature/blob/master/DetectionImg/2015.02.19_00.01.22_M10.png?raw=true)

For the one-minute sample spectrogram (Right) two peaks related to the presence of boats were detected using the FAV signature (Red watermark), where only one peak was detected using the DEMON square-law implementation (Black dots)

## Acknowledgements
The authors acknowledge the financial support of the São Paulo State Research Foundation (FAPESP grants 2017/05838-3 and 2016/02175-0) and the National Council for Scientific and Technological Development (CNPq grant 301847/2017-7). The views expressed do not reflect the official policy or position of either FAPESP or CNPq.

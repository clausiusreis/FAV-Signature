# FAV-Signature
Implementation of the FAV and DEMON Signatures for boat detection.

## 24h Spectrogram
![alt text](https://github.com/clausiusreis/FAV-Signature/blob/master/24hSpectrogram/SpecPeriod_2015.02.19.png?raw=true)

[24H Spectrogram from 2015-02-19 00:01:22 to 2015-02-20 00:06:56](https://github.com/clausiusreis/FAV-Signature/blob/master/24hSpectrogram/SpecPeriod_2015.02.19.png) showing only frequencies up to 1kHz. 

## Sample analysis
[Images for each of the 1440 sample analysis](https://github.com/clausiusreis/FAV-Signature/tree/master/DetectionImg) of the 24h Spectrogram, showing only frequencies up to 1kHz. 

The name pattern for the files is: **year.month.day_hour.minute.second_M0.png** where **M0** is the minute of the file (M0 = minute 0, M1 = minute 1, ...). 

For example: The image bellow of the file **2015.02.19_00.01.22_M10.png.png** corresponds to February, 19 of 2015 where the recording started at 00:11:22 and ended at 00:12:22 (Minute 10)

![alt text](https://github.com/clausiusreis/FAV-Signature/blob/master/DetectionImg/2015.02.19_00.01.22_M10.png?raw=true)

For the one-minute sample spectrogram (Right) two peaks related to the presence of boats were detected using the FAV signature (Red watermark), where only one peak was detected using the DEMON square-law implementation (Black dots)

## Acknowledgements
The authors acknowledge the financial support of the São Paulo State Research Foundation (FAPESP grants 2017/05838-3 and 2016/02175-0) and the National Council for Scientific and Technological Development (CNPq grant 301847/2017-7). The views expressed do not reflect the official policy or position of either FAPESP or CNPq.

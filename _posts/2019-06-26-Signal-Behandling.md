---
title: Signal Behandling
published: true
---



**An illustrated post going into different types of signal processing filters, and how they can be useful for analyzing signals.**

# [](#header-1)Filtre

For this project we chose to use Butterworth filters. Butterworth filter is a type of signal processing filter that is designed to have as flat frequency response as possible, and this type of filter is commonly referred to as maximally flat magnitude filter. All the examples below are made with this type of filter. The reason Butterworth filters were chosen over other types of filters are that Butterworth filters are designed to have as flat of a frequency response as possible. This leads to a slower roll off around the cut-off frequency, but eliminates ripples in stopband and the passband of the signal which other types of filters often produce. It also seems to be the default filter type used in popular applications used to visualize signals, which helped in making the decision on which type of filters to focus on.

Other common types of filters:

* Chebyshev type 1:  has a steeper rolloff and more passband ripples
* Chebyshev type 2:  has a steeper rolloff and more stopband rippes
* Elliptic:  has a steeper rolloff and more ripples in both the passband and stopband

## [](#header-2)High-Pass Filter

High pass filter is an electronic filter which lets through signals with higher frequency than a certain cutoff frequency, and dampens or attenuates signals with a frequency lower than the cutoff frequency.

The image below contains the output from our HighPass filter 


### [](#header-3)Low-Pass Filter

Low pass filter is an electronic filter that passes signals with a lower frequency than a certain cutoff frequency, and dampens or attenuates signals with a frequency higher than the cutoff frequency.

The image below contains the output from our LowPass filter

#### [](#header-4)Band-Pass Filter

BandPass filter is a filter that passes frequencies within a specific certain range, and rejects frequencies outside that specific range.

The image below contains the output from our BandPass filter

##### [](#header-5)Band-Stop Filter

BandStop filter is a filter that attenuates frequencies inside of a certain range, but passes all other frequencies. It is the opposite of a BandPass filter that passes the frequencies within the range while rejecting the frequencies outside of the range.

The image below contains the output from our Band-Stop filter 

###### [](#header-6)Other signal variables

Apart from applying filters on signals, the visual output can be affected by manipulating other variables, such as the amplitude, phase, offset and frequency of a signal. Changing some of these variables can alter the information that the signal is supposed to convey, but in some situations it can help extract information from them or make them more readable. Example of such cases could be adjusting the offset when signals are crowded to make them stand out more or adjusting the amplitude to make minor fluctuations more visible.


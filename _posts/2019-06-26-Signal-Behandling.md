---
title: Signal Behandling
published: true
---

# [](#header-1)Signal Behandling og Filtre

**An illustrated post going into different types of signal processing filters, and how they can be useful for analyzing signals.**

# [](#header-2)Filtre

For this project we chose to use Butterworth filters. Butterworth filter is a type of signal processing filter that is designed to have as flat frequency response as possible, and this type of filter is commonly referred to as maximally flat magnitude filter. All the examples below are made with this type of filter. The reason Butterworth filters were chosen over other types of filters are that Butterworth filters are designed to have as flat of a frequency response as possible. This leads to a slower roll off around the cut-off frequency, but eliminates ripples in stopband and the passband of the signal which other types of filters often produce. It also seems to be the default filter type used in popular applications used to visualize signals, which helped in making the decision on which type of filters to focus on.

Other common types of filters:

- Chebyshev type 1 – has a steeper roll-off and more passband ripples
- Chebyshev type 2 – has a steeper roll-off and more stopband rippes
- Elliptic – has a steeper roll-off and more ripples in both the passband and stopband
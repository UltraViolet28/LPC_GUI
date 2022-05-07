# LPC_GUI

Linear predictive coding (LPC) is a widely used technique in audio signal processing, especially in speech signal processing. It has found particular use in voice signal compression, allowing for very high compression rates.

The original objective of LPC was to model human voice production. LPC is a source-filter model in that there is a sound source that goes through a filter. The source, e(n), models the vocal chords, while the resonant filter, h(n), models the vocal tract. The resulting signal is,

x(n)=h(n)∗e(n)

There are two possible signals for the source: an impulse train or random white noise. These signals model pitched sounds and plosive/fricatives respectively. The common characteristic for both impulse train and white noise is that they are spectrally flat; all spectral information is modeled in the filter. The keen reader will notice the source signal is labeled e(n) . This was chosen so for reasons to be revealed in the following sections.

LPC assumes the filter is a p-th order all-pole filter. Though not physiologically exact, it provides an extendable method for modeling resonances. This also allows for a tractable solution when estimating h(n) from x(n), which we will cover in §4.

Though initially developed for speech signals, the assumption of a spectrally flat source signal and a resonant filter applies well to modeling signals from most tonal instruments as well as many naturally occuring sounds.

Refer the following report for more information on LPC

https://ccrma.stanford.edu/~hskim08/lpc/ 

# GUI

The GUI is designed using MATlAB App Designer.

![WhatsApp Image 2022-04-22 at 7 19 01 PM](https://user-images.githubusercontent.com/88196192/167246110-5b41b928-d8b1-405f-8050-48dee56405cd.jpeg)


# Dependencies
- MATLAB
- Signal Processing Toolbox in MATLAB


# Results

### Pitch Plots for Differents Windows

### Pitch Plots for Different Filter Orders

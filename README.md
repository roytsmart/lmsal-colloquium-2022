# A Convolutional Neural Network for Inverting Observations from the EUV Snapshot Imaging Spectrograph

Roy T. Smart, Charles C. Kankelborg, and the ESIS Team

My colloquium at the Lockheed Martin Solar and Astrophysics Laboratory on
August 18, 2022.

## Abstract

Imaging spectroscopy of the solar atmosphere, with high spatial, spectral, and
temporal resolution over a wide field of view, is a longstanding goal of
heliophysics since it allows for the measurement of important plasma
parameters, such as velocity and density, with high fidelity. The EUV Snapshot
Imaging Spectrograph (ESIS) is a sounding rocket instrument designed to capture
EUV spectral line profiles over a large, 2D field of view with much higher
temporal resolution than current rastering slit spectrographs. ESIS achieves
this by using a computed tomography imaging spectrograph design with four
channels. Each channel is an independent slitless spectrograph fed by a common
primary mirror, but oriented with a unique dispersion direction. Each ESIS
exposure, comprising four images, can be inverted to recover spectral line
profiles for every point in the field of view using limited-angle computed
tomography techniques. In this work, we present a convolutional neural network
that has been trained to solve the ESIS limited-angle tomography problem using
data from the Interface Region Imaging Spectrograph (IRIS) as a training
dataset. We will evaluate the performance of this solution and compare it to
other methods that have been used for ESIS inversions.

## The slides on the web

https://roytsmart.github.io/lmsal-colloquium-2022/ shows the slides with their
movies playing and the speaker notes under each one. It is built from the deck
with [pptx-to-html](https://github.com/roytsmart/pptx-to-html):

```bash
pptx-to-html lmsal_colloquium_2022-08-18_smart.pptx docs \
    --title "A Convolutional Neural Network for Inverting Observations from the EUV Snapshot Imaging Spectrograph" \
    --subtitle "Colloquium · Lockheed Martin Solar and Astrophysics Laboratory · August 18, 2022" \
    --notes
```

## The deck

The deck as it was given, in the
[ESIS repository](https://github.com/Kankelborg-Group/ESIS)'s
`esis/science/colloquia/year_2022/lmsal/presentation/` folder, is 433 MB, and
links to most of its animated GIFs on the computer it was made on rather than
embedding them. The deck here has each animated GIF replaced by an embedded
H.264 movie that starts with its slide and loops, as the GIF did, and its
linked photo embedded, taking it to 47 MB.

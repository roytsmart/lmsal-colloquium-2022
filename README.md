# A Convolutional Neural Network for Inverting Observations from the EUV Snapshot Imaging Spectrograph

Roy T. Smart, Charles C. Kankelborg, and the ESIS Team

My colloquium at the Lockheed Martin Solar and Astrophysics Laboratory on
August 18, 2022.

## The slides on the web

https://roytsmart.github.io/lmsal-colloquium-2022/ shows the slides with their
movies playing and the speaker notes under each one. It is built with
[pptx-to-html](https://github.com/roytsmart/pptx-to-html) from the deck, which
is not kept here: at 433 MB it is far over GitHub's limit for a single file,
and it links to most of its animations rather than embedding them. The deck is
in the [ESIS repository](https://github.com/Kankelborg-Group/ESIS)'s
`esis/science/colloquia/year_2022/lmsal/presentation/` folder, and the
animations it links to are in KSO's
`kso/science/authors/smart/colloquia/msfc_2019/figures/` folder, on the
computer it was made on:

```bash
pptx-to-html lmsal_colloquium_2022-08-18_smart.pptx docs \
    --title "A Convolutional Neural Network for Inverting Observations from the EUV Snapshot Imaging Spectrograph" \
    --subtitle "Colloquium · Lockheed Martin Solar and Astrophysics Laboratory · August 18, 2022" \
    --relink "C:/Users/royts=C:/Users/byrdie" \
    --reencode \
    --notes
```

`--relink` finds the animations under the folders they moved to, and
`--reencode` turns them into movies: about 1.4 GB of animated GIFs becomes
33 MB.

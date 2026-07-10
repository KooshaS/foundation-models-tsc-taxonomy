# A System-Driven Taxonomy of Foundation Models for Time Series Classification

**Author:** Koosha Sadeghi

## Abstract

Foundation models (FMs) have arrived in the time series domain with remarkable speed, but overwhelmingly in pursuit of forecasting, and existing surveys treat classification as just one downstream task among many. We argue that time series classification (TSC) deserves analysis on its own terms. Whereas forecasting is generative, classification is discriminative, with different constraints: a pre-trained representation must be reduced to a label under severe label scarcity, and the model must run wherever decisions are made, from cloud services to embedded sensors and wearables. These are questions of adaptation and deployment, not merely of pre-training.

We present a system-driven account of foundation models for TSC, organized around four groups that specify any such model: **design**, **scale**, **interface**, and **deployment**. Read as a taxonomy, these groups expose the choices that determine whether a model can effectively serve as a classifier. Within the design group, we isolate a three-level hierarchy—**source modality → pre-training objective → architecture**—and use it to position more than forty representative models within a unified framework.

Our analysis reveals that pre-training is heavily concentrated in time-series-native models, Transformers dominate the architectural landscape, adaptation for classification lags behind forecasting, and compact models such as **TSPulse** now match or surpass substantially larger models on classification tasks. These findings suggest that the field's strong emphasis on scale is partly misplaced for TSC. Finally, we present a system-driven decision framework that maps practical constraints—including input dimensionality, label budget, and hardware target—to appropriate regions of the taxonomy. This is a position-and-survey paper whose primary contribution is the organizing framework rather than new empirical results.

## Paper

## Paper

📖 [Read online (PDF)](https://github.com/KooshaS/foundation-models-tsc-taxonomy/blob/main/tsc_fm_taxonomy.pdf)

⬇️ [Download PDF](https://github.com/KooshaS/foundation-models-tsc-taxonomy/releases/download/v1.0.1/tsc_fm_taxonomy.pdf)

## DOI

[https://doi.org/10.5281/zenodo.21195950](https://zenodo.org/records/21301165)

## Citation

Please cite this work using the Zenodo DOI above.

Suggested citation (IEEE):<br>
K. Sadeghi, A System-Driven Taxonomy of Foundation Models for Time Series Classification, Zenodo, 2026. doi:10.5281/zenodo.21195949.

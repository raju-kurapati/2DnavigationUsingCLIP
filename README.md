# Leveraging CLIP for Zero Shot 2D Grid Navigation

In today’s space of deep learning, the number of parameters,
input and the length of time that is required to train models are growing
rapidly. Likewise, to establish top of the line results with reinforcement
learning, we must run tens of thousands to millions of simulations. Al-
though impressive results are being gained from these, at some point the
models will need to be fine tuned to be more accurate using less data.
At the same time, the true and inherent capabilities of a model are not
being explored as much when compared to creating new models and fine
tuning them. Lately, zero-shot models have exhibited outstanding per-
formance in image classification of arbitrary objects (i.e., categorizing
photos at inference using categories not explicitly encountered during
training). We apply the success of the CLIP model to the embodied AI
challenge of 2-D object navigation in this study. Though CLIP has been
used as a part of the architecture in various 3-D Object Navigation Tasks
(on Habitat and RoboTHOR) and it was able to achieve SOTA results
in various downstream tasks like Object Goal Navigation, Room Rear-
rangement and Point Goal Navigation, no work has been done on using
only CLIP in zero shot, with no training for object Navigation Tasks.
We hypothesize that with no additional training and in zero shot, CLIP
embeddings are powerful enough for Object Navigation Tasks. To this
end, we explore the above hypothesis in a 2D environments like gSCAN
and BabyAI.

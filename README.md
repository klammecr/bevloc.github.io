# BEVLoc: Off-Road Aerial-to-Ground Localization and Matching via Birds-Eye-View Synthesis

## Abstract:
Ground to aerial matching is a crucial and challenging task in outdoor robotics, particularly when GPS is absent or unreliable. Structures like buildings or large dense forests create interference, creating necessity for novel approaches for global positioning estimates. The true difficulty lies in reconciling the perspective difference between the ground and air images for acceptable localization.

Previous works in this area predominantly focus on cross-view image synthesis, global descriptor learning, or leveraging non-vision modalities to better bridge the domain gap. Additionally, these works often concentrate on on-road datasets with richer semantic content. In contrast, our work shifts the focus to difficult off-road datasets.

Taking inspiration from the autonomous driving community, we propose a novel framework for synthesizing a birds-eye-view (BEV) scene representation to match and localize within an aerial map. We leverage contrastive learning with domain specific hard netgative mining to train a network to learn similar representations between the synthesized BEV and the aerial map.

During inference, it guides the identification of the most probable locations within the aerial map through a coarse-to-fine matching strategy. Our results demonstrate promising initial outcomes in extremely difficult forest environments with limited semantic diversity. We analyze both global and local matching for scenarios where GPS data is completely absent and when GPS data is intermittently available , respectively.

Our work serves as an initial exploration into off-road map localization while establishing a foundational baseline for future developments in localization.

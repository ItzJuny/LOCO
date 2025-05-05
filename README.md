# LOCO
[Weakly-supervised Audio Temporal Forgery Localization via Progressive Audio-language Co-learning Network]

**Authors**: Junyan Wu, Wenbo Xu, Wei Lu (Corresponding author), Xiangyang Luo, Rui Yang, Shize Guo.

LOCO adopts co-learning and self-supervision manners to prompt localization performance under weak supervision scenarios. 
Specifically,  an audio-language co-learning module is first designed to capture forgery consensus features by aligning semantics from temporal and global perspectives. In this module, forgery-aware prompts are constructed by using utterance-level annotations together with learnable prompts, which can incorporate semantic priors into temporal content features dynamically. In addition, a forgery localization module is applied to produce forgery proposals based on fused forgery-class activation sequences. Finally, a progressive refinement strategy is introduced to generate pseudo frame-level labels and leverage supervised semantic contrastive learning to amplify the semantic distinction between real and fake content, thereby continuously optimizing forgery-aware features.

![framework](./fig/framework.jpg)


**Code and model weights will be made available soon.**

# ViGOR: Visual Attention-Guided Dual-Stream Model for Engagement Recognition

### Full Implementation will be released after paper acceptance

User engagement is a critical metric for adaptive learning systems and intelligent machines. **ViGOR** is a deep learning framework designed to predict engagement levels by analyzing visual cues.

We hypothesize that eye gaze is a distinct and crucial signal for identifying engagement. To leverage this, ViGOR utilizes a **dual-stream architecture** that integrates:
1. **Patchwise global features:** Extracted from the full input frame to capture general context.
2. **Gaze-specific representations:** Extracted from cropped eye regions to capture focused attention.

Evaluated on the **EngageNet** and **DAiSEE** datasets, our experiments demonstrate that fusing global visual data with targeted gaze cues significantly outperforms unimodal approaches. ViGOR offers competitive performance with state-of-the-art models while prioritizing interpretability and contextual understanding.

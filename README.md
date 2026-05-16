Adversarial patch attacks can significantly degrade the performance of object detection
models by introducing localized perturbations in an image. In this project, we implement
Patch-Agnostic Defense (PAD), a training-free defense method for detecting and remov-
ing adversarial patches without prior knowledge of attack type or patch characteristics.
The method uses two key properties of adversarial patches: semantic independence, mea-
sured using mutual information between neighboring regions, and spatial heterogeneity,
identified through recompression-based image analysis. The generated localization maps
are fused, refined using morphological operations and Segment Anything Model (SAM),
and used to remove patch regions. Experiments were conducted on adversarially patched
images using multiple object detectors, including Faster R-CNN, YOLO, and DETR. Re-
sults show that the implemented PAD framework effectively localizes adversarial patches
and improves detection robustness against diverse patch attacks.

Contributors:
Aniket Hinge
Riya S Huddar

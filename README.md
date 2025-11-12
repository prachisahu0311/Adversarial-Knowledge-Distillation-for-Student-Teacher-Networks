# Adversarial-Knowledge-Distillation-for-Student-Teacher-Networks
– Designed two compact student models (Student20 with ∼20% parameters and Student50 with ∼50% parameters
of teacher ResNet-34) for efficient knowledge distillation.
– Integrated a generator network to create synthetic 32×32 images (upsampled to 224×224) for data-free adversarial
training in the absence of real training data.
– Evaluated student models on CIFAR-100 test splits (10 20), achieving up to 13.65accuracy, and analyzed trade-offs
between model capacity and performance.
– Here implement adversarial knowledge distillation, optimize training stability (gradient clipping, cosine annealing),
and assess synthetic image quality.
– Tools: Pytorch, OpenCV etc.

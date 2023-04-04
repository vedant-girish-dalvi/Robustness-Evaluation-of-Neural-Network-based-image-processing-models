# Robustness-Evaluation-of-neural-network-based-image-processing-models

Image processing is one of the most important areas of artificial intelligence. In the
industrial context, object localization and classification play an important role for
applications in robotics and safety systems. State-of-the-art for these tasks are various
forms of neural networks. Due to the high-dimensional data space of images and the
data-based learning methods, it is particularly challenging to determine the exact
reliability of such systems. For this purpose, more comprehensive scenarios can be
represented and tested by various forms of augmentation and modification of a test
data set. Consequently, such test data sets allow the computation of more reliable
metrics for error rates and robustness of the AI system.

The task of this work is to implement an evaluation stage in an existing test tool for
image processing models. Input data of the evaluation stage are
- Either (for external faults):
 a trained neural network
 a clean test data set
 a corrupted data set
- Or (for internal faults):
 A trained corrupted network
 A clean test data set
The goal of the evaluation stage is to apply the AI models to the test data and to
compute, compare, and display various meaningful metrics from that.
In general, two types of evaluation should be considered:
1. Evaluation of error resilience / robustness of one network
The aim of this evaluation is to analyze how one architecture performs
when facing different fault types.
2. Comparison of error resilience / robustness among different architectures
The following steps are to be worked on:
- Literature research on suitable test metrics for measuring error rates and robustness
in image processing
- Implementation of the test process for both test data sets and several AI models
- Implementation of computation, output and display of selected test metrics
- Graphical representation of test metrics for different AI models in comparison plots
- Optional: Implementation of a Graphical User Interface (GUI) to start the test functions
and to meaningfully display the metrics and comparison plots

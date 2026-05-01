---
layout: post
title: Speakers
---

<h1>Speakers</h1>

<style>
    .speakers-table {
        width: 100%;
        border-collapse: collapse;
        font-family: Arial, sans-serif;
    }

    .speakers-table td {
        padding: 20px;
        vertical-align: top;
        border-bottom: 1px solid #e0e0e0;
        font-size:16px;
    }

    .speaker-image {
        width: 120px;
        padding-right: 20px;
    }

    .speaker-image img {
        width: 200px;
        height: 200px;
        border-radius: 50%;
        object-fit: cover;
        max-width: None;
    }

    .speaker-name {
        font-size: 1.3rem;
        font-weight: bold;
        color: #1a2a6c;
        margin-bottom: 5px;
    }

    .speaker-position {
        color: #b21f1f;
        font-style: italic;
        margin-bottom: 10px;
    }

    .talk-title {
        font-weight: bold;
        margin-bottom: 8px;
    }

    .talk-summary {
        color: #555;
        line-height: 1.5;
    }

    @media (max-width: 768px) {
        .speaker-image {
            width: 200px;
            padding-right: 15px;
        }

        .speaker-image img {
            width: 200px;
            height: 200px;
        }

        .speakers-table td {
            padding: 15px 10px;
        }
    }
</style>
<table class="speakers-table">
    <tr>
        <td class="speaker-image">
            <img src="assets/img/photos/radu.png" alt="Radu Ionescu">
        </td>
        <td>
            <div class="speaker-name">Radu Ionescu</div>
            <div class="speaker-position">Professor, University of Bucharest (Romania)</div>
            <div class="talk-title">Scalable real-time abnormal event detection</div>
            <div class="talk-summary">
State-of-the-art video anomaly detectors typically rely on a costly object detection method to increase precision, limiting the processing bandwidth to one video stream per GPU, at around 20-30 FPS. However, for real-world video surveillance, e.g. monitoring an entire city with hundreds or thousands of cameras, the processing costs of object-centric video anomaly detectors are simply too high, given their power consumption and the cost of GPUs. To this end, we will present two lightweight models, capable of processing over 60 video streams at 25 FPS, significantly reducing the processing costs. Different from competing models performing anomaly detection at the object or spatio-temporal cube levels, we present models that take whole video frames as input, which is significantly more efficient. The presented models employ several techniques to achieve efficiency, e.g. adversarial knowledge distillation, self-distillation and masked auto-encoders. Comprehensive experiments on four benchmarks show that the presented methods are significantly faster than state-of-the-art methods, while achieving comparable accuracy levels.
            </div>
        </td>
    </tr>
    <tr>
        <td class="speaker-image">
            <img src="assets/img/photos/wenwu.png" alt="Wenwu Wang">
        </td>
        <td>
            <div class="speaker-name">Wenwu Wang</div>
            <div class="speaker-position">Professor, University of Surrey (United Kingdom)</div>
            <div class="talk-title">Anomalous Sound Detection</div>
            <div class="talk-summary">
Anomalous Sound Detection (ASD) is a vital research field aimed at identifying abnormal or unexpected sounds in acoustic environments, often without prior knowledge of the anomalies themselves. It has broad applications in areas such as industrial monitoring, surveillance, healthcare, and environmental sensing, where early detection of unusual sounds can indicate equipment malfunctions, safety risks, or other critical events. ASD systems typically learn the characteristics of normal acoustic patterns and detect deviations from these patterns using signal processing and machine learning methods. In this talk, we will explore recent advances in anomalous sound detection, highlighting key challenges, emerging techniques, and future research opportunities. We will also present our latest work on contrastive, self-supervised, and statistical approaches designed to enhance robustness, domain generalization, and anomaly sensitivity across noisy, domain-shifted, and machine-specific industrial datasets.

            </div>
        </td>
    </tr>
</table>

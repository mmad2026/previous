---
layout: post
title: Speakers
---

<style>
        .profile-container {
            display: flex;
            align-items: flex-start;
            gap: 30px;
            margin: 20px auto;
            padding: 20px;
            font-family: Arial, sans-serif;
        }

        .profile-image {
            width: 300px;
            height: 300px;
            object-fit: cover;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        .profile-info {
            flex: 1;
        }

        .profile-name {
            font-weight: bold;
            font-size: 1.5em;
            margin: 0 0 8px 0;
            color: #333;
        }

        .profile-links {
            font-style: italic;
            font-size: 1.1em;
            margin: 0 0 15px 0;
        }

        img.link {
            width:20px;
        }

        .profile-affiliation {
            font-style: italic;
            color: #666;
            margin: 0;
            font-size: 1.1em;
        }

        .profile-bio {
            line-height: 1.6;
            color: #444;
            margin: 0;
        }
        .talk-summary {
            color: #555;
            line-height: 1.5;
            text-align: justify;
            margin: 0;
        }
        .talk-title {
            font-weight: bold;
            margin-bottom: 8px;
            font-size: 18px;
            margin: 10px 0;
        }

        /* Responsive design for mobile */
        @media (max-width: 600px) {
            .profile-container {
                flex-direction: column;
                text-align: center;
            }

            .profile-image {
                width: 150px;
                height: 150px;
            }
        }
</style>

<h1>Speakers</h1>

<div class="profile-container">
    <img src="assets/img/photos/radu.png" alt="Radu" class="profile-image">
    <div class="profile-info">
        <h2 class="profile-name">Radu Ionescu <a href="https://raduionescu.herokuapp.com"><img src="assets/img/globe.png" class="link"></a></h2>
        <p class="profile-affiliation">Professor, University of Bucharest (Romania)</p>
        <p class="talk-title">Scalable real-time abnormal event detection</p>
        <p class="talk-summary">
State-of-the-art video anomaly detectors typically rely on a costly object detection method to increase precision, limiting the processing bandwidth to one video stream per GPU, at around 20-30 FPS. However, for real-world video surveillance, e.g. monitoring an entire city with hundreds or thousands of cameras, the processing costs of object-centric video anomaly detectors are simply too high, given their power consumption and the cost of GPUs. To this end, we will present two lightweight models, capable of processing over 60 video streams at 25 FPS, significantly reducing the processing costs. Different from competing models performing anomaly detection at the object or spatio-temporal cube levels, we present models that take whole video frames as input, which is significantly more efficient. The presented models employ several techniques to achieve efficiency, e.g. adversarial knowledge distillation, self-distillation and masked auto-encoders. Comprehensive experiments on four benchmarks show that the presented methods are significantly faster than state-of-the-art methods, while achieving comparable accuracy levels.
        </p>
    </div>
</div>

<div class="profile-container">
    <img src="assets/img/photos/wenwu.png" alt="Wenwu" class="profile-image">
    <div class="profile-info">
        <h2 class="profile-name">Wenwu Wang <a href="https://personalpages.surrey.ac.uk/w.wang/"><img src="assets/img/globe.png" class="link"></a></h2>
        <p class="profile-affiliation">Professor, University of Surrey (United Kingdom)</p>
        <p class="talk-title">Anomalous Sound Detection</p>
        <p class="talk-summary">
Anomalous Sound Detection (ASD) is a vital research field aimed at identifying abnormal or unexpected sounds in acoustic environments, often without prior knowledge of the anomalies themselves. It has broad applications in areas such as industrial monitoring, surveillance, healthcare, and environmental sensing, where early detection of unusual sounds can indicate equipment malfunctions, safety risks, or other critical events. ASD systems typically learn the characteristics of normal acoustic patterns and detect deviations from these patterns using signal processing and machine learning methods. In this talk, we will explore recent advances in anomalous sound detection, highlighting key challenges, emerging techniques, and future research opportunities. We will also present our latest work on contrastive, self-supervised, and statistical approaches designed to enhance robustness, domain generalization, and anomaly sensitivity across noisy, domain-shifted, and machine-specific industrial datasets.
        </p>
    </div>
</div>

<div class="profile-container">
    <img src="assets/img/photos/rafal.png" alt="Rafal" class="profile-image">
    <div class="profile-info">
        <h2 class="profile-name">Rafal Wisniewski</h2>
        <p class="profile-affiliation">Professor, Aalborg University (Denmark)</p>
        <p class="talk-title">Manifold learning with autoencoders for subspace-based anomaly detection</p>
        <p class="talk-summary">
        We propose a method to learn a manifold representation of data covariance Hankel-like matrices using an autoencoder, and demonstrate its use for fault detection in dynamical systems. The autoencoder is trained in two stages to capture both a low-dimensional latent manifold representation and a complementary representation of Hankel matrices constructed from nominal data. We illustrate that when a Hankel matrix built from test data does not lie on a manifold obtained on data collected from a nominal, reference system, a fault occurs. To detect it, we propose a simple residual which is tested in a classical hypothesis testing framework. For linear systems, this residual is closely related to the classical subspace fault detection residual based on the null space of the Hankel matrix. The performance of the proposed detection scheme is validated on linear and weakly nonlinear mechanical benchmark systems.
        </p>
    </div>
</div>

<div class="profile-container">
    <img src="assets/img/photos/line.jpg" alt="Line" class="profile-image">
    <div class="profile-info">
        <h2 class="profile-name">Line Katrine Harder Clemmensen</h2>
        <p class="profile-affiliation">Professor, University of Copenhagen, Dept. of Mathematical Sciences (Denmark)</p>
        <p class="talk-title">Anomaly detection and self-explainability of vessel behavior based on AIS data</p>
        <p class="talk-summary">
        This talk discusses anomaly detection of maritime traffic with a focus on two case studies: A cable breach in Svalbard and a search and rescue event near Bornholm. We propose a variational autoeencoder approach with self-explainability to understand the normal maritime behaviors, and study trransferability of the learned architecture between regions.
        </p>
    </div>
</div>

<div class="profile-container">
    <img src="assets/img/photos/zhenghua.png" alt="Zheng-Hua" class="profile-image">
    <div class="profile-info">
        <h2 class="profile-name">Zheng-Hua Tan <a href="https://zhenghuatan.es.aau.dk"><img src="assets/img/globe.png" class="link"></a></h2>
        <p class="profile-affiliation">Professor, Aalborg University (Denmark)</p>
        <p class="talk-title">Detecting adversarial audio in deep speech systems</p>
        <p class="talk-summary">
        Deep learning-based speech recognition systems are increasingly deployed in real-world applications, yet they are vulnerable to adversarial attacks, subtle perturbations that mislead models while remaining imperceptible to humans. These attacks compromise user privacy, security, and safety. This talk presents strategies for detecting and defending against adversarial audio in speech systems. We begin by formulating adversarial detection as a classification task by training models on systematically generated datasets of white-box and black-box attacks. We then enhance detection performance by leveraging domain-specific features. Finally, we introduce a training-free approach based on pre-trained diffusion models, which purify adversarial inputs and enable accurate detection. Our findings show that combining supervised learning, feature engineering, and generative models provides robust defenses against adversarial attacks. We hope that these approaches offer a different perspective beyond traditional anomaly detection methods and inspire discussion and adoption of similar methodologies in other tasks.
        </p>
    </div>
</div>

<div class="profile-container">
    <img src="assets/img/photos/kamal.png" alt="Kamal" class="profile-image">
    <div class="profile-info">
        <h2 class="profile-name">Kamal Nasrollahi</h2>
        <p class="profile-affiliation">Director of Research, Milestones System. Professor, Aalborg University (Denmark)</p>
        <p class="talk-title">Privacy preserving video surveillance and detecting anomalies where it matters most</p>
        <p class="talk-summary">
        The "Harborfront Dataset" contains real-world data collected from the harbor region in the city of Aalborg. The "Long-Term Drift Dataset", proposed by our team at Aalborg University, is designed to study drift in thermal video analysis tasks, i.e., object detection and long-term scene change detection as conditions shift from day to night and across seasons. By capturing only infrared signatures, the dataset preserves human privacy while still providing critical information about activity near the harbor. This makes it highly valuable for detecting potentially life-threatening events, such as drowning or accidental falls into the water. In this context, anomalies are truly high-stakes, where timely detection can save lives. This talk will introduce the Harborfront Dataset and highlight real-world use cases demonstrating the importance of robust anomaly detection in safety-critical environments.
        </p>
    </div>
</div>


---
layout: post
title: Organization
---

<style>
        .profile-container {
            display: flex;
            align-items: flex-start;
            gap: 30px;
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            font-family: Arial, sans-serif;
        }

        .profile-image {
            width: 200px;
            height: 200px;
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

        .profile-links img {
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

<h1>Organization</h1>

<div class="profile-container">
    <img src="assets/img/photos/kevin.png" alt="Kevin Profile picture" class="profile-image">
    <div class="profile-info">
        <h2 class="profile-name">Kevin Wilkinghoff</h2>
        <p class="profile-affiliation">Postdoctoral Researcher, Aalborg University</p>
        <p class="profile-links">
            <a href="mailto:kevin.wilkinghoff@ieee.org"><img src="assets/img/email.png"></a>
            <a href="https://wilkinghoff.com"><img src="assets/img/globe.png"></a>
            <a href="https://scholar.google.de/citations?user=UKE_q8wAAAAJ&hl=en"><img src="assets/img/googlescholar.png"></a>
        </p>
    </div>
</div>

<div class="profile-container">
    <img src="assets/img/photos/neelu.png" alt="Neelu Profile picture" class="profile-image">
    <div class="profile-info">
        <h2 class="profile-name">Neelu Madan</h2>
        <p class="profile-affiliation">Postdoctoral Researcher, Aalborg University</p>
        <p class="profile-links">
            <a href="https://scholar.google.com/citations?user=tIn34swAAAAJ&hl=en"><img src="assets/img/googlescholar.png"></a>
        </p>
    </div>
</div>

<div class="profile-container">
    <img src="assets/img/photos/miguel.jpg" alt="Miguel Profile picture" class="profile-image">
    <div class="profile-info">
        <h2 class="profile-name">J. Miguel Valverde</h2>
        <p class="profile-affiliation">Postdoctoral Researcher, DTU Compute</p>
        <p class="profile-links">
            <a href="mailto:jmvma@dtu.dk"><img src="assets/img/email.png"></a>
            <a href="https://jmlipman.github.io/"><img src="assets/img/globe.png"></a>
            <a href="https://scholar.google.com/citations?user=OPH9yeIAAAAJ&hl=en"><img src="assets/img/googlescholar.png"></a>
            <a href="https://github.com/jmlipman/"><img src="assets/img/github.png"></a>
        </p>
    </div>
</div>

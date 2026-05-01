---
layout: post
title: Program
---

<h1>Program</h1>

<style>
    .schedule-table {
        /*width: 500px;*/
        border-collapse: collapse;
        font-family: Arial, sans-serif;
        margin: 0 auto;
    }

    .schedule-table th {
        background-color: #3498db;
        color: white;
        padding: 12px;
        text-align: left;
        font-weight: bold;
    }

    .schedule-table td {
        padding: 12px;
        border-bottom: 1px solid #ddd;
        /*vertical-align: center;*/
        font-size: 15px;
    }

    .time-cell {
        width: 20%;
        font-weight: bold;
    }

    /* Session duration visualization */
    .short-session { height: 30px; }
    .medium-session { height: 60px; }
    .long-session { height: 90px; }

    /* Color classes */
    .keynote { background-color: #e8f4fd; }
    .talk { background-color: #f0f9eb; }
    .break { background-color: #fff2e8; }
    .panel { background-color: #f9f0ff; }
    .poster { background-color: #fff8e1; }
    .opening { background-color: #e3f2fd; }
    .closing { background-color: #e8f5e9; }
    .startend { background-color: #f2f2f2; }

    @media (max-width: 768px) {
        .schedule-table {
            display: block;
        }

        .schedule-table thead {
            display: none;
        }

        .schedule-table tr {
            /*display: block;*/
            margin-bottom: 10px;
            border: 1px solid #ddd;
        }

        /*.schedule-table td {
            display: block;
            width: 100%;
        }*/

        .time-cell {
            background-color: #3498db;
            color: white;
            width: 70px;
        }

        .short-session, .medium-session, .long-session {
            height: auto;
        }
    }
</style>

<table class="schedule-table">
    <thead>
        <tr>
            <th>Time</th>
            <th>Session</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td class="time-cell">9:00</td>
            <td class="startend short-session">Registration and Breakfast</td>
        </tr>
        <tr>
            <td class="time-cell">9:30</td>
            <td class="break short-session">Opening remarks and introduction to the P1 Program</td>
        </tr>
        <tr>
            <td class="time-cell">9:45</td>
            <td class="keynote medium-session">Keynote: <i>Privacy preserving video surveillance and detecting anomalies where it matters most</i> — Kamal Nasrollahi</td>
        </tr>
        <tr>
            <td class="time-cell">10:30</td>
            <td class="keynote medium-session">Keynote: "<i>Scalable real-time abnormal event detection</i>" — Radu Ionescu</td>
        </tr>
        <tr>
            <td class="time-cell">11:15</td>
            <td class="break short-session">Coffee break</td>
        </tr>
        <tr>
            <td class="time-cell">11:30</td>
            <td class="talk medium-session">Contributed Talk: <i>Manifold learning with autoencoders for subspace-based anomaly detection</i> — Rafal Wisniewski</td>
        </tr>
        <tr>
            <td class="time-cell">12:00</td>
            <td class="talk medium-session">Contributed Talk: <i>Anomaly detection and self-explainability of vessel behavior based on AIS data</i> — Line Katrine Harder Clemmensen</td>
        </tr>
        <tr>
            <td class="time-cell">12:30</td>
            <td class="break long-session">Lunch break</td>
        </tr>
        <tr>
            <td class="time-cell">13:30</td>
            <td class="talk medium-session">Contributed Talk: <i>Detecting adversarial audio in deep speech systems</i> — Zheng-Hua Tan</td>
        </tr>
        <tr>
            <td class="time-cell">14:00</td>
            <td class="poster long-session">Poster Session and Networking</td>
        </tr>
        <tr>
            <td class="time-cell">15:00</td>
            <td class="break short-session">Coffee break</td>
        </tr>
        <tr>
            <td class="time-cell">15:15</td>
            <td class="keynote medium-session">Keynote: "<i>Anomalous Sound Detection</i>" — Wenwu Wang</td>
        </tr>
        <tr>
            <td class="time-cell">16:00</td>
            <td class="panel medium-session">Panel Discussion: Toward a unified agenda for multimodal anomaly detection</td>
        </tr>
        <tr>
            <td class="time-cell">16:45</td>
            <td class="break short-session">Closing remarks and next steps</td>
        </tr>
        <tr>
            <td class="time-cell">17:00</td>
            <td class="startend short-session">End of workshop</td>
        </tr>
    </tbody>
</table>

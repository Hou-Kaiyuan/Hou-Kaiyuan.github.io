---
layout: archive
title: "Recent Publications"
permalink: /publications/
author_profile: true
---

Recent Publications
---

<!-- Paper 1 -->
<div style="margin-bottom: 20px;">
    <img src="http://hou-kaiyuan.github.io/images/publications/fever.png" align="left" width="180" height="180" style="margin-right: 20px;"/> 
    <b>A Low-Cost In-situ System for Continuous Multi-Person Fever Screening</b><br>
    <b>Kaiyuan Hou</b>, Yanchen Liu, Peter Wei, Chenye Yang, Hengjiu Kang, Stephen Xia, Teresa Spada, Andrew Rundle, Xiaofan Jiang<br>
    <i>2022 21st ACM/IEEE International Conference on Information Processing in Sensor Networks </i> (<b>IPSN 2022</b>)
    <i><a href="https://ieeexplore.ieee.org/abstract/document/9825960">[PDF]</a></i>
    <br clear="left"/>
</div>

<!-- Paper 2 -->
<div style="margin-bottom: 20px;">
    <img src="http://hou-kaiyuan.github.io/images/publications/legosense.png" align="left" width="180" height="180" style="margin-right: 20px;"/> 
    <b>LegoSENSE: An Open and Modular Sensing Platform for Rapidly-Deployable IoT Applications</b> <br>
    Minghui Zhao, Stephen Xia, Jingping Nie, <b>Kaiyuan Hou</b>, Avik Dhupar, Xiaofan Jiang<br>
    <i>Proceedings of the 8th ACM/IEEE Conference on Internet of Things Design and Implementation</i> (<b>IoTDI 2023</b>)
    <i><a href="https://dl.acm.org/doi/abs/10.1145/3576842.3582369">[PDF]</a></i>
    <br clear="left"/>
</div>

<!-- Paper 3 -->
<div style="margin-bottom: 20px;">
    <img src="http://hou-kaiyuan.github.io/images/publications/arsteth.png" align="left" width="180" height="180" style="margin-right: 20px;"/> 
    <b>ARSteth: Enabling Home Self-Screening with AR-Assisted Intelligent Stethoscopes</b> <br>
    <b>Kaiyuan Hou</b>, Stephen Xia, Emily Bejerano, Junyi Wu, Xiaofan Jiang<br>
    <i>Proceedings of the 22nd International Conference on Information Processing in Sensor Networks</i> (<b>IPSN 2023</b>)
    <i><a href="https://dl.acm.org/doi/abs/10.1145/3583120.3586962">[PDF]</a></i>
    <br clear="left"/>
</div>


<!-- Paper 4 -->
<div style="margin-bottom: 20px;">
    <img src="http://hou-kaiyuan.github.io/images/publications/airflow.png" align="left" width="180" height="180" style="margin-right: 20px;"/> 
    <b>Anemoi: A Low-cost Sensorless Indoor Drone System for Autonomous Mapping of 3D Airflow Fields</b><br>
    Stephen Xia, Minghui Zhao, Charuvahan Adhivarahan, <b>Kaiyuan Hou</b>, Yuyang Chen, Jingping Nie, Eugene Wu, Karthik Dantu, Xiaofan Jiang<br>
    <i>Proceedings of the 29th Annual International Conference On Mobile Computing And Networking</i> (<b>MobiCom 2023</b>)
    <i><a href="https://dl.acm.org/doi/pdf/10.1145/3570361.3613292">[PDF]</a></i>
    <br clear="left"/>
</div>


Recents Works
---
<style>
        .video-container {
            display: flex;
            justify-content: space-around;
        }
        video {
            width: 30%;
        }
</style>

<div class="video-container">
    <video id="video1" controls>
        <source src="http://hou-kaiyuan.github.io/files/weather_cycle_comparison_v2.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <video id="video2" controls>
        <source src="http://hou-kaiyuan.github.io/files/weather_cycle_v1.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <video id="video3" controls>
        <source src="http://hou-kaiyuan.github.io/files/weather_cycle_v2.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

<script>
    const videos = [
        document.getElementById('video1'),
        document.getElementById('video2'),
        document.getElementById('video3')
    ];

    function syncVideos(event) {
        const currentVideo = event.target;
        const currentTime = currentVideo.currentTime;
        videos.forEach(video => {
            if (video !== currentVideo) {
                video.currentTime = currentTime;
            }
        });
    }

    videos.forEach(video => {
        video.addEventListener('play', () => {
            videos.forEach(v => v.play());
        });
        video.addEventListener('pause', () => {
            videos.forEach(v => v.pause());
        });
        video.addEventListener('timeupdate', syncVideos);
    });
</script>
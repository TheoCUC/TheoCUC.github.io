---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a Ph.D. candidate at the School of Information and Communication Engineering, Communication University of China, specializing in generative artificial intelligence, cultural technology, and performance technology. My advisor is Professor [Jiang Yujian](https://ices.cuc.edu.cn/2019/0919/c5332a135711/pagem.htm).

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News

<!-- - 2025.03  -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Submission in progress</div><img src='images/LightingGenOverview.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

LightingGen: A DMX based Generation Method for Entertainment Stage Lighting

**Wang Tianhao**, [Jiang Yujian](https://ices.cuc.edu.cn/2019/0919/c5332a135711/pagem.htm), [Jiang Wei](https://ices.cuc.edu.cn/2019/0919/c5332a135716/pagem.htm), Zhou Xiangzhong and Guan Xuzeng

We have completed a paper that models stage lighting in popular music performances through a data-driven approach by simulating the programming methods of professional designers. This work presents the first data-driven generative modeling method for stage lighting and plans to open-source the core code and related data in the future. The paper is currently under review.

</div>
</div>

<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Sensors</div><img src='images/STRMOAF.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Music-Driven Dance Generation Method Based on a Spatial-Temporal Refinement Model to Optimize Abnormal Frames](https://www.mdpi.com/1424-8220/24/2/588)

Wang Huaxin, Song Yang, [Jiang Wei](https://ices.cuc.edu.cn/2019/0919/c5332a135716/pagem.htm) and **Wang TianHao**

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
Existing music-driven dance generation methods often produce unnatural movements due to abnormal frames, prompting the proposal of a spatial-temporal refinement model to optimize these irregularities. The method employs a cross-modal alignment model to match music and dance segments, an abnormal frame optimization algorithm to correct distortions, and a temporal refinement model to enhance music-dance synchronization. Experiments demonstrate that the approach generates more realistic and diverse dance sequences, reducing the FID by 1.2 and improving diversity by 1.7 compared to previous methods.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Electronics</div><img src='images/SNAS-GCN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Skeleton-Based Human Action Recognition Based on Single Path One-Shot Neural Architecture Search](https://www.mdpi.com/2079-9292/12/14/3156)

[Jiang Yujian](https://ices.cuc.edu.cn/2019/0919/c5332a135711/pagem.htm), Yu Saisai, **Wang Tianhao**, Sun Zhaoneng and [Wang Shuang](https://ices.cuc.edu.cn/2019/0918/c5332a211231/page.htm)

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
One-shot Neural Architecture Search (NAS) for skeleton-based action recognition improves efficiency through weight sharing but faces challenges like large search spaces, high computational costs, and inefficient search strategies. To address these issues, this study proposes SNAS-GCN, which introduces a simplified four-category search space, a single-path one-shot sampling approach, and an adaptive CMA-ES strategy to optimize model search and reduce training costs. Experiments on NTU-RGB+D and Kinetics datasets show that the proposed method reduces search time by 0.3× compared to state-of-the-art approaches while maintaining comparable recognition accuracy to NAS-GCN.
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->
# 🔧 Projects

<!-- 无线环境光照传感系统 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NCPA</div>
<div class="scroll-container">
        <div class="scroll-item"><img src="images/NCPA/RealTest.jpg"></div>
        <div class="scroll-item"><img src="images/NCPA/Box1.jpeg"></div>
        <div class="scroll-item"><img src="images/NCPA/Box2.jpeg"></div>
        <div class="scroll-item"><img src="images/NCPA/Box3.jpeg"></div>
</div>

</div></div>
<div class='paper-box-text' markdown="1">

Wireless Ambient Light Sensing System

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
To address the issue of illuminance distribution in theater seating areas, we designed a wireless multi-node illuminance acquisition system based on ambient light sensors. Each sensor node connects to the local area network via an ESP chip and transmits the sensor's illuminance values to the host computer. The host computer, developed using Electron, features software that receives data in real-time, performs graphical analysis, and allows data export for further examination.
</div>
</div>

<!-- 科技冬奥 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">科技冬奥</div>
<div class="scroll-container">
    <div class="scroll-item"><img src="images/BW2022/System.png"></div>
    <div class="scroll-item"><img src="images/BW2022/FrameWork.png"></div>
    <div class="scroll-item"><img src="images/BW2022/Demo.jpg"></div>
</div>



</div></div>
<div class='paper-box-text' markdown="1">

Research and Development of an Interactive Audiovisual Control System for Wearable Light-Emitting Devices

Based on our laboratory's research findings on the relationships between timbre and color, as well as timbre and texture, we have developed a system that automatically selects timbre and texture images from a material library according to musical timbre. This system can be used to create and jointly control the audience light stick materials for the 2022 Beijing Winter Olympics.

</div>
</div>

# 🎖 Honors and Awards
- *2022.12* Communication University of China, Merit Student
- *2022.12* Communication University of China, Starlight Scholarship
- *2021.12* Outstanding Undergraduate Thesis of Beijing

# 📖 Educations
- *2021.09 - (now)*, PhD Student, Information and Communication Engineering, Communication University of China, Beijing.
- *2017.09 - 2021.06*, Undergraduate, Automation, Communication University of China, Beijing.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

<script>
    const scrollContainers = document.querySelectorAll('.scroll-container');

    function autoScroll() {
        scrollContainers.forEach(scrollContainer => {
            if (scrollContainer.scrollLeft + scrollContainer.clientWidth >= scrollContainer.scrollWidth) {
                scrollContainer.scrollLeft = 0; // Reset scroll to the start
            } else {
                scrollContainer.scrollBy({
                    left: 403, // Adjust this value to match the width of your scroll items
                    behavior: 'smooth'
                });
            }
        });
    }

    setInterval(autoScroll, 3000); // Adjust the interval as needed (3000ms = 3 seconds)
</script>
<style>
    .scroll-container {
        width: 400px;
        overflow-x: auto;
        white-space: nowrap;
        padding: 0; /* Ensure no padding */
        margin: 0; /* Ensure no margin */
        box-sizing: border-box; /* Include borders in width calculation */
    }
    .scroll-item {
        display: inline-block;
        width: 400px; /* Explicitly set width to match image width */
        margin: 0; /* Ensure no margin */
        padding: 0; /* Ensure no padding */
    }
    .scroll-item img {
        width: 400px;
        height: 260px;
        display: block; /* Prevent inline spacing issues */
    }
</style>

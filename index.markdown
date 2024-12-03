---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<html>
<head>
<style>
body {
    margin: 0;
    background-color: #f4f4f4;
    font-family: Helvetica, Arial, sans-serif;
    text-align: center; /* Center align all content */
}

.container {
    display: flex;
    flex-direction: column; /* Stack content vertically */
    align-items: center; /* Center content horizontally */
    margin-top: 50px; /* Adjust spacing from the top */
}

.circular-image {
    width: 250px;
    height: 250px;
    border-radius: 50%;
    overflow: hidden;
    border: 4px solid #555;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    margin-bottom: 20px; /* Add spacing below the image */
}

.circular-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.icons-container {
    display: flex;
    justify-content: center; /* Align icons horizontally in the center */
    gap: 20px; /* Add spacing between icons */
}

.icon {
    width: 40px;
    height: 40px;
    border-radius: 50%; /* Optional: Make icons circular */
    overflow: hidden;
    transition: transform 0.2s; /* Add hover effect */
}

.icon img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.icon:hover {
    transform: scale(1.1); /* Scale up slightly on hover */
}

.role-header, .list-header {
    font-size: 24px; /* Adjust header font size */
    margin: 20px 0 10px; /* Add spacing around the headers */
    color: #333; /* Header color */
}

.role-description {
    font-size: 18px; /* Font size for role description */
    margin-bottom: 20px; /* Spacing below the description */
    color: #555; /* Text color */
}

.list-container {
    text-align: left; /* Align list to the left */
    max-width: 600px; /* Set a max width for the list */
    margin: 0 auto; /* Center the list */
}

.list-container ul {
    list-style-type: disc; /* Use bullet points */
    padding-left: 20px; /* Indent the list */
}

</style>
</head>
<body>

<div class="container">
    <!-- Profile Image -->
    <div class="circular-image">
        <img src="/assets/photo.jpg" alt="Profile Image">
    </div>

    <!-- Social Icons -->
    <div class="icons-container">
        <div class="icon">
            <a href="https://scholar.google.com/citations?user=nI_wF6gAAAAJ&hl=en&oi=ao" target="_blank">
                <img src="/assets/Untitled.png" alt="Google Scholar">
            </a>
        </div>
        <div class="icon">
            <a href="https://orcid.org/my-orcid?orcid=0009-0004-8775-5306" target="_blank">
                <img src="/assets/orc.png" alt="ORCID">
            </a>
        </div>
        <div class="icon">
            <a href="https://www.researchgate.net/profile/Pratyush-Nandi" target="_blank">
                <img src="/assets/rg.png" alt="ResearchGate">
            </a>
        </div>
        <div class="icon">
            <a href="https://www.linkedin.com/in/pratyush-nandi-458a13172/" target="_blank">
                <img src="/assets/linkd.png" alt="LinkedIn">
            </a>
        </div>
        <div class="icon">
            <a href="pratyush.nandi@utah.edu">
                <img src="/assets/email.png" alt="Email">
            </a>
        </div>
    </div>

<!-- Role Header -->
    <div class="role-header">PhD Student @University of Utah</div>
    <div class="role-description">
    Graduate Research Assistant at <a href="https://arch.cs.utah.edu/" style="text-decoration: none; color: #333;">Utah Arch Research Group</a>
    </div>

    <!-- List Header -->
    <div class="list-header">Publications</div>
    <div class="list-container">
        <ul>
            <li><a href="https://dl.acm.org/doi/abs/10.1145/3649476.3658743">GOLDS: Genetic Algorithm-based Optimization of Custom FPGA Architecture Layout Design for Secure Silicon</a></li>
            <li><a href="https://ieeexplore.ieee.org/abstract/document/10360959/">ApproxCNN: Evaluation Of CNN With Approximated Layers Using In-Exact Multipliers</a></li>
            <li><a href="https://link.springer.com/article/10.1007/s12652-023-04667-w">Soil friction coefficient estimation using CNN included in an assistive system for walking in urban areas</a></li>
            <li><a href="https://ieeexplore.ieee.org/abstract/document/10238594/">Design-space exploration of multiplier approximation in cnns</a></li>
            <li><a href="https://ieeexplore.ieee.org/abstract/document/10108325">Design and evaluation of CNN hardware accelerator designs for in-seat passenger anomaly detection</a></li>
            <li><a href="https://ieeexplore.ieee.org/abstract/document/9871777">A novel cnn-lstm model based non-invasive cuff-less blood pressure estimation system</a></li>
            <li><a href="https://ieeexplore.ieee.org/abstract/document/9773868">Design of a CNN based autonomous in-seat passenger anomaly detection system</a></li>
            <li><a href="https://ieeexplore.ieee.org/abstract/document/9304666">Design of a real-time autonomous in-cabin sensory system to detect passenger anomaly</a></li>
        </ul>
    </div>

</div>

</body>
</html>



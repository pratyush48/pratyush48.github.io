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
</div>

</body>
</html>



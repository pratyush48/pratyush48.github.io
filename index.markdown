---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<html>
<head>
<style>
body {
    margin: 0; /* Keeps default margin */
    background-color: #f4f4f4; /* Optional: Add a background color */
    font-family: Helvetica,Arial, sans-serif; /* Optional: Set a font for other content */
}

.center-container {
    display: flex; /* Enables flexbox */
    justify-content: center; /* Centers content horizontally */
    align-items: center; /* Centers content vertically */
    height: 100vh; /* Full viewport height */
    width: 100%; /* Full viewport width */
}

.circular-image {
    width: 300px; /* Set the width */
    height: 300px; /* Set the height */
    border-radius: 50%; /* Make it circular */
    overflow: hidden; /* Hide the overflow */
    border: 4px solid #555; /* Optional: Add a border */
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Optional: Add a shadow */
}

.circular-image img {
    width: 100%; /* Ensures high pixel quality */
    height: 100%;
    object-fit: cover; /* Ensures the image fits the circle */
}
</style>
</head>
<body>

<div class="circular-image">
    <img src="/assets/photo.jpg" alt="Circular Image">
</div>

</body>
</html>

---

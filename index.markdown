---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<html>
<head>
<style>
body {
    display: flex; /* Enables flexbox layout */
    justify-content: center; /* Centers content horizontally */
    align-items: center; /* Centers content vertically */
    height: 100vh; /* Full viewport height */
    margin: 0; /* Removes default margin */
    background-color: #f4f4f4; /* Optional: Add a light background color */
}

.circular-image {
    width: 500px; /* Set the width */
    height: 500px; /* Set the height */
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

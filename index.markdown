---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<!DOCTYPE html>
<html>
<head>
<style>
.circular-image {
    width: 200px; /* Set the width */
    height: 200px; /* Set the height */
    border-radius: 50%; /* Make it circular */
    overflow: hidden; /* Hide the overflow */
    border: 2px solid #000; /* Optional: add a border */
}

.circular-image img {
    width: 100%;
    height: 100%;
    object-fit: cover; /* Ensure the image covers the circle */
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

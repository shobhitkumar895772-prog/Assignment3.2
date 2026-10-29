Step-by-Step Instructions
Create the Folder: In the same folder where your HTML files are saved, create a new folder and name it images (all lowercase).

Add Your Images: Choose at least 3 images and place them inside the images folder. (For example, you can name them profile.jpg, project1.jpg, and project2.jpg).

Update Your HTML: Add the following code snippet inside your portfolio page (you can add it to your index.html or a separate portfolio section) to display the images with correct paths, sizes, and meaningful alt text.

Example HTML Code
<!-- Images Section / Portfolio Gallery -->
    <h2>My Portfolio Gallery</h2>
    <p>Here are a few snapshots and projects from my work:</p>

    <div class="image-gallery">
        <!-- Image 1 -->
        <img src="images/profile.jpg" alt="Portrait photo of me working at a desk with a laptop" width="300" height="200">

        <!-- Image 2 -->
        <img src="images/project1.jpg" alt="Screenshot of a responsive web design project showing a modern landing page" width="300" height="200">

        <!-- Image 3 -->
        <img src="images/project2.jpg" alt="Graphic design showcase featuring minimalist typography and abstract shapes" width="300" height="200">
    </div>
    Key Requirements Checklist for Your Submission:
images folder: Created and located in your project directory.

At least 3 images: Placed inside the images folder.

Attributes used: Every <img> tag includes src, alt, width, and height.

Correct paths: The src attribute correctly points to the folder (e.g., images/filename.jpg).

Meaningful Alt Text: Each alt description clearly explains what the image shows (great for accessibility!).
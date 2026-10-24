Step 1: Create the images Folder
Open your project folder in Visual Studio Code.

In the Explorer sidebar, click the New Folder icon next to your project root directory.

Name the folder images.

Step 2: Add at Least 3 Images
Choose or download 3 images relevant to your portfolio (e.g., a profile picture, a screenshot of a project you built, or a graphic).

Save these images inside your new images folder.

Give them short, clean, descriptive file names without spaces (e.g., profile-photo.jpg, project-one.png, project-two.png).

Step 3: Add the Images Section to Your Portfolio HTML
Open your portfolio HTML file (e.g., index.html) and add an images or projects section using the <img> tag with src, alt, width, and height attributes.

HTML
<section id="portfolio-images">
    <h2>My Portfolio Gallery</h2>
    <p>Here are some snapshots of my projects and work:</p>

    <div class="image-gallery">
        <!-- Image 1 -->
        <div class="image-card">
            <img src="images/profile-photo.jpg" 
                 alt="Portrait of me working on code at my desk" 
                 width="300" 
                 height="200">
            <p>Profile Picture</p>
        </div>

        <!-- Image 2 -->
        <div class="image-card">
            <img src="images/project-one.png" 
                 alt="Screenshot of a responsive landing page project showing header and navigation bar" 
                 width="300" 
                 height="200">
            <p>Project One: Landing Page</p>
        </div>

        <!-- Image 3 -->
        <div class="image-card">
            <img src="images/project-two.png" 
                 alt="Screenshot of a structured HTML portfolio website with a clean layout" 
                 width="300" 
                 height="200">
            <p>Project Two: Personal Portfolio</p>
        </div>
    </div>
</section>
Step 4: Verify Your Attributes
src: Points accurately to the location of the image relative to your HTML file (e.g., images/profile-photo.jpg).

alt: Provides a clear, descriptive text alternative explaining what the image depicts (essential for screen readers and accessibility if the image fails to load).

width & height: Explicitly defines the display dimensions in pixels to reserve layout space and prevent page jumping while loading.

Step 5: Test in the Browser
Right-click your HTML file in VS Code and select Open with Live Server.

Scroll down to your portfolio images section to verify that all 3 images render correctly without broken image icons.

Inspect the page using Chrome DevTools (Press F12 or Ctrl+Shift+I / Cmd+Option+I) to confirm that the images folder and your assets load properly under the Network or Sources tab.
Travel Website Exoskeleton
This exoskeleton code serves as a template for creating travel websites, Customize it for different travel destinations.


Getting Started

Step 1: Clone the Repository
Clone this repository to your local machine using the following command:
git clone https://github.com/saadhussain01306/travel-website-exoskeleton.git

Step 2: Customize HTML Templates
For each travel destination, create a new HTML file based on the index.html template. Replace {{Page Title}} with the actual title of the page and add destination-specific content.

<!-- destination.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Head content specific to the destination -->
</head>
<body>
    <header class="header">
        <!-- Header content specific to the destination -->
    </header>

    <div class="container">
        <section>
            <!-- Content specific to the destination goes here -->
        </section>
    </div>

    <div class="footer">
        <footer>&copy; Saad-Hussain. All rights reserved.</footer>
    </div>

    <script src="https://code.jquery.com/jquery-3.6.4.min.js"></script>
</body>
</html>

Step 3: Customize CSS Styles

Customize the common styles in the styles.css file located in the common directory. Create additional CSS files for each destination if needed.

/* common/styles.css */
body {
    /* Common body styles */
}

.header {
    /* Common header styles */
}

.container {
    /* Common container styles */
}

.footer {
    /* Common footer styles */
}

/* Add additional styles for specific destinations */

Step 4: Customize JavaScript
If there are common JavaScript functionalities, include them in the main template (index.html). 
For destination-specific scripts, create separate files and include them in the respective pages.

Step 5: Repeat for Each Website
Repeat the process for each new website by creating new HTML files for different destinations. 
You can reuse the main template and styles, only modifying the content and styles that are specific to each destination.

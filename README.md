# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="week3style.css">

<body>
     <!-- Header Section -->
     <header id="main-header">
        <h1>Welcome to Trapid Hub</h1>
        <h6>Re-defining People and Business Development</h6>
    </header>

    <!-- Main Content -->
    <main>
        <section>
                <H2>Trapid Hub: Empowering Digital Skills for the Future</H2>
                <h3>Introduction</h3>
            <p>In today’s fast-paced digital world, acquiring relevant skills is no longer a luxury but a necessity. Trapid Hub is at the forefront of this transformation, equipping individuals with in-demand digital skills that drive career growth and business success. As an e-community dedicated to digital learning, Trapid Hub is focused on capacity building, professional development, and innovation, aligning with Goal 9 of the United Nations Sustainable Development Goals (Industry, Innovation, and Infrastructure).</p>
            <img src="https://images.pexels.com/photos/30539348/pexels-photo-30539348/free-photo-of-woman-working-remotely-at-home-dining-table.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" alt="Technology Image">
            
        </section>
       
    </main>
    <section>

        <h3>
            What Trapid Hub Offers
        </h3>
        <h4>Trapid Hub is a learning and development platform that provides structured training programs in various digital fields, including:</h4>
        <ol>
            <li>Web Development & Software Engineering</li>
            <li>Data Analytics & Cybersecurity</li>
            <li>Product & Project Management</li>
            <li>Social Media Management & Digital Marketing</li>
            <li>Virtual Assistance & Administrative Support</li>
        </ol>
        <p></p>By offering these courses, the Hub ensures that individuals, businesses, and organizations can stay ahead in a digitally evolving economy.</p>
    </section>

<section>
    <h3>A Community-Driven Approach</h3>
    <p>Trapid Hub is more than just an educational platform; it is an ecosystem that fosters collaboration, mentorship, and networking. The e-community connects learners with experts, mentors, and peers, ensuring that learning is not just theoretical but also practical and interactive.</p>
</section>
<section>
    <h3>Why Trapid Hub?</h3> 
    <ol>
        <li><strong>Training</strong>  – Programs are designed to match current job market demands.</li>
        <li><strong>Learning </strong> – Courses are accessible online, making it easier for students and professionals to upskill at their own pace.</li>
        <li><strong>Advancement</strong>  – Participants gain job-ready skills, making them competitive in their respective fields.</li>
        <li><strong>Business Growth Support</strong> – Entrepreneurs and startups can leverage training and professional services to scale their businesses effectively.</li>
    </ol>
</section>

<section>
    <h3>Future Prospects</h3>
    <p>As digital transformation continues to reshape industries, Trapid Hub remains committed to expanding its course offerings, engaging in corporate training, and partnering with organizations to bridge the digital skills gap. The goal is to create a skilled workforce that is prepared for the future of work.</p>
</section>

<section>
    <h3><strong>Join the next generation of techstars!!!</strong> </h3>
    <p>Are you ready to take your skills to the next level? Join Trapid Hub today and become part of a growing community of digital innovators!
    </p>
    <a href="https://forms.gle/g2WC5bza7truU71o8" class="btn">Register</a>
</section>
    <footer id="footer">
        <p id="footer-text">Contact us at: Trapidhub@gmail.com</p>
        <p>&copy; 2025 Trapid Hub. All rights reserved.
        </p>
    </footer>

</body>
</html>


CSS

/* Style for the body */
body {
    font-family: Times New Roman;
    background-color: #f4f4f4;
    margin: 5px;
    padding: 10px 20px;
}

/* Header styling using an ID */
#main-header {
    background-color: #1d8506;
    color: white;
    text-align: center;
    padding: 20px;
}

/* Paragraph styling using a class */
.text-content {
    font-size: 18px;
    color: #555;
    margin: 5px;
    padding: 10px 20px;
    border-left: 5px solid #333;
}

/* Styling an image */
img {
    display: block;
    width: 150px;
    height: auto;
    margin: 20px auto;
    border: 3px;
    border-radius: 10px;
}

/* Button styling using a class */
.btn {
    background-color: #1d8506;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    display: inline-block;
    margin: 20px;
    border-radius: 5px;
}

/* Hover effect for the button */
.btn:hover {
    background-color: #005f73;
}
/* Header styling using an ID */
#footer {
    background-color: #010300;
    color: white;
    text-align: center;
    padding: 20px;


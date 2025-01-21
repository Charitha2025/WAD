<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Creating Tables in HTML</title>
    <style>
        /* Ensure the image fits its container */
        img {
            width: 100%;
            height: auto;
            object-fit: cover; /* This makes the image cover the box */
        }

        /* Center the content in the "Other Options" column */
        .center-content {
            text-align: center; /* Horizontally center the text */
            vertical-align: middle; /* Vertically center the content */
            padding: 20px; /* Add some padding around the content */
        }
    </style>
</head>
<body text-align="center">
    <table border="1" width="100%" height="100%" text-align="center">
        <!-- First row with logo -->
        <tr height="50">
            <td width="50">
                <img src="https://www.logologo.com/logos/abstract-isometric-logo-design-free-logo.jpg" alt="MY Logo">
            </td>
            <td width="80%">
                <h1>Internship Opportunities at One Place!</h1>
            </td>
        </tr>
        
        <!-- Second row with navigation links -->
        <tr height="50">
            <td colspan="2">
                <div class="row">
                    <div class="text-center">
                        <a href="https://www.virtualinternships.com/" target="content">Home</a> |
                        <a href="https://web.virtualinternships.com/welcome" target="content">Login</a> |
                        <a href="https://www.virtualinternships.com/companies/how-it-works" target="content">Registration</a> |
                        <a href="https://www.virtualinternships.com/universities/" target="content">Catalogue</a> |
                        <a href="https://www.virtualinternships.com/interns/how-it-works" target="content">How it works</a> |
                        <a href="https://www.virtualinternships.com/our-team/" target="content">Contact Us</a>
                    </div>
                </div>
            </td>
        </tr>
        
        <!-- Third row with other options and iframe -->
        <tr>
            <!-- Center the content in the first column -->
            <td width="20%" class="center-content">
                <h3>Other Options</h3>
                <a href="https://www.virtualinternships.com/" target="display">Internships</a><br>
                <a href="https://www.niti.gov.in/" target="display">NITI Aayog</a><br>
                <a href="https://www.makeintern.com/" target="display">Make Intern</a><br>
                <a href="https://pminternship.mca.gov.in/login/" target="display">PM Internship</a>
            </td>
            <td width="80%">
                <iframe src="home.html" name="display" width="100%" height="400" frameborder="1"></iframe>
            </td>
        </tr>
    </table>
</body>
</html>

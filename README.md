# First
Dec 2023
<!DOCTYPE html>
<html class="no-js" lang="en">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Cesar Lozano's Resume</title>
    <style>
        body {
            font-family: 'Lato', sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: white;
            padding: 10px;
        }

        #lead {
            background: url('background-image.jpg'); /* Add your background image URL */
            background-size: cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }

        #lead-content {
            max-width: 600px;
            margin: 0 auto;
        }

        #education,
        #experience {
            padding: 40px 20px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>

<body>
    <header>
        <div id="mobile-menu-close">
            <span>Close</span> <i class="fa fa-times" aria-hidden="true"></i>
        </div>
        <ul id="menu" class="shadow">
            <li><a href="#education">Education</a></li>
            <li><a href="#experience">Experience</a></li>
        </ul>
    </header>

    <div id="lead">
        <div id="lead-content">
            <h1>Cesar Lozano</h1>
            <h2>Electrical Engineer</h2>
            <a href="#" class="btn-rounded-white">View Resume</a><br>
        </div>

        <div id="lead-overlay"></div>

        <div id="lead-down">
            <span>
                <i class="fa fa-chevron-down" aria-hidden="true"></i>
            </span>
        </div>
    </div>

    <div id="education">
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <h2 class="heading">Education</h2>
                </div>
                <div class="col-md-8">
                    <p>
                        High School Diploma - El Dorado High School, 2013 <br>
                        Associate Degree in Electrical Engineering - El Paso Community College <br>
                        Bachelor's Degree in Electrical Engineering - University of Texas at El Paso
                    </p>
                </div>
            </div>
        </div>
    </div>

    <div id="experience" class="background-alt">
        <h2 class="heading">Work Experience</h2>
        <div id="experience-timeline">
            <div data-date="Past - Present">
                <h3>Big 5 Sporting Goods</h3>
                <h4>Sales Associate / Cashier</h4>
                <p>
                    Responsible for customer service and cash handling.
                </p>
            </div>
            <div data-date="Past - Present">
                <h3>UPS</h3>
                <h4>Package Handler</h4>
                <p>
                    Efficiently handled and processed packages for timely delivery.
                </p>
            </div>
            <div data-date="Past - Present">
                <h3>Summer Moon Coffee</h3>
                <h4>Barista / Cashier</h4>
                <p>
                    Prepared and served coffee beverages while managing customer transactions.
                </p>
            </div>
        </div>
    </div>

    <footer>
        <div class="container">
            <div class="row">
                <div class="col-sm-5 copyright">
                    <p>
                        Copyright &copy; 2023 Cesar Lozano
                    </p>
                </div>
                <div class="col-sm-2 top">
                    <span id="to-top">
                        <i class="fa fa-chevron-up" aria-hidden="true"></i>
                    </span>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Your JavaScript code here (if needed)
    </script>
</body>

</html>

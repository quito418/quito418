<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: auto;
            overflow: hidden;
            padding: 0 20px;
        }
        header {
            background: #35424a;
            color: #ffffff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #e8491d 3px solid;
        }
        header a {
            color: #ffffff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        header .highlight, header .current a {
            color: #e8491d;
            font-weight: bold;
        }
        header a:hover {
            color: #ffffff;
            font-weight: bold;
        }
        .banner {
            padding: 80px 0;
            color: #ffffff;
            background: url('banner_background.jpg') no-repeat 0 0;
            background-size: cover;
        }
        .banner h1 {
            margin: 0;
            font-size: 55px;
            text-transform: uppercase;
            letter-spacing: 8px;
        }
        .banner p {
            font-size: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1><span class="highlight">AI and Genomics</span> Researcher</h1>
            </div>
            <nav>
                <ul>
                    <li class="current"><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="banner">
        <div class="container">
            <h1>Your Name</h1>
            <p>Exploring the intersections of artificial intelligence and genomics</p>
        </div>
    </div>

    <div class="container">
        <section class="main">
            <h2>About Me</h2>
            <p>I am an AI and Genomics researcher with a deep interest in the application of machine learning in genomic data analysis. My work involves the development of computational models that can predict genetic predispositions to certain diseases, personal responses to medications, and potential genetic modifications for improved health outcomes.</p>
            <p>With a strong background in both computer science and molecular biology, I am dedicated to advancing the field of personalized medicine through innovative AI research.</p>
        </section>

        <section class="sidebar">
            <h2>Research Interests</h2>
            <p>My research interests include but are not limited to:</p>
            <ul>
                <li>Genomic sequence analysis</li>
                <li>Predictive modeling in personalized medicine</li>
                <li>Biological data mining</li>
                <li>Machine learning applications in genomics</li>
            </ul>
        </section>

        <footer>
            <p>Connect with me on <a href="https://linkedin.com/in/your-profile">LinkedIn</a></p>
        </footer>
    </div>
</body>

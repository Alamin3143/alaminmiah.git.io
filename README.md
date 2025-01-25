<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Business Intelligence Analyst Portfolio in Finance">
    <title>Your Name | BI Analyst Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
</head>
<body>
    <header class="header">
        <div class="container">
            <h1>Your Name</h1>
            <p>Business Intelligence Analyst | Financial Analytics | Data Enthusiast</p>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="about" class="about">
        <div class="container">
            <h2>About Me</h2>
            <p>
                I am a Business Intelligence Analyst specializing in financial analytics and data visualization. 
                Passionate about turning complex datasets into actionable insights, I aim to help organizations 
                make data-driven decisions. Proficient in Python, SQL, Power BI, and Tableau, I thrive in projects 
                like revenue forecasting, fraud detection, and customer analytics.
            </p>
        </div>
    </section>

    <section id="projects" class="projects">
        <div class="container">
            <h2>Projects</h2>
            <div class="project-card">
                <h3>Revenue Forecasting Dashboard</h3>
                <p>Built an interactive Power BI dashboard to analyze revenue trends and forecast growth.</p>
                <a href="https://github.com/yourusername/revenue-forecasting" target="_blank">View on GitHub</a>
            </div>
            <div class="project-card">
                <h3>Loan Default Prediction Model</h3>
                <p>Created a machine learning model in Python to predict loan default risks with 85% accuracy.</p>
                <a href="https://github.com/yourusername/loan-default-model" target="_blank">View on GitHub</a>
            </div>
            <div class="project-card">
                <h3>Customer Lifetime Value Analysis</h3>
                <p>Developed SQL queries and a Power BI report to segment high-value customers.</p>
                <a href="https://github.com/yourusername/clv-analysis" target="_blank">View on GitHub</a>
            </div>
        </div>
    </section>

    <section id="skills" class="skills">
        <div class="container">
            <h2>Skills</h2>
            <ul>
                <li>Data Analysis: Python, SQL</li>
                <li>Data Visualization: Power BI, Tableau</li>
                <li>Financial Modeling: Excel, FMVA techniques</li>
                <li>Machine Learning: Scikit-learn, TensorFlow</li>
            </ul>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact</h2>
            <p>Feel free to reach out to discuss opportunities or collaborations!</p>
            <p>Email: <a href="mailto:yourname@email.com">yourname@email.com</a></p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/yourusername" target="_blank">linkedin.com/in/yourusername</a></p>
            <p>GitHub: <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></p>
        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <p>&copy; 2025 Your Name. All Rights Reserved.</p>
        </div>
    </footer>
</body>
</html>

/* General Styles */
body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    line-height: 1.6;
    color: #333;
}

.container {
    width: 90%;
    margin: 0 auto;
    max-width: 1200px;
}

/* Header */
.header {
    background: #003366;
    color: #fff;
    text-align: center;
    padding: 2rem 0;
}

.header h1 {
    margin: 0;
    font-size: 2.5rem;
}

.header p {
    font-size: 1.2rem;
}

.header nav ul {
    list-style: none;
    padding: 0;
    margin: 1rem 0 0;
}

.header nav ul li {
    display: inline;
    margin: 0 15px;
}

.header nav ul li a {
    color: #fff;
    text-decoration: none;
}

/* Sections */
section {
    padding: 2rem 0;
}

section h2 {
    font-size: 2rem;
    text-align: center;
    margin-bottom: 1rem;
}

/* About Section */
.about p {
    text-align: center;
    max-width: 800px;
    margin: 0 auto;
}

/* Projects Section */
.projects .project-card {
    background: #f4f4f4;
    margin: 1rem 0;
    padding: 1rem;
    border: 1px solid #ddd;
    border-radius: 5px;
}

.projects .project-card h3 {
    margin-top: 0;
}

/* Skills Section */
.skills ul {
    list-style: none;
    padding: 0;
    text-align: center;
}

.skills ul li {
    display: inline-block;
    margin: 0 15px;
    padding: 10px 20px;
    background: #f4f4f4;
    border-radius: 20px;
}

/* Contact Section */
.contact p {
    text-align: center;
}

.contact a {
    color: #003366;
    text-decoration: none;
}

/* Footer */
.footer {
    text-align: center;
    background: #003366;
    color: #fff;
    padding: 1rem 0;
}
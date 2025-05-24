<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mirza Razibul Islam Shatu - Modern Data Analyst Profile</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f0f4f8; /* Lighter, cooler background */
            color: #2d3748; /* Darker, more refined text */
            line-height: 1.6;
        }
        .container {
            max-width: 1024px; /* Max width for content */
            margin: 2rem auto; /* Center with more vertical margin */
            padding: 2rem; /* Increased padding */
            background-color: #ffffff;
            border-radius: 1.5rem; /* More rounded corners */
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.08); /* Softer, larger shadow */
            transition: all 0.3s ease-in-out;
        }
        .container:hover {
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.12); /* Slightly more prominent shadow on hover */
        }
        @media (min-width: 640px) {
            .container {
                padding: 3rem; /* Larger padding for larger screens */
            }
        }
        .section-title {
            position: relative;
            font-size: 2.25rem; /* Larger title */
            font-weight: 700; /* Bolder title */
            color: #4c51bf; /* Deeper indigo for titles */
            margin-bottom: 2rem;
            padding-bottom: 0.75rem;
        }
        .section-title::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 60px; /* Short underline effect */
            height: 4px;
            background-color: #667eea; /* Lighter indigo for underline */
            border-radius: 2px;
        }
        /* New skill card styling */
        .skill-card {
            background-color: #f8fafc; /* Lighter background for cards */
            padding: 1.5rem;
            border-radius: 1rem; /* Rounded corners */
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.2s ease-in-out, box-shadow 0.2s ease-in-out;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        .skill-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }
        .skill-icon {
            width: 2.5rem; /* Larger icons for prominence */
            height: 2.5rem;
            margin-bottom: 0.75rem;
            color: #4c51bf; /* Icon color */
        }
        .skill-name {
            font-weight: 600;
            color: #2d3748;
            margin-bottom: 0.5rem;
            font-size: 1.125rem; /* text-lg */
        }
        .skill-description {
            font-size: 0.9rem; /* text-sm */
            color: #4a5568;
        }

        /* Project card styling */
        .project-card {
            background-color: #f8fafc; /* Lighter background for cards */
            padding: 1.75rem;
            border-radius: 1rem; /* Rounded corners */
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.2s ease-in-out, box-shadow 0.2s ease-in-out;
        }
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }
        .project-title {
            color: #4c51bf; /* Deeper indigo for project titles */
            font-weight: 600;
        }
        .project-description {
            color: #4a5568;
            margin-bottom: 1rem;
        }
        .project-tech {
            color: #718096;
            font-size: 0.9rem;
        }
        /* Experience/Education/Certifications card styling */
        .info-card {
            background-color: #f8fafc;
            padding: 1.5rem;
            border-radius: 1rem;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.03);
        }
        .info-card-title {
            color: #2d3748;
            font-weight: 600;
        }
        .info-card-subtitle {
            color: #667eea; /* Accent color for subtitles */
            font-style: italic;
            margin-bottom: 0.5rem;
        }
        .info-card-description {
            color: #4a5568;
        }
        /* Button styling */
        .profile-button {
            font-weight: 600;
            padding: 0.8rem 2rem;
            border-radius: 9999px; /* Pill shape */
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease-in-out;
        }
        .profile-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
        }
        .btn-linkedin { background-color: #0a66c2; }
        .btn-linkedin:hover { background-color: #094c92; }
        .btn-website { background-color: #4a5568; }
        .btn-website:hover { background-color: #2d3748; }
        .btn-email { background-color: #dc2626; }
        .btn-email:hover { background-color: #b91c1c; }

    </style>
</head>
<body class="antialiased">
    <div class="container">
        <header class="text-center py-8 border-b border-gray-100 mb-8">
            <h1 class="text-5xl font-extrabold text-gray-900 mb-3">Mirza Razibul Islam Shatu 👋</h1>
            <h2 class="text-2xl font-semibold text-indigo-700">Data Analyst | Statistician | Machine Learning Enthusiast</h2>
            <div class="mt-6 text-gray-600 text-lg">
                Rajshahi, Bangladesh | +8801518749293 | <a href="mailto:mirzashatu@gmail.com" class="text-indigo-600 hover:underline">mirzashatu@gmail.com</a> |
                <a href="https://www.yourpersonalwebsite.com" target="_blank" class="text-indigo-600 hover:underline">Personal Website</a> |
                <a href="https://www.linkedin.com/in/your-linkedin-profile/" target="_blank" class="text-indigo-600 hover:underline">LinkedIn</a>
            </div>
        </header>

        <section class="py-8 border-b border-gray-100">
            <h3 class="section-title">About Me</h3>
            <p class="text-gray-700 leading-relaxed text-lg">
                I'm a passionate and analytical Data Analyst with a strong academic background in Statistics and a keen interest in leveraging data to solve real-world problems. My expertise spans across data analysis, machine learning model development, and insightful data visualization. I'm proficient in Python (Pandas, NumPy, Scikit-Learn), SQL, and R, and I thrive on transforming complex datasets into actionable insights.
            </p>
            <p class="mt-4 text-gray-700 leading-relaxed text-lg">
                I am always eager to learn new technologies and contribute to impactful projects. Feel free to explore my repositories to see my work!
            </p>
        </section>

        <section class="py-8 border-b border-gray-100">
            <h3 class="section-title">Skills</h3>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="bg-gray-50 p-6 rounded-xl shadow-sm">
                    <h4 class="text-xl font-semibold text-gray-800 mb-4">Programming Languages</h4>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><path d="M4 17l6-6-6-6M12 17h8"/></svg>
                            <span class="skill-name">Python</span>
                            <span class="skill-description">(Pandas | NumPy | Scikit-Learn)</span>
                        </div>
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><ellipse cx="12" cy="5" rx="9" ry="3"/><path d="M3 5V19A9 3 0 0 0 12 22A9 3 0 0 0 21 19V5"/><path d="M3 12A9 3 0 0 0 12 15A9 3 0 0 0 21 12"/></svg>
                            <span class="skill-name">SQL</span>
                            <span class="skill-description">Database querying & management.</span>
                        </div>
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><path d="M18 20V10"/><path d="M12 20V4"/><path d="M6 20V14"/></svg>
                            <span class="skill-name">R</span>
                            <span class="skill-description">Statistical computing & graphics.</span>
                        </div>
                    </div>
                </div>

                <div class="bg-gray-50 p-6 rounded-xl shadow-sm">
                    <h4 class="text-xl font-semibold text-gray-800 mb-4">Data Analysis & Visualization</h4>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><path d="M3 3v18h18"/><path d="m18 10-6 6-4-4L3 14"/></svg>
                            <span class="skill-name">Matplotlib</span>
                            <span class="skill-description">Static, animated, and interactive visualizations.</span>
                        </div>
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><path d="M3 3v18h18"/><path d="m18 10-6 6-4-4L3 14"/></svg>
                            <span class="skill-name">Seaborn</span>
                            <span class="skill-description">Statistical data visualization.</span>
                        </div>
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><path d="M3 3v18h18"/><path d="m18 10-6 6-4-4L3 14"/></svg>
                            <span class="skill-name">Plotly</span>
                            <span class="skill-description">Interactive, publication-quality graphs.</span>
                        </div>
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2H2v10l10 10 10-10V12z"/><path d="M2 12h10l10 10"/><path d="M12 2v20"/></svg>
                            <span class="skill-name">Excel</span>
                            <span class="skill-description">Data manipulation & reporting.</span>
                        </div>
                    </div>
                </div>

                <div class="bg-gray-50 p-6 rounded-xl shadow-sm">
                    <h4 class="text-xl font-semibold text-gray-800 mb-4">Machine Learning</h4>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><path d="M12 5c-3.314 0-6 2.686-6 6v7c0 2.21 1.79 4 4 4h4c2.21 0 4-1.79 4-4v-7c0-3.314-2.686-6-6-6z"/><path d="M12 5v14"/><path d="M16 9h-8"/><path d="M16 13h-8"/></svg>
                            <span class="skill-name">Supervised Learning</span>
                            <span class="skill-description">Classification & Regression models.</span>
                        </div>
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><path d="M12 5c-3.314 0-6 2.686-6 6v7c0 2.21 1.79 4 4 4h4c2.21 0 4-1.79 4-4v-7c0-3.314-2.686-6-6-6z"/><path d="M12 5v14"/><path d="M16 9h-8"/><path d="M16 13h-8"/></svg>
                            <span class="skill-name">Unsupervised Learning</span>
                            <span class="skill-description">Clustering & Dimensionality Reduction.</span>
                        </div>
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><path d="M12 5c-3.314 0-6 2.686-6 6v7c0 2.21 1.79 4 4 4h4c2.21 0 4-1.79 4-4v-7c0-3.314-2.686-6-6-6z"/><path d="M12 5v14"/><path d="M16 9h-8"/><path d="M16 13h-8"/></svg>
                            <span class="skill-name">Model Evaluation</span>
                            <span class="skill-description">Assessing model performance.</span>
                        </div>
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><path d="M12 5c-3.314 0-6 2.686-6 6v7c0 2.21 1.79 4 4 4h4c2.21 0 4-1.79 4-4v-7c0-3.314-2.686-6-6-6z"/><path d="M12 5v14"/><path d="M16 9h-8"/><path d="M16 13h-8"/></svg>
                            <span class="skill-name">Feature Engineering</span>
                            <span class="skill-description">Creating impactful features.</span>
                        </div>
                    </div>
                </div>

                <div class="bg-gray-50 p-6 rounded-xl shadow-sm">
                    <h4 class="text-xl font-semibold text-gray-800 mb-4">Statistical Methods</h4>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><path d="M18 4H6l6 8-6 8h12"/></svg>
                            <span class="skill-name">Hypothesis Testing</span>
                            <span class="skill-description">Statistical inference.</span>
                        </div>
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><path d="M22 3H2l8 12.46V21l4-2v-3.54L22 3z"/></svg>
                            <span class="skill-name">Data Wrangling</span>
                            <span class="skill-description">Cleaning & transforming data.</span>
                        </div>
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><path d="M3 3v18h18"/><path d="m18 10-6 6-4-4L3 14"/></svg>
                            <span class="skill-name">Probability Distributions</span>
                            <span class="skill-description">Understanding data patterns.</span>
                        </div>
                    </div>
                </div>

                <div class="bg-gray-50 p-6 rounded-xl shadow-sm">
                    <h4 class="text-xl font-semibold text-gray-800 mb-4">Databases</h4>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><path d="M11 20A7 7 0 0 1 9.8 6.1C15.5 5 17 4.48 19 2c1 2 2 4.5 2 6.5A7 7 0 0 1 11 20z"/><path d="M17 13H8a2 2 0 0 0-2 2c0 1 0.5 2 1 3h4"/></svg>
                            <span class="skill-name">MongoDB</span>
                            <span class="skill-description">NoSQL database.</span>
                        </div>
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><ellipse cx="12" cy="5" rx="9" ry="3"/><path d="M3 5V19A9 3 0 0 0 12 22A9 3 0 0 0 21 19V5"/><path d="M3 12A9 3 0 0 0 12 15A9 3 0 0 0 21 12"/></svg>
                            <span class="skill-name">Microsoft SQL Server</span>
                            <span class="skill-description">Relational database.</span>
                        </div>
                    </div>
                </div>

                <div class="bg-gray-50 p-6 rounded-xl shadow-sm">
                    <h4 class="text-xl font-semibold text-gray-800 mb-4">Tools & Platforms</h4>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><path d="M2 6h4"/><path d="M2 10h4"/><path d="M2 14h4"/><path d="M2 18h4"/><path d="M7 2h14v20H7z"/></svg>
                            <span class="skill-name">Jupyter Notebook</span>
                            <span class="skill-description">Interactive computing.</span>
                        </div>
                        <div class="skill-card">
                            <svg class="skill-icon" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" stroke-linecap="round" stroke-linejoin="round"><line x1="6" x2="6" y1="3" y2="15"/><path d="M18 6V3"/><path d="M18 18v3"/><path d="M12 21a6 6 0 0 0 3-5.5 5.77 5.77 0 0 0-1.5-3.5L12 10l-2.5-2.5a5.77 5.77 0 0 0-1.5-3.5A6 6 0 0 0 6 3"/></svg>
                            <span class="skill-name">Git</span>
                            <span class="skill-description">Version control.</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section class="py-8 border-b border-gray-100">
            <h3 class="section-title">My Projects</h3>
            <div class="space-y-6">
                <div class="project-card">
                    <h4 class="text-2xl project-title mb-2">
                        <a href="https://github.com/YourGitHubUsername/Academic-Success-ML-Model-Repo" target="_blank" class="hover:underline">Best ML Model for Academic Success</a>
                    </h4>
                    <p class="project-description">
                        Developed and benchmarked multiple machine learning models to accurately predict academic success, focusing on robust data preprocessing and feature importance analysis.
                    </p>
                    <p class="project-tech">
                        **Technologies:** Python (Pandas, NumPy, Matplotlib, Scikit-Learn)
                    </p>
                </div>
                <div class="project-card">
                    <h4 class="text-2xl project-title mb-2">
                        <a href="https://github.com/YourGitHubUsername/House-Price-Prediction-Repo" target="_blank" class="hover:underline">House Price Prediction</a>
                    </h4>
                    <p class="project-description">
                        Constructed and compared various machine learning models for precise house price prediction, implementing advanced data preprocessing and generating interactive visualizations.
                    </p>
                    <p class="project-tech">
                        **Technologies:** Python (Pandas, NumPy, Plotly, Scikit-Learn)
                    </p>
                </div>
                <div class="project-card">
                    <h4 class="text-2xl project-title mb-2">
                        <a href="https://github.com/YourGitHubUsername/Titanic-Classifier-Repo" target="_blank" class="hover:underline">Random Forest Classifier for Titanic Dataset</a>
                    </h4>
                    <p class="project-description">
                        Built and optimized a Random Forest Classifier to predict survival outcomes, including essential data preprocessing and comprehensive model evaluation.
                    </p>
                    <p class="project-tech">
                        **Technologies:** Python (Pandas, NumPy, Matplotlib, Scikit-Learn)
                    </p>
                </div>
            </div>
        </section>

        <section class="py-8 border-b border-gray-100">
            <h3 class="section-title">Experience</h3>
            <div class="space-y-4">
                <div class="info-card">
                    <h4 class="text-xl info-card-title">Joint Secretary | Statistical Pioneer Club, Rajshahi College</h4>
                    <p class="info-card-subtitle">May 2024 – Present | Rajshahi</p>
                    <ul class="list-disc list-inside info-card-description space-y-1">
                        <li>Streamlined information management systems and provided critical technical assistance for club events.</li>
                    </ul>
                </div>
                <div class="info-card">
                    <h4 class="text-xl info-card-title">Cultural Secretary | Statistical Pioneer Club, Rajshahi College</h4>
                    <p class="info-card-subtitle">March 2023 – May 2024 | Rajshahi</p>
                    <ul class="list-disc list-inside info-card-description space-y-1">
                        <li>Directed digital content creation and managed data handling for participant registration and reporting.</li>
                    </ul>
                </div>
            </div>
        </section>

        <section class="py-8 border-b border-gray-100">
            <h3 class="section-title">Education</h3>
            <div class="space-y-3">
                <div class="info-card">
                    <h4 class="text-xl info-card-title">BSc in Statistics</h4>
                    <p class="info-card-description">Rajshahi College, Rajshahi</p>
                </div>
                <div class="info-card">
                    <h4 class="text-xl info-card-title">Higher Secondary Certificate (HSC)</h4>
                    <p class="info-card-description">Police Lines School and College, Rangpur</p>
                </div>
                <div class="info-card">
                    <h4 class="text-xl info-card-title">Secondary School Certificate (SSC)</h4>
                    <p class="info-card-description">Bir Uttam Shaheed Samad School and College, Rangpur</p>
                </div>
            </div>
        </section>

        <section class="py-8 border-b border-gray-100">
            <h3 class="section-title">Certifications</h3>
            <div class="space-y-3">
                <div class="info-card">
                    <h4 class="text-xl info-card-title">Applied Data Science Lab</h4>
                    <p class="info-card-description">Data Science Badge | WorldQuant University</p>
                </div>
                <div class="info-card">
                    <h4 class="text-xl info-card-title">Data Scientist Certification Program</h4>
                    <p class="info-card-description">Ostad</p>
                </div>
            </div>
        </section>

        <section class="py-8">
            <h3 class="section-title">Connect With Me</h3>
            <div class="flex flex-wrap gap-4 justify-center">
                <a href="https://www.linkedin.com/in/your-linkedin-profile/" target="_blank" class="profile-button btn-linkedin text-white">
                    LinkedIn
                </a>
                <a href="https://www.yourpersonalwebsite.com" target="_blank" class="profile-button btn-website text-white">
                    Personal Website
                </a>
                <a href="mailto:mirzashatu@gmail.com" class="profile-button btn-email text-white">
                    Email
                </a>
            </div>
            <div class="mt-12 text-center">
                <h4 class="text-2xl font-semibold text-gray-700 mb-6">My GitHub Activity</h4>
                <img src="https://github-readme-stats.vercel.app/api?username=YourGitHubUsername&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="Mirza Razibul Islam Shatu's GitHub stats" class="github-stats-img">
            </div>
        </section>
    </div>
</body>
</html>

<h1 align="center">MOVIE DATABASE MANAGEMENT SYSTEM</h1>

<p align="center">
<img src="https://img.shields.io/badge/last%20commit-january-blue" alt="last commit january">
<img src="https://img.shields.io/badge/Updated-January-green" alt="Updated January">
<img src="https://img.shields.io/badge/JavaScript-60%25-yellow" alt="JavaScript 60%">
<img src="https://img.shields.io/badge/Python-40%25-orange" alt="Python 40%">
<img src="https://img.shields.io/badge/languages-2-red" alt="languages 2">
</p>

---

<h3 align="center">Built with the tools and technologies:</h3>

<p align="center">
<img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" alt="React">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white" alt="Flask">
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white" alt="SQLite">
<img src="https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML">
<img src="https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS">
<img src="https://img.shields.io/badge/Semantic_UI-35BDB2?style=flat&logo=semantic-ui&logoColor=white" alt="Semantic UI">
<img src="https://img.shields.io/badge/CSV_Import-FF6B6B?style=flat&logo=file-csv&logoColor=white" alt="CSV Import">
<img src="https://img.shields.io/badge/REST_API-FF6B6B?style=flat&logo=api&logoColor=white" alt="REST API">
<img src="https://img.shields.io/badge/CRUD_Operations-42B883?style=flat&logo=database&logoColor=white" alt="CRUD Operations">
<img src="https://img.shields.io/badge/Infinite_Scroll-28A745?style=flat&logo=scroll&logoColor=white" alt="Infinite Scroll">
</p>

<h2>Introduction</h2>

<p>The <code>Movie Database Management System</code> is a powerful, full-stack web application for efficient movie data management. It provides a modern React frontend with a Flask backend and SQLite database, offering complete CRUD operations for movie collections without requiring complex setup or advanced database knowledge.</p>

<h2>Benefits</h2>

<ul>
<li><strong>Complete Movie Management</strong>: Create, read, update, and delete movie entries with detailed information</li>
<li><strong>Real-time Search</strong>: Instant search functionality with live filtering by movie titles</li>
<li><strong>User-Friendly Interface</strong>: Modern React UI with Semantic UI components for intuitive navigation</li>
<li><strong>RESTful API</strong>: Clean Flask backend with proper HTTP methods and JSON responses</li>
<li><strong>CSV Data Import</strong>: Bulk import movie data from CSV files with automatic UUID generation</li>
<li><strong>Infinite Scroll</strong>: Seamless pagination with automatic loading of more content</li>
<li><strong>Real-time Updates</strong>: Live UI updates when movies are added, edited, or deleted</li>
<li><strong>Modern Design</strong>: Beautiful interface with responsive design and smooth animations</li>
</ul>

<h2>Features</h2>

<ul>
<li>✓ <strong>Full CRUD Operations</strong>: Create, read, update, and delete movie entries</li>
<li>✓ <strong>Advanced Search</strong>: Real-time search by movie title with pagination</li>
<li>✓ <strong>CSV Import</strong>: Bulk import movie data from CSV files</li>
<li>✓ <strong>Infinite Scroll</strong>: Automatic loading of more movies as you scroll</li>
<li>✓ <strong>Modal Interface</strong>: Detailed movie view and editing in modal dialogs</li>
<li>✓ <strong>Database Management</strong>: SQLite database with proper schema and relationships</li>
<li>✓ <strong>RESTful API</strong>: Complete REST API with proper HTTP methods</li>
<li>✓ <strong>Error Handling</strong>: Comprehensive error handling and user feedback</li>
<li>✓ <strong>Responsive Design</strong>: Works on different screen sizes and devices</li>
<li>✓ <strong>Modern UI Components</strong>: Built with Semantic UI React components</li>
</ul>

<h2>Guide to Using the Movie Database System</h2>

<h3>Prerequisites</h3>

<ol>
<li><strong>Node.js & Yarn</strong>: You need Node.js and Yarn package manager installed</li>
<li><strong>Python 3</strong>: Python 3.x with pip package manager</li>
<li><strong>Modern Browser</strong>: Works on modern browsers (Chrome, Firefox, Safari, Edge)</li>
<li><strong>Development Environment</strong>: Code editor like VS Code or similar</li>
</ol>

<h3>Installation & Usage</h3>

<ol>
<li><strong>Clone the Repository</strong>:
   <pre><code>git clone [repository-url]
cd flask-react-app</code></pre>
</li>

<li><strong>Install Dependencies</strong>:
   <ul>
   <li>Install React dependencies: <code>yarn install</code></li>
   <li>Install Python dependencies: <code>cd api && pip install -r requirements.txt</code></li>
   </ul>
</li>

<li><strong>Initialize Database</strong>:
   <ul>
   <li>Start the Flask API: <code>yarn start-api</code></li>
   <li>Initialize database: Visit <code>http://localhost:5000/initdb</code></li>
   <li>Populate with sample data: Visit <code>http://localhost:5000/populatedb</code></li>
   </ul>
</li>

<li><strong>Start the Application</strong>:
   <ul>
   <li>Start React frontend: <code>yarn start</code></li>
   <li>Open browser to <code>http://localhost:3000</code></li>
   </ul>
</li>
</ol>

<h3>Available Scripts</h3>

<ul>
<li><strong>yarn start</strong>: Runs the React app in development mode at localhost:3000</li>
<li><strong>yarn start-api</strong>: Starts the Flask API server at localhost:5000</li>
<li><strong>yarn build</strong>: Builds the app for production</li>
<li><strong>yarn test</strong>: Launches the test runner</li>
</ul>

<h3>API Endpoints</h3>

<ul>
<li><strong>GET /movies</strong>: Retrieve all movies with pagination</li>
<li><strong>GET /movies/{id}</strong>: Get specific movie by ID</li>
<li><strong>POST /movies</strong>: Create new movie entry</li>
<li><strong>PUT /movies/{id}</strong>: Update existing movie</li>
<li><strong>DELETE /movies/{id}</strong>: Delete movie entry</li>
<li><strong>GET /search/{term}</strong>: Search movies by title</li>
<li><strong>GET /initdb</strong>: Initialize database schema</li>
<li><strong>GET /populatedb</strong>: Populate database from CSV</li>
</ul>

<h2>Technical Details</h2>

<h3>Frontend Technologies</h3>

<ul>
<li>» <strong>React 17.0.1</strong> - Modern JavaScript library for building user interfaces</li>
<li>» <strong>Semantic UI React 2.0.1</strong> - React components for beautiful UI</li>
<li>» <strong>React Scripts 4.0.0</strong> - Build tools and development server</li>
<li>» <strong>Web Vitals 0.2.4</strong> - Performance monitoring and optimization</li>
<li>» <strong>Testing Library</strong> - Comprehensive testing utilities</li>
</ul>

<h3>Backend Technologies</h3>

<ul>
<li>» <strong>Flask 1.1.2</strong> - Lightweight Python web framework</li>
<li>» <strong>SQLite3</strong> - Embedded database for data storage</li>
<li>» <strong>Werkzeug 1.0.1</strong> - WSGI toolkit for Flask</li>
<li>» <strong>Jinja2 2.11.2</strong> - Template engine for Python</li>
<li>» <strong>UUID</strong> - Unique identifier generation for database records</li>
</ul>

<h3>Database Schema</h3>

<pre><code>CREATE TABLE movies (
    id TEXT NOT NULL PRIMARY KEY,
    release_year TEXT,
    title TEXT,
    origin TEXT,
    director TEXT,
    cast TEXT,
    genre TEXT,
    wiki_page TEXT,
    plot TEXT
)</code></pre>

<h3>Key Features</h3>

<ul>
<li>✓ <strong>Infinite Scroll</strong>: Automatic loading with Visibility component</li>
<li>✓ <strong>Real-time Search</strong>: Instant filtering with debounced input</li>
<li>✓ <strong>Modal Management</strong>: Detailed view and editing in modal dialogs</li>
<li>✓ <strong>State Management</strong>: React hooks for component state</li>
<li>✓ <strong>Error Handling</strong>: Comprehensive error handling and user feedback</li>
<li>✓ <strong>Responsive Design</strong>: Mobile-friendly interface</li>
</ul>

<h2>Project Structure</h2>

<pre><code>flask-react-app/
├── api/
│   ├── api.py              # Flask backend API
│   ├── requirements.txt    # Python dependencies
│   ├── movies.db          # SQLite database
│   └── movie_plots.csv    # Sample data
├── src/
│   ├── components/
│   │   ├── MovieTable/     # Main movie listing component
│   │   └── MovieModal/     # Movie detail/edit modal
│   ├── App.js             # Main React component
│   └── index.js           # React entry point
├── public/                # Static assets
└── package.json          # Node.js dependencies</code></pre>

<h2>Development Features</h2>

<ul>
<li>✓ <strong>Hot Reload</strong>: Automatic browser refresh on code changes</li>
<li>✓ <strong>Proxy Configuration</strong>: Seamless API communication</li>
<li>✓ <strong>ESLint Integration</strong>: Code quality and consistency</li>
<li>✓ <strong>Testing Setup</strong>: Jest and React Testing Library</li>
<li>✓ <strong>Build Optimization</strong>: Production-ready builds</li>
</ul>

<h2>Future Enhancements</h2>

<ul>
<li><strong>SQLAlchemy Integration</strong>: Replace basic SQLite with ORM</li>
<li><strong>Enhanced Security</strong>: Input validation and SQL injection prevention</li>
<li><strong>Advanced Filtering</strong>: Filter by genre, year, director, etc.</li>
<li><strong>User Authentication</strong>: Login system and user management</li>
<li><strong>File Upload</strong>: Direct CSV file upload via API</li>
<li><strong>Export Functionality</strong>: Export data to various formats</li>
<li><strong>Advanced UI</strong>: Better styling and animations</li>
<li><strong>Automated Testing</strong>: Comprehensive test coverage</li>
</ul>

<h2>Support & Updates</h2>

<ul>
<li><strong>Email</strong>: Contact through <a href="https://hiubdn.com">hiubdn.com</a></li>
<li><strong>Issues</strong>: Report bugs and feature requests</li>
<li><strong>Documentation</strong>: Comprehensive guides and tutorials</li>
<li><strong>Contributions</strong>: Open source development</li>
</ul>

<h2>License</h2>

<p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>

<h2>Disclaimer</h2>

<p>This application is for educational and demonstration purposes. Users are responsible for data security and backup. The developers are not responsible for any data loss or misuse.</p>

---
<p align="center"><strong>Powered by <a href="https://hiubdn.com">hiubdn</a> - Enhanced Version</strong></p>

<p align="center"><em>Copyright hiubdn - All rights reserved</em></p>

<p align="center">
<img src="https://img.shields.io/github/stars/yourusername/facebook-bm-admin-tool?style=social" alt="GitHub stars">
<img src="https://img.shields.io/github/forks/yourusername/facebook-bm-admin-tool?style=social" alt="GitHub forks">
<img src="https://img.shields.io/github/issues/yourusername/facebook-bm-admin-tool?style=social" alt="GitHub issues">
</p>

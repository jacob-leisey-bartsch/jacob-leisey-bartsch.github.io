<link href="./style.css" type="text/css" rel="stylesheet">

# Professional Work
Due to the confidential/proprietary nature of many of these projects, I am unable to share code from these projects. However, I do discuss these projects at a high level and provide some details about tools and methods used.

# Navigation
* [Home](https://jacob-leisey-bartsch.github.io)
* [Professional Work](https://jacob-leisey-bartsch.github.io/pages/professional-work)
* [Personal Projects](https://jacob-leisey-bartsch.github.io/pages/personal-projects)
* [Down Time](https://jacob-leisey-bartsch.github.io/pages/down-time)

# BNY
<div class="jlb-dark-section">
	<h2 id="dockerization">Production Deployment of Internal Applications</h2>
	<p>Goal:</p>
	<ul>
		<li>Transform internally developed, locally hosted applications into production-ready services via containerization.</li>
	</ul>
	<p>Tech Stack:</p>
	<ul>
		<li>Application Frameworks:
			<ul>
				<li>Streamlit (Python)</li>
				<li>FastAPI (Python)</li>
				<li>PyPI Server (Python)</li>
				<li>Shiny (R)</li>
			</ul>
		</li>
		<li>Containerization:
			<ul>
				<li>Docker</li>
				<li>Docker Swarm</li>
			</ul>
		</li>
		<li>Infrastructure:
			<ul>
				<li>Gitlab Runners on Linux-based servers</li>
			</ul>
		</li>
	</ul>
	<p>Results:</p>
	<ul>
		<li>Converted dozens of locally hosted applications into production-ready Docker containers that reduced environment-specific issues.</li>
		<li>Enabled faster and more reliable releases that could be completed with the single click of a button.</li>
	</ul>
</div>

<div class="jlb-dark-section">
	<h2 id="dashboard-modernization">Dashboard Modernization</h2>
	<p>Goal:</p>
	<ul>
		<li>Modernize the team's internal dashboard development process by identifying a framework that could better support the rapidly growing demand for dashboards while simultaneously reducing the development complexity and maintenance overhead.</li>
	</ul>
	<p>Tech Stack:</p>
	<ul>
		<li>Streamlit</li>
		<li>Plotly Dash</li>
	</ul>
	<p>Results:</p>
	<ul>
		<li>Researched and established Streamlit as the preferred framework for new analytical applications, allowing the team to keep pace with rapidly increasing demand from both internal stakeholders and external clients.</li>
		<li>Reduced average dashboard development time from approximately one month to one week, enabling the team to increase delivery capacity by roughly 4×.</li>
	</ul>
</div>

<div class="jlb-dark-section">
	<h2 id="python-packaging">Python Packaging</h2>
	<p>Goal:</p>
	<ul>
		<li>Develop a centralized Python package to consolidate shared business logic, data access utilities, and financial calculations used across multiple internal analytics applications.</li>
	</ul>
	<p>Tech Stack:</p>
	<ul>
		<li>Languages:
			<ul>
				<li>Python</li>
			</ul>
		</li>
		<li>Core Functionality:
			<ul>
				<li>Portfolio uploads and downloads</li>
				<li>Performance calculations</li>
				<li>Data transformation utilities</li>
				<li>Shared visualization components</li>
			</ul>
		</li>
		<li>Package Deployment:
			<ul>
				<li>Gitlab Package Registry</li>
				<li>Internally hosted PyPI Server</li>
			</ul>
		</li>
	</ul>
	<p>Results:</p>
	<ul>
		<li>Designed and maintained a reusable Python package that standardized functionality across our internal analytics projects.</li>
		<li>Eliminated duplicated code by centralizing common business logic, reducing maintenance effort while improving code consistency.</li>
		<li>Accelerated future application development by providing a shared library of tested, reusable components.</li>
	</ul>
</div>

# VISIMO
<div class="jlb-dark-section">
	<h2 id="agility-prime">Agility Prime</h2>
	<p>Goal:</p>
	<ul>
		<li>Develop a real-time object detection system capable of identifying collision hazards in first-person aerial footage and deploy an accessible web portal enabling users to analyze drone video without specialized tooling.</li>
	</ul>
	<p>Tech Stack:</p>
	<ul>
		<li>Training Data:
			<ul>
				<li>100,000+ annotated frames from VisDrone dataset</li>
				<li>~15 minutes of proprietary footage</li>
			</ul>
		</li>
		<li>Model:
			<ul>
				<li>YOLO-based object detection model (trained on VisDrone + proprietary footage)</li>
				<li>Google Colab GPU instances for model training and hyperparameter tuning</li>
			</ul>
		</li>
		<li>Data Processing:
			<ul>
				<li>Python (OpenCV) for frame extraction, preprocessing, and bounding box rendering</li>
			</ul>
		</li>
		<li>Application Layer:
			<ul>
				<li>Python (Streamlit) for interactive web interface</li>
			</ul>
		</li>
		<li>Deployment:
			<ul>
				<li>Docker containerization for reproducible local deployment</li>
			</ul>
		</li>
	</ul>
	<p>Results:</p>
	<ul>
		<li>Trained an object detection model that identified collision hazards up to 0.5 seconds earlier than the baseline benchmark model, improving reaction time for downstream avoidance systems.</li>
		<li>Built and deployed an interactive web application enabling users to upload drone footage and receive annotated hazard overlays within seconds.</li>
	</ul>
</div>

<div class="jlb-dark-section">
	<h2 id="nixn">NIXN</h2>
	<p>Goal:</p>
	<ul>
		<li>Develop a browser-based application that allows construction safety professionals to preemptively and efficiently assess risk at their sites and prescribe optimal corrective actions to reduce injuries.</li>
	</ul>
	<p>Tech Stack:</p>
	<ul>
		<li>Application Layer:
			<ul>
				<li>Python (Django)</li>
				<li>JavaScript (jQuery)</li>
			</ul>
		</li>
		<li>Data Management:
			<ul>
				<li>PostgreSQL database for persistent storage of risks, violations, and remediation guidance</li>
			</ul>
		</li>
		<li>User Interface:
			<ul>
				<li>Multi-page workflow for recording activity, violations, and generating corrective recommendations</li>
				<li>Self-service administrative pages that allowed designated superusers to manage users, activities, and risk scores</li>
				<li>Self-service reporting that allowed power-users the ability to generate comprehensive reports broken down along multiple key factors</li>
			</ul>
		</li>
		<li>Deployment:
			<ul>
				<li>Docker containerization for reproducible deployment</li>
			</ul>
		</li>
	</ul>
	<p>Results:</p>
	<ul>
		<li>Built and deployed a multi-page web application that simplified the process of documenting construction safety violations and retrieving recommended corrective actions.</li>
		<li>Centralized safety observations and remediation guidance in a searchable database, reducing reliance on manual documentation and improving consistency across inspections.</li>
		<li>Delivered an intuitive interface that enabled field personnel to quickly record findings and generate reports with minimal training.</li>
	</ul>
</div>

<div class="jlb-dark-section">
	<h2 id="virtual-waiting-room">Virtual Waiting Room</h2>
	<p>Goal:</p>
	<ul>
		<li>Develop a web-based virtual waiting room platform that enabled medical practices to safely manage patient check-in, communication, and appointment flow while minimizing unnecessary in-person contact during the COVID-19 pandemic.</li>
	</ul>
	<p>Tech Stack:</p>
	<ul>
		<li>Application Layer:
			<ul>
				<li>Python (Django)</li>
				<li>JavaScript (jQuery)</li>
			</ul>
		</li>
		<li>Database:
			<ul>
				<li>PostgreSQL</li>
			</ul>
		</li>
		<li>Real-Time Communication:
			<ul>
				<li>Python (websockets)</li>
				<li>Redis</li>
			</ul>
		</li>
		<li>Messaging:
			<ul>
				<li>Twilio SMS integration</li>
			</ul>
		</li>
	</ul>
	<p>Results:</p>
	<ul>
		<li>Built and deployed a multi-page web application that allowed patients to remotely check in, receive appointment updates, and communicate with medical staff in real-time without entering crowded waiting rooms.</li>
		<li>Developed an administrative portal for managing patient information, appointment workflows, and site content, providing healthcare staff with a centralized management interface.</li>
		<li>Designed the application to meet HIPAA requirements by ensuring all protected health information remained on-premises, implementing tokenization for personally identifiable information (PII), and adhering to strict security practices throughout the application architecture.</li>
	</ul>
</div>

# Internships
<div class="jlb-dark-section">
	<h2 id="sap-ariba">SAP Ariba</h2>
	<p>Developed demand forecasting models using time-series techniques including temporal regression, ARIMA, and vector autoregression, and validated model performance using a rolling-horizon backtesting framework.</p>
</div>

<div class="jlb-dark-section">
	<h2 id="mylan">Mylan</h2>
	<p>Analyzed high-potential international markets by combining external demographic data with internal sales data, applying dimensionality reduction and regression modeling to identify expansion opportunities, and presenting findings to leadership.</p>
</div>

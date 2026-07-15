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
	<p>Developed a multi-page web application enabling construction safety specialists to record workplace safety violations and receive recommended remediation actions to reduce risk. Built an administrative portal allowing users to manage violations and remediation guidance.</p>
</div>

<div class="jlb-dark-section">
	<h2 id="virtual-waiting-room">Virtual Waiting Room</h2>
	<p>Developed a multi-page web application that enabled medical offices to operate virtual waiting rooms during the pandemic, reducing unnecessary in-person contact between patients. Built integrated messaging, automated SMS notifications, and an administrative portal for managing patient data and site content.</p>
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

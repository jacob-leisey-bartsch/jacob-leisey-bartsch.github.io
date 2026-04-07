# Professional Work
Due to the confidential/proprietary nature of many of these projects, I am unable to share code from these projects. However, I do discuss these projects at a high level and provide some details about tools and methods used.

# Navigation
* [Home](https://jacob-leisey-bartsch.github.io)
* [Professional Work](https://jacob-leisey-bartsch.github.io/pages/professional-work)
* [Personal Projects](https://jacob-leisey-bartsch.github.io/pages/personal-projects)
* [Down Time](https://jacob-leisey-bartsch.github.io/pages/down-time)

# BNY
## Dockerization
Containerized our python applications to support the proper testing of applications prior to deployments, which led to a significant decrease in the number of required redeployments. Additionally, I assembled a set of Dockerfiles that allowed the test environments to access hard-to-reach internal package repositories.

## Python Packaging
Designed and maintained a multi-module Python package that standardized common functionality across projects, including portfolio uploads/downloads, return calculations, and API data retrieval.

## Dashboarding
Led internal research into state-of-the-art dashboarding technologies, presented findings to senior management, and ultimately convinced them to transition away from Dash and adopt Streamlit instead.


# VISIMO
## Agility Prime
<div style="color: #f5fcff; background-color: #303136; border-radius: 15px; padding-left: 20px; padding-right: 20px; padding-top: 10px; padding-bottom: 10px; margin-bottom: 10px;">
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

## NIXN
Developed a multi-page web application enabling construction safety specialists to record workplace safety violations and receive recommended remediation actions to reduce risk. Built an administrative portal allowing users to manage violations and remediation guidance.

## Virtual Waiting Room
Developed a multi-page web application that enabled medical offices to operate virtual waiting rooms during the pandemic, reducing unnecessary in-person contact between patients. Built integrated messaging, automated SMS notifications, and an administrative portal for managing patient data and site content.

# SAP Ariba
Developed demand forecasting models using time-series techniques including temporal regression, ARIMA, and vector autoregression, and validated model performance using a rolling-horizon backtesting framework.

# Mylan
Analyzed high-potential international markets by combining external demographic data with internal sales data, applying dimensionality reduction and regression modeling to identify expansion opportunities, and presenting findings to leadership.
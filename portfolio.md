---
layout: page
title: Portfolio
image: assets/images/arctic_wave.jpg
nav-menu: true
---

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Conferences and Publications</h1>
		</header>
		<li>Train, evaluate, monitor, infer: End-to-end machine learning in Elastic. <a href="https://www.elastic.co/blog/train-evaluate-monitor-infer-end-to-end-machine-learning-in-elastic"> Learn more</a></li>
		<li>Joshi, A., (2019, October). Using Lexical Features for Malicious URL Detection- A Machine Learning Approach. Paper to be presented at Conference on Applied Machine Learning for Information Security (CAMLIS), Washington, DC, USA. <a href="https://www.camlis.org/2019/talks/joshi"> Learn more</a></li>
		<li>Wang, X., Joshi, A., Zhao, K., Zhou, X., (2018, December). Social Support and User Churn Prediction for Online Health Communities -- A Trajectory-based Deep Learning Method. Paper presented at the 28th Workshop on Information Technology and Systems (WITS), California, USA.</li>
		<li>Master's Thesis: Trajectory-based methods to predict user churn in online health edict user churn in online health communities. <a href="https://ir.uiowa.edu/cgi/viewcontent.cgi?article=7709&context=etd"> Learn more</a></li>
	</div>
</section>

<!-- Two -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Projects</h1>
		</header>

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<a href="portfolio.html" class="image">
			<img src="{% link assets/images/viz.jpg %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Model Monitoring Pipeline</h3>
				</header>
				<p>Designed a pipeline to visually evaluate the efficacy of candidate production machine learning models and monitor their performance after deployment. The pipeline processes metadata from more than 200 million PE binaries prior to every model release to generate a set of dashboards to validate the new model for production by comparing it against previous model versions and other VirusTotal AV vendors. Post deployment, the model performance is monitored in almost realtime and alerts are generated if performance deteriorates.
				<br />
				<b>Technology used: Python, AWS Batch, Elasticsearch, Kibana</b>
				</p>
			</div>
		</div>
	</section>
	<section>
		<a href="portfolio.html" class="image">
			<img src="{% link assets/images/anomaly.jpg %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>ProblemChild in the Elastic Stack</h3>
				</header>
				<p>Implemented an Elastic Stack based solution to identify anomalous and rare parent-child relationships in local user environments. A binary classification model was trained in the Elastic Stack to identify malicious Windows process events. Elastic Anomaly Detection was then used to prioritize malicious events containing anomalous and rare parent-child relationships for security analysts to investigate. 
				<br />
				<b>Technology used: Elasticsearch, Kibana</b>
				</p>
			</div>
		</div>
	</section>
	<section>
		<a href="portfolio.html" class="image">
			<img src="{% link assets/images/url.jpg %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Malicious URL Detection</h3>
				</header>
				<p>Scoped and developed a fast, lightweight Random Forest model for malicious URL detection using a combination of static lexical features and ngrams derived from URL strings. The model resulted in a 22% increase in detections coming from FireEye's URL Detection Engine. 
				<br />
				<b>Technology used: Python, NLTK, Scikit-Learn (Random Forest), AWS (several services)</b>
				</p>
			</div>
		</div>
	</section>
	<section>
		<a href="portfolio.html" class="image">
			<img src="{% link assets/images/phishing.jpg %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Clustering to identify phishing campaigns</h3>
				</header>
				<p>Built a clustering algorithm using Transfer Learning and Annoy to cluster screenshots of webpages, which was used to identify and detect large phishing campaigns in FireEye's URL Detection Engine. A pre-trained Deep CNN model was used to learn features from the webpage screenshots and Annoy was used for approximate clustering since the algorithm was expected to deal with ~9 million URLs per day.
				<br />
				<b>Technology used: Python, Keras (TensorFLow backend), Annoy, AWS (several services)</b>
				</p>
			</div>
		</div>
	</section>
	<section>
		<a href="portfolio.html" class="image">
			<img src="{% link assets/images/nlp.jpg %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Predicting user churn in online health communities</h3>
				</header>
				<p>Used an NLP and ensemble learning approach to categorize ~3 million user posts contributed by ~50,000 users on an online health community into different types of social support. These annotated posts were then used to create state trajectories to capture the change in posting activity of users across several months. Finally, the trajectories were used as inputs to a Bayesian model to predict the probability of a user churning from the community.
				<br />
				<b>Technology used: Python, NLTK, Gensim, GCP</b>
				</p>
			</div>
		</div>
	</section>

</div>

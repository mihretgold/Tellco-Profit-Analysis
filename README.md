<h1>TellCo Profit Analysis</h1>

<h2>Overview</h2>
<p>
    This project focuses on conducting a comprehensive analysis of TellCo, an existing mobile service provider, to determine opportunities for growth and profitability. The analysis involves exploring a telecom dataset to extract insights into user behavior, engagement, experience, and satisfaction. The project aims to provide valuable recommendations to the investor regarding whether TellCo is worth buying or selling.
</p>

<h2>Project Structure</h2>
<ul>
    <li><strong>src/</strong>: Contains the main Python scripts for data analysis and dashboard creation.</li>
    <li><strong>notebooks/</strong>: Contains Jupyter notebooks for exploratory data analysis and documentation.</li>
    <li><strong>tests/</strong>: Includes unit tests for ensuring code reliability and correctness.</li>
    <li><strong>scripts/</strong>: Additional scripts for data preprocessing or specific tasks.</li>
    <li><strong>requirements.txt</strong>: Lists all Python dependencies required for the project.</li>
    <li><strong>README.md</strong>: Detailed documentation outlining project objectives, tasks, and instructions for running the project.</li>
    <li><strong>.gitignore</strong>: Specifies files and directories to be ignored by version control.</li>
    <li><strong>.github/workflows/unittests.yml</strong>: GitHub Actions workflow for running unit tests.</li>
    <li><strong>Dockerfile</strong>: Configuration for building the project as a Docker image.</li>
</ul>

<h2>Project Tasks</h2>
<p>The project is divided into four main tasks:</p>
<ol>
    <li><strong>Task 1: User Overview Analysis</strong></li>
    <ul>
        <li>Identify top handsets used by customers.</li>
        <li>Identify top handset manufacturers.</li>
        <li>Identify top handsets per manufacturer.</li>
        <li>Analyze user behavior on various applications.</li>
    </ul>
    <li><strong>Task 2: User Engagement Analysis</strong></li>
    <ul>
        <li>Track engagement metrics such as session frequency, duration, and total traffic.</li>
        <li>Classify customers into engagement groups using k-means clustering.</li>
        <li>Analyze engagement per application and cluster users accordingly.</li>
    </ul>
    <li><strong>Task 3: Experience Analytics</strong></li>
    <ul>
        <li>Aggregate network parameters and device characteristics per customer.</li>
        <li>Analyze TCP retransmission, RTT, throughput, and handset type.</li>
        <li>Conduct k-means clustering to segment users based on experience metrics.</li>
    </ul>
    <li><strong>Task 4: Satisfaction Analysis</strong></li>
    <ul>
        <li>Assign engagement and experience scores to users.</li>
        <li>Calculate satisfaction score as the average of engagement and experience scores.</li>
        <li>Predict satisfaction score using regression modeling.</li>
        <li>Perform k-means clustering on engagement and experience scores.</li>
        <li>Export user data with engagement, experience, and satisfaction scores to a local MySQL database.</li>
    </ul>
</ol>

<h2>Running the Project</h2>
<ol>
    <li>Clone the repository to your local machine.</li>
    <li>Install dependencies using <code>pip install -r requirements.txt</code>.</li>
    <li>Run unit tests to ensure code integrity.</li>
    <li>Execute the main Python scripts for data analysis and dashboard creation.</li>
    <li>Deploy the Docker image for easy distribution and deployment.</li>
</ol>

<h2>Results and Recommendations</h2>
<p>The analysis will provide valuable insights into TellCo's performance, customer behavior, and areas for improvement. Based on the findings, recommendations will be made to the investor regarding the potential purchase or sale of TellCo.</p>

<h2>Author</h2>
<ul>
    <li>Mihret Agegnehu</li>
</ul>

<h2>Conclusion</h2>
<p>The TellCo Profit Analysis project aims to leverage data-driven insights to make informed decisions regarding the investment in TellCo. By analyzing user behavior, engagement, experience, and satisfaction, the project aims to uncover opportunities for growth and profitability in the telecommunications industry.</p>

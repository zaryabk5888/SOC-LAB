<h1>SOC-LAB</h1>

<p><strong>Cybersecurity Project</strong></p>

<h2>Challenges</h2>
<p>Setting up Elastic (SIEM) </p>
<p>Since the project is on cloud i was finally able to understand how to effectively use public and private ip </p>
<p></p>

<h2>Project Overview</h2>

<p>This project demonstrates a cybersecurity mechanism to protect a Windows 10 system, collect data, and analyze logs for threat detection.</p>

<h3>Components</h3>

<ul>
    <li><strong>Victim (Windows 10):</strong> Target system connected to enforcing rules and data collection.</li>
    <li><strong>Enforcing Rules:</strong> Mechanisms/protocols safeguarding the system.</li>
    <li><strong>LimaCharlie Web:</strong> Tool collecting data from Windows 10 for analysis.</li>
    <li><strong>Azure:</strong> Cloud service storing and analyzing logs.</li>
    <li><strong>Attacker C&C:</strong> Monitored system for suspicious activities.</li>
    <li><strong>Elastic Siem Ubuntu:</strong> Security tool analyzing logs and detecting threats.</li>
</ul>

<h3>Architecture Diagram</h3>

<img src="images/architecture.png" alt="SOC-LAB Architecture">

<h2>How to Run the Project</h2>

<h3>Requirements</h3>

<ul>
    <li>Windows 10</li>
    <li>LimaCharlie Web</li>
    <li>Azure</li>
    <li>Elastic Siem Ubuntu</li>
</ul>

<h3>Instructions</h3>

<p>Refer to detailed instructions: <a href="https://blog.ecapuano.com/p/so-you-want-to-be-a-soc-analyst-intro">https://blog.ecapuano.com/p/so-you-want-to-be-a-soc-analyst-intro</a>.</p>

<h2>Additional Points</h2>

<ul>
    <li>Prebuilt Elastic Dashboards (e.g., Powershell commands) are helpful.</li>
    <li>AgentTesla detection using the dashboard demonstrates effectiveness.</li>
    <li>Own malware (sliver-server) created for controlled damage and log observation.</li>
    <li>Data dumping from lsass.exe, a crucial Windows security process.</li>
    <li>LimaCharlie rule creation for lsass.exe detection and successful testing.</li>
</ul>

<h2>Screenshots</h2>

<img src="images/dashboard.png" alt="Powershell Commands Dashboard">
<img src="images/logondashboard.png" alt="Logon Dashboard">
<img src="images/lsass.exe.png" alt="lsass.exe Process">
<img src="images/lsassrulecreation.png" alt="LimaCharlie Rule Creation">
<img src="images/lsassrulework.png" alt="LimaCharlie Rule Working">

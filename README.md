<style>
:root {
    /* Light theme variables */
    --bg-gradient-start: #667eea;
    --bg-gradient-end: #764ba2;
    --container-bg: rgba(255, 255, 255, 0.95);
    --container-border: rgba(255, 255, 255, 0.2);
    --header-gradient-start: #f093fb;
    --header-gradient-end: #f5576c;
    --text-primary: #1f2937;
    --text-secondary: #4c1d95;
    --text-accent: #6366f1;
    --section-bg: rgba(248, 250, 252, 0.8);
    --details-bg: rgba(248, 250, 252, 0.6);
    --details-border: rgba(102, 126, 234, 0.2);
    --summary-bg: rgba(102, 126, 234, 0.1);
    --blockquote-bg: rgba(102, 126, 234, 0.1);
    --shadow-color: rgba(0, 0, 0, 0.1);
    --divider-gradient-start: #667eea;
    --divider-gradient-end: #764ba2;
}

/* Dark theme variables */
@media (prefers-color-scheme: dark) {
    :root {
        --bg-gradient-start: #1a1a2e;
        --bg-gradient-end: #16213e;
        --container-bg: rgba(30, 41, 59, 0.95);
        --container-border: rgba(71, 85, 105, 0.3);
        --header-gradient-start: #6366f1;
        --header-gradient-end: #8b5cf6;
        --text-primary: #f1f5f9;
        --text-secondary: #a78bfa;
        --text-accent: #818cf8;
        --section-bg: rgba(51, 65, 85, 0.6);
        --details-bg: rgba(51, 65, 85, 0.4);
        --details-border: rgba(139, 92, 246, 0.3);
        --summary-bg: rgba(139, 92, 246, 0.2);
        --blockquote-bg: rgba(139, 92, 246, 0.15);
        --shadow-color: rgba(0, 0, 0, 0.3);
        --divider-gradient-start: #6366f1;
        --divider-gradient-end: #8b5cf6;
    }
}

body {
    background: linear-gradient(135deg, var(--bg-gradient-start) 0%, var(--bg-gradient-end) 100%);
    min-height: 100vh;
    margin: 0;
    padding: 20px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: var(--text-primary);
    transition: all 0.3s ease;
}

.resume-container {
    background: var(--container-bg);
    backdrop-filter: blur(10px);
    border-radius: 20px;
    box-shadow: 0 20px 40px var(--shadow-color);
    padding: 40px;
    margin: 0 auto;
    max-width: 900px;
    border: 1px solid var(--container-border);
    transition: all 0.3s ease;
}

.header-section {
    background: linear-gradient(135deg, var(--header-gradient-start) 0%, var(--header-gradient-end) 100%);
    margin: -40px -40px 30px -40px;
    padding: 40px;
    border-radius: 20px 20px 0 0;
    color: white;
    text-align: center;
}

.section-divider {
    background: linear-gradient(90deg, var(--divider-gradient-start), var(--divider-gradient-end));
    height: 3px;
    border: none;
    border-radius: 2px;
    margin: 30px 0;
    transition: all 0.3s ease;
}

table {
    background: var(--section-bg);
    border-radius: 12px;
    padding: 20px;
    box-shadow: 0 4px 12px var(--shadow-color);
    transition: all 0.3s ease;
}

details {
    background: var(--details-bg);
    border-radius: 12px;
    padding: 15px;
    margin: 10px 0;
    border: 1px solid var(--details-border);
    transition: all 0.3s ease;
}

details summary {
    cursor: pointer;
    font-weight: 600;
    color: var(--text-secondary);
    padding: 10px;
    border-radius: 8px;
    background: var(--summary-bg);
    transition: all 0.3s ease;
}

details[open] summary {
    margin-bottom: 15px;
}

h1, h2, h3, h4, h5, h6 {
    color: var(--text-primary);
    transition: color 0.3s ease;
}

h2 {
    color: var(--text-secondary);
    border-bottom: 2px solid var(--divider-gradient-start);
    padding-bottom: 5px;
}

h3 {
    color: var(--text-accent);
}

blockquote {
    background: var(--blockquote-bg);
    border-left: 4px solid var(--divider-gradient-start);
    padding: 20px;
    border-radius: 0 12px 12px 0;
    font-style: italic;
    color: var(--text-secondary);
    transition: all 0.3s ease;
}

/* Ensure links work well in both themes */
a {
    color: var(--text-accent);
    transition: color 0.3s ease;
}

a:hover {
    color: var(--header-gradient-start);
}

/* Enhanced contrast for better readability */
strong {
    color: var(--text-primary);
    font-weight: 600;
}

/* Smooth transitions for theme switching */
* {
    transition: background-color 0.3s ease, color 0.3s ease, border-color 0.3s ease;
}
</style>

<div class="resume-container">
<div class="header-section">

<img src="image.png" width="120" height="120" style="border-radius: 60px; object-fit: cover; border: 3px solid white; box-shadow: 0 8px 16px rgba(0,0,0,0.2);"/>

# RAGUNATH MARKANDAN
### 🚀 Lead Engineer | Solution Architect | Technical Consultant
**New Zealand Citizen**

📧 **mragunath@outlook.com** | 📱 **+64 22 160 7798** | 🔗 **[LinkedIn](https://www.linkedin.com/in/ragunath-markandan/)**

📍 **Upper Hutt, Wellington, New Zealand**

</div>
</div>

<hr class="section-divider">

## 🎯 EXECUTIVE SUMMARY

**20+ years** of experience as a **quality-focused Technical Leader** specializing in solution design, engineering excellence, and digital transformation. Proven track record in architecting and delivering scalable, high-impact solutions that drive measurable business outcomes.

**Core Expertise:** Full-stack development • Cloud architecture • Team leadership • DevOps practices • Enterprise systems

> *"Transforming complex technical challenges into elegant, scalable solutions that deliver continuous value"*

<hr class="section-divider">

## 💻 TECHNICAL EXPERTISE

<table>
<tr>
<td><strong>🚀 Languages</strong></td>
<td>C# • Java • Python • JavaScript</td>
</tr>
<tr>
<td><strong>🧪 Testing</strong></td>
<td>xUnit • Cypress • Selenium • Playwright • JUnit • TestNG</td>
</tr>
<tr>
<td><strong>💾 Data</strong></td>
<td>Snowflake • SQL Server • PostgreSQL • MongoDB • DynamoDB • Couchbase • Oracle</td>
</tr>
<tr>
<td><strong>📡 Messaging</strong></td>
<td>AWS SQS/SNS • Apache Kafka • IBM MQ • RabbitMQ</td>
</tr>
<tr>
<td><strong>⚡ Serverless</strong></td>
<td>AWS Lambda • Azure Functions • Step Functions • Logic Apps</td>
</tr>
<tr>
<td><strong>🐳 Containers</strong></td>
<td>Amazon EKS • Azure AKS • Red Hat OpenShift</td>
</tr>
<tr>
<td><strong>🏗️ IaC</strong></td>
<td>Terraform • AWS CDK • PowerShell • Vagrant</td>
</tr>
<tr>
<td><strong>🔄 CI/CD</strong></td>
<td>TeamCity • Azure Pipelines • AWS CodePipeline • Jenkins • Spinnaker</td>
</tr>
<tr>
<td><strong>☁️ Cloud</strong></td>
<td>AWS • Microsoft Azure • VMware vCenter</td>
</tr>
<tr>
<td><strong>📊 Monitoring</strong></td>
<td>Dynatrace • Sumo Logic • New Relic • Datadog</td>
</tr>
</table>

<hr class="section-divider">

## 🏢 PROFESSIONAL EXPERIENCE

### 🚀 Lead Engineer
**Kiwibank** | 📅 *Nov 2021 – Present* | 📍 *Wellington, NZ*

<details>
<summary><strong>Key Achievements & Responsibilities</strong></summary>

✅ **Technical Leadership**: Drive cross-functional technical initiatives, solving high-impact challenges across multiple teams  
✅ **Engineering Excellence**: Define and champion core engineering principles for consistency, scalability, and technical excellence  
✅ **Team Development**: Mentor and grow 5+ engineers while partnering with Engineering Managers on talent development  
✅ **Strategic Decision Making**: Lead complex technical decisions with high risk/low reversibility impact  
✅ **Team Scaling**: Bootstrap and scale new engineering teams from inception to production readiness  
✅ **Collaboration**: Foster effective multidisciplinary squad collaboration for high-quality deliverables

</details>

<hr class="section-divider">

### ⚡ Senior Engineer
**Xero Ltd** | 📅 *Apr 2018 – Nov 2021* | 📍 *Wellington, NZ*

<details>
<summary><strong>Key Achievements & Responsibilities</strong></summary>

**🎯 Core Responsibilities:**
- ✅ **Product Excellence**: Developed high-quality, scalable software products through collaborative cross-functional teamwork
- ✅ **Technical Leadership**: Contributed to solution architecture designs and conducted comprehensive code reviews
- ✅ **Engineering Standards**: Championed Xero's engineering practices and standards across software delivery processes
- ✅ **DevOps Innovation**: Automated development lifecycle for seamless CI/CD implementation
- ✅ **Platform Enhancement**: Drove platform-wide improvement and stabilization initiatives
- ✅ **Team Mentorship**: Provided technical guidance and knowledge sharing to ensure best practice adoption

**🏆 Key Achievements:**
- 🚀 **Process Automation**: Successfully automated delivery processes for continuous integration and deployment
- 📈 **Agile Optimization**: Identified and improved agile methodologies and delivery processes for enhanced efficiency
- 🎯 **Incident Leadership**: Led critical incident responses and post-mortems, proactively identifying and resolving future issues
- 👥 **Talent Acquisition**: Participated in technical interviews to identify top talent, collaborating closely with leadership
- ⏰ **Crisis Management**: Demonstrated exceptional ability to prioritize and coordinate time-sensitive, critical responsibilities
- 🏦 **Domain Expertise**: Developed deep expertise in bank-feeds domain architecture and scalability
- 🌟 **Strategic Secondment**: 8-month assignment with "Sums of Anarchy" team, training on latest technologies (K8s, .NET Core)
- 🤝 **Team Building**: Built trust through open communication and continuous feedback loops
- ☁️ **Platform Pioneer**: Early adopter of PaaS Kubernetes platform, successfully implementing through to production
- 📚 **Knowledge Equity**: Ensured equal opportunities for team members to acquire domain and technical expertise

</details>

<hr class="section-divider">

### 🏛️ Technical Lead/Technical Consultant
**DXC Technology** | 📅 *Oct 2012 – Apr 2018* | 📍 *Wellington, NZ*

<details>
<summary><strong>Key Achievements & Responsibilities</strong></summary>

**🎯 Core Responsibilities:**
- 🏛️ **Mission-Critical Leadership**: Led cross-functional development team for **New Zealand Passport System** - high-availability national identity platform
- 🔧 **End-to-End Delivery**: Managed complete software lifecycle from design reviews to production maintenance
- 🤝 **Client Partnership**: Collaborated closely with government clients to ensure business continuity and operational excellence
- 💾 **Database Excellence**: Led database development initiatives including performance optimization and scalability enhancements
- 🚨 **Crisis Management**: Efficiently managed high-severity production issues with rapid resolution and minimal downtime
- 💡 **Innovation Leadership**: Identified and championed adoption of emerging technologies through regular team discussions

**🏆 Key Achievements:**
- ✅ **Government Compliance**: Ensured adherence to strict government standards for data privacy, security, and availability
- ✅ **Stakeholder Collaboration**: Built strong relationships with business stakeholders, architects, and QA teams
- ✅ **System Reliability**: Delivered robust, scalable digital services supporting millions of citizens and government agencies
- ✅ **Performance Optimization**: Achieved significant database performance improvements through strategic optimization
- ✅ **Team Development**: Fostered continuous learning culture through technology knowledge sharing sessions

</details>

<hr class="section-divider">

### 🏗️ Technical Architect/Technical Lead
**HCL Technologies** | 📅 *Jun 2010 – Sep 2012* | 📍 *Wellington, NZ*

<details>
<summary><strong>Key Achievements & Responsibilities</strong></summary>

**🎯 Core Responsibilities:**
- 🌍 **Global Team Leadership**: Led both onshore (Wellington) and offshore development teams for **New Zealand Corrections Systems**
- 🏛️ **Critical Infrastructure**: Managed design, development, and maintenance of public safety and justice operation systems
- 🤝 **Business Continuity**: Partnered closely with government clients to ensure seamless business-as-usual operations
- 🚨 **Production Excellence**: Efficiently resolved high-severity production issues with minimal impact to critical services
- 👥 **Knowledge Transfer**: Championed IOMS application architecture education for new team members
- 🔧 **Cross-Functional Support**: Provided technical assistance to testing and support teams for rapid problem resolution

**🏆 Key Achievements:**
- ✅ **Quality Standards**: Maintained exceptional code quality and system reliability across full SDLC
- ✅ **Regulatory Compliance**: Delivered secure, scalable solutions meeting stringent government operational requirements
- ✅ **Innovation Pioneer**: Led POC development for cross-platform communication between desktop and web applications
- ✅ **Legacy Integration**: Successfully implemented parallel running of legacy and modern systems with seamless communication
- ✅ **Team Development**: Mentored team members on complex system architecture and best practices
- ✅ **Problem Resolution**: Established efficient troubleshooting processes reducing incident response time

</details>

<hr class="section-divider">

### 💊 Senior Software Engineer
**iSOFT R&D PVT Ltd** | 📅 *Jun 2008 – Jun 2010* | 📍 *India*

<details>
<summary><strong>Key Achievements & Responsibilities</strong></summary>

**🎯 Core Responsibilities:**
- 🏥 **Healthcare Innovation**: Core developer for **LORENZO Care Event Management** module serving UK NHS
- 🔧 **Framework Development**: Collaborated on core framework development including enhancements and critical bug fixes
- 💾 **Database Optimization**: Led database development initiatives with focus on performance optimization
- 🔄 **Build Automation**: Managed integrated build processes using NAnt and CruiseControl.NET for Care Event modules
- 🧪 **Quality Assurance**: Implemented comprehensive unit testing frameworks using NUnit for care modules
- 🎨 **UI/UX Development**: Designed intuitive user interfaces and developed custom controls for healthcare workflows

**🏆 Key Achievements:**
- ✅ **Critical Systems**: Delivered mission-critical healthcare software supporting national health services
- ✅ **Performance Excellence**: Achieved significant database performance improvements for large-scale healthcare data
- ✅ **Quality Standards**: Established robust testing environments ensuring high-quality deliverables
- ✅ **Crisis Management**: Efficiently resolved high-severity issues in production healthcare environments
- ✅ **Development Environment**: Created optimized development and testing environments for team productivity

</details>

<hr class="section-divider">

### 🌐 Software Engineer
**TEKSOFT CS PVT LTD** | 📅 *May 2003 – Jun 2008* | 📍 *India*

<details>
<summary><strong>Key Achievements & Responsibilities</strong></summary>

**🎯 Core Responsibilities:**
- 🚀 **Web Innovation**: Designed and developed cutting-edge reusable AJAX-based web controls
- 🎨 **UI/UX Excellence**: Created intuitive graphical user interfaces with custom functionality based on client specifications
- 🧪 **Quality Assurance**: Implemented comprehensive unit testing protocols ensuring high-quality deliverables
- 🤝 **Cross-Team Collaboration**: Partnered with Quality Analysis teams to track and resolve project module issues
- 📚 **Best Practices**: Applied industry-standard design and implementation practices under expert guidance

**🏆 Key Achievements:**
- ✅ **Component Architecture**: Built scalable, reusable frontend components for enterprise applications
- ✅ **Client Satisfaction**: Delivered custom solutions meeting diverse client requirements and specifications
- ✅ **Quality Excellence**: Maintained zero-defect delivery through rigorous testing and quality control processes
- ✅ **Process Improvement**: Contributed to development process optimization and standardization
- ✅ **Technical Foundation**: Established strong foundation in software engineering principles and practices

</details>

<hr class="section-divider">

## 🎓 EDUCATION

🏛️ **Master of Computer Applications** | Bharathidasan University, India  
🏛️ **Bachelor of Computer Applications** | Bharathidasan University, India

<hr class="section-divider">

## 🌟 KEY DIFFERENTIATORS

- 🎯 **Government Systems Expertise**: Proven track record with mission-critical national systems (Passport, Corrections)
- 🚀 **Scale Leadership**: Successfully scaled teams and systems at high-growth companies (Xero, Kiwibank)
- 🔄 **Full-Stack Versatility**: End-to-end delivery capability from architecture to production support
- 🌍 **Global Experience**: Led distributed teams across multiple time zones and cultures
- 📈 **Business Impact**: Consistent delivery of solutions that drive measurable business outcomes

<hr class="section-divider">

<div align="center">

*"Bridging the gap between complex technical challenges and elegant business solutions"*

**Last Updated: August 2025** | **Available for opportunities in New Zealand and Australia**

</div>

</div>

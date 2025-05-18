Overview

The OWASP Risk Calculator is a web-based tool designed to assist security professionals, developers, and organizations in assessing the risk associated with potential vulnerabilities in their applications. It leverages the OWASP Risk Rating Methodology to provide a structured approach to risk assessment.

By inputting various factors related to threat agents, vulnerabilities, and potential impacts, users can calculate:

    Likelihood Score: The probability of a vulnerability being exploited.

    Impact Score: The potential damage resulting from an exploit.

    Overall Risk Rating: A qualitative measure (e.g., Low, Medium, High, Critical) derived from the likelihood and impact scores.

This tool aids in prioritizing security efforts by identifying the most critical risks that require immediate attention.
Features

    User-Friendly Interface: Intuitive design for easy input of risk factors.

    Real-Time Calculations: Immediate feedback on risk scores as inputs are adjusted.

    Comprehensive Risk Factors: Includes threat agent factors, vulnerability factors, technical impact factors, and business impact factors.

    Visual Representation: Clear display of calculated scores to facilitate understanding.

Technologies Used

    HTML: Structures the content and layout of the web application.

    CSS: Styles the application for an aesthetically pleasing and responsive design.

    JavaScript: Implements the logic for calculating risk scores based on user inputs.

Implementation Details

The application is a single-page web application (SPA) that operates entirely on the client side. Here's how it works:

    Input Collection: Users select options for various risk factors categorized under:

        Threat Agent Factors: Skill level, motive, opportunity, and size.

        Vulnerability Factors: Ease of discovery, ease of exploit, awareness, and intrusion detection.

        Technical Impact Factors: Loss of confidentiality, integrity, availability, and accountability.

        Business Impact Factors: Financial damage, reputation damage, non-compliance, and privacy violation.

    Score Calculation:

        Each selected option has an associated numerical value (typically on a scale from 0 to 9).

        Likelihood Score: Calculated as the average of threat agent and vulnerability factors.

        Impact Score: Calculated as the average of technical and business impact factors.

        Overall Risk Rating: Determined by mapping the likelihood and impact scores to a qualitative rating (e.g., Low, Medium, High, Critical).

    Result Display: The calculated scores and overall risk rating are displayed dynamically as users adjust their inputs.

Use Cases

    Security Assessments: Evaluate the risk associated with identified vulnerabilities.

    Prioritization: Determine which vulnerabilities require immediate remediation based on their risk ratings.

    Educational Tool: Aid in teaching the OWASP Risk Rating Methodology.

    Decision Support: Assist stakeholders in making informed decisions regarding security investments.

How to Use

    Access the Application: Navigate to the Live Demo.

    Input Risk Factors: Select appropriate options for each risk factor category.

    Review Results: Observe the calculated likelihood score, impact score, and overall risk rating.

    Adjust Inputs: Modify selections to explore how changes affect the risk assessment.

Project Structure

owasp-risk-calculator/
├── index.html        # Main HTML file containing the structure of the application.
├── styles.css        # CSS file for styling the application.
├── script.js         # JavaScript file containing the logic for calculations.
└── README.md         # Project documentation.

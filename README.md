# Alteryx-Project
Alteryx Workflow Project-User Access Review
Overview
This repository contains an Alteryx workflow developed as part of a class project. The goal of the project was to create an automated process that consolidates data from various sources, including current users with access, new hires, and terminated employees. The workflow ultimately generates a comprehensive list of users whose access needs to be reviewed, ensuring that the organization maintains secure and up-to-date access controls.

Project Details
Tool Used: Alteryx
Objective: To streamline and automate the process of identifying users whose access permissions require review by combining data from current users, new hires, and terminated employees.
Key Outputs:
A consolidated list of all users with access.
Identification of users requiring access review, based on their current status.
Workflow Structure
1. Data Input and Preparation
Current Users Data: Import data containing details of current users who have access to various systems within the organization.
New Hires Data: Import data related to recently hired employees who may require new access permissions.
Terminated Employees Data: Import data for employees who have been terminated, indicating access that needs to be revoked.
2. Data Transformation and Combination
Data Cleansing: The workflow cleanses and standardizes the input data to ensure consistency across all datasets.
Data Joins: The workflow then joins the datasets, combining current users, new hires, and terminated employees into a single comprehensive dataset.
Flagging for Review: The workflow flags users who require an access review, such as terminated employees who still have access or new hires who need access permissions.
3. Output and Reporting
Consolidated Access List: The final output is a list of all users with access, including those flagged for review.
Review Report: A report is generated that highlights users who need immediate attention, ensuring that the organization's access controls are properly maintained.
Key Benefits
Automation: The workflow automates the process of identifying access issues, saving time and reducing the risk of human error.
Comprehensive Review: By combining multiple data sources, the workflow provides a complete view of user access, making it easier to identify and address potential security risks.
Scalability: The workflow can be easily adapted to handle larger datasets or additional data sources, making it a flexible solution for growing organizations.
Conclusion
This Alteryx workflow project provides a robust solution for managing user access reviews within an organization. By automating the process of combining and analyzing data from various sources, the workflow helps ensure that access controls are kept secure and up-to-date.

Feel free to explore the workflow, adapt it to your own needs, or use it as a learning tool for Alteryx and data management best practices. If you have any questions or suggestions, don't hesitate to reach out!

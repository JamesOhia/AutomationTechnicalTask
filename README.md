#Automation Technical Quiz Solution
This document outlines the solution for the Automation Technical Quiz, which includes tasks related to UI automation using Selenium WebDriver with NUnit and SpecFlow, as well as API testing using Postman and RestSharp.

UI Automation Solution
Task Description
The UI automation task involves navigating to Amazon's website as an unregistered user, searching for a specific item, adding it to the cart, and validating the correctness of the item and its amount in the cart.

Implementation Details
SpecFlow Feature File: AmazonItemFeature.feature contains the Gherkin scenarios defining the steps for the UI automation task.
Step Definitions: The steps are implemented in C# using SpecFlow in the AmazonItemSteps.cs file. This includes navigation, searching for the item, adding it to the cart, and validation.
Page Object Model: The automation framework utilizes the Page Object Model pattern for better organization and maintenance of elements and actions. The page objects are defined in the AmazonItemPage.cs file.
Video Proof
A video demonstrating the execution of the UI automation test can be found here [link](https://youtu.be/8ePmjxrvvxw).

API Testing Solution
Task Description
The API testing task involves sending a request to an API endpoint using Postman, verifying the status code, and validating the response body to ensure it contains expected data.

Implementation Details
Postman Test Script: A JavaScript test script within Postman is created to verify the status code and check for expected properties in the response body.
Export to RestSharp: The scenarios in Postman are exported to RestSharp, which allows for programmatically sending requests and validating responses using C#.
C# Test Script: The exported scenarios are implemented in C# using RestSharp in the Program.cs file. This includes sending the request, verifying the status code, and validating the response body properties.
Submission Details
Files
The complete solution code for both UI and API automation tasks is provided.
The Newman HTML report for Postman tests is included in the document files.
GitHub Repository
The solution code and related files are available in the GitHub repository [link](https://github.com/JamesOhia/AutomationTechnicalTask/).

Google Drive
Additional documentation(Solution code) and files, including the video proof, are available in the Google Drive folder [link](https://drive.google.com/drive/folders/1bkblW4S3fDp2l83kFBuXSVQXlMfONjBf?usp=sharing).

Conclusion
The provided solution demonstrates proficiency in UI and API automation using industry-standard tools and best practices. The inclusion of video proof and comprehensive documentation ensures transparency and credibility in the submission. If you have any questions or require further clarification, please feel free to reach out.

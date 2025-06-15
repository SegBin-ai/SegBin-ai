# SegBin.AI

click on the thumbnail below for demo video

[![Video Thumbnail](https://img.youtube.com/vi/xi4odXWze9k/0.jpg)](https://www.youtube.com/watch?v=xi4odXWze9k)

https://www.youtube.com/watch?v=xi4odXWze9k

3D Sketch of Dustbin
![3D drawing](images/Drawing.jpg)


## Table of Contents
- [Project summary](#project-summary)
  - [The issue we are hoping to solve](#the-issue-we-are-hoping-to-solve)
  - [How our technology solution can help](#how-our-technology-solution-can-help)
  - [Our idea](#our-idea)
- [Technology implementation](#technology-implementation)
  - [IBM AI service(s) used](#ibm-ai-services-used)
  - [Other IBM technology used](#other-ibm-technology-used)
  - [Solution architecture](#solution-architecture)
- [Presentation materials](#presentation-materials)
  - [Solution demo video](#solution-demo-video)
  - [Project development roadmap](#project-development-roadmap)
- [Additional details](#additional-details)
  - [How to run the project](#how-to-run-the-project)
  - [Live demo](#live-demo)

_INSTRUCTIONS: Complete all required deliverable sections below._

## Project summary

### The issue we are hoping to solve

Improper waste segregation poses significant environmental and financial challenges. In colleges, even students often neglect to separate waste correctly, leading to damaged recyclables, increased landfill waste, and the labor-intensive task of sorting improperly discarded waste. This issue extends beyond universities, indicating a larger problem with waste management globally. The current approach of replacing traditional single-bin systems with costly three-bin recycling bins has improved diversion rates but falls short of expectations. Financial burdens arise from the need to hire workers for manual waste sorting. To address this problem, we developed a cost-effective solution that ensures minimal damage to recyclables by sorting waste at the point of disposal.

### How our technology solution can help

Smart waste sorting alternative to dustbins with AI, data insights, and revenue optimization.

### Our idea

We are proud to introduce two innovative waste management solutions: SegBin lite and SegBin X. SegBin lite is a sleek, plate-shaped device that can be placed on existing dustbins, offering automated waste sorting. Equipped with four adjustable openings, each corresponding to a waste category (plastic products, food waste, metals, and office products), SegBin lite utilizes a wide angle Full HD camera module and an infrared sensor. Users simply hold the trash above the camera for a few seconds, allowing our advanced algorithm to analyze the photo and open the appropriate hole for disposal.
Alternatively, along with all the features discussed SegBin X adds a smart separator system. Users can conveniently dispose of all their waste through the central hole, and our product automatically separates and sorts the items accordingly. Both solutions come with a comprehensive data analysis dashboard, empowering users with insights into their disposal trends. Leveraging AI-driven analytics, data visualization, and predictive modeling, customers gain valuable information on waste composition. Furthermore, our AI-powered chatbot offers suggestions on maximizing the use of each waste type. Additionally, our platform features an auction system connecting customers with waste buyers, optimizing their potential revenue.


### Why we are unique?

By revolutionizing the waste management process through automated waste sorting at the point of disposal, our innovative dustbin offers a streamlined solution that not only optimizes operational efficiency but also drives substantial cost savings for waste management companies. The labor-intensive task of manual waste sorting is significantly reduced, enabling our customers to reallocate their valuable resources to more critical endeavors, thereby enhancing overall productivity. Furthermore, our seamlessly integrable dustbin eliminates the need for expensive infrastructure modifications, seamlessly assimilating into existing waste management systems.

Our product goes beyond mere convenience and efficiency; it champions environmental sustainability by minimizing contamination and maximizing the recovery of recyclable materials. By empowering our customers to achieve their sustainability goals, our dustbin ensures a positive impact on the environment while fostering responsible waste management practices. Moreover, from our customer interviews in the university of Illinois waste transfer station leads and the coordinator of zero waste initiative we understood that our customers were not satisfied with the current system for waste management since the waste had to go through many stages to finally be sorted appropriately. Our customers also have to employ manual labor to sort the waste, which is both inefficient and expensive. Therefore, our product will help resolve all these issues in waste management by automatically sorting waste with high accuracy. 

In determining the success of our business venture, we have identified key performance metrics that will serve as vital indicators of our impact:
- Market Penetration: A pivotal measure of our success lies in the widespread adoption of our dustbin as the preferred waste management system. We aim to assess its acceptance by customers and ensure it meets their requirements without the need for significant additional sorting efforts.
- Waste Diversion Rate: Tracking the percentage of waste that is properly segregated and diverted from landfills will serve as a tangible demonstration of the efficacy of our solution in achieving waste management goals. This metric highlights our commitment to reducing environmental harm and promoting sustainable practices.
- Customer Satisfaction: Placing utmost importance on user experience, we prioritize customer satisfaction as a critical metric of success. By continuously refining our dustbin's ease of use and addressing customer feedback, we strive to cultivate high levels of satisfaction among our valued customers.
  
To effectively monitor these metrics, we have devised a comprehensive approach to data tracking and evaluation:

- Usage Analytics: Utilizing sophisticated analytics tools, we will gather data on dustbin usage patterns, encompassing frequency, duration, and user behavior. This data will provide insights into adoption rates, identify potential usage-related challenges, and guide future enhancements.
- Waste Audit Partnerships: Collaborating closely with waste management partners, we will conduct thorough waste audits to measure the diversion rate achieved by our dustbin. These audits will validate the effectiveness of our solution and enable us to make data-driven improvements.
- Customer Surveys: Regularly conducting customer surveys will afford us a deeper understanding of our customers' needs, preferences, and overall satisfaction. By actively seeking and acting upon feedback, we will continuously refine our dustbin's features and user experience.

Through these well-defined methods of tracking and evaluation, we are poised to measure our progress, ensure continuous improvement, and forge enduring relationships with our customers.

## Technology implementation

### IBM AI service(s) used

- IBM Watson Studio:
Instructions: The code run on watson studio is present as a python notebook in the Machine-learning model file.

IBM Watson Studio was utilized to improve and fine-tune the TensorFlow machine learning model. This iterative refinement process will lead to better prediction accuracy and performance.

### Under Development/Future IBM AI usage

- IBM Watson Assistant: IBM Watson Assistant serves a dual purpose in our system: first, it enables users to effortlessly navigate the dashboard hosted on IBM Cloud by answering their inquiries and guiding them through simple tasks with natural language interactions.
- Second, deployed on our website, Watson Assistant acts as a responsive customer support chatbot, readily addressing common queries and offering assistance, thereby enhancing user experience and engagement. 

![ChatBot](images/ezgif.com-video-to-gif.gif)

- IBM Analytics: We leverage IBM Analytics to process and analyze data from various sources, including the TensorFlow model's predictions and Cloudant-stored metrics. This provides valuable insights presented on the IBM Cloud-hosted dashboard.

### Other IBM technology used

All the technologies have been showcased in our demo video: https://www.youtube.com/watch?v=xi4odXWze9k

- Cloudant:
Our TensorFlow machine learning model interacts with IBM Cloudant, a NoSQL database service. The model sends data, such as predictions and training metrics, to Cloudant for storage and analysis. This data can be accessed, retrieved, and visualized through the system's dashboard.

- Node-RED:
We established communication between the Jetson Nano and ESP32 devices using Node-RED. MQTT (Message Queuing Telemetry Transport) protocol was used for device-to-device communication. Node-RED facilitated the exchange of data and commands between the devices, enabling seamless coordination.

- IBM Cloud Hosting:
The dashboard that displays the system's data and insights is hosted on the IBM Cloud platform. Users can access this dashboard from their web browsers to monitor the machine learning model's performance, view predictions, and interact with the system.

### Solution architecture

Diagram and step-by-step description of the flow of our solution:

![Solution Architecture](https://raw.githubusercontent.com/SegBin-ai/IBM-CFC-2023/main/images/Solution%20Architecture.jpeg)

## Presentation materials

### Solution demo video

https://www.youtube.com/watch?v=xi4odXWze9k

Feel free to watch the video by clicking on the image above.

### Dashboard demo link
https://segbindashboard-37lp.onrender.com

### Project development roadmap
See below for our proposed schedule on next steps after Call for Code 2023 submission.

https://github.com/SegBin-ai/IBM-CFC-2023/blob/main/5-year%20plan.pdf

#### Features of SegBin lite and SegBin X:

- Automated Waste Sorting:
SegBin lite: Four adjustable openings for different waste categories, activated by analyzing waste items through a camera.
SegBin X: Central hole for disposal, with a smart separator system that automatically sorts items into the appropriate waste categories.
- Advanced Imaging and Sensors:
Full HD camera module and infrared sensor for accurate waste detection and sorting.
- Data Analysis Dashboard:
Provides users with insights into disposal trends and waste composition.
Empowers users with actionable information through AI-driven analytics, data visualization, and predictive modeling.
- Auction System:
Connects customers with waste buyers to optimize potential revenue from recyclable materials.

#### Future Plans:

- Enhanced Waste Detection Algorithm:
Continuously improve waste sorting accuracy and efficiency through ongoing algorithm refinement.
Incorporate advanced machine learning techniques to handle a wider variety of waste items and optimize sorting decisions.
- AI-Driven Insights and Recommendations:
Develop more sophisticated AI algorithms to uncover deeper insights from waste management data.
Provide personalized recommendations to users for waste reduction and better disposal practices.
- Expanded Data Analytics:
Implement predictive modeling to forecast waste trends and enable proactive waste management strategies.
Enhance data visualization capabilities to make insights more accessible and actionable.
- Chatbot Enhancement:
Train the chatbot to handle a wide range of user queries and provide accurate and detailed suggestions.
Integrate Natural Language Processing (NLP) advancements for improved conversational capabilities.
- Geographical Expansion:
Expand the availability of SegBin lite and SegBin X to new regions and markets.
Adapt the technology to meet the waste management challenges specific to different areas.

#### Areas Where Assistance is Needed:

- Refining Waste Detection Algorithm:
Collaborate with AI and machine learning experts to improve the accuracy and robustness of waste sorting algorithms.
- Data Analytics and Insights:
Partner with data analytics specialists to develop advanced AI-driven insights and predictive modeling capabilities.
- Infrastructure Development:
Seek support in establishing efficient 3D printed component production and optimizing supply chain management.
Work with experts to seamlessly integrate hardware and software components.
- Chatbot Development:
Engage NLP experts to enhance the chatbot's conversational abilities and expand its knowledge base.

## Additional details

_INSTRUCTIONS: The following deliverables are suggested, but **optional**. Additional details like this can help the judges better review your solution. Remove any sections you are not using._

### How to run the project

INSTRUCTIONS: In this section you add the instructions to run your project on your local machine for development and testing purposes. You can also add instructions on how to deploy the project in production.

#### How to run ML model?
Download the Jupyter notebook in the Machine-Learning Model Folder and run all cells for Classfication of waste into the right category.

#### How to run ESP32 coder?
Download the files in the folder and flash the .ino file onto a ESP32 Tembed Device.

#### How to run the dashboard locally?

- step 1: clone the repository onto your local machine using git clone
- step 2: cd into the frontend folder and run npm install to install all the dependencies
- step 3: run npm start to start the front end
- step 4: cd into the back end folder and run nodemon (download if you haven't already) server


### Authors

- Aaditya Voruganti
- Pranav Chandra Varma Penmatcha

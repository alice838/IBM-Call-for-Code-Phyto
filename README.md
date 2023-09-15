[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Community](https://img.shields.io/badge/Join-Community-blue)](https://developer.ibm.com/callforcode/solutions/projects/get-started/)

_INSTRUCTIONS: This GitHub repository serves as a template you can use to create a new project for the [2023 Call for Code Global Challenge](https://developer.ibm.com/callforcode/global-challenge/). Use the **Use this template** button to create a new version of this repository and start entering content for your own Call for Code submission project. Make sure you have [registered for the 2023 Call for Code Global Challenge](https://developer.ibm.com/callforcode/global-challenge/register/) to access resources and full project submission instructions. Remove any "INSTRUCTIONS" sections when you are ready to submit your project._

_New to Git and GitHub? This free online course will get you up to speed quickly: [Getting Started with Git and GitHub](https://www.coursera.org/learn/getting-started-with-git-and-github)_.

# PHYTO 

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
- [About this template](#about-this-template)
  - [Contributing](#contributing)
  - [Versioning](#versioning)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

_INSTRUCTIONS: Complete all required deliverable sections below._

## Project summary

### The issue we are hoping to solve

Over 17 million hectares of land in Indonesia is used for coal mining, contaminating adjacent land with heavy metals and thereby reducing crop yield by up to 50%. Land rehabilitation is possible by executing phytoremediation, a process which uses certain crops to extract heavy metals from the soil. However, many farmers do not understand which plants are best for their land. 

### How our technology solution can help

Our solution designs a tailored phytoremediation plan for farmers by using geospatial and weather analytics. 

### Our idea
The solution seeks to address the issue of heavy metal contamination in farming land adjacent to coal mining sites in Indonesia. Farmers currently experience a 50% decrease in crop yields, leading to a decrease in income of up to Rp 10,000,000 (or AUD 1000) annually. While it is possible to rehabilitate land through phytoremediation, most farmers have neither adequate understanding nor sufficient resources to execute this process. 

Enter Phyto. Our app designs tailored phytoremediation plans using geospatial analytics and weather data. Unlike existing solutions which require extensive and expensive field testing, our app functions on completely remote technology. The app first detects the farmer’s location. It proceeds to use IBM Environmental Intelligence Suite to access satellite images of the location. These images are analyzed to determine contamination levels, soil conditions, moisture levels, and nearby vegetation. IBM Weather Data APIs enable analysis on weather conditions and forecasts of the location. These two data sources build an understanding of the farmer’s land and conditions. A machine learning model then processes the optimal growing conditions of seven phytoremediation plants. Finally, it selects the plant that is most suitable for the farmer based on their land conditions. 

The app selects one out of seven phytoremediation plants: vetiver, sunflower, jatropha, golden shower tree, water hyacinth, mangrove, and wild sugarcane. These plants are not only potent for rehabilitating land contaminated by heavy metals, but are also raw materials for a range of commercial products such as perfumes, essential oils, cosmetics, and even biofuels. This way, farmers are able to rehabilitate their land whilst still gaining financial returns. This whole process is powered by our app features. 

The app has four main features: plan, monitor, connect, and sell. The “plan” feature is the bulk of the solution, as it is responsible for designing the tailored phytoremediation plan. If the user is unable to plant the suggested crop, the app recommends alternatives. During the plantation process, the “monitor” feature provides access to growing guidelines, weather alerts, and land rehabilitation resources. The user can use the “connect” feature to engage with community members and experts. Lastly, the “sell” feature provides access to an online marketplace which connects farmers to small local businesses who are sourcing raw materials. The app hence provides farmers with an end-to-end phytoremediation plan, ensuring that the rehabilitation process is simple, accessible, and economically viable.

Phyto not only enables farmers to rehabilitate land, but is also easily scalable to large rehabilitation efforts around the world. Using the same technology, it is possible to determine the soil conditions of abandoned mining sites and design phytoremediation plans for these areas. The scalability of the solution reflects our main goal, to not only empower farmers, but also global change. Phyto proudly empowers the future of land rehabilitation.  

## Technology implementation

### IBM AI service(s) used

_INSTRUCTIONS: Included here is a list of commonly used IBM AI services. Remove any services you did not use, or add others from the linked catalog not already listed here. Leave only those included in your solution code. Provide details on where and how you used each IBM AI service to help judges review your implementation. Remove these instructions._

- [IBM Natural Language Understanding](https://cloud.ibm.com/catalog/services/natural-language-understanding) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Assistant](https://cloud.ibm.com/catalog/services/watson-assistant) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Discovery](https://cloud.ibm.com/catalog/services/watson-discovery) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Speech to Text](https://cloud.ibm.com/catalog/services/speech-to-text) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Text to Speech](https://cloud.ibm.com/catalog/services/text-to-speech) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- List any additional [IBM AI services](https://cloud.ibm.com/catalog?category=ai#services) used or remove this line

### Other IBM technology used

INSTRUCTIONS: List any other IBM technology used in your solution and describe how each component was used. If you can provide links to/details on exactly where these were used in your code, that would help the judges review your submission.

### Solution architecture

Diagram and step-by-step description of the flow of our solution:

![Video transcription/translaftion app](https://developer.ibm.com/developer/tutorials/cfc-starter-kit-speech-to-text-app-example/images/cfc-covid19-remote-education-diagram-2.png)

1. The user navigates to the site and uploads a video file.
2. Watson Speech to Text processes the audio and extracts the text.
3. Watson Translation (optionally) can translate the text to the desired language.
4. The app stores the translated text as a document within Object Storage.

## Presentation materials

_INSTRUCTIONS: The following deliverables should be officially posted to your My Team > Submissions section of the [Call for Code Global Challenge resources site](https://cfc-prod.skillsnetwork.site/), but you can also include them here for completeness. Replace the examples seen here with your own deliverable links._

### Solution demo video



### Project Phyto development roadmap

The project currently does the following things.

- Feature 1
- Feature 2
- Feature 3

In the near future, we plan to refine data sources in order to build a functional app that uses real-time, real-live data. We also plan to complete the app design, ensuring that all features work seamlessly. Following this, the app will be launched in East Kalimantan. After customer feedback is received, the app will be improved to enable a wider selection of phytoremediation plants. The improved  version will then be launched other areas of Indonesia, followed by deployment in South East Asia. 
Concurrently, we plan to execute collaboration efforts with manufacturers, as well as mining and environmental organisations. The aim of these efforts is to establish partnerships which enable large-scale rehabilitation efforts. We aim to partner with manufacturers who are willing to purchase the harvest of phytoremediation crops from farmers, thus enhancing the commercial value of the solution. Partnerships with environmental and mining organisations seek to establish large-scale rehabilitation opportunities using our solution. This will mainly focus on the opportunity to rehabilitate abandoned mining sites which are currently non-arable. The team will then develop a technological solution which is tailored to these efforts, called Phyto Enhance. Our roadmap reflects our overarching goal of redesigning the future of land rehabilitation and empowering positive global change. 

See below for our proposed roadmap after the Call for Code 2023 submission.

![Phyto Roadmap](https://github.com/alice838/IBM-Call-for-Code-Phyto/assets/141798368/fd418cb6-112c-43c8-9935-f481bf0f5328)


## Additional details

_INSTRUCTIONS: The following deliverables are suggested, but **optional**. Additional details like this can help the judges better review your solution. Remove any sections you are not using._

### How to run the project

INSTRUCTIONS: In this section you add the instructions to run your project on your local machine for development and testing purposes. You can also add instructions on how to deploy the project in production.

### Live demo

You can find a running system to test at...

See our [description document](./docs/DESCRIPTION.md) for log in credentials.

---

### License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- Based on [Billie Thompson's README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).

[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Community](https://img.shields.io/badge/Join-Community-blue)](https://developer.ibm.com/callforcode/solutions/projects/get-started/)

API Key: 9273f14c853b4634b3f14c853bd634ab

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

## Project summary

### The issue we are hoping to solve

Over 17 million hectares of land in Indonesia is used for coal mining, contaminating adjacent land with heavy metals and thereby reducing crop yield by up to 50%. Land rehabilitation is possible by executing phytoremediation, a process which uses certain crops to extract heavy metals from the soil. However, many farmers do not understand which plants are best for their land. 

### How our technology solution can help

Our solution designs a tailored phytoremediation plan for farmers by using geospatial and weather analytics. 

### Our idea
The solution seeks to address the issue of heavy metal contamination in farming land adjacent to coal mining sites in Indonesia. Farmers currently experience a 50% decrease in crop yields, leading to a decrease in income of up to Rp 10,000,000 (or AUD 1000) annually. While it is possible to rehabilitate land through phytoremediation, most farmers have neither adequate understanding nor sufficient resources to execute this process. 

Enter Phyto. Our app designs tailored phytoremediation plans using geospatial analytics. Unlike existing solutions which require extensive and expensive field testing, our app functions on completely remote technology. The app first detects the farmer’s location. It proceeds to use IBM Environmental Intelligence Suite to access satellite images of the location. These images are analyzed to determine contamination levels, soil conditions, moisture levels, and nearby vegetation. A Watson machine learning model then uses IBM Weather Data APIs to access these soil condition. It then selects the phytoremediation plant most suitable for the farmer based on their land conditions. 

The app selects one out of seven phytoremediation plants: vetiver, sunflower, jatropha, golden shower tree, water hyacinth, mangrove, and wild sugarcane. These plants are not only potent for rehabilitating land contaminated by heavy metals, but are also raw materials for a range of commercial products such as perfumes, essential oils, cosmetics, and even biofuels. This way, farmers are able to rehabilitate their land whilst still gaining financial returns. This whole process is powered by our app features. 

The app has four main features: plan, monitor, connect, and sell. The “plan” feature is the bulk of the solution, as it is responsible for designing the tailored phytoremediation plan. If the user is unable to plant the suggested crop, the app recommends alternatives. During the plantation process, the “monitor” feature provides access to growing guidelines, weather alerts, and land rehabilitation resources. The user can use the “connect” feature to engage with community members and experts. Lastly, the “sell” feature provides access to an online marketplace which connects farmers to small local businesses who are sourcing raw materials. The app hence provides farmers with an end-to-end phytoremediation plan, ensuring that the rehabilitation process is simple, accessible, and economically viable.

Phyto not only enables farmers to rehabilitate land, but is also easily scalable to large rehabilitation efforts around the world. Using the same technology, it is possible to determine the soil conditions of abandoned mining sites and design phytoremediation plans for these areas. The scalability of the solution reflects our main goal, to not only empower farmers, but also global change. Phyto proudly empowers the future of land rehabilitation.  

## Technology implementation

### IBM AI service(s) used

- IBM Weather Data APIs: The Weather Data APIs provide soil and weather conditions according to the user's location. 
- IBM Watson Studio: The IBM Watson Studio enables the creation and deployment of machine learning models. It is used to build a classification prediction model. It uses the information from the Weather Data APIs to select the most suitable phytoremediation plant. 
  
### Solution architecture

Diagram and step-by-step description of the flow of our solution:

![Screenshot 2023-10-11 094943](https://github.com/alice838/IBM-Call-for-Code-Phyto/assets/141798368/c560fa89-0ddd-4c03-80e6-0eba441830e9)

1. The user navigates to the app and inputs their location.
2. IBM Weather Data API is used to gather information about the soil and weather conditions of the user's location.
3. Watson Studio deploys a machine learning model to select the most suitable phytoremediation plant for the user.
4. The user receives a tailored phytoremediation plan. 


## Presentation materials

### Solution demo video
[![Phyto Demo](https://img.youtube.com/vi/TAaIGB7fXZM/0.jpg)](https://youtu.be/TAaIGB7fXZM)

### Project development roadmap

The project currently does the following things.

- Accepts the user's location using latitude and longitude
- Processes the user's location and recommends a suitable phytoremediation plant. 

In the near future, we plan to refine data sources in order to build a functional app that uses real-time, real-live data. We also plan to complete the app design, ensuring that all features work seamlessly. Following this, the app will be launched in East Kalimantan. After customer feedback is received, the app will be improved to enable a wider selection of phytoremediation plants. The improved  version will then be launched other areas of Indonesia, followed by deployment in South East Asia. 
Concurrently, we plan to execute collaboration efforts with manufacturers, as well as mining and environmental organisations. The aim of these efforts is to establish partnerships which enable large-scale rehabilitation efforts. We aim to partner with manufacturers who are willing to purchase the harvest of phytoremediation crops from farmers, thus enhancing the commercial value of the solution. Partnerships with environmental and mining organisations seek to establish large-scale rehabilitation opportunities using our solution. This will mainly focus on the opportunity to rehabilitate abandoned mining sites which are currently non-arable. The team will then develop a technological solution which is tailored to these efforts, called Phyto Enhance. Our roadmap reflects our overarching goal of redesigning the future of land rehabilitation and empowering positive global change. 

See below for our proposed roadmap after the Call for Code 2023 submission.

![Phyto Roadmap](https://github.com/alice838/IBM-Call-for-Code-Phyto/assets/141798368/fd418cb6-112c-43c8-9935-f481bf0f5328)


## Additional details

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

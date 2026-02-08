# Smart Food Safety Auditor
Building AI course project

## Summary
The "Smart Food Safety Auditor" is an AI-powered system designed to identify foreign objects in food (such as bones, plastic, or hair) through image recognition. It helps consumers document food safety violations and provides an automated escalation path to regulatory authorities if businesses fail to respond.

## Background
Food safety is a critical issue that affects public health. Common problems include:
* Discovery of hazardous foreign objects in meals.
* Lack of responsiveness from restaurant management regarding customer complaints.
* Difficulty for consumers to provide "objective proof" of a violation.

My personal motivation comes from experiencing a situation where a foreign object was found in a meal, but the establishment remained unresponsive. This project aims to empower consumers and improve food industry accountability.

## How is it used?
The process is simple:
1. The user takes a photo of the contaminated food through the app.
2. The AI analyzes the image to detect and highlight the foreign object.
3. The system generates a timestamped report including the restaurant's location.
4. If the restaurant ignores the complaint, the report can be directly uploaded to local consumer protection or municipality portals (like the "Balady" app in Saudi Arabia).

## Data sources and AI methods
* **Data Sources:** Crowdsourced images of food safety violations and open-source datasets of non-food objects.
* **AI Techniques:** * **Computer Vision (Convolutional Neural Networks):** To detect and classify objects within the food.
    * **Natural Language Processing (NLP):** To help users draft formal complaint letters based on the detected issue.

## Challenges
* **Accuracy:** Differentiating between intentional ingredients (like bones in bone-in chicken) and hazardous foreign objects.
* **Lighting:** Poor lighting in restaurants might affect image recognition quality.
* **Privacy:** Ensuring that images do not capture sensitive personal data.

## What next?
The project could grow into a global platform for food safety transparency, perhaps integrating with restaurant review sites to provide a "Safety Score" based on verified AI reports.

## Acknowledgments
* Inspired by the "Elements of AI" course modules on Computer Vision.
* Built using the project template provided by Reaktor Innovations and University of Helsinki.

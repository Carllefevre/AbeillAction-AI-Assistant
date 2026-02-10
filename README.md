# Abeill’Action AI Assistant  
Building AI course project

## Summary
Abeill’Action AI Assistant is a smart helper designed for independent pest‑control workers.  
It analyzes customer photos, classifies requests, estimates risks, and suggests an optimized intervention plan.  
This project explores how AI can reduce workload, improve safety, and support decision‑making.

## Background
Independent workers in pest‑control often face:
* Unclear or low‑quality photos from customers  
* Difficulty identifying species (wasps, hornets, bees)  
* Safety risks due to height, location, or weather  
* High mental load during peak season  
* Time lost sorting messages and planning routes  

The goal is to create an AI assistant that helps a solo operator make faster, safer, and more informed decisions.  
This topic matters because small businesses rarely have access to advanced tools, yet they face real‑world risks and time pressure.

## How is it used?
The assistant is used by a pest‑control worker receiving customer requests through messages or social media.

Typical workflow:
1. The customer sends a photo of a suspected nest.  
2. The AI analyzes the image and identifies the likely species.  
3. It estimates height, accessibility, and potential danger.  
4. It classifies the request (urgent / normal / low priority).  
5. It suggests an intervention window based on weather and distance.  
6. The worker reviews the suggestion and makes the final decision.

This tool supports, but never replaces, human judgment.

## Data sources and AI methods
Data sources:
* Customer photos of nests (taken with permission)  
* Short text descriptions from customers  
* Public weather data  
* GPS location or address information  

AI methods:
* Image classification (CNNs or pretrained vision models)  
* Object detection for nest location and height estimation  
* Natural Language Processing (NLP) for message triage  
* Simple route optimization for planning  
* Risk‑scoring model combining image + text + weather  

Example external resources:
* OpenWeather API

## Challenges
This project does **not** solve:
* Perfect species identification in all conditions  
* Safety decisions — the worker must always verify on site  
* Legal or regulatory constraints  
* Situations where customers send no photo or misleading information  

Ethical considerations:
* Customer privacy and data protection  
* Avoiding over‑reliance on automated decisions  
* Ensuring the worker remains in full control  

## What next?
Future improvements could include:
* A mobile app for real‑time photo capture  
* A larger dataset for better species recognition  
* Integration with calendar and invoicing tools  
* A more advanced route optimizer  
* Collaboration with other pest‑control professionals  

To move forward, the project would need:
* More annotated images  
* Basic coding skills in Python  
* Access to cloud computing or pretrained models  

## Acknowledgments
* Inspired by the Elements of AI course  
* Thanks to open‑source communities for tools and documentation  
* No external images or code used without permission  

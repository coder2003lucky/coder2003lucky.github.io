---
layout: page
title: ""
---

Hi! I'm Prarthan, a high school senior in the Bay Area. With a solid background in coding, I'm particularly interested in projects around **AI and the brain**.

In addition to my academic interests, I have a keen interest in chess, debate, and piano.

## Example Projects

Provide an overview of some projects you have worked on. This could include professional work, personal projects, or academic assignments. For each project, give a brief description and, if possible, include links to the project or images that showcase your work.

### Project 1: ReadyTuber AI

<img src="./potato_scanned.jpeg" width="200" height="400" />

Have you ever tried to grow potatoes? It's pretty easy—they don't have complex requirements for soil, watering, or sunlight. But they _do_ grow undergroud, making it very tough to tell when they're ready or not.

I would know—during the pandemic, I tried to grow potatoes. 3 times I tried, 3 times I pulled them up prematurely. 

This problem inspired my 2022 science fair project (I got 2nd in Senior Plant Biology at CSEF!), and culminated intoReadyTuber AI. Just take a simple picture of a plant, and the app will tell you whether the plant is ready or not!

Internally, the app has two main components: a custom YOLOv8 that identifies the plant, and a model built in TensorFlow that classifies the plant as "ready" or "not ready."

My initial approach only employed YOLO. However, YOLO's performance was underwhelming, yielding only about 50% accuracy—no better than random chance. In retrospect, I realized why. YOLO, typically adept at identifying distinct objects quickly, struggled to differentiate between similar elements in each image, such as leaves, stems, and dirt.

![The YOLO model incorrectly identifies these recently planted onion plants as ready, and also not ready. This run demonstrates YOLO’s inability to distinguish between similar objects](onion_why_yolo_bad.jpeg)

Realizing the need for a more tailored solution, I pivoted to creating a custom model using TensorFlow. This shift demanded a complete reevaluation of the model's components and their layout. Despite the limited dataset (only 140 images for onion plants) and the inherent complexity of distinguishing subtle variations in tubers, the new model has over 80% accuracy and precision. This breakthrough is pretty significant, especially considering the functional challenges and the similarity in visual cues across images.

![ReadyTuber AI Homescreen](homescreen.png =200x400)

The journey wasn't without its hurdles. Data scarcity was a major obstacle; organized, pre-labeled datasets for this niche application were non-existent. Manually labeling images was a tedious and time-consuming task, often complicated by the ambiguous nature of tuber maturity. Additionally, many images were of poor quality or lacked variability in factors like lighting.

Despite these challenges, the project was a success, meeting my engineering goals for all three targeted plants: potatoes, onions, and radishes. The app has been in review for a couple of weeks now, and I hope that it'll be available on the App Store soon!

- [Link to Project 1 or an Image]

### Project 2: [Project Title]

[Short Description of Project 2]

- [Link to Project 2 or an Image]

### Project 3: [Project Title]

[Short Description of Project 3]

- [Link to Project 3 or an Image]

## Research

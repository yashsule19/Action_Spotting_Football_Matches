# Action_Spotting_Football_Matches
The following is a part of a **Major Project (M.Sc. Dissertation)** for the **M.Sc. Data Science** Course at the **Nottingham Trent University, Nottingham, England, United Kingdom**.
 - **Title:** **_Action Spotting in Football Matches_**.

## Aim
The project aims to study the existing state-of-art deep learning algorithms for action spotting and developed deep learning model for detecting events in football matches by using different metrics to compute the accuracy for the developed model.

## Objectives
- To carry out an extensive background research of the topic “Video Understanding”.
- Understanding the approaches and their methodologies for the current state-of-art algorithms.
- Reviewing and reporting the short comes of the previous state-of-art algorithms.
- Developing new artificial intelligence model based on deep learning techniques.
- Comparing and analysing the different outcomes of the model being implemented by using different performance metrics to calculate the model accuracy.

## Why the project is important?
- In computer vision, the area of Video understanding is growing and is quite challenging also. Videos related to football games in which spotting action events like “goals”, “substitutions” and “cards” across each video frame is quite difficult due to their sparse nature.
- If efficient deep learning models are developed to captured important actions like “goals”, “substitutions”, “cards”, “penalties” from football matches videos, then it will lead to automate the process of generating highlights of the football matches.

## What problem the project solves?
The designed deep learning models can detect among the video frames of football matches which one are action frames and which are non – action frames.

## About the Dataset
- The original dataset contains 500 games of football matches in the form of videos from six European Championships covering three seasons for the years 2014 to 2017.
- I have only worked on first six games from the Englsih Premier League (EPL) for the season 2014-15 amounting almost 2GB of storage.
- Each game had 6 pre - extracted feature (already extracted features from the videos - that I have utilized for my work) files and 1 labelled file (action labels such as goals, substituitons).
- Pre - extracted features files were in numpy format (.npy) and labelled file was in JavaScript Object Notation format (.json).
- Overall, there were 36 pre - extracted features files and 6 action labelled files.

## Tools Used
- **Kaggle**: For building deep learning models using Python Programming Language.
- **Microsoft Excel**: For understanding the statistics of dataset and recording experimental results.
- **Microsoft Word**: For writing the report of Major Project.
- **Microsoft PowerPoint**: For creating Major project presentation.
- **Microsoft Teams**: For recording the video of the presentation.

| Python Libraries Used | Purpose |
| :-------------------- | :------ |
| os | For navigating through different folders which are present in the operating system. |
| json | For handling json files (In this project, Labels are in json format). |
| numpy | For performing numerical computations (In this project, Features are in npy format). |
| tensorflow, keras | For developing deep learning models. |
| matplotlib.plot, seaborn | For graphical visualizations. |
| sklearn.metrics | For measuring the accuracy of the models |

## Adopted Methodology
- The general pipeline of designing deep neural networks using pooling techniques is as follows:
    - **_Step – 1_**: Extracting features from videos or images.
    - **_Step – 2_**: Assigning annotations for those features.
    - **_Step – 3_**: Applying Pooling Techniques (either **MAX, AVERAGE, MIXED, NetVLAD**) to obtain new reduced feature matrix.
    - **_Step – 4_**: Passing newly obtained reduced feature matrix to the fully-connected layers.
    - **_Step – 5_**: Adding activation functions, dropout and output layers.
    - **_Step – 6_**: Compiling the model with the set parameters.
    - **_Step – 7_**: Train the designed deep neural network model and predict the outcomes.
    - **_Step – 8_**: Evaluate the performance of the model.
    - **_Step – 9_**: Plot necessary graphical visualizations as per the problem domain.
- In total, there were three pre - extracted types of features which were C3D, I3D and RESNET. 
- Hence, with 3 types of pre - extracted features and 4 types of pooling techniques, 12 deep learning models were developed and analysed throughout this project.

## Conclusion
- The ideology was to understand and study new emerging topic “Action spotting” in sporting videos related to the game of football.
- Developed an artificial intelligence system that can detect if a given video frame is an action frame or a non – action frame which can further be utilized for action localization tasks.
- Among the 12 models, 2 models performed better and 2 models performed worst, rest of the 8 models gave average performance. 
- For evaluation of models, performance metrics such as Precision, Recall and F1 – score were used.





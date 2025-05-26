Activity-Recognition-for-AmbientAssisted-Living

Author: Betelehem Z. Belayneh
Institution: Augsburg University – Department of Computer Science
Contact: bettibelayneh@gmail.com

🔍 What is Ambient Assisted Living (AAL)?
Ambient Assisted Living (AAL) refers to technologies designed to help older adults live safely and independently in their homes. 
These technologies include:
      Smart devices
      Wireless networks
      Software applications
      Medical and environmental sensors

AAL enhances quality of life and supports aging in place.

🎯 Purpose of the Research
To recognize daily activities of elderly individuals using sensor data collected in an AAL environment.
This data-driven activity recognition system can:
        Help monitor well-being
        Identify anomalies for emergency response
        Improve personalized support systems

🛠️ Methodology
Step 1: Data Collection
Dataset: CASAS Smart Home Simulator Dataset

Collected by: Center for Advanced Studies in Adaptive Systems (CASAS), Washington State University

Sensors used:
      30 motion sensors
      4 door sensors
      5 temperature sensors

Step 2: Data Preprocessing
Reformatted into a column-based structure suitable for supervised learning

Total records: 6477
Labeled with 12 daily activities (e.g., sleeping, cooking, relaxing)

Step 3: Model Training
Technique: Artificial Neural Networks (ANN)

Data Split:
    70% training
    30% testing

ANN architecture:
    5 hidden layers
    2 nodes per layer

Step 4: Model Testing
Evaluation via a confusion matrix
Achieved 89% accuracy


🧠 Background Concepts
Machine Learning
Branch of AI focused on learning from data

Supervised Learning: uses labeled data

Unsupervised Learning: uses unlabeled data

Artificial Neural Networks (ANN)
Supervised learning model inspired by the human brain

Effective in classifying complex patterns


📊 Results & Discussion
High accuracy for activities like sleeping, relaxing, and preparing meals

Some confusion between similar activities (e.g., washing dishes vs. preparing meals)

More diverse sensor data may improve model differentiation


💻 Tools & Technologies
Language: Python


Libraries:
  Pandas
  Scikit-learn
  Matplotlib
  Seaborn

⚠️ Challenges
Difficulty selecting useful features during preprocessing

Temperature data (float) caused training instability

Learning curve with new Python libraries and ANN structure

📚 References
Ambient Assisted Living (AAL)
CASAS Smart Home Datasets
IBM – Machine Learning
Supervised vs. Unsupervised Learning – GeeksforGeeks
IBM – Neural Networks
Confusion Matrix – Wikipedia
Python Data Science Handbook
W3Schools Pandas Tutorial

❓ Questions?
Feel free to reach out at bettibelayneh@gmail.com

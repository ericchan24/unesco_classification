# Classifying UNESCO World Heritage Sites  
---
I used a Support Vector Machine (SVM) model to classify UNESCO World Heritage Sites. The model was built using data from UNESCO, Wikipedia, the US National Park Service, the Canadian National Park Service, and TripAdvisor.  

I used a PostgreSQL database on an AWS cloud server to store my data.  

I build my model using skLearn. The final SVM model improved on an initial baseline F1 score of 48% to 62%.  

There is are 3 notebooks in this repository:  
1. Get CSVs from PostgreSQL  
2. Cleaning the data  
3. Modeling  

This is my [blog post](https://ericchan24.squarespace.com/blog/2017/10/28/classifyingworldheritagesites) on the project.

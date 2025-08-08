# Project Output

## 1. Console Output

When running the project, the console displays:

```
Displaying the distinct categories of resume:
['Data Science' 'HR' 'Advocate' 'Arts' 'Web Designing' 'Mechanical Engineer' ...]

Displaying the distinct categories of resume and the number of records:
Data Science              120
HR                         85
Advocate                   80
...

Feature completed .....
(Train, Test shapes) : (962, 86)

Accuracy of KNeighbors Classifier on training set: 0.98
Accuracy of KNeighbors Classifier on test set:     0.94

Classification report:
              precision    recall  f1-score   support

           0       0.94      0.95      0.94        50
           1       0.93      0.92      0.92        45
           ...
```

---

## 2. Visual Output

1. **Category Distribution Plot**  
   - A bar graph showing the number of resumes in each category.

2. **Pie Chart of Resume Categories**  
   - Displays the proportion of each resume category in percentage.

3. **WordCloud**  
   - A visual representation of the most frequent words appearing in resumes.

---

## 3. Key Insights

- **Training Accuracy:** ~98%
- **Testing Accuracy:** ~94%
- High accuracy in predicting categories such as Data Science, HR, Advocate, etc.

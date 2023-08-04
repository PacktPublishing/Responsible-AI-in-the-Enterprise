# Responsible AI in the Enterprise 

<a href="https://www.packtpub.com/product/responsible-ai-in-the-enterprise/9781803230528?utm_source=github&utm_medium=repository&utm_campaign=9781803230528"><img src="https://content.packt.com/B18337/cover_image_small.jpg" alt="" height="256px" align="right"></a>

This is the code repository for [Responsible AI in the Enterprise](https://www.packtpub.com/product/responsible-ai-in-the-enterprise/9781803230528?utm_source=github&utm_medium=repository&utm_campaign=9781803230528), published by Packt.

**Practical AI risk management for explainable, auditable, and safe models with hyperscalers and Azure OpenAI**

## What is this book about?

This book covers the following exciting features:
Understand explainable AI fundamentals, underlying methods, and techniques
Explore model governance, including building explainable, auditable, and interpretable machine learning models
Use partial dependence plot, global feature summary, individual condition expectation, and feature interaction
Build explainable models with global and local feature summary, and influence functions in practice
Design and build explainable machine learning pipelines with transparency
Discover Microsoft FairLearn and marketplace for different open-source explainable AI tools and cloud platforms

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1803230525) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter07.

The code will look like the following:
```
import numpy as np 
def laplace_noise(sensitivity, epsilon): 
    return np.random.laplace(scale=sensitivity / epsilon) 
def dp_average(ages, epsilon): 
    n = len(ages) 
sensitivity = 1 / n 
noise = laplace_noise(sensitivity, epsilon) 
return np.mean(ages) + noise 
ages = [ 
     25,30,35,45,28,32,40,36, 
     ] 
epsilon = 0.5 
dp_avg = dp_average(ages, epsilon) 
print ('Differentially private average age:', dp_avg) 
```

**Following is what you need for this book:**
This book is for data scientists, machine learning engineers, AI practitioners, IT professionals, business stakeholders, and AI ethicists who are responsible for implementing AI models in their organizations.

With the following software and hardware list you can run all code files present in the book (Chapter 3-10).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 3-10 | Jupyter Notebook (Python 3.x) | Windows, macOS, or Linux |


### Related products
* Natural Language Understanding with Python[[Packt]](https://www.packtpub.com/product/natural-language-understanding-with-python/9781804613429?utm_source=github&utm_medium=repository&utm_campaign=9781804613429) [[Amazon]](https://www.amazon.com/dp/1804613428)

* Platform and Model Design for Responsible AI[[Packt]](https://www.packtpub.com/product/platform-and-model-design-for-responsible-ai/9781803237077?utm_source=github&utm_medium=repository&utm_campaign=9781803237077) [[Amazon]](https://www.amazon.com/dp/1803237074)


## Get to Know the Author
**Adnan Masood**
,PhD is a visionary leader practitioner in the field of artificial intelligence, with over 20 years of experience in financial technology and large-scale systems development. He drives the firm’s digital transformation, machine learning, and AI strategy. Dr. Masood collaborates with renowned institutions like Stanford AI Lab and MIT CSAIL, holds several patents in AI and machine learning, and is recognized by Microsoft as an AI MVP and Regional Director. In addition to his work in the technology industry, Dr. Masood is a published author, international speaker, STEM robotics coach, and diversity advocate.


## Other books by the authors
[Automated Machine Learning](https://www.packtpub.com/product/automated-machine-learning/9781800567689?utm_source=github&utm_medium=repository&utm_campaign=9781800567689)

[Learning F# Functional Data Structures and Algorithms](https://www.packtpub.com/product/learning-f-functional-data-structures-and-algorithms/9781783558476?utm_source=github&utm_medium=repository&utm_campaign=9781783558476)







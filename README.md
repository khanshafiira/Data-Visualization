# Data Visualization using Python
If you are curious about Python programming and want to learn more about it, sure, this page may suit you!

This README will provide you a clear grasp of some important fundamental in Python, making your learning experience more enjoyable and straightforward.

Anyway, you can check my previous Github to elaborate what we learn about Python for Beginner:
1. Introducing to Data Analyst for Python
   
   https://github.com/khanshafiira/PythonKnowledge-1
2. Data Analyst Essentials for Python

   https://github.com/khanshafiira/PythonKnowledge-2
3. Data Manipulation in Python

   https://github.com/khanshafiira/PythonKnowledge-3

4. Data Analysis with Python

   https://github.com/khanshafiira/PythonKnowledge-4   

Happy growing!

## Data Visualization
Data visualization refers to the graphical depiction of information and data. Data visualization tools use visual components such as charts, graphs, and maps to make trends, outliers, and patterns in data more visible and understandable. Furthermore, it allows employees or business owners to convey facts to non-technical audiences without confusion. Data visualization tools and technology are critical in Big Data analysis and decision-making.

The advantages of data visualization:
- Information can be easily shared.
- Explore options in an interactive way.
- Visualize the patterns and correlations.

The disadvantages of data visualization:
- Biased or incorrect information.
- Correlation does not always indicate causality.
- Core messages can become lost in translation.

### Basic of Visualization
4 characteristics called ACES:

a) Accurate

The visualization should accurately depict the data and its trends.

b) Clear

Your visualization should be simple to grasp.

c) Empowering

The reader should know what to do after viewing your depiction.

d) Succinct

Your message should resonate quickly.

#### 1. Comparison
The term "comparison" refers to **comparing various variables in datasets or categories within one variable**. This can be demonstrated using bar charts, line graphs, or other comparison visualization methods.

Example:
- bar chart can compare exam scores between two classes in the school
- line graph can compare a variable between two groups over time

Types of Comparison Chart:
- Among Categories
  
  a) Bar chart vertical

  <img src="https://github.com/khanshafiira/Data-Visualization/assets/166186201/7f5727f7-427a-4846-a892-58008d9da556" width="400" height="280">

  b) Bar chart horizontal

  <img src="https://github.com/khanshafiira/Data-Visualization/assets/166186201/cefd85d4-a2a8-4978-a4fd-4e3af4b26a60" width="400" height="280">

- Over Time

  a) Line chart

  <img src="https://github.com/khanshafiira/Data-Visualization/assets/166186201/8862c3f7-85d3-4986-891a-cdfac2e0f013" width="400" height="290">

  b) Multiple line chart

  <img src="https://github.com/khanshafiira/Data-Visualization/assets/166186201/a6e07a4d-7b4a-4548-be19-740302bb5f34" width="400" height="290">
  
#### 2. Composition
Composition is the representation of **one or more variables in absolute numbers and normalized forms**. This can be visualized using pie charts or stacked bar charts. While pie charts are considered outdated, they can nonetheless provide data in a visually pleasing and familiar way.

Types of Composition Chart:
- Changing Over Time
  
  a) Stacked bar chart
  
  <img src="https://github.com/khanshafiira/Data-Visualization/assets/166186201/933052ec-e166-4423-9bba-abde683f0a33" width="400" height="290">

  b) Stacked 100% bar chart
  
  <img src="https://github.com/khanshafiira/Data-Visualization/assets/166186201/69b5a5a7-f8e3-48a2-95c2-c83b9833bf5e" width="500" height="290">

- Static

  a) Pie chart
  
  <img src="https://github.com/khanshafiira/Data-Visualization/assets/166186201/1aeac12a-547b-4a92-9348-041d18a717e0" width="410" height="300">

  b) Waterfall chart

  <img src="https://github.com/khanshafiira/Data-Visualization/assets/166186201/bd5fa4aa-e936-4f39-ae7f-c575095a1b4e" width="510" height="280">

  c) Tree map

  <img src="https://github.com/khanshafiira/Data-Visualization/assets/166186201/cd70a16a-9a6d-40c5-ad8f-20aada3ad6b8" width="550" height="280">

#### 3. Relationship
A relationship is the **connection between two or more variables**. A decent visualization can help identify these links without requiring sophisticated statistical analysis.

Example:

A graph can be used to depict the link between a tree's height and age
#### 4. Spatial
Spatial data charts, commonly called maps, are useful tools for **displaying and evaluating geographic data**. It is offer a strong method of showing data in a way that facilitates the analysis and identification of patterns, correlations, and trends. Users may readily determine where specific occurrences or phenomena are taking place and how they are spread throughout a geographical region. This is especially beneficial for examining data on population, demography, climate, and natural resources, among other topics.
## CRISP-DM
CRISP-DM stands for Cross-Industry Standard Process for Data Mining. It is a cyclical process that provides a structured approach to planning, organizing, and implementing a data mining project. The process consists of six major phases:

<img src="https://github.com/khanshafiira/Data-Visualization/assets/166186201/3ef18b7f-1cdb-45fa-886d-069d9fcc253b" width="400" height="320">

### 1. Business Understanding
It has a quite vital part. Business understanding requires knowledge of the business objects, how to build or obtain data, and how to match modeling goals to business goals; so that the best model can be built. Activities carried out include: define business objectives, assessing the current scenario, setting data mining targets, and creating a project plan. 

### 2. Data Understanding
Data understanding provides the analytical foundation for a study by creating a summary and identifying potential problems in the data. It must also be carried out carefully and not in a rush, such as in data visualization, where sometimes the insight is very difficult to obtain when connected to the summary data. If there are problems at this step that have not been answered, it will interfere with the modeling step.

### 3. Data Preparation
The data is rarely clean. Data preparation focuses on cleaning and translating raw data into a modelable format. It includes: selecting data, cleaning data, constructing data (feature engineering), integrating data, and formatting data.

### 4. Modeling
With clean data at hand, numerous modeling strategies are used. Each approach may require specialized data formats, so it is not uncommon to return to the data preparation phase. Key activities include: selecting modeling techniques, designing tests, building the model, and evaluating the model.

### 5. Evaluation
Evaluation is used to analyze the outcomes of data mining generated during the preceding stage of the modeling process. This is done on the model used in the previous step, with the goal of ensuring that the model determined is consistent with the objectives set in the first step.

### 6. Deployment
The model is finally deployed in a real-world situation. This might be as easy as creating a report or as complicated as establishing a repeatable data mining process. The key activities include planning deployment, monitoring and maintenance, reviewing the project, and completing the project.

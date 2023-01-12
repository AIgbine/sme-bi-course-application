# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The two exercises should not replicate the exact actions shown in your screencast. The goal of exercises is for learners to apply what was learned in the screencasts to new problems or situations. This is best pedagogical practice for retaining and building skills. For example, this can be done by using another dataset between screencasts and exercises or focusing on a different portion of the dataset.
- We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/introduction-to-power-bi/getting-started-with-power-bi?ex=14) from Introduction to Power BI. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners.

## 1st VM Exercise

#### Dataset

- [x] Add datasets used to the `datasets/` folder

#### Files

- [x] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [x] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix`

#### Learning Objective

*Carry out running total calculations on time-series data*

#### Context

*We have the data of office supplies for Sapphire Limited from 2020 till 2021. To find out the total amount spent on supplies from 2020 to at any given time, you will find the total running calculation at the specified date*

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

- Drag the “Order Date” and "Total" into the “Columns” and "Rows" section in Tableau visualization area.
- From the “Show me” tab, select the line chart if not automatically selected
- Drill down your visualization into months using continuous date format
- Duplicate “Sum(Total)” in the Row section
- From the "quick calculation option", select "Running Total"



#### Exercise question:
*Using the line chart, what is the “Running sum of Total” in December 2021?*

*9258*

#### End goal:

<img width="1440" alt="Ex-1-sol" src="https://user-images.githubusercontent.com/35337868/211958513-84978791-f7a3-4355-b6e3-9b9a7d12416f.png">


## 2nd VM Exercise

#### Dataset

- [x] Add datasets used to the `datasets/` folder

#### Files

- [x] **Initial**: Add file to the `exercises/`  folder with the name `ex-2-intial.twbx` or `ex-2-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [x] **Solution**: Add file to the `exercises/`  folder with the name `ex-2-sol.twbx` or `ex-2-sol.pbix`

#### Learning Objective

*Smoothen data using moving averages*

#### Context

*3 - The moving average can be used to identify downward and upward trend in data. A rising moving average indicates an increase in quantity (usually price) while a declining moving average indicates a drop in quantity. Determine if the amount spent on company supplies has increased, reduced or remained the same over time*

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

- Duplicate the “Sum (Total)” again
- Apply the moving average calculation from the quick calculation menu
- Edit Table Calculation: summarise values using the moving average for 2 previous values and 2 next values
- ...

#### Exercise question:
*From the moving average, has the price spent on office supplies increased or reduced over time? (apply trendlines to see the general trend of the moving average)*

*Increased*

#### End goal:
<img width="1440" alt="Screenshot 2023-01-12 at 03 23 42" src="https://user-images.githubusercontent.com/35337868/211960961-008ceb3c-35ac-4b65-ba36-2e68f5f2489f.png">





# Engineer Technical Test 

Thank you for taking the time to do our technical test. It consists of two parts:

* [A coding test](#coding-test)
* [A few technical questions](#technical-questions)

In order to avoid bounced emails we would like you to submit your results by uploading the relevant ZIP file to a shared Google Drive folder. In order to obtain the URL for this folder, please supply your Gmail or Google-based email address to person who assigned you the test.

Please make this a **single** zip file named `{yourname}.zip` containing:

1. a single markdown file with the answers to the technical questions
2. one folder containing the technical test

## Coding Test

The task is to create a web application that shows a list of products and the following information about each product:

- Name
- Description
- Category
- Rating
- Price

Allow user to sort and filter data by each column. 

**List loading, sorting and filtering have to be a server side operations, either web api or mvc action calls**

Use **[product.json](products.json)** file as a data source for your application.

### Platform choice

Create a web application in any of the following platforms

- ASP.NET MVC
- Web Api and Angular

### Task requirements

Feel free to spend as much or as little time on the exercise as you like as long as the following requirements have been met. However, we understand people have busy lives and would guide you to spend no more than 2-3 hours on a submission. We also take into consideration the [Answers to technical questions.md](#technical-questions) file and what you would like to have added if you had more time. You should look at this as the complete solution, it's much quicker to explain what you would like to have done than code it.

- Please complete the user story below.
- Your code should compile and run in one step.
- Feel free to use whatever frameworks / libraries / packages you like.
- Please avoid including artifacts from your local build (such as NuGet packages or the bin folder(s)) in your final ZIP file

### User Story

Given I am a **user running the application**
When I **open application main page**
Then I want to see a **list of all products**
And I want to **sort product list by Name, Description, Category, Rating and Price**
And I want to **filter product list by Name, Description, Category, Rating and Price**

#### Acceptance criteria

- Entire list of products is displayed
- The Name, Description, Category, Rating and Price of the product are displayed
- When sorting applied the list is displayed accordingly to sort criteria
- When filter applied the list is displayed including data which match filter criteria.

# Technical questions

Please answer the following questions in a markdown file called `Answers to technical questions.md`.

1. How long did you spend on the coding test? What would you add to your solution if you had more time? If you didn't spend much time on the coding test then use this as an opportunity to explain what you would add.
2. What was the most useful feature that was added to the latest version of your chosen language? Please include a snippet of code that shows how you've used it.
3. How would you track down a performance issue in production? Have you ever had to do this?

#### Thanks for your time, we look forward to hearing from you!

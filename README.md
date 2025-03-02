# Introductions (2025)
Author: Ryan Tran
Eric Pogue and ChatGPT created this repository as a template for an "Introductions" website.

Additional GitHub Page information can be found at [GitHub Pages](https://pages.github.com/). Also, there is a 5-minute 
[Hello World with GitHub Pages](https://www.lewis.education/?cpsc=sp24-cpsc-20000-002#/activity/hello-world-web-part-1)
video tutorial that was created for the Lewis University ”Introduction to Computer Science” class that might be helpful. 


---

# Background

## The initial prompt given to ChatGPT was:
```
Create an HTML and CSS-based application that introduces yourself and includes the following items:
    Your first and last name
    The name that you would prefer to be called if that is different from your first name
    Your current or most recent job title
    A summary of your current or most recent job responsibilities
    Your hobbies or special interests
    Your reasons for pursuing this degree
    Your reasons for taking this course
    A fun fact about yourself that will help your classmates remember you
```

This is provided only as background. No action is needed on your part yet. 

## ChatGPT responded with:
As an AI, I don't have personal information such as a name, job title, or hobbies. However, I can create a template based on your 
request. You can fill in your details where necessary. Below is a basic HTML and CSS code to create a webpage introducing 
yourself:
```
<!DOCTYPE html>
<html>
<head>
    <title>About Me</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            line-height: 1.6;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .main-info {
            background: #333;
            color: #fff;
            padding: 20px;
        }
        .main-info h1 {
            margin: 0;
        }
        .hobbies, .career, .course {
            background: #e7e7e7;
            padding: 15px;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="main-info">
            <h1>Your Name: [Your Full Name]</h1>
            <p>Preferred Name: [Your Preferred Name]</p>
            <p>Current/Recent Job Title: [Your Job Title]</p>
        </header>

        <section class="career">
            <h2>Job Responsibilities</h2>
            <p>[Summary of your current or most recent job responsibilities]</p>
        </section>

        <section class="hobbies">
            <h2>Hobbies and Special Interests</h2>
            <p>[Your hobbies or special interests]</p>
        </section>

        <section class="career">
            <h2>Reasons for Pursuing This Degree</h2>
            <p>[Your reasons for pursuing the degree]</p>
        </section>

        <section class="course">
            <h2>Reasons for Taking This Course</h2>
            <p>[Your reasons for taking this course]</p>
        </section>

        <section class="fun-fact">
            <h2>Fun Fact</h2>
            <p>[A fun fact about yourself]</p>
        </section>
    </div>
</body>
</html>
```

Credits go to eric pogue and Chat GPT



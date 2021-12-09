## Welcome to Jenna Wanket's Cloud Resume Challenge Blog Post!

[My Cloud Resume](https://jennawanket.com)
[My LinkedIn](https://www.linkedin.com/in/jenna-wanket/)

When I first read about the Cloud Resume Challenge, I was fully engulfed with feelings of anxiety and doubt. All of the different skills needed to complete this task appeared to be foreign in my eyes, even though I had experience with each of them individually. I decided to settle my nerves and take it one step at a time. Luckily, we were able to address concerns in class and start together. I first deployed my personal chosen domain to an S3 Bucket in AWS. I had navigated AWS before this course, however, my knowledge was very minimal. S3 allowed me to safely store my main domain and the “www.jennawanket.com” domain in container buckets. My S3 domain needed to use HTTPS rather than HTTP because it adds another level of security to the main domain. This also provided easy access to the stored files and data. Moreover, I had to register my “jennawanket.com” domain in Route 53 to ensure it’s properly connected to a DNS server. 

During this time, I began to feel much better about completing the Cloud Resume Challenge. I enjoyed having the opportunity to ask questions during class about the different steps. I feel that this helped me understand the material better, rather than simply following instructions step-by-step. By practicing the different AWS services hands-on, I was able to thoroughly understand them at a deeper level. Countless times I remember going back and looking up what S3 and Route 53 do so I could gain a better understanding. 

Next, we created an API to keep track of the domain’s visitor count and displayed that on the site. I did this by creating two tables in a DynamoDB NoSQL database. NoSQL is a non-relational database management system that is better used than MySQL when it comes to collecting messier data. Although NoSQL is much more difficult to query with, due to the lack of normalization, it has higher ​​performance, availability, and scalability. 

Thereafter, I created an API built on AWS Lambda and Automated Programming Interface (API) Gateway that accepts requests from the web application and communicates with the database. This will then display the visitor number on the website. AWS Lambda is an AWS service that allows code to run without having to worry about servers or scalability. This is in lieu of creating an EC2 instance that could be limited by RAM or scaling issues. 

In this code, I first imported the JSON package to help decode the data. Next, I connected to the DynamoDB resource and created a “visitor_count” table to track the number of website visitors. I then wrote a code that would increment the “visitor_count” table by one each time someone accessed the site.
Nearing this time, I found myself having more trouble comprehending the material. The abstract idea of virtual servers and APIs becomes overwhelming quite fast. I combat this confusion by doing more research on each topic and ensuring that I understand each intricate part. For instance, I often do a quick Google search if I ever have a moment of questioning what each service provides. 

Once I’ve completed each of these steps and the visitor count is effectively showcased, I was able to begin my search for an HTML/CSS template for the website. This search was somewhat complicated for a few different reasons. First, I found it difficult to find a template I liked and could say I’m proud of. However, I was also wrestling with the unwanted feelings of inadequacy. I thought that a complex template would turn out to be too much, so I settled for a simple, one-page template. Looking back, I’m very content with my decision because I feel I gained the necessary experience to build off of later in my academic career. 

I downloaded the HTML/CSS template from a public website and had an example of what the end product would look like available. This became my new “index.html” file that I would use for my domain. Moving forward, I compared the placement of the variables with the HTML code, altering them to fit my liking. This process took upwards of two hours because I would get caught in minuscule details about coloring and font sizing. I then was able to edit the beginning code so that the file would reference the visitor counter API and the proper CSS file “resume.css”. After the version was to my liking, I imported the “index.html” file into the S3 bucket domain. 

Once this process was complete, the website functioned as it did in the previous version that wasn’t accessible through the cloud domain. In the end, I’m very satisfied with the product of my cloud resume. I learned greatly about HTML and CSS coding, and the perseverance that comes with developing any new skill. Moving forward, I am extremely interested in persuing a career in cloud computing and expanding my knowledge as much as possible!

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```


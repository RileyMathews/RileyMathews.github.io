Title: Lesson Ninja
Date: 2023-06-26 14:30
Category: Projects
Tags: python, django, django-rest bulmacss, javascript, react

This was my final capstone project from my time at Nashville Software School. The inspiration came from my brief time before school working as a music instructor at a Guitar Center. One small frustration I had was writing up very similar music or guitar tabs for each student. While a copier on hand at the store probably would have worked just as well... leave it to a developer to over-engineer a solution 😂.

The idea behind the project: a teacher could setup pre-planned lessons with attached documents and assign them to students. When the student logged in they would see a list of their assigned lessons and be able to view and download the documents for study/practicing/etc...

My favorite part about the website was the ability for the teacher to see if the student had opened their lessons or not. It was a simple one time notification, but if I had more time I would have loved to flesh that out into an actual log of student activity.

Looking back on this project I think the main takeaway I have is that it really didn't need a React front end. We were given the option of doing a pure Django project with server side rendering or a React front end with Django REST back end. Because I thought it would be "fancier," I went with React and Django REST. If I were to revive this project, I would definitely start with pure server side rendered Django. A lot of the pages were simply about linking data together. One such link was using an "invite code" system to attach a student to a teacher, which in retrospect would have been infinitely simpler as a page with the invite code in the get parameters instead of having to go through the React app. As my knowledge has progressed I definitely find myself leaning more towards doing as much on the server as possible and using the dumbest templates possible.

This project has a [front end React repository](https://github.com/RileyMathews/lesson-ninja-frontend-NSS-Capstone) and a [Django REST backend repository](https://github.com/RileyMathews/lesson-ninja-backend-NSS-Capstone)

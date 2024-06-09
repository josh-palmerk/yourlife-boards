# CSE 310 - Module Report

Name: Josh Palmer

## Part 1 - Module Planning

This section should be filled on the first Monday of the Sprint and submitted

### Section 1.1 - Module Selection

1. What Sprint is this for (1-5)? 2

2. Select the Module (with a single X) that you will do this Sprint:

|Module                   |Selected Module|
|-------------------------|---------------|
|Cloud Databases          |               |
|Data Analysis            |               |
|Game Framework           |               |
|GIS Mapping              |               |
|Mobile App               |               |
|Networking               |               |
|SQL Relational Databases |               |
|Web Apps                 |       X       |
|C++                      |               |
|Java                     |               |
|Kotlin                   |               |
|Erlang                   |               |
|TypeScript               |               |
|Rust                     |               |
|Choose Your Own Adventure|               |

3. Find the list of unique requirements for your selected module in the Module Summary in Canvas.  In some circumstances, you will need to modify the requirements based on the technology or language you selected.  For the Choose Your Own Adventure, you need to create your own requirements.  List the unique module requirements below:

* __Must have at least two HTML pages populated by content determined by your code. However, if you use React, then you can keep to a single page with multiple interactions.__

* __Your software must be interactive meaning that the content displayed in your web app must be in some part based on user input.__

* __The web app must run on your local computer using the test server provided by your framework. If desired, you can host your web app on a cloud server.__


### Section 1.2 - Planning

During the Sprint, you will spend 4 hours in class meetings, 4 hours on your team project (2 of which during class), and 10 hours on your selected module.  Make a plan for your 10 hours by answering the questions below.  You should refer back to this plan and make adjustments during the Sprint.

1. What sources have you selected to learn the technical material?

https://docs.djangoproject.com/en/3.0/contents/
https://www.tutorialspoint.com/django/index.htm
https://realpython.com/get-started-with-django-1/
https://chat.openai.com/

2. What is your plan to practice the new material?  In other words, what is the order in which you plan to learn the material before working on your demonstration software?

I made a Django app YEARS ago, so I'll pull that repository and fix all the bugs that will definitely exist. I know enough about programming to know that this thing won't work immediately when I run it. But as I fix it I'll get refamiliarized. Then I'll make my own from square one.

3. What demonstration software do you plan on submitting at the end of the Sprint (note that this can and may change)?

My MVP would be my e-portfolio with a form box, but I want to make some kind of FOSS discussion/request forum.

4. Identify the days, times, and locations that you will work on the module.

Probably Wednesday, Friday, and Saturday, evenings & afternoons, in my room (that's where my PC workstation is)

5. Identify both a technical risk and a behavioral risk that you antcipate may occur during this Sprint.  What is your mitgigation plan?

Technical risk: Networking issues with apartment wifi
Mitigation: just make localhost work at least

Behavioral risk: scope creep
Mitigation: good phase-by-phase planning

## Part 2 - Time Log

This section should be filled out during the Sprint. 

Record all CSE 310 work that you do on your individual module or the team project.  Include time learning, practicing, developing, testing, and documenting.  Don't include time spent in the 4 class meetings (Planning, Stand-Up, Team Review, and Individual Review).  You will need to sum of these hours at the end of the Sprint. Note that the hours you report will affect your grades.

Note that `IM` stands for Individual Module and `TP` stands for Team Project.  

|Date      |Start Time|IM or TP|Description                                 |Hours:Minutes|
|----------|----------|--------|--------------------------------------------|-------------|
|   5/16   |  11:30am |   TP   |  Finalizing DB model                       |    3:30     |
|   5/16   |  11pm    |   IM   |  Learning Django framework (again)         |    1:00     |
|   5/18   |  2pm     |   TP   |  Fixing errors in DB                       |     :30     |
|   5/23   |  9pm     |   IM   |  Starting apps and making HTML             |    1:30     |
|   5/24   |  6pm     |   IM   |  Getting nowhere with the django framework |    3:30     |
|   5/25   |  11pm    |   IM   |  Scrapping my whole idea and starting fresh with my new knowledge  |  1:30   |
|   6/7    |  7pm     |   IM   |  Trying to figure out forms and models     |    3:30     |
|   6/8    |  11am    |   IM   |  Literally scrapped again, 3rd time was the charm I guess         |   4:30    |



## Part 3 - Module Results

This section should be filled out at the end of the Sprint and submitted.

1. Put your GitHub link for your demonstration software here: https://github.com/josh-palmerk/yourlife-boards

2. Put your YouTube link for your code walkthrough and demo video here: https://youtu.be/_YuNvBd1sms

3. Complete the following checklist by either indicating "Yes" or "No". If you indicate "No" then provide an explanation of why beneath the table.

|Question                                                    |Response|
|------------------------------------------------------------|--------|
|Are the links above public and working?                     |   Yes  |
|Did you complete all the unique requirements for the module?|  Yes   |
|Did you write at least 100 lines of code?                   |  Yes   |
|Did you fully complete the readme.md file?                  |  Yes   |
|Did you put the readme.md file in GitHub in the top folder? |  Yes   |

4. If you completed a Stretch Challenge (as shown in the Module Description document in Canvas) then describe what you did.  If you did the Choose Your Own Adventure module, then you get to decide what qualifies as a Stretch Challenge.

I did not complete a stretch challenge.

5. Did you change your selected module during the middle of the Sprint?  If yes, then describe what you changed it to, when you changed it, and why you changed it.

I did not change the module topic, but I did restart my project twice due to IDE and framework failures caused by extreme user incompetence.

6. Using the log above, fill in the total hours and minutes you spent on the individual module:

|Activity         |Total Hours:Minutes|
|-----------------|-------------------|
|Individual Module|     15:30         |

7. What strategies (behavioral and technical) worked well during this Sprint?  What did not work well?  List some possible ways that you can improve next Sprint.

Being less afraid to restart helped me get over some stupid bugs that were causing me hours of pain. I think I need to start using git branches more, so I can revert instead of restart. But restarting also helps you learn the fundamentals more solidly, so I'm split between the two approaches.
---
layout: default
title: Home
nav_order: 1
description: "Advanced Data Systems (COSI 167A)"
banner_image: /assets/css/p2.jpg
banner_heading: "Advanced Data Systems"
banner_description: "COSI 167A"
season_year: "Fall 2024"
permalink: /
---

|----------|----------|----------|
| __Instructor__{: .fs-4} | [<u>Subhadeep Sarkar</u>](https://subhadeep.net){:target="_blank"} | __Email:__ [subhadeep@brandeis.edu](mailto:subhadeep@brandeis.edu) |
| __Lectures__{: .fs-4} | __Timings:__ Tue & Fri: 12:45 PM – 2:05 PM | __Location:__ Gerstenzang: 121 |
| __Student hours__{: .fs-4} | __Timings:__ Tue & Fri: 2:15 PM – 3:15 PM | __Location:__ Volen 259 |
| __Recitation__{: .fs-4} <sup>1</sup> | __Timings:__ Fri: 4:00 PM – 5:00 PM <sup>2</sup> | __Location:__ Volen 259 <sup>3</sup> |

<sup>1</sup> Recitations are __optional__ for this class and will be used as __additional student hours__ to discuss project progress and updates. <br>
<sup>2</sup> Students are encouraged to [email the instructor](mailto:subhadeep@brandeis.edu) to __set up an appointment__ if they want to attend a recitation session. <br> 
<sup>3</sup> The recitations will be held in __Volen 259__ (instead of Gerstenzang: 121). <br>


## <u>Course Description</u>
Data is everywhere. As scientists, users, and citizens we are both generating and exploiting large, ever-growing, diverse sets of data. For several applications – ranging from scientific discovery to business analysis, governance, and everyday activities – we are directly using and indirectly affecting hundreds of data systems! The big challenge is to turn data into useful knowledge, and to do so quickly, in order to increase the impact of the new insights. Achieving these goals comes with a number of technical challenges. How to exploit the continuously evolving hardware (storage, computation, network)? How to collect all incoming data efficiently? How to query dynamic collections of data that keep accumulating incoming data? How to parallelize query processing from one core to a few (scale-up), and then to thousands (scale out)? What are the needs of evolving workloads (hybrid transactional/analytical processing, graph analytics, Internet-of-Things, micro-payments, monitoring)? In this course, we will discuss how to design data systems that can address these challenges. We will see in detail the two driving forces behind innovation in data systems: hardware and workloads, and we will discuss recent and future trends of both. We will use examples from several data management areas including relational systems, distributed database systems, key-value stores, newSQL and NoSQL systems, data systems for machine learning (and machine learning for data systems), interactive analytics, and data management as a service. In a quickly moving industry and research landscape, such skills are essential.

## <u>Prerequisites</u>
__COSI 127b --  Database Management Systems__. A working knowledge of C/C++ and Java or Python programming and a fundamental understanding of data structures and algorithms is required. Please see the instructor if you are not sure about the level of your preparation.

## <u>Learning Goals</u>
Students who successfully complete all components of this course will be able to demonstrate the following by the end of the semester.
    1. Familiarization with the history and evolution of NoSQL data systems design over the past decades. 
    2. Understanding of the challenges and tradeoffs associated with large-scale data management and analysis.
    3. Knowledge about the key design principles of state-of-the-art NoSQL systems.
    4. Ability to interact and tune with modern key-value stores.
    5. Understanding how large-scale commercial data systems work and how to optimize such systems for a given workload and performance target. 
    6. Ability to program, experiment, evaluate complex, scalable data systems, and reason about their performance.
    7. Read and interpret state-of-the-art research papers, with the ability to criticize them constructively.

## <u>Topics</u>
In this class, we will cover data systems design principles from the following different angles.
1.	What affects new data systems designs (data and applications, emerging hardware, and new workloads)
2.	Traditional data systems for modern hardware
3.	Distributed database systems
4.	NoSQL, newSQL, and key-value stores
5.	Hardware-conscious systems design

<!-- 
## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %} -->

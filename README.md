# DSE I2450 - 3GG - 💿🐘✨ Big Data & Scalable Computation

**Instructor:** Professor Madeline Blount \
**Term:** Spring 2024 \
**Time:** Wednesdays 4:50-7:20pm \
**Space:** NAC 4/161 when in-person; HYBRID w/online \
**Office Hours:** virtual by appointment, [schedule here](https://www.cal.com/mab253) \
**E-mail:** `mblount@ccny.cuny.edu`
City College, City University of New York

## course description

This is a graduate-level course on the theory, practice, design, and critique of big data and contemporary scalable computation systems. After introducing the foundations of the hardware and software infrastructures of "big data", we will explore case studies of several specific systems and practice working with the programming libraries that leverage their use.  Students will take on self-directed research projects to investigate state-of-the-art tools and issues within scalable systems. We will also delve into the real limitations and ethical urgencies surrounding big data's current and growing role in sociotechnical systems.

## what will we do in this class?

- explore foundational concepts and architectures of big data systems (incl. Hadoop, MapReduce, Spark)
- work hands-on with big data programming paradigms via libraries (Python, SQL)
- prepare for an evolving ecosystem by learning *to learn and teach* new technologies
- compare, evaluate, and critique new research and new tools in the field
- analyze and contextualize the role of big data in terms of limitations and ethical concerns
- interrogate the concept of big data as a form of knowledge production

## course format

This is a **hybrid** course. We will meet mostly synchronously, some weeks online and some weeks in-person. Each week will be labeled as 1 of the following:

- **🏙️ In-Person @ CCNY**
    - At NAC 4/161, we will meet for discussion and hands-on work (Wednesday evenings)
- **🏠 Online Zoom**
    - We will meet on Zoom together (simultaneous, Wednesday evenings)
- **🦋 Asynchronous**
    - Some weeks, we will not meet at a simultaneous time. We will be active online and learn at our own pace.

👾 For this class, we will build an asynchronous offline community (as exists in nearly every endeavor @ this point!). We will have a class [Discord](https://github.com/mab253/bigdata_spring24/blob/main/discord.md) server with multiple channels for posting updates, posing questions, commenting on readings and each others' work, sharing resources and opportunities, etc.

Big data is a widely-encompassing term referring to rapidly changing fields - learning foundational concepts and the ability to pick up new material will be more valuable to you than honing specific techniques! Because of this, our class will be structured more as a research seminar than a lecture course. In the introductory weeks, we will read original papers and use our class time to discuss the design of the systems described. Programming assignments in this early unit of the course are self-paced. After Week 5, we will transition into significantly self-directed work; you will have ample spacetime to follow your own curiosity and interests. Students will pair up to choose a research topic to present during a Symposium on Weeks 10 and 11, and continue focused work on this topic into a final paper/coding project.

All work for this class will be project and presentation-based, and there will be no exams.

## important info:
[key dates](#key-dates) \
[materials & references](#materials-and-references) \
[tools](#tools-we-will-use-a-lot) \
[expectations & requirements](#expectations-and-requirements) \
[evaluation](#evaluation) \
[academic honesty & integrity](#academic-honesty-and-integrity) \
[contact & questions](#contact-and-questions)

## SCHEDULE, ASSIGNMENTS, READINGS:

💥*subject to change*

**Week 0: Jan. 31** \
🏙️ In-Person @ CCNY

*Introduction to Big Data, Hello World!*

**Assignment:**
- read syllabus; complete class survey; "hello world" post on Discord, sign up for codecademy (invite/link for all will be e-mailed)
- **DUE:** Friday Feb. 2nd, 5:00pm

---

**Week 1: Feb. 7** \
🏙️ In-Person @ CCNY

*Distributed File Systems*

**Reading for today:**
- "[The Google File System](https://github.com/mab253/bigdata_spring24/blob/main/readings/google-file-system.pdf)," Ghemawat et. al (paper)
- *[Hadoop, The Definitive Guide](https://github.com/mab253/bigdata_spring24/blob/main/readings/OReilly.Hadoop.The.Definitive.Guide.4th.Edition.2015-Ch-1-3.pdf)*, White:
    - Ch. 1, pp. 3-14
    - Ch. 3, pp. 43-50 and pp. 69-71

**Recommended:**
- "[Hadoop in 5 Minutes](https://www.youtube.com/watch?v=aReuLtY0YMI)," Simplilearn (video)
- [other resources](LINK) for GFS/HDFS


---

**Week 2: Feb. 14** \
🏠 Online Zoom

*Parallel Computation: MapReduce*

**Reading for today:**
- "[MapReduce: Simplified Data Processing on Large Clusters](https://github.com/mab253/bigdata_spring24/blob/main/readings/map-reduce.pdf)," Dean and Ghemawat (paper)
- *[The Mining of Massive Datasets](https://github.com/mab253/bigdata_spring24/blob/main/readings/mining_massive_datasets-ch-2.pdf),* Leskovec, Rajamaran, Ullman - Ch. 2 pp. 21-31

**Recommended:**
- from [*Hadoop, The Definitive Guide,* White Ch. 2](https://github.com/mab253/bigdata_spring24/blob/main/readings/OReilly.Hadoop.The.Definitive.Guide.4th.Edition.2015-Ch-2.pdf), pp. 19-37 (you can skim/skip the Java code!)
- "[What is MapReduce?](https://www.youtube.com/watch?v=43fqzaSH0CQ)," G. Challen (internet-class), (video, 5 min.)
- "[MapReduce](https://www.youtube.com/watch?v=cvhKoniK5Uo)," R. Tickle (computerphile, U. of Nottingham), (video, 6 min.)
- [other resources](LINK) for MapReduce

---

**Week 3: Feb. 21** \
🏠 Online Zoom

*Spark + PySpark I*

**Reading for today:**
- "[Resilient Distributed Datasets: A Fault-Tolerant Abstraction for In-Memory Cluster Computing](https://github.com/mab253/bigdata_spring24/blob/main/readings/spark.pdf)," Zaharia et. al (paper)
- *Hadoop: The Definitive Guide* Ch. 19, pp. TBD 

**Recommended:**
- reading from the codecademy course: "[What is Spark](https://www.codecademy.com/courses/big-data-pyspark/articles/what-is-spark)," "[RDDs With PySpark](https://www.codecademy.com/courses/big-data-pyspark/lessons/pyspark-rdd-lesson/exercises/the-foundations-of-spark-rdds)"
- "[Apache Spark](https://www.youtube.com/watch?v=tDVPcqGpEnM)," R. Tickle (computerphile, U. of Nottingham), (video, 7 min.)
- [other resources](LINK) for Spark, PySpark, Python, etc.

---

**Week 4: Feb. 28** \
**NO CLASS, CCNY on Monday schedule**

---

**Week 5: March 6** \
🦋 Asynchronous

*Spark + Pyspark II*

**For this week:**
- finish the codecademy course + programming final notebook
- finalize symposium pairs + topics, start bibliography

**Recommended:**
- [other resources](LINK) for Spark, PySpark, Python, SQL etc.

---

**🏆 codecademy completed screenshot + final notebook DUE by Friday March 8th, 11:59pm**

---

**Week 6: March. 13** \
🏠 Online Zoom

*Data in the Cloud*

**For this week:**
- self-directed reading

**📚 bibliography + symposium proposal DUE by March 13th, 11:59pm**

---

**Week 7: March 20** \
🏠 Online Zoom

*AI Pipelines in the Cloud*

**Reading for today:**
- "Anatomy of an AI," *Atlas of AI* (Crawford) - pp. TBD
- self-directed reading

---

**Week 8: March 27** \
🏙️ In-Person

*Questions of Scale: Infrastructure + Materiality*

**TBD: DATA CENTER TOUR**

**Reading for today:**
- "The Cloud is Material: On the Environmental Impacts of Computation and Data Storage," Monserrate
- "View of a Former Verizon Building," Wakeling (video, 19min.)
- self-directed reading

---

**Week 9: Apr. 3** \
🏠 Online Zoom

*Ethics at Scale*

**Readings due today:**
- "Six Provacations for Big Data," boyd and Crawford
- *Mining of Massive Datasets,* Leskovec, Rajamaran, Ullman from Ch. 1, pp. 1-7
- self-directed reading

---

**Week 10: Apr. 10** \
🏙️ In-Person @ CCNY

*Symposium: Group 1 Presentations*

**Readings:**
- self-directed

---

**Week 11: Apr. 17** \
🏙️ In-Person @ CCNY

*Symposium: Group 2 Presentations*

**Readings:**
- self-directed

---

**Week 12: Apr. 24** \
**NO CLASS, SPRING RECESS**

---

**Week 13: May 1** \
🏠 Online Zoom

*NoSQL and Current Ecosystems; Final Project Check-In*

**Readings:**
- self-directed

---

**Week 14: May 8** \
🏠 Online Zoom

*Special Topics TBD; Final Project Workshop*

**Readings:**
- self-directed

---

**Week 15: May 15** \
🏙️ In-Person @ CCNY

*Wrap-Up & Final Presentations*

FINAL PROJECT DUE: May. 20th, 11:59pm

---

## key dates

- mini-course complete + programming notebook: due March 8th, 11:59pm
- bibliography + symposium proposal DUE by March 13th, 11:59pm
- TO BE CONFIRMED: in-person data center tour, Week 8 ~March 27th
- symposium: in-person, April 10th & April 17th
- final project presentation: in-person, May 15th
- final project paper/code: due May 20th, 11:59pm

## assignments

You will be responsible for:
- weekly: 💥 MAB ADD LINK![Discord log](https://github.com/mab253/dataviz_fall23/blob/main/found-visualizations.md), due 4:00pm EST *before* every class session, starting Week 1
- weekly: active participation in seminar discussion
- 1 programming assignment (codecademy mini-course + final notebook)
- 1 symposium presentation, in pairs
- 1 final project, pairs + solo work

More details for each of these assignments will be given throughout the semester.

## materials and references

All course material will be linked via this page on Github. I will often post extra links, tool documentation, and further references beyond the required materials that might be helpful to you in your own projects or filling in any gaps in your learning - but these extra resources will be optional. There will be no textbook for this course other than what's linked here. I will post the readings at least 2 weeks in advance, but if you look far ahead you might see some "TBDs." I will also post any in-class or online workshop material (slides, links, etc.) in a folder for each week.

## tools we will use a lot

- Blackboard
- [Discord](https://discord.com)
- [Google Colab/Jupyter Notebooks](https://research.google.com/colaboratory/faq.html)
- [Codecademy](https://codecademy.com/) - free account
- Cloud platform TBD: Hugging Face, Databricks

## expectations and requirements
### how can I do well in this class?

This class assumes a significant amount of self-directed, self-paced work - you have multiple weeks to finish the 1st programming project, for example, but I highly recommend starting early. The self-directed research phase is also meant to give you ample time to read deeply and tinker with tools related to your own curiosity. The more of this work you do and bring to the class, the better our seminar will be!

The format of this class means that **attendance is very important**, both for your own learning and the learning of your fellow students. Collaborative workshops and rich seminar discussions simply will not happen if we don't have a consistently present, engaged crew of classmates. Attendance in-class and during the online synchronous zoom sessions, as well as engagement (active listening, asking questions, etc.), will count toward your final grade.

That said, things happen. Everyone in this course will be allowed 1 absence, no questions asked. Every absence after this 1 will result in a deduction from your partipication/attendance portion of your final grade. **If you know ahead of time that you will need to miss class, please let me know as soon as possible**, and we can arrange a way for you to make up the work.

It is crucial that we build a space where everyone can learn. This class will be an inclusive and harassment-free space for everyone, with no tolerations of discimination based on gender, race, sexual orientation, religion, disability, or appearance. Please let me know privately if you require an academic accommodation.

## evaluation:

Grading breakdown:
- Active Participation/Attendance: 15%
- Weekly Discord Log: 10%
- Programming Assignment: 20%
- Bibliography + Symposium Presentation: 30%
- Final Project + Reflection:  25%

on late work:

**Late assignments drop 10% per day, starting after the due time.** (If you submit a Discord post 1 hour after the due date, for example, it drops 10%. If you wait another 24 hours, it drops 20%.)

**✉️ To receive credit for late work, you will need to e-mail me once you have completed it.**

If you have a reason for needing an **extension** (where you will receive full points), please reach out to me _before_ the due date for an assignment.

## academic honesty and integrity:

Plagiarism is "the act of presenting another person's ideas, research or writings as your own." [(CUNY)](https://www.ccny.cuny.edu/it/academic-integrity-policy). **This is as true for writing code as it is for writing others' words and pretending that they are yours.**

It is important that everything you turn in for this class is your own work. I understand that collaborating with your classmates can be really helpful when learning - you are allowed and encouraged to do this! However, the code and designs you submit must reflect work you have done on your own. To outline some of the boundaries here, it is acceptable to:

- Discuss the course’s material with others in order to understand it better.
- Help a classmate identify a bug in their code.
- Incorporate a few lines of code that you find online or elsewhere into your own code, provided that those lines are not solutions to assigned work and that you **cite** the lines’ origins.
- Turning to the web or elsewhere for instruction beyond the course’s own, for references, and for solutions to technical difficulties, but not for outright solutions to assigned work.
- Whiteboarding solutions with others using diagrams or pseudocode but not actual code.

It is **not acceptable** to:

- Search for or solicit outright solutions to assessments online or elsewhere.
- Split an assessment’s workload with another individual and combine your work. (exception: group projects)
- Submit (after possibly modifying) the work of another individual

_These terms (above) modified and inspired by Harvard's CS50's academic honesty policy, [here](https://cs50.harvard.edu/x/2022/honesty/)._

🤖 **On Generative AI:**

These tools are only going to get more powerful and more present; I want you to be able to know how to use them effectively in your own workflow. You **may** experiment with Generative AI (ChatGPT, etc.) for your work in this class, if you choose. In general:

- Proceed with caution: ask yourself if you would be better served by trying the solve the problem inside your own brain, or with reading materials, first!
- Also remember that these tools can provide inaccurate answers, i.e. "hallucinations" - be careful to cross-check with another source
- You may use Generative AI like a tutor, to ask questions to further clarify new material
- You may use Generative AI to improve code and generate lines of code within a larger assignment - **however, you must cite the tool you used**. 💥 MAB ADD LINK!
- You may NOT use Generative AI without citation 💥 MAB ADD LINK!
- You may NOT use Generative AI outputs as the entirety of an assignment: for example, an entire paper, an entire solution to a programming problem, etc.

I have ways of checking on the originality of your code and assignments. Consequences for violating this academic honesty policy will be severe, including but not limited to failing the course.

You can find CCNY’s Academic Integrity Policy in full [here](https://www.ccny.cuny.edu/it/academic-integrity-policy).  Do not plagiarize.

## contact and questions

👾 Our class will have a [Discord](https://github.com/mab253/dataviz_fall23/blob/main/discord.md) server for posting questions and communicating with each other.

If you would like to ask a question privately, please e-mail me - I am available and I try to respond within 24 hours. You are also invited to schedule some virtual office hour time to talk, [here](https://www.cal.com/mab253). If you need a time that's not on this schedule, please e-mail me.

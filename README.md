# Free and Open-Source Software Course 🕊

This repository provides a university course template to teach about Free and Open-Source Software (FOSS).
The course is broadly structured as follows:

1. Initial phase: kick-off event for interested students. Advertise the course at your faculty and ask students to submit a letter of motivation.
2. Select students and plan the semester. Send selected students an [e-mail](templates/mail_students_select_project.md) to select a project.
   Get in touch with guest speakers.
3. Start of the semester, theory part (3-4 weeks): students will learn and discuss theoretical aspects of FOSS .
4. Preliminary report: students submit a preliminary report about their community of choice and hold a brief presentation.
5. Practical part (~12 weeks): students will contribute to their project of choice.
   They meet bi-weekly with their supervisors to report on their progress and problems.
6. Final report: students submit their final report, reflecting on their experiences and hold a brief presentation.

Moreover, we **highly recommend** to invite guest speakers from industry and academia to supplement the course content.
You should evenly schedule them throughout the practical part of the course.
This way, there's a regular place for students to meet and discuss their experiences.

## Why Teach FOSS 🤔

Here is a [great post](http://teachingopensource.org/for-instructors/why-teach-open-source/) answering that question.
Besides what is said there, computer scientists have an incredibly strong impact on the development of our society by controlling
the technology empowering it.
We believe that it is our duty to shed light on the different means of engaging with artefacts created by computer scientists and their
sociological as well as moral ramifications.

## How to Use This❓

The template files are provided as markdown files.
You can transpile them to, for example, HTML using [pandoc](https://pandoc.org/).

**Note:** At [TU Munich](https://www21.in.tum.de/teaching/osp/WS20/), we used [Hakyll](https://jaspervdj.be/hakyll/) to automate this process,
including a custom `navbar-template: templates/navbar.html` property to render the shared navigation bar.
Simply change/remove this property and use whatever fits your purpose.

You will then have to:
1. Clone the repository
2. Fill in the TODOs in each file according to your plan
3. Run the course and contribute back to this repository :)

## Tips for Guest Speakers 🗣

The course covers most aspects to practically work with FOSS projects.
It also covers some theoretical, legal, and moral aspects, but to a way smaller extent.
We hence **highly recommend** you to invite guest speakers that are able to talk about
some of these aspects.
Here are some possible questions you can try to address by means of a guest speaker:

1. (Philosophy, Politics, Social Sciences) Are we ought to work on FOSS projects?
   What are the moral, historical, and sociological implications of a world run by FOSS or proprietary software?
   Can we employ principles of FOSS outside the world of software development in politics and social sciences?
    - Invite scientists, philosophers, and politicans to talk about their experiences and judgements
2. (Economics) How to build a profitable business around FOSS projects?
   Are there alternatives to exponential-growth capitalism founded on proprietary software?
    - Invite successful entrepreneurs whose business is radically based on FOSS projects.
3. (Practical Experience) How to motivate an open-source community?
   How to find new maintainers and make them flourish?
    - Invite maintainers of large FOSS projects to talk about their motivation strategy and insights.

Ideas to find guest speakers:
1. [GNU and Free Software Speakers](https://www.gnu.org/people/speakers.en.html)
2. Contact maintainers of well-known FOSS projects
3. Personal contact: do you know anyone in your area working on FOSS software? Local speakers create a tangible atmosphere!
4. Check the speakers list of FOSS conferences.
5. Contact authors of books dealing with FOSS.

## Tips for Communication 🔤

We learnt that students love to share and discuss their knowledge and ideas during the semester.
We hence **highly recommend** you to make use of some sort of communication platform for your course,
e.g. [Zulip](https://zulip.com/) or [Mattermost](https://mattermost.com/).

## Known Iterations 👩‍🏫👨‍🏫

Here are some known iterations of this course to get inspired:
- 10.2020 to 03.2021 at [TU Munich](https://www21.in.tum.de/teaching/osp/WS20/): you can also check out the students' reports on the course website

Gonna run this course as well? Make a pull-request to add your course to this list! :)

## What Our Students Say 👩‍🎓👨‍🎓

```quote
Highly relevant to any computer scientist!
Covering theoretical, practical, and moral aspects of software development.
```
```quote
The course offers many paths to success and individuality for everyone.
Students feel valued and actually learn how to work with real world projects.
```
```quote
Extremely well-organised course. My friends got envious when I told them about it.
```

## Contributing 👥

If you run this course, you surely have ideas to further improve it.
Please let your ideas flow back into this repository so that everyone in this world can benefit it!

## Acknowledgements 🙌

This course was developed by

1. [Kevin Kappelmann](https://github.com/kappelmann),
2. [Lukas Stevens](https://github.com/lukasstevens), and
3. [Maximilian Haslbeck](https://github.com/maxhaslbeck)

at the [Chair for Logic and Verification](www21.in.tum.de) at the [Technical University of Munich](https://www.tum.de/en/).
Special thanks to [Simon Wimmer](https://github.com/wimmers) that supported the initiation of this project.

The course structure was inspired by the [FOSS development course](https://gitlab.cecs.anu.edu.au/comp8440/course) at the Australian National University.


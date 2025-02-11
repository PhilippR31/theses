---
title: Home
layout: home
nav_order: 1
description: "Welcome"
permalink: /
---

# Bachelor's and Master's Theses

This page provides an overview and resources for writing a thesis in the area of [digital work](https://www.uni-bamberg.de/digital-work/){: target="_blank"}.
The thesis is one of the key accomplishments when studying at a University.
To support you throughout the process, we provide a clear overview of the steps, transparent evaluation criteria, as well as a developmental approach.

{: .text-center}
```mermaid
flowchart LR

    subgraph Process[" "]
        Feedback -. consult .-> Init
        Feedback(["<a href='docs/feedback.html'>Feedback</a>, <a href='https://digital-work-lab.github.io/handbook/docs/30-teaching/30_processes/30.22.improvements.html'>improvement</a>,<br><a href='docs/completed.html'>completed theses</a>, <a href='docs/hall_of_fame.html'>hall-of-fame</a>"]) -.- Grading
        OpenTopics(["<a href='docs/topics.html'>Open topics</a>"]) -.- |consult| Init
        Init["<a href='#1-initial-meetings-to-discuss-the-topic'>Initial meeting</a>"] ==> |"<a href='docs/expose.html'>Write an exposé</a>"| Admission["<a href='#2-formal-admission'>Formal admission</a>"]
        Admission ==> Writing["<a href='#3-thesis-writing-and-feedback-sessions'>Thesis writing and feedback sessions</a>"]
        Writing ==> Submission["<a href='#4-submission-of-the-thesis'>Submission</a>"]
        Submission ==> Grading
        Writing -. Master's students .-> Presentation["<a href='#5-thesis-presentation'>Presentation</a>"]
        Presentation -.-> Grading["<a href='#6-grading-and-feedback-session'>Grading and feedback</a>"]
        Criteria(["<a href='docs/evaluation.html'>Evaluation criteria</a>"]) -.- Writing
        Criteria -.- Presentation
        Criteria -.- Grading
    end
    style Init stroke:#333,stroke-width:3px
    style Admission stroke:#333,stroke-width:3px
    style Writing stroke:#333,stroke-width:3px
    style Presentation stroke:#333,stroke-width:3px
    style Submission stroke:#333,stroke-width:3px
    style Grading stroke:#333,stroke-width:3px
    style Process fill:white,stroke:#333,stroke-width:3px
```

- A detailed overview of the administrative process is available [here](https://digital-work-lab.github.io/handbook/docs/30-teaching/30_processes/30.40.theses_process.html){: target="_blank"}.
- A changelog for this document is available [here](https://github.com/digital-work-lab/theses/commits/main/index.md){: target="_blank"}.

## 1. Initial meetings to discuss the topic

Students can select [open topics](docs/topics.html) or suggest topics related to our research areas.
To start the process, reach out via e-mail and schedule a meeting to discuss topic and next steps:

{: .text-center}
[Schedule a meeting](https://calendly.com/gerit-wagner/30min){: .btn .btn-green target="_blank"}
{: .text-center}

To prepare the next step, it is recommended to start developing an [exposé](docs/expose.html).

## 2. Formal admission

Students send the **application for admission** to the thesis to the *examination office* via their Stud e-mail address.
You can use [this e-mail template](docs/admission_mail.html).

The examination office **verifies** the admission requirements.

- If admission requirements are met, the topic confirmation is created with text fields so that the topic of the thesis and the date of topic issue can be entered.
- If the admission requirements are not met, the student is notified that the application has been rejected.

The examination office may ask the student to request an **approval by the examination committee** (Prüfungsausschuss) to write a thesis in the area of *Digital Work*.
This is the case when older regulations (Studien- und Fachprüfungsordnung) apply (i.e., when master studies were started before 2018), or for students of Informatics and Applied Informatics (e.g., International Software Systems Science).

Students **receive the topic confirmation** as a (protected) Word document (.docx) by e-mail together with processing/submission instructions as well as inspection statement.
The next step is to make an appointment with the thesis advisor to determine the topic and sign the topic confirmation.
Please share the Word document with your thesis advisor shortly before the meeting.

Student and thesis advisor schedule a meeting to determine the topic and **sign the topic confirmation**.
If the appointment is online, you can print and sign the confirmation, and send it to our [postal address](https://www.uni-bamberg.de/digital-work/team/prof-dr-gerit-wagner/){: target="_blank"}.
It is important that we receive **two paper versions with original signatures**:

- 1 original with signature of the professor and the student **for the student**.
- 1 original with signature of the professor and the student **for archiving at the chair** .

## 3. Thesis writing and feedback sessions

Bachelor's theses are usually due in 4 months, Master's theses in 6 months.
The official requirements can be found in the regulations linked below.
It is not necessary to submit the thesis in the semester in which it was started (unless you would take longer than the maximum duration of study).
For students of Applied Informatics, Software Systems Science, and Computing in the Humanities a practical part is required for Bachelor's and Master's theses.

Students are expected to complete the exposé before writing the thesis.
A thesis must be written in English.
The following resources may be helpful:

- The [evaluation criteria](docs/evaluation.html)
- The thesis template for [Markdown](https://github.com/digital-work-lab/thesis-template){: target="_blank"} ([create repository from template](https://github.com/new?template_name=thesis-template&template_owner=digital-work-lab){: target="_blank"}) <!-- or [word](https://raw.githubusercontent.com/digital-work-lab/handbook/main/assets/docs/template.docx) -->
- The [literature review section](https://digital-work-lab.github.io/handbook/docs/20-research/20_processes/20.10.literature-review.html)
- The [analysis templates section](https://digital-work-lab.github.io/handbook/docs/20-research/20_processes/20.21.analysis-templates.html)
- The [writing section](https://digital-work-lab.github.io/handbook/docs/20-research/20_processes/20.29.writing.html) (in particular correct citation practices)
- The [guideline for the use of digital tools](docs/digital_tools.html)
- Note: ethics statements cannot be issued for theses, but students are advised to consult the [ethics](https://www.uni-bamberg.de/gremien/senat-kommissionen/kommissionen/ethikrat/){: target="_blank"} page.

It is good practice to write the thesis in a Git-versioned repository, to add notes from the meetings to the README.md file, and give your thesis advisor access to the repository.

We offer regular **feedback sessions** (every one to two weeks) to discuss open questions and the next steps:

- Feedback sessions can be in person or online
- They can be scheduled via [calendly](https://calendly.com/gerit-wagner/30min){: target="_blank"}

To receive feedback on the written document, please

- Share it 1-2 days before the meeting
- Indicate which sections should be read
- Use a file-format suitable for adding comments (pdf or doc/x)
- Use a suitable filename (e.g., `2023-12-01-Thesis-Name.pdf`)

We expect you to communicate on an equal level:

- In e-mails, write `"Hallo Herr Wagner"` (instead of `"Sehr geehrter Herr Prof. Dr. Wagner"`).
- If you do not agree with a particular suggestion, challenge it and explain why you would do it differently.
- Instead of apologizing, say [thank you](https://www.popsugar.com/smart-living/why-you-should-say-thank-you-instead-of-sorry-47250332){: target="_blank"}.

Before submitting the thesis, we encourage students to consult the [pre-submission checklist](docs/pre_submission.html).

## 4. Submission of the thesis

Two copies in hard bound form and one digital version each are to be submitted to the examination office.

- During opening hours Mon-Fri 10.00 - 12.00: Hand in the thesis at the examination office (Kapuzinerstr. 25)
- Outside of opening hours: Drop the thesis in the mailbox of the University Administration (Kapuzinerstr. 16)
- Dispatch by mail (the date of the postmark counts) Otto-Friedrich-University, Examination Office - 96045 Bamberg

The digital thesis can be a CD-ROM or USB stick. It contains the thesis as a PDF document, and possibly a digital appendix.

## 5. Thesis presentation

- Students present their master thesis. Evaluation criteria are stated [here](docs/evaluation.html#presentation).
- Students can suggest a date for the presentation (before or after submitting the thesis) and the thesis advisor selects a second examiner.

## 6. Grading and feedback session

The thesis advisor (professor) grades the thesis based on the predefined [criteria](docs/evaluation.html). Grades are entered by the examination office. Students can check the grade via FlexNow.

Afterward we provide feedback on the thesis and explain the grading.
A short summary is stored on our [feedback page](docs/feedback.html) if students agree.

{: .text-center}
[Schedule feedback session](https://calendly.com/gerit-wagner/30min){: .btn .btn-green target="_blank"}
{: .text-center}

## Applicable regulations

<!-- 
- Bachelor Business Information Systems
- Bachelor International Information Systems Management
- Bachelor Angewandte Informatik
- Bachelor Software Systems Science
- Master Business Information Systems
- Master International Information Systems Management
- Master Angewandte Informatik
- Master Software Systems Science
- Master Computing in the Humanities
 -->

- [Prüfungs- und Studienordnungen](https://www.uni-bamberg.de/abt-studium/aufgaben/pruefungs-studienordnungen/){: target="_blank"}, insbes. Modulhandbücher

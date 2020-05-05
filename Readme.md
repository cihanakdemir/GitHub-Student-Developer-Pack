# GitHub Student Developer Pack

Here you'll find the information to provide your student the GitHub Student Developer Pack

![GitHub Student Developer Pack](resources/ghdp.png "GitHub Student Developer Pack")


In December 2019 we started a partnership with GitHub and we’ve been accepted in the [GitHub Education Campus Program](https://education.github.com/schools).

As a GitHub Education school we’ve access to several benefits for the students and trainers:


- free access to GitHub Enterprise Server and GitHub Pro account for teachers

- advanced training to master GitHub with the Campus Advisors & Campus Expert programs

- automated access to premium GitHub Education features, like the GitHub Student Developer Pack

## Students' Benefits

In the past to access the GitHub benefits our students had to apply individually by sending a documentation provided by the campus office.

In some cases (too many) students' applications were rejected without a specific reason and without any details. Many students became discouraged, decided to give up and didn't try to access the benefits again.

Now as GitHub partner we can provide them with a unique link to access to the GitHub Student Developer Pack directly.

The information about the GitHub benefits for students are in [this document](resources/GitHubStudentDeveloperPack-Students.pdf)

You should review and share it with your students.

List of the [benefits](https://education.github.com/pack#offers) on GitHub Education


## Access code

### Each student will ask you, their teacher, to recive the access code. 

1 - The students request the access code to their teacher  
2 - The teacher open a request for all the students of a class  
3 - The Github Campus Advisor (Leandro) create the code and send them back to the teachers  
4 - The teacher distribute the code to the students 

To issue the GitHub Student Developer Pack code you need to provide a list with the info of your students.

The list should be in JSON format. Here an example:

```
[{
      "studentId": "01",
      "email": "anne.bonni@web.de",
      "class": "BER-FbW123",
      "firstName": "Anne",
      "lastName": "Bonny"
},{
      "studentId": "02",
      "email": "mary.read@gmx.de",
      "class": "BER-FbW123",
      "firstName": "Mary",
      "lastName": "Read"
}]
```

- You can use the student number from your *Classbook* spreadsheet or a sequential number list
- The student email should be the same used by the students on their GitHub account

## Code request process for trainers


- Follow this [link](https://classroom.github.com/a/ff3VkF_2)
to start a **GitHub Classroom** assignment: it will automatically create a copy of this repository

- If you need help with **GitHub Classroom** review the [documentation](https://classroom.github.com/help)

- Add the JSON file with your students list in your repository. Please use the location and class in the filename, eg. `BER_FbW28.json`

- Validate your JSON, you can use [JSON-formatter](https://jsonformatter.curiousconcept.com/)


- When you're ready, submit your student list (push **your** repository)

- Issue a new [Request](https://github.com/DCI-TechEd/GitHub-Student-Developer-Pack/issues/new/choose) to notify that you submitted your list.

- Fill the request with the information about class/location. If you want you can add extra info and labels.

- You can check the progress of your request in the [Project](https://github.com/DCI-TechEd/GitHub-Student-Developer-Pack/projects/1).



If you have any question feel free to contact me in Slack (Leandro) or on github@digitalcareerinstitute.org



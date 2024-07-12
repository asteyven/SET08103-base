# Coursework Reassessment Details

## Reassessment Coursework Proforma

| |                                                          |
| --- |----------------------------------------------------------|
| Module number | SET08103-SET08403                                        |
| Module title | Software Engineering Methods                             |
| Module leader | Andreas Steyven                                          |
| Tutor with responsibility for this Assessment. Student's first point of contact. | As above.                                                |
| Assessment | Project                                                  |
| Weighting | 60% of module assessment                                 |
| Size and/or time limits for assessment | See description below.                                   |
| Deadline of submission | Monday the 5th August, 3pm                               |
| Arrangements for submission | Coursework to be submitted via Moodle and GitHub.        |
| Assessment Regulations | All assessments are subject to the University Regulations |
| The requirements for the assessment | See below.                                               |
| Special instructions | N/A                                                      |
| Return of work and feedback | Online via Moodle.                                       |
| Assessment criteria | See below.                                               |

## Coursework Specification

The resit coursework is the same as the first diet but will be conducted as an individual project rather than as part of a Scrum team. You should still follow an agile methodology by using project management tools covered in the module to organise your work into sprints. 
Details on Scrum are provided in [Unit 01 (b)](../units/unit01/unit01b.md), including an FAQ on how to apply Scrum in the module.
As you are working on the project alone the number of reports needed to be generated has been reduced from 32 to 8.

You work for an organisation that requires reporting on population information.  You have been tasked with designing and implementing a new system to allow easy access to this population information.  The organisation has provided you with an SQL database to work from available [here](https://downloads.mysql.com/docs/world-db.zip).

The organisation has asked for the following reports to be generated:

- All the countries in the world organised by largest population to smallest.
- All the cities in the world organised by largest population to smallest.
- All the capital cities in the world organised by largest population to smallest.
- The top `N` populated cities in the world where `N` is provided by the user.
- The population of people, people living in cities, and people not living in cities in each country.

Additionally, the following information should be accessible to the organisation:

- The population of the world.
- The population of a continent.
- The population of a region.
- The population of a country.
- The population of a district.
- The population of a city.

Finally, the organisation has asked if it is possible to provide the number of people who speak the following languages from greatest number to smallest, including the percentage of the world population:

- Chinese.
- English.
- Spanish.

### Country Report

A country report requires the following columns:

- Code.
- Name.
- Continent.
- Region.
- Population.
- Capital.

### City Report

A city report requires the following columns:

- Name.
- Country.
- District.
- Population.

### Capital City Report

A capital city report requires the following columns:

- Name.
- Country.
- Population.

### Population Report

For the population reports, the following information is requested:

- The name of the continent/region/country.
- The total population of the continent/region/country.
- The total population of the continent/region/country living in cities (including a %).
- The total population of the continent/region/country not living in cities (including a %).

---
# Submission

The submission should be submitted to Moodle by the date stated at the top of this document.

A zip of your master branch should be submitted to Moodle along with a text file with links to your GitHub repository and zube.io web pages.

The marking criteria will reflect the use of the tools covered in the module as well as coding quality and testing.

### Marking Criteria

The following criteria will be used to assess the quality of your work.

- GitHub project set up and used effectively
- Evidence of project management
    - Product Backlog created
    - Kanban Boards in use
- Project builds to self-contained JAR with Maven
- Dockerfile for project set-up and works
- GitHub Actions for project set-up and build is working using JAR, and Docker on GitHub Actions
- Correct branches for GitFlow workflow created - includes `master`, `develop`, and `release` branches
- Release created on GitHub
- Code of Conduct defined
- Metrics from GitHub  
    - Number and frequency of commits
- Code quality including comments
- Issues being used on GitHub
- Correct badges in README.md on `master` branch
    - Build status for `master`
    - Build status for `develop`
    - Code coverage of tests for `master`
    - Release name
    - License
- Tasks defined as user stories
- Full use cases defined
- Use case diagram created
- Suitable unit tests defined
- Suitable integration tests defined
- Tests running on GitHub Actions
- Project requirements met (reports generated)


# Final Deliverable

**You must follow these steps to receive a coursework grade for the module.** 
We require a copy of your submission for moderation, and therefore you will have to submit your work as defined below.  You will also receive your final 10% grade for final delivery based on the completeness and quality of your submission.

## Step 1: Ensure You Have Submitted Your GitHub Repository Clone URL and zube.io URL to Moodle

Ensure you submit a text file providing links to your GitHub Repository and Zube.io URL along with a zip of your master branch to Moodle by the deadline stated at the top of this document. 
If you do not provide this information, it will be counted as a non submission.

## Step 2: Your Main Repository Readme Details the Requirements Met

There are 8 requirements in total. 
Your `README.md` should state how many out of 8 have been met, and a percentage. 
For example:

> 4 requirements of 8 have been implemented, which is 50%.

We then want evidence of each feature being met. 
This will be in the form of a table (written in Markdown) with a screenshot from your application showing output that meets the requirements.  
We require the following columns:

1. ID of the requirement.
2. Name of the requirement.
3. Has the requirement been met (Yes or No).
4. Screenshot.

For example:

| ID    | Name                                                                             | Met  | Screenshot |
|-------|----------------------------------------------------------------------------------|------|------------|
| 1     | All the countries in the world organised by largest population to smallest.      | Yes | image |
| 2     | All the cities in the world organised by largest population to smallest.         | No |   |
| 3     | All the capital cities in the world organised by largest population to smallest. | Yes | image |

**Your submission will be checked to ensure this information is correct. 
If incorrect information is provided this will be considered an act of academic misconduct and dealt with accordingly.**

No demo of your work is required unless academic misconduct is suspected.
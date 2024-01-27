# Technical Exercise

The purpose of this document is to provide candidates with details of the technical exercise, which form part of the interview process at Bamg Sports Ltd.

Below are given details of the exercise and expectations.

Once the exercise has been submitted a code review interview will be conducted with the CTO to assess the candidate submission against expectations.

## Guidence

The Job Description highlights some of the major packages, languages and tools used by Bamg Sports during their day to day operations.  It is not expected that candidates use them all if they are not known to them already, however, it would be most helpful for the candidate to use as many of them as they are familiar with.

However, we strongly suggest the following tools be used: git, typescript, markdown for documentation.

## Expectations

The purpose of the exercise is not a test, but to be a tool with which an informed dialog can be had with the candidate.  Example points which will be discussed in the review interview may include:

* Comprehension of the exercise and expectations
* Which tooling were chosen and why
* Discussions on planning and features that might be developed
* Use of versioning tools to aid development
* Any patterns that might be used
* Test of and or consideration for testing
* Self documentation

## Deliverables

Please provide a gitlab hosted repository containing all files associated with your submission.

Include in that repository a `CANDIDATE_DOCUMENTATION.md` which should contain:
1. Any notes your made preparing for the exercise
1. Instructions for executing the submission
1. Any notes about additional work that could be achieved had you had more time

When complete, email the submission URL to julia.underwood@bamgsports.com.


# The Exercise

The exercise is split into two parts, frontend and backend.  You must attempt **at least one**.

In essence this is a simple data management system, where the user can view/edit a table of data, forms to add and edit the data, and the display of related data, along with an accompanying API.

## Backend

Provided in the backend folder is an `.sql` file describing a database.  Use it to create the schema of a database.

The task is to create an API that will interact with this database.  The following is required

1. Provide an API with endpoints that allows data to be retrieved from the tables
1. Provide an ability to update some of the fields in the tables whilst disallowing changes to other fields
1. Provide an ability to add a new record, and delete a record
1. Ideally the endpoints will provide some nested data to be obtained
1. The resulting program must be executable and be able to interact with via a tool like Postman

1. **BONUS: Only if you have time** normalise the database in a spreadsheet spreadsheet, include a link to it in CANDIDATE_DOCUMENTATION.md

## Frontend

The task is to create a UI that could provide access to the API and data held within.  Use the `.sql` file in the
backend folder to inform yourself of the data you will need to work with.   The following are required

1. Provide a set of UIs which could display the data to be retrieved from the API

    NOTE: You may mock the backend responses if you do not implement a backend.  **Important** Include your mock data in your git history

1. Provide an ability to display any nested data / repeating data which may be returned from the API
1. Provide forms that permit the update of some data, but also prevent the update of other data
1. Provide an ability to add a new record, and delete a record
1. Ideally the UI should display nested data
1. The resulting program must be executable and be able to interact with any browser
1. **BONUS: Only if you have time** implement a client-side caching strategy


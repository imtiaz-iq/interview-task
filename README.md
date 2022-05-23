# iQuantile Interview Task

Hello candidate,

Thank you for your interest in this position.

To understand what kind of a colleague you are we have set up some tasks for you. This is not a typical test that has pass fail criteria.

What we want to know is what kind of a developer you are. What skills you have. And what makes you different.

We would prefer that you use Vue.js for this project. While it's not required to use Vue.js, we want to make sure that you have a good understanding of how modern SPAs work. So we cannot accept projects that do not use any modern framework. If you use any other framework, we expect that you will read up on Vue and be ready to draw comparisons with other frameworks.

In the tasks we have set up you will be expected to follow some best practices and standards. Following are some resources to help you with that:
- [Front-end checklist](https://github.com/thedaviddias/Front-End-Checklist)
- [Lighthouse](https://developers.google.com/web/tools/lighthouse)

# Task

This task was copied from [App Ideas Collection](https://github.com/florinpop17/app-ideas) by [Florin Pop](https://www.florin-pop.com/)

You are required to build the most you can in 7 days. This does not mean we will accept a broken project. Use your judgement to build a working project with as many features as you can.

We will be building a website for conducting surveys. While not necessary-- if you can connect a backend to this then that would be a plus. Otherwise, just use static data or browser APIs.

Users of this app are divided into two distinct roles, each having different
requirements:
-   _Survey Coordinators_ define and conduct surveys. This is an administrative
    function not available to normal users.
-   _Survey Respondents_ Complete surveys and view results. They have no
    administrative privileges within the app.

We will try to focus more on the _Survey Respondents_ for this project. Again this doesn't mean we will accept a broken project. You can roughly build a working survey builder tool or just define some static survey. You will not be judged critically for the _Survey Coordinators_ part. What we really want to see is how you build working forms and manage their data.

Commercial survey tools include distribution functionality that mass emails
surveys to Survey Respondents. For simplicity, this app assumes that surveys
open for responses will be accessed from the app's web page.

## User Stories

### General

-   [ ] Survey Coordinators and Survey Respondents can define, conduct, and
        view surveys and survey results from a common website
-   [ ] Survey Coordinators can login to the app to access administrative
        functions, like defining a survey.

### Defining a Survey

-   [ ] Survey Coordinator can define a survey containing 1-10 multiple choice
        questions.
-   [ ] Survey Coordinator can define 1-5 mutually exclusive selections to each
        question.
-   [ ] Survey Coordinator can enter a title for the survey.
-   [ ] Survey Coordinator can click a 'Cancel' button to return to the home
        page without saving the survey.
-   [ ] Survey Coordinator can click a 'Save' button save a survey.

### Conducting a Survey

-   [ ] Survey Coordinator can open a survey by selecting a survey from a
        list of previously defined surveys
-   [ ] Survey Coordinators can close a survey by selecting it from a list of
        open surveys
-   [ ] Survey Respondent can complete a survey by selecting it from a list of
        open surveys
-   [ ] Survey Respondent can select responses to survey questions by clicking
        on a checkbox
-   [ ] Survey Respondents can see that a previously selected response will
        automatically be unchecked if a different response is clicked.
-   [ ] Survey Respondents can click a 'Cancel' button to return to the home
        page without submitting the survey.
-   [ ] Survey Respondents can click a 'Submit' button submit their responses
        to the survey.
-   [ ] Survey Respondents can see an error message if 'Submit' is clicked,
        but not all questions have been responded to.

### Viewing Survey Results

-   [ ] Survey Coordinators and Survey Respondents can select the survey to
        display from a list of closed surveys
-   [ ] Survey Coordinators and Survey Respondents can view survey results as
        in tabular format showing the number of responses for each of the possible
        selections to the questions.

## Bonus features

-   [ ] Survey Respondents can create a unique account in the app
-   [ ] Survey Respondents can login to the app
-   [ ] Survey Respondents cannot complete the same survey more than once
-   [ ] Survey Coordinators and Survey Respondents can view graphical
        representations of survey results (e.g. pie, bar, column, etc. charts)

## Useful links and resources

Libraries for building surveys:

-   [SurveyJS](https://surveyjs.io/Overview/Library/)

Some commercial survey services include:

-   [Survey Monkey](https://www.surveymonkey.com/)
-   [Traversy](https://youtu.be/SSDED3XKz-0)
-   [Typeform](https://www.typeform.com/)

## Example projects

[Javascript Questionnaire](https://codepen.io/amyfu/pen/oLChg)

[React Survey App](https://chamatt.github.io/survey-web-app/#/) ([Code](https://github.com/chamatt/survey-web-app))
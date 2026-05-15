# Industry Earnings Survey - Interactive Prototype

The web-based prototype represents a government style survey. Using to basis of a high-fidelity Figma design it incorporates HTML and CSS to create a fully functioning website. The prototype demonstrates use of semantic HTML, accessible interaction states, and user-centred design principles.
The prototype was designed iteratively in CodePen. Semantic HTML was used as the basis then CSS was applied reflecting the style elements from the high fidelity Figma prototype. The source Figma prototype can be found at: https://www.figma.com/design/WEadueZauvI1aJOoIZgrHO/Industry-Earnings-Survey-Interactive-Prototype?node-id=0-1&t=eZp7FLUnNfQWpzeA-1

## Live prototype

[Introduction — Industry Earnings Survey](https://bensgts.github.io/Industry-Earnings-Survey/)


## Pages

The prototype is a five-page static website that supports which supports the complete user task of answering a survey question and submitting it. 

`index.html` - Introduction and overview of the survey

`question.html` - Survey question with two alternative input formats and on-submit validation

`submit.html` - Review answers and submit, with an error summary if any question is unanswered

`thank-you.html` - Confirmation that the survey has been submitted

`save-exit.html` - Confirmation that progress has been saved when the respondent exits early

`styles.css` - Shared stylesheet for all pages


## User task

* Begin at the introduction page, answer the hours question (in either HH:MM or decimal form), review your answer on the submission page, and submit. 
* Use the back and next buttons, and the left-hand navigation menu to navigate the website.
* Navigating to the submission page without answering or answering in the wrong format  triggers the error summary pattern.
* Click either save & exit button at any point to see the saved progress confirmation.

## User goal
Access the website to complete and submit the survey as easily and accurately as possible through clear and simple methods for reporting statistical information.

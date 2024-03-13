Cloze Moodle Questions Generator
==============

This is an [online Cloze Moodle Questions Generator](https://jocoteles.github.io/clozeMoodleGenerator/) suitable for generating multiple random instances of a question using python code. The application is composed of two windows.

In the first window, you enter the Cloze question text of your choice following the Cloze syntax as described in the [Embedded Answers (Cloze) question type page](https://docs.moodle.org/403/en/Embedded_Answers_(Cloze)_question_type). But in this application, you can include python variables and operations (using double square brackets) in place of the traditional fixed text or numerical cloze values.

In the second window, you include python code that will perform the desired calculations in the variables placed in the first window, including the use of random variables for generating multiple values for the same question.

By clicking in the Generate XML button, the chosen Number of random questions will be generated and saved in a single moodle cloze XML file, which can be uploaded to a moodle course in order to be included as a random question, for example.

You can locally save the text and code of both input windows as a single json file by clicking in the Save button. The json file contain two keys, called "cloze" and "python", with the text of the respective windows. In the same way, you can load your saved json file into the application by clicking in the Choose File button.

In order to check if the application will render the desired cloze questions before saving the many instances to the XML file, you can click at the Render HTML sample.

Your Project's Name
One or two paragraphs providing an overview of your project.

Essentially, this part is your sales pitch.

UX
Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:

As a user type, I want to perform an action, so that I can achieve a goal.
This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

Features
In this section, you should go over the different parts of your project, and describe each in a sentence or so.

Existing Features
Feature 1 - allows users X to achieve Y, by having them fill out Z
...
For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

Features Left to Implement

I do have many ideas of how to improve my application. Here are some of them:

1. First and most important is to make accounts secure and provide such features as retrieving forgotten passwords, disabling accounts, also connecting and registering cookbook with facebook accounts.
3. Separating different parts of user's filter, so that user will be able to discard any filters without using query form again.
4. Re-structuring database by adding sub-categories.


Technologies Used
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- HTML and CSS
    - project uses **HTML** and **CSS** to build webpages.
-  [Bootstrap](https://getbootstrap.com/)
    -project uses **Bootstrap** for webpages' layout.
- [Javascript](https://www.javascript.com/) 
    -The project uses **Javascript** to enhance pages functionality.
- [JQuery](https://jquery.com)
    - The project is using Bootstrap's **JQuery** for responsiveness.
- [Python](https://www.python.org/)
    - The project's back-end was written in **Python** .
- [Flask](http://flask.pocoo.org/)
    - project was built **flask** microframework due to its simplicity.
    - project uses **flask.session** for session functionality. 
- [MongoDB](https://www.mongodb.com/)
    - The project uses **MongoDB** database, mongod version 3.6.6..
- [Mlab](https://mlab.com/)
    - The project's database is hosted on **Mlab.com**.
- [Pymongo](https://pypi.org/project/pymongo/)
    - The project uses **Pymongo** as driver to connect to the database.
- [Flask-Pymongo](https://pypi.org/project/Flask-PyMongo/)
    - The project uses  **Flask-Pymongo** as a support for some tasks.
- [Flask-paginate](https://pythonhosted.org/Flask-paginate/)
    - The project uses **Flask-paginate** for pagination.

## Database structure

As the project is using **mongodb**, I have just made a simple file explaining documents' structure. Link

Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

Credits
Content
The text for section Y was copied from the Wikipedia article Z
Media
The photos used in this site were obtained from ...

## Acknowledgements

Inspirations for this project was [Allrecipes](http://allrecipes.co.uk/)
- how they require users to upload for example, list of ingredients for a recipe. Of course I have no idea how it is implemented, but just watching gave me some hints.
- there is no requirements for image size, and also images displayed in search results are not statically sized, and I used a similar solution in my project.

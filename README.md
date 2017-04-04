# Small Unity client to work with the Yle API

* You will need to install Unity version 5.5 (or newer) to complete this assignment
* YLE API documentation at http://developer.yle.fi/index.en.html

Functional specification of the app:
* The application should have an input field where the user can provide what programs to search for (a search query).
* The Finnish title of each result should be displayed in a scrollable list.
* When submitting a search, only the first 10 results should be retrieved from the API.
* When the user scrolls to the last few items in the list, the next 10 results should be appended to the list. An example for this type of scrolling can be seen here: http://9gag.com/

NOTE: You will need to register an application key and secret for the YLE API, and put them in the application, after which it should be usable.

You task is to:
* Initialize a local git repository, and add all the current files.
* Test the application manually, you may modify the source code while doing this.
* Write a small set of unit/integration tests. Don't test everything, but concentrate on what you think is relevant and meaningful. Commit the tests to your repository. Add a comment to each test to describe why you think it is important.
* Document your findings in the level of detail you would use if you were to report them to a developer. Add this documentation as an easy to find file in your git repository.
* OPTIONAL: fix the issues you find. This is not required, but if you want to make sure your tests pass when the application behaves properly, you may do this.
* Using `git bundle create firstname_lastname.bundle --all` create a bundle of you repository, and submit it back to us via email.

The purpose of the tests and testing is to:
* Find out if there are any bugs in the application
* Find out if there are situations where the application may behave badly in any way

While writing tests, feel free to refactor the code structure. However, please document your progress in your git history, by making meaningful commits. If you decide to fix the issues you find, please add a git tag to a version with no fixes included.

# TestSpecsCypress

I have attached here a few test specs for automating the previously provided link. 
I have not previously used the Cypress Framework but I pulled this down to experiement with and get a feel for it 

Tests have been written using Arrange, act and assert methodology. 
Tests have been written as individual end to end tests that do not rely on previous set up or logic. 
I can make ammendments and the tests need tweaked e.g the waits would be better waiting on an element on the page instead of using explicit/implicit waits or for a period of time.
I have written 4 tests, that cover:

- clicking from the initial page
- accessing the interactove video ad
- pulling out the drawer of products
- asserting that all the products are in the list
- checking the pull out drawer is closed 
- checking products are not displayed 

I have only tested a sample of functionality here and can talk about this and why I have chosen to do certain things, I wasn't sure how much or how little to automate
Again, the selectors aren't perfect but they work for the purposes. 
A describe has been added at the top and then 'it' seperating out the different tests and they run as seperate tests on the Cypress runner. 

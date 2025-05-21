1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed. When the code is pushed, new changes made will be checked for 
correctness/validation so that no buggy code is merged into main, instead it is marked and then fixed.

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No. Not specifically. To test a specific function for correct output, one could use console.log() or other simple tests. 
E2E tests would be used for more general user interactions, this would involve the entire application workflow.

3) What is the difference between navigation and snapshot mode?

Naviation mode analyzes the page after it loads. Snapshot mode analyzes the page as it is in its current state. Navigation finds issues in overall performance while snapshot is for finding accessibility issues.

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

- Properly size images
- \<html> element should have a [lang] attribute
- Document should have a meta description
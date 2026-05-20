1) **Where would you fit your automated tests in your Recipe project development pipeline?** <br>
   I would fit them within a GitHub Action that runs whenever code is pushed. I think that this is the most effective approach because it ensures that tests are automatically executed every time new code is integrated. It also helps identify potential bugs or regressions immediately, ensuring the quality of the software is maintained throughout the development pipeline.

2) **Would you use an end-to-end test to check if a function is returning the correct output?** <br>
   No, because End-to-end testing is designed to emulate a user's workflow from start to finish, focusing on interactions with the webpage and the DOM. Testing individual functions for correct output is the purpose of unit testing, not E2E testing.

3) **What is the difference between navigation and snapshot mode?** <br>
   Navigation mode analyzes a page immediately after it loads, providing overall performance metrics but failing to analyze user interactions or DOM changes.  Snapshot mode analyzes the page in its current state, which is best for identifying accessibility issues, but it cannot analyze JavaScript performance or changes to the DOM tree.

4) **Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.** <br>
   * Improve Performance: Optimize image sizes or defer non-critical JavaScript to improve page load speed.
   * Enhance Accessibility: Ensure all images have descriptive alt tags and that the site has sufficient color contrast for text to meet accessibility standards.  
   * Best Practices: Ensure the site is served over HTTPS and address any deprecated APIs or browser console errors identified in the audit.

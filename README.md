# resilient-checkout-playwright-js

Assignment 5 1. The &quot;Resilient Checkout&quot; (E-Commerce Strategy)
Site: https://www.saucedemo.com/ Focus: Error Handling, State Management &amp; Negative
Paths
 The Scenario: Automate a &quot;Clean State&quot; checkout flow. Most testers just buy one
item. Your lead-level task is to:
1. Log in with the problem_user (which intentionally has broken UI logic).
2. Implement a Self-Healing Selector or a fallback mechanism that detects
when the &quot;Add to Cart&quot; button fails and logs a detailed report with a DOM
snapshot.
3. Validate the cart persistence: Log in, add items, close the browser, and
reopen to verify items are still there (Session/Cookie management).
 Lead Challenge: Implement a Global Tear-down that clears the cart and resets the
user state regardless of whether the test passed or failed, ensuring zero data
leakage between test runs.
Swag Labs
Sauce Labs Swag Labs app

# Notes-on-TDD

A little git repo to hold my goto if I need a refresher on TDD.

# Specification vs Verification.

Think **Specification** rather than **Verification***

***Specification:*** Defines what the feature should do.

## Example
When the user does not enter a quantity of the product, an error message is shown.

***Verification:*** Write the code to satisfy the specificaiton.

## Example
The user can enter the quantity of the product.

# Specification template

**Scenario:** When the user does not enter a quantity of the product, then click next

  **1. Expectation:** an error message is shown.

**Scenario:** When the user enters a valid quantity of a product, then click next

  **1.Expectation:** the user's payment page is shown.

## TDD for system specs

Start with high level, non-technical to separate the "what" from the "how"

### Example
1. Create a customer
2. Sign in
3. Visit the customer index page
4. Click on "Delete" on the customer row
5. Expect that the customer is no longer present on the page.

Paste it into the spec/test.

Replace the comments with code.

## Meaningful test
Target ends(result/output), instead of means


# Build an Invoice Generator according to the following template from Figma:
**Design Template for the exercise**
[Invoice Generator Figma Template](https://www.figma.com/file/roUn8DT7zHTI9tcL2JXNZG/Invoice-Generator?type=design&node-id=0-14&mode=design&t=cQEoUsHAZtwvAaqN-0)

- The Invoice Generator should resemble the design provided in Figma - choose either the light or dark design (you don't need to implement both).
- Clicking on a button (Wash Car, Mow Lawn, Pull Weeds) should add the corresponding product to the invoice, for example, onclick="addProduct(1)".
- When adding a product to the invoice, recalculate the total invoice amount.
- Each product can only be added to the invoice once.
- The "Remove" button should remove a product from the invoice.
- Recalculate the invoice total after each action.
- The "Send invoice" button does not need to have a function.

Hints:
- Make it easy to add and remove products. Store all products in an object.
- Provide only one function for adding addProduct(productId) and removing removeProduct(productId), not a separate function for each product.
- Dynamically create the product list on the invoice, rather than just toggling the visibility of products.


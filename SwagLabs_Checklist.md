# 🧪 Swag Labs QA Checklist

**Author:** Bogdan  
**Company:** SoftServe Academy (Practice)  
**Project:** Swag Labs – Demo e-commerce  
**Date:** 2025-08-16  

---

## ✅ Checklist Table

| Module  | Submodule          | Summary                                                                 | Expected Result                                                                                       | Status  |
|---------|--------------------|-------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|---------|
| Catalog | Filters | Check whether the 'A–Z' filtering works | Products are displayed in alphabetical order from A to Z | Failed |
| Catalog | Filters | Check whether the 'Z–A' filtering works | Products are displayed in alphabetical order from Z to A | Failed |
| Catalog | Filters | Check if the price filters from 'Low to High' are working | Products are displayed from the lowest to the highest | Failed |
| Catalog | Filters | Check if the price filters from 'High to Low' are working | Products are displayed from the highest to the lowest | Failed |
| Catalog | Search | Search is not applicable | N/A | N/A |
| Catalog | Product Catalog | Check if the product names are related to the cover | Each product name corresponds to the correct product image | Failed |
| Catalog | Product Catalog | Check if there are any mistakes in the product description | The product description is displayed correctly, without spelling, grammar, or formatting mistakes | Failed |
| Catalog | Product Catalog | Check the product navigation buttons—do they work, and what is displayed | Product navigation buttons are clickable and redirect the user to the correct pages | Failed |
| Catalog | Product Catalog | Check whether the price is displayed / whether it displays correctly after navigating to the product page | The product price is displayed on the Product Details Page and matches the price shown in the catalog | Failed |
| Catalog | Product Catalog | Check if the 'Add to cart' button works | When clicking the 'Add to Cart' button, the product is successfully added to the shopping cart | Passed |
| Catalog | Product Catalog | Check if the 'Remove' button works | When clicking the 'Remove' button, the product is successfully removed from the shopping cart | Passed |
| Cart | Add Product/Remove | Check whether adding and deleting a single product from the main screen works | When clicking 'Add to Cart' on the main screen (catalog), the product is added to the cart | Passed |
| Cart | Add Product/Remove | Check whether adding and deleting two products from the main screen works | After adding two products from the main screen (catalog), both products appear in the cart | Passed |
| Cart | Add Product/Remove | Check whether adding and deleting three products from the main screen works | All three products appear in the cart and all are deleted | Failed |
| Cart | Add Product/Remove | Check whether the selected item is added to the cart correctly | Clicking 'Add to Cart' on a specific item adds that exact item to the cart | Passed |
| Cart | Add Product/Remove | Check whether deleting items from the cart works correctly | Clicking 'Remove' deletes the selected item from the cart | Passed |
| Cart | Checkout | Check whether the checkout works with an empty cart | System should not create an empty order in the database | Failed |
| Cart | Checkout | Check whether it works with a product | User is able to proceed to checkout when there is at least one product in the cart | Failed |
| Cart | Checkout | Check the functionality of the personal information input field in the 'Your Information' section | All required fields (First Name, Last Name, Postal Code) accept valid input | Failed |

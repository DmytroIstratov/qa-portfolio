# Add product to cart without authentication

## Description
This test verifies that a guest (unauthenticated) user is able to add a product to the shopping cart.

## Preconditions
- User is not logged in ROZETKA
- Product is available and visible in catalog

## Steps to Reproduce
1. Open product listing page
2. Select a product
3. Click “Add to Cart” button
4. Navigate to cart page

## Expected Result
- Product is successfully added to cart
- Cart reflects the selected item even though user is not authenticated

## Notes
- Applicable for guest checkout flow
- Should fail if product requires authentication to purchase

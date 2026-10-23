# Tasty Foods API Testing

![API Testing](https://img.shields.io/badge/Testing-API%20Testing-blue)
![Tool](https://img.shields.io/badge/Tool-Postman-orange)
![Focus](https://img.shields.io/badge/Focus-Manual%20Testing-green)

## Project Overview

This project contains a Postman collection created to manually test the **Tasty Foods API**. The collection covers customer-facing endpoints and Admin Dashboard endpoints for authentication, food catalog browsing, search, checkout/orders, product management, newsletter subscriptions, wishlist, and cart operations.

**Base URL:** `http://localhost:5000`

> **Note:** The API must be running locally on port `5000` for these requests to work. Update the base URL if your local setup uses a different host or port.

## Tools & Technologies

- **Postman** — sending API requests and inspecting responses
- **REST API** — exercising HTTP endpoints
- **JSON** — request payloads and response data
- **JWT authentication** — for endpoints that require an authenticated user or admin session

## API Coverage

The collection contains **27 requests**, organized into these areas:

| Area | Requests | Coverage |
|---|---:|---|
| Authentication | 5 | Admin/customer registration, login, and authenticated profile |
| Customer — Food & Catalog | 5 | Categories, promotional banners, products, single-product details, and search |
| Customer — Checkout & Orders | 2 | Place an order and retrieve order status |
| Admin Dashboard | 6 | Overview stats, order status update, order deletion, and product create/update/delete |
| Newsletter | 1 | Newsletter API endpoint |
| Wishlist | 3 | Retrieve wishlist items, add an item, and remove an item |
| Cart | 5 | Retrieve cart, add/update/remove an item, and clear the cart |
| **Total** | **27** | |

## Testing Activities

- Sent API requests through Postman.
- Checked endpoint behavior and inspected returned responses.
- Covered both customer-facing functionality and administrative operations.
- Exercised request payloads, route parameters, and authentication where applicable.

## How to Run the Collection

1. Start the Tasty Foods backend locally and confirm that it is listening on port `5000`.
2. Open Postman.
3. Import `Tasty-Foods-API.postman_collection.json`.
4. Review the request URLs and sample payloads.
5. Sign in using valid local test accounts and provide the required authentication token for protected endpoints.
6. Run requests individually, or run a folder after confirming its setup and dependencies.
7. Inspect the HTTP status code and response body for each request.

## Configuration Notes

- The collection uses `http://localhost:5000` as its base URL.
- Some requests depend on valid product IDs, order IDs, or a logged-in session. Replace sample IDs with IDs that exist in your local test database.
- For protected endpoints, use a valid token from your local test environment.
- Sample credentials and data should be treated as placeholders and adjusted to match your local test setup.
- Do not commit real passwords, access tokens, personal customer data, or production secrets to a public repository.

## Testing Summary

The collection was used to exercise the API endpoints listed above. This README does not state a numerical pass/fail total because a consolidated execution report has not been included with the collection.

## Project Outcome

This project demonstrates practical experience with manual API testing in Postman, including endpoint coverage across authentication, catalog, order, admin, newsletter, wishlist, and cart functionality.

---

**Author:** Muhammad Faizan  
**GitHub:** [Faizan-Fr-Dev](https://github.com/Faizan-Fr-Dev)

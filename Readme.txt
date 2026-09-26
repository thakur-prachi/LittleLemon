Little Lemon Restaurant API - Endpoints for Testing

Menu API:
GET    /restaurant/menu/           - List all menu items
POST   /restaurant/menu/           - Create a new menu item
GET    /restaurant/menu/<id>/      - Retrieve a single menu item
PUT    /restaurant/menu/<id>/      - Update a menu item
DELETE /restaurant/menu/<id>/      - Delete a menu item

Booking API (requires authentication token):
GET    /restaurant/booking/tables/       - List all bookings
POST   /restaurant/booking/tables/       - Create a new booking
GET    /restaurant/booking/tables/<id>/  - Retrieve a single booking
PUT    /restaurant/booking/tables/<id>/  - Update a booking
DELETE /restaurant/booking/tables/<id>/  - Delete a booking

User Registration and Authentication (Djoser):
POST   /auth/users/               - Register a new user
POST   /auth/token/login/         - Login and obtain auth token
POST   /auth/token/logout/        - Logout (invalidate token)
POST   /api-token-auth/           - Obtain auth token (alternative endpoint)

Note: The Booking API requires a valid token in the Authorization header:
Authorization: Token a83a08578cf7428bcdf0fc381f1f673711de1872

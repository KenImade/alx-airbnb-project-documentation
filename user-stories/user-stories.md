# 🏡 Airbnb Clone — User Stories

## 🧍‍♂️ User Story 1: User Registration and Authentication

**As a** new user (guest or host), **I want to** register and log in using my email or social media accounts, **so that** I can securely access the platform and manage my bookings or listings.

### Acceptance Criteria

* Users can sign up using email and password.
* OAuth login options (Google, Facebook) are available.
* Passwords are securely hashed.
* Upon successful login, a JWT token is generated for session management.

---

## 🏠 User Story 2: Property Listing Management (Host)

**As a** host, **I want to** add, edit, or delete my property listings, **so that** guests can view and book available properties on the platform.

### Acceptance Criteria

* Hosts can create new listings with title, description, price, location, and amenities.
* Hosts can update or remove their listings.
* Property images can be uploaded to file storage (e.g., AWS S3 or Cloudinary).
* Only hosts can manage their own listings.

---

## 🔍 User Story 3: Search and Filtering

**As a** guest, **I want to** search for properties using filters like location, price, and amenities, **so that** I can quickly find listings that match my preferences and budget.

### Acceptance Criteria

* Guests can search by location, price range, number of guests, and amenities.
* Results are paginated for better performance.
* Search queries return only active and available listings.

---

## 📅 User Story 4: Booking and Payment

**As a** guest, **I want to** book a property and pay securely online, **so that** I can confirm my stay and avoid double bookings.

### Acceptance Criteria

* Guests can select available dates and confirm a booking.
* System validates availability to prevent double bookings.
* Payments are processed securely via Stripe or PayPal.
* Hosts receive automatic payouts after the booking is completed.

---

## ⭐ User Story 5: Reviews and Ratings

**As a** guest, **I want to** leave a review and rating for a property after my stay, **so that** I can share my experience and help other guests make informed decisions.

### Acceptance Criteria

* Guests can only leave reviews for completed bookings.
* Hosts can respond to guest reviews.
* Reviews are linked to specific bookings to prevent fake feedback.
* Reviews appear on property detail pages.

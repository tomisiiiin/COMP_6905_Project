# Student Peer to Peer Marketplace

# Features

## Authentication & Login
- Role based Authorization (Admin, User)
- Signup
	- Required Attributes: [Profile Image, Full Name, Email, Password, Confirm Password]
- Login
	- Required Attributes: [Email, Password]
- Password Hashing
- Forgot Password
- Update Profile
	- Editable Attributes: [Profile Image, Full Name, Password]
- User Rating & Review

## Product Management
- **[Admin]** Product CRUD Operation
- **[User]** Add to Cart
- **[User]** Product Purchase
- **[User]** Private Product Listing
- **[User]** Product Status Management (Active / Inactive)
- **[User]** Product Auction/Bid Management
    - Set Initial Bid
    - Set Timer 
    - If Highest Bidder doesn't Purchase
        - Ban From Bidding Again.
        - Pay a Fine to Retain Bidding Privilages.

## Lost & Found Item Management
- **[User]** Lost Item CRUD Operation
- **[User]** Post Anonymously 
- **[User]** Claim Lost Item (Multiple Users Can Claim)
- **[User]** Private Chat for Varification.

## Delivery System
- Delivery Based on Product Type & Shipping Speed
	- **Online:** Gift Cards, Vouchers, etc.
	- **Physical:** Furnitures, Tech items, etc.
		- Same-Day Delivery
		- Next-Day Delivery
		- Standard Delivery
- Delivery Tracking: 4 Phases
    - Processing
    - Picked Up
    - In Transit
    - Delivered
- Delivery Cost Based on Location & Delivery Type.


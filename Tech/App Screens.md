## Splash Screen
- would be visible until the app load in completed, and would be visible for each cold start
---
## Onboarding Flow
#### Disclaimer - This is a user blocking flow
- Authentication screens
	- Social Auth - Google and Apple
		- Get user's phone number (could be skipped while onboarding)
	- Phone / Email Auth
		- Get user's name and phone number (could be skipped while onboarding)
	- Log-in / Sign-up
- Location (use mapbox [free])
	- Map Screen to pin the location of the user
	- Save address screen (could be skipped during onboarding)

---

## Home Page
- Should have user location at the top 
	- if that area is not serviceable then have a error state showing that we are currently not operational in that area and are expanding to that area very soon
- List of all items with cards showing the image, MRP, truncated description of the item 
	- have different iterations and sizes of cards, we can pick which we like and use them accordingly
	- clicking on the card should redirect to the item details page
	- clicking on + should directly add to card and then change state to a counter like this ![[add-cart-state.png]]
- Filters
	- Modal / Overlay
		- veg/non-veg
		- sorting
- should have view card CTA at the bottom floating
---

## Items Page
- contains 
	- image
	- name
	- description
	- macros
- CTA that opens a customisable drop down for add-ons etc (can remove for pilot)
- have a CTA at the bottom to add to cart 
---

## Cart Screen
- should have all the items added to card with quantity
- coupon handling
- show delivery time (will have to handle the math of this in the app) 
- show bill breakdown
- fixed CTA at the bottom to pay if user has already saved the address other to add pending user details
---

## Payments Screen
- Have COD working as of now and other to be shown under WIP 🚧
---
## Tracking Screen
- style similar to zepto
- have different states or copies for 
	- PENDING = 'pending',
	- DELIVERED = 'delivered',
	- DISPATCHED = 'dispatched',
	- PREPARING = 'preparing',
- have option to cancel order here [lets discuss this once]
--- 

## Settings page
---

## User Details
- should have saved address
- order history
- user profile details
- logout
- delete acc. - should take 3 steps to reach here. make it difficult for the user to delete the acc
--- 
## How to prepare 
### should be under a different bottom tab or only accessible via PN or after completing order for couple of hours
- list of ingredients
- steps to cook
- audio for the same (not for pilot)
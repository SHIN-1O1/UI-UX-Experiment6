## UI – UX
## EXPERIMENT 6

# Aim:
To practice solution ideation, user story creation, scenario development, flow mapping, and information architecture design to improve user experience through structured UX design activities.

# Output:
 
 <img width="975" height="642" alt="image" src="https://github.com/user-attachments/assets/ae8a251c-4f5e-4419-891e-d14588614d30" />
  
<img width="975" height="975" alt="image" src="https://github.com/user-attachments/assets/1c4991fa-4424-49d4-a571-5f5c999e0605" />

1.	Solution Ideation: Crazy 8s
The Crazy 8s exercise is a fast-paced ideation method where you sketch eight different ideas in eight minutes (one minute per idea).
•	Known UX Problem: "I'm indecisive and get overwhelmed by too many restaurant choices. I often spend 15 minutes scrolling before just giving up or ordering the same old thing." (Choice Paralysis)
Here are 8 low-fidelity ideas from a Crazy 8s session to solve this:
1.	"Surprise Me" Button: A single button on the homepage. The user sets a budget (e.g., "under $20") and a single cuisine type (e.g., "Mexican"), and the app orders a highly-rated, popular dish for them.
2.	"Top 3 for You" Modal: When the app opens, a pop-up shows just three personalized recommendations based on past orders, time of day, and location. The user can pick one or close the modal to browse normally.
3.	Visual "Tinder" Swipe: A full-screen, "swipe left to reject, swipe right to save" interface for dishes (not restaurants). The user can swipe through 10-15 dishes and then order from their "saved" list.
4.	"Quick-Order" Menu: A persistent menu bar at the bottom with three icons: "Re-order Last," "Your Favorite," and "Trending Nearby."
5.	Time-Limit Filter: A filter that only shows restaurants that can deliver in "Under 20 minutes." This drastically cuts down the list for users in a hurry.
6.	"What's Your Mood?" Helper: A simple, non-intrusive prompt: "What are you in the mood for?" with 3-4 emoji-based buttons (e.g.,  Spicy, Healthy, Comfort Food) to instantly filter the homepage.
7.	"Friend's Favorites" Row: A social feature. A new carousel on the homepage shows "What your friends are ordering," helping the user anchor their choice on a trusted recommendation.
8.	"Order Roulette": The user "spins a wheel" that lands on a random cuisine type. The app then only shows restaurants from that category. This gamifies the indecision and makes it fun.
________________________________________
2. Creating User Stories
User stories help the team understand a feature from the user's perspective. I'll create a quick persona to guide them.
•	Persona: "Priya, the Health-Conscious Planner." Priya is a 28-year-old graphic designer who uses the app for her weekday lunches. She's vegan, tracks her budget, and likes to plan her meals in advance.
Here are 5 user stories for Priya:
1.	As a health-conscious user (Priya), I want to permanently filter my view to only show vegan-friendly restaurants, so that I don't have to waste time checking the menu for every option.
2.	As a planner (Priya), I want to schedule an order for delivery at 12:30 PM tomorrow, so that my lunch arrives right when my meeting ends.
3.	As a budget-conscious user (Priya), I want to see the total price (including fees, tip, and tax) for an item before I add it to my cart, so that I can avoid "sticker shock" at checkout.
4.	As a specific eater (Priya), I want to add a "common special instruction" (e.g., "no plastic cutlery, please") to my profile, so that it gets automatically applied to every order.
5.	As a health-conscious user (Priya), I want to be able to see nutritional information (like calories and protein) for menu items, so that I can make an informed choice that fits my diet.
________________________________________
3. Creating a Scenario
A scenario adds context and a narrative to a user story, helping designers and stakeholders build empathy.
•	Selected User Story: "As a planner (Priya), I want to schedule an order for delivery at 12:30 PM tomorrow, so that my lunch arrives right when my meeting ends."
Scenario: Priya's Lunch Crunch
It's 8:30 PM on a Tuesday, and Priya is winding down on her couch, checking her work calendar for the next day. She sees she has back-to-back meetings from 10:00 AM until 12:30 PM. "Ugh," she thinks, "I'll be starving by 12:30 and won't have any time to stop and order food. I'll probably just end up eating a snack bar."
She feels a little anxious, knowing a busy morning without a real lunch will make her afternoon unproductive. She opens her food delivery app. She scrolls to her favorite vegan-friendly café, "The Green Leaf," and finds the quinoa bowl she likes.
Instead of hitting "Order Now," she taps the "Schedule" option. A calendar and time-picker appear. She selects tomorrow's date and sets the delivery time for 12:30 PM. She confirms her order and pays.
Priya closes the app and goes back to her evening, feeling a wave of relief. She's "future-me" proofed her day. She knows that just as her last meeting is ending, her healthy, pre-paid lunch will be arriving, and she can just relax and eat without any more stress or decision-making.
________________________________________
4. Flow Diagram / Task Flow
This diagram maps the specific steps a user takes to complete a single task. This is the "happy path" (no errors) for a new user ordering food.
 
Getty Images
Here is the flow described in text:
1.	(Terminator) Start: User opens the app.
2.	(Process) Home Screen: User is shown restaurant listings.
3.	(Process) Select Restaurant: User taps on a restaurant card.
4.	(Process) Menu Screen: User browses the menu items.
5.	(Process) Select Item: User taps "Add" on a dish.
6.	(Decision) Customize?
o	Yes: (Process) User selects options (e.g., "extra spicy") -> (Process) Taps "Add to Cart."
o	No: (Process) Item is added directly to the cart.
7.	(Process) View Cart: User taps the "Cart" icon.
8.	(Process) Checkout Screen: User reviews items, price, address, and payment.
9.	(Process) Place Order: User taps the final "Confirm Order" button.
10.	(Process) Confirmation Screen: A "Thank you, your order is being prepared" message is shown.
11.	(Terminator) End: Flow is complete.
________________________________________
5. Information Architecture (IA)
IA is the practice of organizing and labeling content in a way that is understandable to users.
•	Method: Open Card Sorting. We'd give users virtual "cards" with app features (e.g., "Track Order," "Your Profile," "Pizza," "Offers," "FAQ"). We ask them to group these cards in a way that makes sense to them and then name those groups.
•	Goal: To create a Site Map (a high-level hierarchy of the app's navigation).
Simulated Card Sort Results & Site Map
Based on a typical card sort for a food app, users would likely create these main categories, which we can then turn into our primary navigation:
Main Navigation (Bottom Tab Bar):
•	Home: The main browsing and discovery page.
•	Search/Browse: A dedicated screen for finding specific cuisines or restaurants.
•	Orders: All information about current and past orders.
•	Account: All personal information, settings, and support.
Here is a simple Site Map based on those findings:
•	1.0 Home
o	1.1 Banners / Promotions
o	1.2 Cuisines Carousel (e.g., Pizza, Sushi, Indian)
o	1.3 Recommended For You
o	1.4 All Restaurants List
•	2.0 Search
o	2.1 Search Bar
o	2.2 Filter & Sort Options
o	2.3 Browse by Category (e.g., Vegan, Healthy, Top Rated)
•	3.0 Orders
o	3.1 Active Orders
	3.1.1 Track Order Map
	3.1.2 Contact Driver/Support
o	3.2 Past Orders
	3.2.1 Re-order Button
	3.2.2 Leave a Review
	3.2.3 View Receipt
•	4.0 Account
o	4.1 Your Profile (Name, Email, Phone)
o	4.2 Payment Methods
o	4.3 Saved Addresses
o	4.4 Your Favorites
o	4.5 Vouchers & Offers
o	4.6 Help Center
	4.6.1 FAQ
	4.6.2 Contact Support
o	4.7 Settings (Notifications, etc.)
o	4.8 Log Out


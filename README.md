# Habit-Tracker-v1
Final project 4Geeks

Plane.so
https://sites.plane.so/issues/4b5f547bdd104fe78937f54decca2b38


I have identified 3 main users: 

1. **Basic User:** Someone using the free version of the app with basic features.
2. **Premium User:** A user who has subscribed to the premium features.
3. **Admin User:** The administrator who manages the app and its content.


## Level 1: MVP (Minimum Viable Product)

**Objective:** Deliver a functional habit tracker that meets the basic requirements and provides core functionalities.

General Structure: 
	4 levels. 
		1 is free
		2-4 are paid
	You can add up to 10 habits per level. 
	Each level represents 1 tree
	Each habit grows the tree. 
		*# how much design I will do here in the MVP is questionable*
	Looking back over 1 month, you should see multiple trees of varying sizes. 
	30 days of perfect performance will make level 2 available. 

### Features:

1. **User Registration & Authentication:**
    
    - User can register with email and password.
    - User can log in with their credentials.
    - Basic password reset functionality.
2. **Dashboard:**
    
    - User can view a list of their current habits.
    - User can mark habits as completed for the day.
    - Basic progress visualization (e.g., simple progress bars).
3. **Habit Management:**
    
    - User can add new habits.
    - User can edit existing habits.
    - User can delete habits.
4. **Basic Levels:**
    
    - User starts at Level 1 with 5 basic habits.
    - User can progress to higher levels by completing habits (manually set levels for simplicity).
5. **Backend:**
    
    - RESTful API with endpoints for user authentication and habit management.
    - Basic database schema for users, habits, and progress tracking.
6. **Deployment:**
	- ? 
7. Onboarding process! 
	- We need an ob process
	- Ask what habits do you want to gain or improve
	- color code each habit according to category
	- Give guidance on what types of habits are good? 
		- can be completed in less than 15 min
		- Are important for your "foundation"
		- can be defined whether they were completed or not! 
		- if there are more than 10 habits listed, then ask for a ranking

### Success Metrics:

- User registration and login functionality working.
- Users can add, edit, and delete habits.
- Basic level progression implemented.
	- ticking off habits
- Deployed and accessible by users.
- Dashbaord to see graph and scores

## Level 2: Add Flair and Design

**Objective:** Enhance the MVP with better design, improved user experience, and additional features.

### Additional Features:

1. **Enhanced UI/UX:**
    
    - Improved dashboard design with better styling (Bootstrap/Tailwind CSS).
    - More intuitive user interface for habit management.
    - Basic animations and transitions for better user experience.
2. **Advanced Progress Visualization:**
    
    - Implement progress graphs (e.g., Chart.js) to visualize daily, weekly, and monthly progress.
3. **Gamification Elements:**
    
    - Introduce tree growth visualization for each habit completed.
    - More detailed level progression with visual feedback.
4. **Friends & Comparison:**
    
    - User can invite friends.
    - User can compare their progress with friends (basic comparison).
5. **Profile Management:**
    
    - User can view and edit their profile information.
    - User can change their password.
6. **Backend Enhancements:**
    
    - Improved API endpoints with better error handling and validation.
    - Enhanced database schema to support additional features.

### Success Metrics:

- Improved user interface and experience.
- Advanced progress visualization implemented.
- Gamification elements added to increase engagement.
- Basic social features (friends and comparison) implemented.
- Enhanced API performance and stability.

## Level 3: Full Featured Product

**Objective:** Deliver a fully featured product with comprehensive functionality, polished design, and robust performance.

### Full Features:

1. **Complete UI/UX Overhaul:**
    
    - Fully polished design with custom styles and advanced animations.
    - Mobile responsiveness and accessibility improvements.
    - User onboarding experience with tutorials and tips.
2. **Full Gamification:**
    
    - Advanced tree growth visualization with different stages.
    - Achievement badges and rewards for completing habits and levels.
    - Customizable habit categories and themes.
3. **Advanced Social Features:**
    
    - Detailed friend comparison and leaderboards.
    - Community challenges and group habits.
    - Social sharing options for achievements.
4. **Subscription Model:**
    
    - Implement subscription plans for accessing higher levels and premium features.
    - Secure payment processing (e.g., Stripe integration).
5. **Advanced Profile Management:**
    
    - Detailed user profiles with statistics and habit insights.
    - Customizable privacy settings.
    - Notifications and reminders for habits.
6. **Comprehensive Backend:**
    
    - Scalable API with microservices architecture.
    - Real-time data synchronization (e.g., using WebSockets).
    - Advanced analytics and reporting tools.

### Success Metrics:

- Fully polished and responsive design.
- Comprehensive gamification and social features.
- Secure and reliable subscription model.
- Advanced user profile and notification system.
- Scalable and robust backend architecture.
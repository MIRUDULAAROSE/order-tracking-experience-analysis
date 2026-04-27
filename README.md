# order-tracking-experience-analysis
Improving order tracking experience using Business Analysis and data-driven insights

1. Problem Statement
Users are not receiving clear and timely updates after placing an order.  
Lack of transparency in delivery status leads to poor user experience, increased anxiety, and higher customer support queries.

2. Objective
- Improve order tracking transparency  
- Enhance user experience  
- Reduce customer support queries  
- Increase customer satisfaction  

3. Business Requirements (BRD)
- Provide clear and timely delivery updates  
- Improve transparency in order tracking  
- Enable smooth communication between users and delivery partners  
- Reduce order-related customer complaints  

4. Functional Requirements (FRD)
- System should display real-time order status (confirmed, preparing, dispatched, out for delivery)  
- System should send notifications for each order update  
- System should display delivery partner details (name & contact)  
- System should allow users to track delivery partner location on map  

5. Non-Functional Requirements (NRD)
- Page load time should be less than 2 seconds  
- System should provide real-time and accurate updates  
- Application should have high availability (99%)  
- User data should be secure  

6. Agile Approach
  Epic
  Improve Order Tracking Experience

  User Stories
- As a user, I want to see real-time order status so that I know when my food will arrive  
- As a user, I want to receive notifications so that I stay updated  
- As a user, I want to view delivery partner details so that I can contact them  
- As a user, I want to track my order on a map so that I can estimate delivery time  

  Acceptance Criteria
- Order status updates in real-time  
- Notifications are sent without delay  
- Delivery partner details are visible and functional  
- Map tracking is accurate and loads within 2 seconds  

Sprint Plan
- Sprint Goal: Improve order tracking visibility  

Sprint Backlog:
- Real-time order status  
- Notifications system  
- Delivery partner details  

7. Flow Diagram:
   
 A[User Places Order] --> B[Order Confirmed] 
 B --> C[Order Preparing] C --> D[Order Dispatched] 
 D --> E[Out for Delivery] E --> F[Show Delivery Partner Details] 
 F --> G[Live Location Tracking] 
 G --> H{Any Delay?} 
 H -- Yes --> I[Send Delay Notification] 
 H -- No --> J[Continue Tracking] 
 J --> K[Order Delivered] 
 I --> K 
 K --> L[User Receives Confirmation] 

8. Expected Outcomes
- Reduced customer support queries  
- Improved user satisfaction  
- Increased order completion rate  
- Better trust in the platform  

9. Tools & Skills Used
- Business Analysis  
- Requirement Gathering  
- Agile (User Stories & Acceptance Criteria)  
- Data Analysis (User Behavior & Feedback)

10. Core Metrics for your project:
 - Order Tracking Visibility Rate (% of users who viewed tracking after placing order)
 -  Notification Delivery Rate (% of notifications successfully delivered)
 - Average Tracking Load Time (Time taken to load tracking screen)
 - Customer Support Queries (Number of “Where is my order?” complaints)
 - Order Completion Rate(% of orders successfully delivered without cancellation)

11. Metrics                                                      
- Tracking Visibility-(Before-40%)(After-75%)                               
- Load Time-(Before-5sec)(After-1.8sec)
- Support Queries-(Before-High)(After-Reduced by 30%)
- Order Completion(Before-65%)(After-85%)

12. Dashboard
A dashboard can be built using this dataset to track:
- Order tracking visibility
- Delivery performance
- App performance metrics
- Customer support trends

Project Type:
Business Analysis Case Study (Portfolio Project)

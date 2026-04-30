# order-tracking-experience-analysis
Improving order tracking experience using Business Analysis and data-driven insights

# Project Overview:
This project focuses on improving the order tracking experience in a food delivery app by identifying performance issues and enhancing real-time visibility using Business Analysis and data-driven insights

# 1. Problem Statement
Users are not receiving clear and timely updates after placing an order.  
Lack of transparency in delivery status leads to poor user experience, increased anxiety, and higher customer support queries.

# 2. Objective
- Improve order tracking transparency  
- Enhance user experience  
- Reduce customer support queries  
- Increase customer satisfaction

# 3. Analysis
- Delivery time vs estimated time
- Status updates (on time / delayed / no update)
- Customer ratings or feedback
- Order stages (confirmed → preparing → out for delivery → delivered)

# 4. Root cause Analysis:
- Inaccurate delivery time estimation
- Delays in updating order status
- Poor communication between system and delivery partners
- Lack of real-time GPS tracking

# 5. Tools & Skills Used
- Business Analysis  
- Requirement Gathering
- Agile (User Stories & Acceptance Criteria)  
- Data Analysis through Excel (User Behavior & Feedback)
- Power BI (Data Visualization)
- DAX

# 6. Business Requirements (BRD)
- Provide clear and timely delivery updates  
- Improve transparency in order tracking  
- Enable smooth communication between users and delivery partners  
- Reduce order-related customer complaints  

# 7. Functional Requirements (FRD)

- System should display real-time order status (confirmed, preparing, dispatched, out for delivery)  
- System should send notifications for each order update  
- System should display delivery partner details (name & contact)  
- System should allow users to track delivery partner location on map  

# 8. Non-Functional Requirements (NRD)

- Page load time should be less than 2 seconds  
- System should provide real-time and accurate updates  
- Application should have high availability (99%)  
- User data should be secure  

# 9. Agile Approach
 
# Epic
  Improve Order Tracking Experience

# User Stories
- As a user, I want to see real-time order status so that I know when my food will arrive  
- As a user, I want to receive notifications so that I stay updated  
- As a user, I want to view delivery partner details so that I can contact them  
- As a user, I want real-time tracking updates to know when my order will arrive

# Acceptance Criteria
- Order status updates in real-time  
- Notifications are sent without delay  
- Delivery partner details are visible and functional  
- Live location tracking enabled and loads within 2 seconds
- Location status update at each stage
- Accurate ETA displayed

# Sprint Plan
- Sprint Goal: Improve order tracking visibility  

# Sprint Backlog:
- Real-time order status  
- Notifications system  
- Delivery partner details  

# 10. Flow Diagram:
   
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

# 11. Expected Outcomes
- Reduced customer support queries  
- Improved user satisfaction  
- Increased order completion rate  
- Better trust in the platform  


# 12. Core Metrics for the project:
 - Order Tracking Visibility Rate (% of users who viewed tracking after placing order)
 - Notification Delivery Rate (% of notifications successfully delivered)
 - Average Tracking Load Time (Time taken to load tracking screen)
 - Customer Support Queries (Number of “Where is my order?” complaints)
 - Order Completion Rate(% of orders successfully delivered without cancellation)

# 13. Metrics                                                      
- Tracking Visibility-(Before-40%)(After-75%)                               
- Load Time-(Before-5sec)(After-1.8sec)
- Support Queries-(Before-High)(After-Reduced by 30%)
- Order Completion(Before-65%)(After-85%)

# 14. Key Insights
- High load time (>2 sec) is directly linked to delayed deliveries  
- Orders with delayed notifications have higher support queries  
- Improving real-time tracking can reduce customer complaints significantly  
- Faster performance leads to higher order completion rate

  
# 15. Business Impact
- Reduced customer uncertainty during delivery  
- Improved transparency in order tracking  
- Potential reduction in support queries  
- Enhanced user satisfaction and trust


# 16. Dashboard
A dashboard can be built using this dataset to track:
- Order tracking visibility
- Delivery performance
- App performance metrics
- Customer support trends

# 17. Key Highlights from Dashboard
- High load time (>2 sec) impacts delivery experience  
- Delayed deliveries lead to increased support queries  
- Real-time tracking improves customer trust and reduces complaints

# 18. Expected Impact
- Reduce support queries by 20–30%  
- Improve delivery transparency  
- Increase user satisfaction

# 19. Business Recommendations
- Implement real-time GPS tracking
- Improve ETA prediction algorithms
- Increase frequency of status updates
- Notify users proactively about delays

# Project Type:
Business Analysis Case Study (Portfolio Project)

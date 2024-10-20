
### Final Project: **Fitness Tracker App**

----------

### **Task 1: Project Setup & Basic Components (100 Points)**

**Task:**

-   Set up the React project using `create-react-app` or a custom setup.
-   Create the following components:
    -   **Header** (displays app title and navigation links: "Home," "Track Workout," "Dashboard").
    -   **Workout List** (displays a list of logged workouts).
    -   **Workout Item** (displays details of an individual workout: type, duration, calories burned, etc.).

**Evaluation Criteria:**

-   Project is set up correctly and runs without errors (10 points).
-   Header component displays the app title and is styled (10 points).
-   Workout List component correctly renders an array of workouts (25 points).
-   Workout Item component displays individual workout details (25 points).
-   Basic CSS styling applied (30 points).

----------

### **Task 2: Add New Workout Form (100 Points)**

**Task:**

-   Implement a form where users can add new workouts.
-   The form should include fields like workout type, duration, and calories burned.
-   Ensure the form data is saved in the state and updates the workout list when submitted.

**Evaluation Criteria:**

-   The form is rendered correctly with appropriate input fields (25 points).
-   Users can add new workouts, and the workout list updates (35 points).
-   Input validation is applied (e.g., duration must be a positive number) (20 points).
-   Form is styled and user-friendly (20 points).

----------

### **Task 3: User Authentication (100 Points)**

**Task:**

-   Implement a simple user authentication system (using Firebase, Auth0, or a mock backend).
-   Users should be able to sign up, log in, and log out.
-   Certain features (like adding workouts or accessing the dashboard) should only be available when logged in.

**Evaluation Criteria:**

-   Users can sign up and log in (40 points).
-   Authenticated users can add workouts and access the dashboard (30 points).
-   Users can log out successfully (10 points).
-   Authentication status is managed correctly throughout the app (20 points).

----------

### **Task 4: Dashboard with Workout Stats (100 Points)**

**Task:**

-   Create a dashboard that displays a summary of the user's workout history.
-   Include metrics such as total workouts, total calories burned, and average workout duration.
-   Optionally, add a chart or graph (e.g., using Chart.js) to visualize workout trends over time.

**Evaluation Criteria:**

-   Dashboard displays accurate workout stats (40 points).
-   Total workouts, calories burned, and average duration are calculated correctly (25 points).
-   Chart or graph to visualize workout trends is implemented (20 points).
-   The dashboard is well-styled and responsive (15 points).

----------

### **Task 5: Advanced Features (100 Points)**

**Task:**

-   Implement one or more advanced features:
    -   **Workout Categories**: Allow users to filter workouts by type (e.g., cardio, strength).
    -   **Workout Goals**: Users can set goals (e.g., burn 500 calories/week) and track progress.
    -   **Social Sharing**: Allow users to share their workout achievements on social media.

**Evaluation Criteria:**

-   Workout categories and filters work correctly (25 points).
-   Goals can be set and tracked (35 points).
-   Social sharing feature works (optional but can earn bonus points) (20 points).
-   Advanced features are well-integrated and don’t break other functionality (20 points).

----------

### **Task 6: Polishing and Deployment (100 Points)**

**Task:**

-   Polish the app with responsive design, accessibility improvements, and smooth navigation.
-   Deploy the app using a platform like Vercel or Netlify.
-   Ensure the app works smoothly across different devices and browsers.

**Evaluation Criteria:**

-   App is fully responsive (30 points).
-   Accessibility features like keyboard navigation and ARIA labels are implemented (20 points).
-   App is deployed successfully and accessible via a public URL (30 points).
-   The app works without issues across multiple browsers (20 points)
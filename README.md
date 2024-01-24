### Coding Task: Feedback Management System

#### Objective:
Develop a simple feedback management platform where users can view a list of feedback posts, add new feedback, edit feedback details, and delete feedback. Each feedback post can have comments associated with it, which users can view and add.

#### Requirements:

**1. Backend (Rails API):**
   - **Models:**
     - `Feedback`: title, description, user_id, status (e.g., open, resolved, pending)
     - `Comment`: content, belongs to feedback, user_id
   - **Controllers:**
     - Feedback: Implement CRUD operations for feedback posts.
     - Comments: Implement CRUD operations for comments associated with feedback.
   - **Routes:**
     - RESTful routes for feedback and their comments.

**2. Frontend (React/Next.js):**
   - **Pages:**
     - Feedback List: Display all feedback with options to add, edit, or delete.
     - Feedback Detail: Show details of selected feedback and its comments.
     - Add/Edit Feedback: Form to add or edit feedback information.
   - **Features:**
     - Consume Rails API for all CRUD operations.
     - Proper state management and component structuring.
   - **Styling:**
     - Use a CSS framework or styled-components for styling.

**3. Testing:**
   - **Backend (RSpec):**
     - Write tests for model validations and associations.
     - Write tests for API endpoints ensuring proper responses.
   - **Frontend:**
     - **Jest:** Write unit tests for React components.
     - **Cypress:** Write end-to-end tests covering user flows.

**4. Bonus (CI/CD):**
   - Set up a Continuous Integration/Continuous Deployment pipeline.
   - Include steps for running tests, and automating deployment to a hosting platform of your choice.

#### Deliverables:

1. A GitHub repository containing the Rails API and React/Next.js code.
2. A README file documenting:
   - Setup instructions.
   - How to run the application and tests.
   - Any assumptions or decisions made during development.
3. A live demo would be advantageous but is not mandatory.

#### Evaluation Criteria:

1. **Code Quality:** Clean, readable, and well-structured code.
2. **Functionality:** All requirements are correctly implemented.
3. **Error Handling:** Proper handling of edge cases and errors.
4. **Testing:** Comprehensive and meaningful tests.
5. **Documentation:** Clear and thorough documentation.
6. **Bonus:** Implementation of CI/CD pipeline.

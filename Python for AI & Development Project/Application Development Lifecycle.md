# Application Development Lifecycle (ADLC)

## The ADLC is a structured process with seven phases:

1.  ### **Requirement Gathering:**
    *   **Goal:** Collect comprehensive requirements for the application.
    *   **Types of Requirements:**
        *   **User Requirements:** What users need the application to do (user stories, use cases).
        *   **Business Requirements:** How the application supports business goals (e.g., increase sales, improve efficiency).
        *   **Technical Requirements:** Specifications for the technology stack, infrastructure, security, performance, etc.
        *   **Constraints:** Limitations or restrictions (budget, time, technology, regulations).

2.  ### **Analysis:**
    *   **Goal:** Analyze and refine the gathered requirements.
    *   **Activities:**
        *   **Verify:** Ensure requirements are complete, consistent, and unambiguous.
        *   **Revise:** Update requirements based on analysis and feedback. Identify and resolve conflicts.

3.  ### **Design:**
    *   **Goal:** Create a detailed plan for the application's architecture and implementation.
    *   **Activities:**
        *   **Define Architecture:** Determine the overall structure (e.g., client-server, microservices).
        *   **Choose Technologies:** Select specific programming languages, frameworks, databases, etc.
        *   **Design Components:** Define modules, classes, functions, data structures, and their interactions.
        *   **Create Design Documents:** Document the design (e.g., UML diagrams, flowcharts, technical specifications).
        *   **Verify and revise** the design, iterating as necessary.

4.  ### **Code and Test:**
    *   **Goal:** Write the code and perform initial testing.
    *   **Activities:**
        *   **Develop Code:** Implement the design, following coding standards and best practices.
        *   **Unit Testing:** Test individual components (functions, classes) in isolation to ensure they work as expected.  *This is a key focus of Module 1.*
        *   **Code Review:** Have other developers review the code for quality, correctness, and maintainability.
        *   **Revise:** Fix bugs and refactor code based on testing and review.

5.  ### **User and System Testing:**
    *   **Goal:** Validate the application as a whole and ensure it meets requirements.
    *   **Activities:**
        *   **Unit Testing (Continued):** Ensure individual components still function after integration.
        *   **Integration Testing:** Test how different components work together.
        *   **System Testing:** Test the entire application in an environment that simulates production.
        *   **User Acceptance Testing (UAT):** Have actual users test the application to ensure it meets their needs and expectations.
        *   **Performance Testing:** Evaluate the application's speed, scalability, and stability under load.
        *   **Security Testing:** Assess the application's vulnerability to security threats.
        *   **Validate Test Results:** Analyze test results, identify defects, and prioritize fixes.
        * **Final Tested Programs:** The result is a set of programs ready for deployment.

6.  ### **Production:**
    *   **Goal:** Deploy the application to a live environment where end-users can access it.
    *   **Activities:**
        *   **Deployment:** Install and configure the application on production servers.
        *   **Data Migration:** Migrate any existing data to the new system.
        *   **Monitoring:** Set up monitoring tools to track performance and identify issues.
        * **Promote to Production:** Make the final, tested program available to end users.
        * **Production Repository:** Store a copy of all code, scripts, etc. in a repository for safety and version control.
      * **Important:** *Make no changes to the code after it has been promoted to production* without going through the testing process again.

7.  ### **Maintenance:**
    *   **Goal:** Provide ongoing support, fix bugs, and add new features.
    *   **Activities:**
        *   **Bug Fixing:** Address any issues reported by users or discovered through monitoring.
        *   **Performance Tuning:** Optimize the application's performance.
        *   **Security Updates:** Apply security patches to address vulnerabilities.
        *   **Feature Enhancements:** Add new features or functionality based on user feedback or changing business needs.  *These enhancements should go through the full ADLC.*
        *  **Upgrades:** Perform needed upgrades, e.g. to accomodate new or changed external libraries.

### **Multiple Files (Best Practice):**

*   **Modular Design:** Structure your code into multiple files, each responsible for a specific functionality or module.
*   **Benefits:**
    *   **Improved Maintainability:** Easier to understand, modify, and debug code.
    *   **Increased Reusability:** Components can be reused in other projects.
    *   **Easier Collaboration:** Multiple developers can work on different parts of the application simultaneously.
    *   **Reduced Complexity:** Breaking down a large application into smaller, manageable pieces.
* **Central Program:** Use a main program or script to call the individual files and functions, orchestrating the overall application flow.

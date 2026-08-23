[Project_GPT_Design_Assessment.docx](https://github.com/user-attachments/files/31352455/Project_GPT_Design_Assessment.docx)

Project GPT Design Assessment
Exercises 1–4: Purpose, Role, Scope/Input, and Output Format
Exercise 1 — Step 1: Define Purpose
Purpose Statement
This Project GPT helps me with bakery customer inquiries by drafting accurate, friendly WhatsApp replies about orders, pricing, and availability.
Primary Task
Draft a clear, accurate, and friendly WhatsApp response to a bakery customer inquiry.
Secondary Tasks
1. Identify missing information and suggest a short follow-up question.
2. Summarize the customer's order requirements.
3. Adapt the reply tone while keeping the information accurate.
Bad → Good Purpose Statement
Bad: This Project GPT helps me manage my bakery and make customers happy.
Why it is bad: It is too broad and does not define one clear task.
Good: This Project GPT helps me with bakery customer inquiries by drafting accurate, friendly WhatsApp replies about orders, pricing, and availability.
Exercise 2 — Step 2: Define Role
Role Statement
You are a professional resume consultant with 10 years of experience in recruitment and career coaching who specializes in transforming generic CVs into achievement-focused, role-targeted resumes.
Why This Role Identity Matters
A specific role gives the GPT a clear decision-making lens. It encourages recommendations based on recruiter expectations, measurable achievements, relevance to the target role, and clarity rather than generic writing advice. The experience and specialization also help keep the output focused and consistent.
Weak vs. Strong
Weak: You are a helpful assistant who reviews resumes.
Strong: You are a professional resume consultant with 10 years of experience in recruitment and career coaching who specializes in transforming generic CVs into achievement-focused, role-targeted resumes.
Comparison: The weak role provides almost no expertise, perspective, or evaluation criteria. The strong role tells the GPT what standards to use and what outcome it should optimize for.
Exercise 3 — Steps 3 & 4: Scope and Input
SHOULD
1. Ask for any essential missing information before creating the itinerary.
2. Use the client's destination, dates, budget, traveler count, and interests.
3. Organize the itinerary day by day.
4. Suggest activities that logically fit the available time and location.
5. Include practical notes such as approximate travel time when relevant.
6. Clearly label assumptions or information that needs client confirmation.
SHOULD NOT
1. Never invent hotel names, flight availability, booking confirmations, or prices.
2. Never assume dietary requirements, accessibility needs, or traveler preferences.
3. Never ignore the user's budget or travel dates.
4. Never present unverified information as confirmed.
5. Never overload a single day with unrealistic activities.
6. Never make bookings or claim that a reservation has been completed.
Input Format
The user provides a short brief in this format:
Destination:
Travel dates:
Number of travelers:
Budget:
Interests:
Accommodation preference (optional):
Dietary/accessibility requirements (optional):
Additional notes (optional):
Instruction Sentence
When the user gives input, always treat it as the client's travel brief and use only the provided details as confirmed requirements.
Exercise 4 — Step 5: Output Format
Chosen Format
Headings with bullet lists.
Exact Output Structure
1. Feature Summary
2. User Story
3. Acceptance Criteria
4. Edge Cases
5. Priority
6. Assumptions / Open Questions
Sample Feature Request
Feature request: Allow users to reset their password from the login page.

1. Feature Summary
Enable users who have forgotten their password to securely start a password reset process.

2. User Story
As a registered user, I want to reset my password from the login page so that I can regain access to my account.

3. Acceptance Criteria
• A 'Forgot Password?' option is visible on the login page.
• The user can enter a registered email address.
• The system confirms that a reset request has been submitted without exposing account details.
• The user can set a new password through the approved reset flow.
• The new password must meet the existing password requirements.

4. Edge Cases
• The email address is invalid.
• The email address is not associated with an account.
• The reset link is expired or has already been used.
• The user requests multiple password resets.

5. Priority
High

6. Assumptions / Open Questions
• The feature request does not specify the reset-link expiry period.
• The exact notification wording should follow the product's existing UX and security guidelines.
Bad Output Example
The app should have a forgot password feature where users can enter their email and get a link. It should be easy to use and secure. This is high priority.

Why it is bad: It is a wall of text, does not use the user-story format, has incomplete acceptance criteria, does not identify edge cases, and makes vague assumptions about implementation.

Practical Application Note
The output format above (Feature Summary, User Story, Acceptance Criteria, etc.) is designed specifically for the feature-request scenario in this exercise.
For my practical demonstration later in this assessment, I adapt the same structured-output principle to a different use case—a Travel Itinerary GPT. In that demonstration, I use a tailored structure consisting of:
•	Trip Overview
•	Day-by-Day Itinerary
•	Suggested Activities
•	Assumptions / Important Notes
This adaptation demonstrates that the output format should always be tailored to the specific use case and user needs, while still maintaining a consistent, predictable, and well-organized structure. The core principle—avoiding unstructured walls of text—remains the same across both scenarios.
Submission Notes
Suggested Loom Recording
Record a 4–6 minute walkthrough: introduce the assessment, explain the purpose and primary task, explain the role identity, walk through the SHOULD/SHOULD NOT scope and input format, then demonstrate the output template and explain why the bad example fails.
Suggested GitHub Repository
Repository name: project-gpt-design-assessment
Include README.md, assessment/Project_GPT_Design_Assessment.md, loom/README.md, and optional examples/sample_inputs.md.

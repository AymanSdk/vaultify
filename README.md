Here’s a guide to the shapes you should use for each step in a flowchart, based on standard flowchart conventions:

1. **Start**: **Oval**

   - Shape: Represents the beginning of the process.
   - Text: "Start: User enters full name and email."

2. **Process**: **Rectangle**

   - Shape: Represents a specific action or step.
   - Example: "Send OTP to the user's email" or "Create a new user document."

3. **Decision**: **Diamond**

   - Shape: Represents a decision point with branching paths.
   - Example: "Does the user already exist?"

4. **Connector**: **Arrow**

   - Shape: Represents the flow between steps.
   - Example: Arrow connecting "Does the user already exist?" to subsequent steps like "Yes" or "No."

5. **End**: **Oval**
   - Shape: Represents the termination of the process.
   - Text: "End: User authenticated and logged in."

Here’s how you can map your flow:

1. **Oval**: Start
2. **Rectangle**: "Enter full name and email."
3. **Diamond**: "Does the user already exist?"
   - **Yes**: **Rectangle** for "Send OTP to email."
   - **No**: **Rectangle** for "Create new user document," followed by **Rectangle** for "Send OTP to email."
4. **Rectangle**: "Send secret key for session."
5. **Rectangle**: "Return account ID."
6. **Rectangle**: "Verify OTP and authenticate."
7. **Oval**: End

Let me know if you need a visual version or further explanation!

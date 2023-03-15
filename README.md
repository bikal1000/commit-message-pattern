# Commit Message Pattern for Efficient Development Workflow

As a member of our development team, I want us to use a structured and informative commit message convention to help us keep track of changes and work more effectively together. That's why I suggest we use a commit message pattern that includes a commit type, scope, subject, and Jira ticket number.

## How to Use the Commit Message Pattern
`<Type>(<Scope>): <Subject> #<TicketNumber>`

Here's how we can use this commit message pattern in our workflow:

1. Choose a commit type: When making a commit, start by selecting one of the six commit types listed below, depending on the nature of the change you are making:
    - Add: for new features
    - Change: for changes in existing functionality
    - Deprecate: for soon-to-be removed features
    - Remove: for now removed features
    - Fixed: for any bug fixes
    - Security: in case of vulnerabilities

2. Specify a scope: The scope should indicate which part of the application you are modifying or adding. This could be a specific module, component, or feature. 

3. Write a subject: The subject should provide a brief summary of the change you are making. 

4. Include the Jira ticket number: Since we use Jira to track tasks and issues, it's important to include the ticket number in the commit message. This will make it easier to track changes and link them back to specific tasks or issues. 

Here's an example commit message that follows this pattern:
`Add(login-page): Add login form component #XP-1234`

In this example, the commit message:

- Uses the `Add` verb to indicate that a new component has been added
- Specifies the `login-page` scope to indicate which part of the application has been modified
- Includes the Jira ticket number (`#XP-1234`) in the message to link the commit to the corresponding Jira issue
- Provides a brief summary of the change in the subject line

By following this commit message pattern, we can help make our commits more informative and easier to understand for other team members. Additionally, if we decide to include a body or footer section in our commit messages in the future, we can use them to provide additional context and references to related issues or pull requests.

Let's start using this commit message pattern in our workflow to help us work more efficiently and effectively together.

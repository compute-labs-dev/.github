# **Pull Request Template**

## **Issue Link**

[Link]

## **Description**

[Provide a brief description of the changes in this PR]

## **Type of Change**

- [ ]  Bug fix (non-breaking change that fixes an issue)
- [ ]  New feature (non-breaking change that adds functionality)
- [ ]  Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ]  Performance improvement
- [ ]  Code refactoring
- [ ]  Documentation update
- [ ]  Other (please describe):

## **Approach**

[Briefly describe the approach/solution implemented]

## **Key Changes**

- [Highlight the most important changes]
- [List modified components or files]
- [Mention any architectural decisions made]

## **Test Plan**

[Describe how you tested these changes]

### **Unit Tests**

- [List key unit tests added/modified]

### **Integration Tests**

- [List key integration tests added/modified]

### **Manual Testing**

- [Describe any manual testing performed]

## **Performance Impact (Optional for small PRs)**

[Describe any performance improvements or concerns]

## **Dependencies (Optional for small PRs)**

[List any new dependencies added]

## **Deployment Considerations (Optional for small PRs)**

[Any special deployment steps required]

## **Screenshots (if applicable)**

[Include relevant screenshots or images]

## **Checklist**

- [ ]  My code follows the established code style of the project
- [ ]  I have commented my code, particularly in hard-to-understand areas
- [ ]  I have made corresponding changes to the documentation
- [ ]  I have added tests that prove my fix is effective or that my feature works
- [ ]  New and existing unit tests pass locally with my changes
- [ ]  Any dependent changes have been merged and published
- [ ]  Review code for logical errors
- [ ]  Ensure adherence to architecture patterns
- [ ]  Verify code addresses the issue requirements
    
    The PR should only address the issue that it’s trying to resolve
    
    - should not contain irrelevant code changes
        - will the code work without this
        - and does the code resolve the issue the PR is focused on
- [ ]  Should never include secrets and sensitive info in the PR
- [ ]  For adhoc scripts and other temporary files, should place them in a `temp` directory and never commit those
- [ ]  Proper logging and monitoring through test and sentry integration

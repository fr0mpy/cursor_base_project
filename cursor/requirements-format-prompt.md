# Requirements Generation Prompt

Generate comprehensive project requirements for [PROJECT TYPE] that strictly follow this structure:

# Project Requirements

<!--
This template follows the format specified in your Cursor settings.
Each requirement should include:
- A unique ID with category prefix
- A descriptive title
- Description of what needs to be implemented
- Current status (using the status indicators)
- Any additional notes or considerations
-->

## [Category Name]

### [REQ-CATG-001] Requirement Title

- Description: Detailed description of what needs to be implemented
- Status: [ ] Not started
- Notes: Additional information, considerations, constraints, or guidance

### [REQ-CATG-002] Another Requirement

- Description: Detailed description of what needs to be implemented
- Status: [ ] Not started
- Notes: Additional information, considerations, constraints, or guidance

## [Another Category]

### [REQ-CATG2-001] First Requirement in Category

- Description: Detailed description of what needs to be implemented
- Status: [ ] Not started
- Notes: Additional information, considerations, constraints, or guidance

<!--
Status indicators:
[ ] Not started
[~] In progress
[x] Complete

Category prefixes examples:
- AUTH: Authentication
- UI: User Interface
- API: API Integration
- FEAT: Features
- SEC: Security
- PERF: Performance
-->

## Example (Authentication)

### [REQ-AUTH-001] User Login

- Description: Implement a secure login form with email/password fields and validation
- Status: [ ] Not started
- Notes: Include error handling for invalid credentials and rate limiting for failed attempts

### [REQ-AUTH-002] User Registration

- Description: Create a registration form with fields for email, password, and password confirmation
- Status: [ ] Not started
- Notes: Validate email format and ensure password meets security requirements

Important guidelines:

- Use meaningful category names that reflect major system components
- Create logical category prefixes in the requirement IDs
- Ensure each requirement has a unique ID with correct numbering
- Write clear, specific descriptions that explain what must be implemented
- All requirements should start with "Not started" status
- Include relevant notes that provide additional context or implementation guidance
- Replace the example section with actual requirements when done

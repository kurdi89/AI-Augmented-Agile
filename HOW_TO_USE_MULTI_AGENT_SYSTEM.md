# How to Use the Multi-Agent SDLC System with Cursor

## Overview
The Multi-Agent SDLC System is a comprehensive software development automation framework that orchestrates specialized AI agents through a complete Software Development Life Cycle (SDLC). This guide shows you how to use it with Cursor's custom agent feature to build any project.

## Quick Start

### 1. Set Up Custom Agent in Cursor
1. Open Cursor
2. Go to Settings → Features → Custom Agent
3. Copy the entire content from `multi-agent-synthesis/CURSOR_AGENT_PROMPT.md`
4. Paste it into the Custom Agent prompt field
5. Save the configuration

### 2. Activate the System
Simply provide a project request in this format:
```
Build me a [PROJECT_TYPE] called "[PROJECT_NAME]" that [BRIEF_DESCRIPTION].
Requirements: [SPECIFIC_REQUIREMENTS]
Tech Stack: [PREFERRED_TECHNOLOGIES]
```
_You can ignore the tech stack and keep to the design phase with the Solution Arch. to decide_

### 3. Example Project Requests

**E-commerce Platform**:
```
Build me a full-stack e-commerce platform called "ShopSmart" that allows users to browse products, add items to cart, and complete purchases.
Requirements: User authentication, product catalog, shopping cart, payment integration, admin dashboard
Tech Stack: React, Node.js, MongoDB, Stripe API
```

**Task Management App**:
```
Build me a task management application called "TaskFlow" that helps teams organize and track project progress.
Requirements: User collaboration, task assignment, progress tracking, notifications, reporting
Tech Stack: Next.js, TypeScript, PostgreSQL, Prisma
```

**Social Media Dashboard**:
```
Build me a social media management dashboard called "SocialHub" that aggregates content from multiple platforms.
Requirements: Multi-platform integration, content scheduling, analytics, user management
Tech Stack: Vue.js, Python FastAPI, Redis, Docker
```

## What the System Will Do

### Phase 1: Requirements Engineering (Automatic)
The system will:
- **Analyze** your project request
- **Create** a detailed Project Brief
- **Generate** a comprehensive Product Requirements Document (PRD)
- **Produce** user personas and feature specifications
- **Request** your approval before proceeding

**You'll Get**:
- `Projects/[PROJECT_NAME]/01_Requirements/Project_Brief.md`
- `Projects/[PROJECT_NAME]/01_Requirements/PRD.md`
- `Projects/[PROJECT_NAME]/01_Requirements/PRD_Approval_Form.md`

### Phase 2: Technical Architecture (After Your Approval)
The system will:
- **Design** complete system architecture
- **Create** technical specifications
- **Generate** API documentation
- **Produce** UI/UX specifications
- **Request** technical validation

**You'll Get**:
- `Projects/[PROJECT_NAME]/02_Architecture/TDD.md`
- `Projects/[PROJECT_NAME]/02_Architecture/System_Architecture.md`
- `Projects/[PROJECT_NAME]/02_Architecture/UIUX_Spec.md`
- `Projects/[PROJECT_NAME]/02_Architecture/API_Specifications.md`

### Phase 3: Implementation (After Your Approval)
The system will:
- **Break down** work into Epics and User Stories
- **Generate** complete, production-ready source code
- **Create** comprehensive tests
- **Build** deployment scripts
- **Produce** documentation

**You'll Get**:
- `Projects/[PROJECT_NAME]/03_Implementation/Epics/`
- `Projects/[PROJECT_NAME]/03_Implementation/User_Stories/`
- `Projects/[PROJECT_NAME]/03_Implementation/Source_Code/`
- `Projects/[PROJECT_NAME]/03_Implementation/Tests/`
- `Projects/[PROJECT_NAME]/03_Implementation/Deployment/`
- `Projects/[PROJECT_NAME]/03_Implementation/Documentation/`

## Human Checkpoints

The system includes **mandatory human approval points**:

1. **PRD Approval**: Review and approve requirements before architecture
2. **TDD Validation**: Validate technical design before implementation
3. **Sprint Reviews**: Review completed features during development
4. **Deployment Approval**: Final approval before production deployment

## Key Features

### ✅ Complete SDLC Automation
- Requirements analysis and documentation
- System architecture and design
- Agile implementation with user stories
- Quality assurance and testing
- Deployment and DevOps

### ✅ Professional Documentation
- Uses industry-standard templates
- Comprehensive technical specifications
- Clear user stories and acceptance criteria
- Deployment and maintenance guides

### ✅ Quality Assurance
- Built-in checklists and validation
- Code quality standards
- Testing requirements
- Human review checkpoints

### ✅ Production-Ready Code
- Clean, maintainable codebase
- Comprehensive test coverage
- Deployment automation
- Documentation and guides

## Advanced Usage

### Custom Requirements
You can specify detailed requirements:
```
Build me a healthcare management system called "MedFlow" that manages patient records and appointments.
Requirements: 
- HIPAA compliance required
- Patient portal with appointment scheduling
- Doctor dashboard with patient history
- Billing and insurance integration
- Mobile-responsive design
- Multi-language support (English, Spanish)
Tech Stack: React, Node.js, PostgreSQL, Docker
Deployment: AWS with high availability
```

### Technology Constraints
Specify technology preferences:
```
Build me a learning management system called "EduConnect" using only open-source technologies.
Requirements: Course creation, student enrollment, progress tracking, assessments
Tech Stack: Vue.js, Python Django, PostgreSQL, Redis
Deployment: Self-hosted with Docker Compose
```

## Best Practices

### 1. Be Specific with Requirements
- Include functional requirements (what the system should do)
- Specify non-functional requirements (performance, security, etc.)
- Mention any compliance or regulatory needs

### 2. Provide Context
- Explain the target audience
- Describe the problem you're solving
- Include any business constraints

### 3. Review Thoroughly
- Carefully review the PRD before approval
- Validate the technical architecture
- Test the delivered application

### 4. Provide Feedback
- Use the validation forms to provide feedback
- Be specific about requested changes
- Approve phases only when satisfied

## Troubleshooting

### If the System Doesn't Start
- Ensure you've copied the complete prompt
- Check that you've saved the custom agent configuration
- Restart Cursor and try again

### If You Need Changes
- Provide specific feedback in the validation forms
- Request revisions before approving phases
- The system will adapt based on your input

### If You Want to Modify the System
- Edit the agent files in `multi-agent-synthesis/Agents/`
- Modify templates in `multi-agent-synthesis/Templates/`
- Update the main prompt in `multi-agent-synthesis/CURSOR_AGENT_PROMPT.md`

## Example Complete Workflow

1. **Request**: "Build me a blog platform called 'WriteFlow' with user authentication, post creation, and commenting."

2. **Phase 1**: System creates requirements documents and requests approval

3. **You Review**: Check PRD, approve or request changes

4. **Phase 2**: System creates technical architecture and requests validation

5. **You Review**: Validate architecture, approve or request changes

6. **Phase 3**: System implements complete application with:
   - User authentication system
   - Blog post creation and editing
   - Commenting system
   - Admin dashboard
   - Responsive design
   - Test coverage
   - Deployment scripts

7. **You Review**: Test the application, approve for deployment

8. **Result**: Complete, production-ready blog platform with documentation

---

# Using with Cline (VS Code Extension)

## Overview
Cline is a powerful VS Code extension that provides enhanced AI assistance with direct file system access. This section shows you how to use the Multi-Agent SDLC System with Cline for automatic file creation and management.

## Quick Start with Cline

### 1. Set Up Cline in VS Code
1. Install the Cline extension from the VS Code marketplace
2. Open VS Code in your project workspace
3. Open the Command Palette (Ctrl+Shift+P / Cmd+Shift+P)
4. Type "Cline: Open" and select it
5. In the Cline interface, click on the settings/configuration icon
6. Copy the entire content from `multi-agent-synthesis/CLINE_AGENT_PROMPT.md`
7. Paste it into the Custom Instructions field
8. Save the configuration

### 2. Activate the Multi-Agent System in Cline
Simply provide a project request in the same format:
```
Build me a [PROJECT_TYPE] called "[PROJECT_NAME]" that [BRIEF_DESCRIPTION].
Requirements: [SPECIFIC_REQUIREMENTS]
Tech Stack: [PREFERRED_TECHNOLOGIES]
```

### 3. Cline-Specific Advantages

**Enhanced File Management**:
- Cline will automatically create all project files and directories
- Real-time file creation with progress tracking
- Automatic validation of created files
- Terminal integration for package installation and testing

**Interactive Development**:
- Files are created directly in your VS Code workspace
- You can see and edit files as they're being created
- Immediate access to created code for review and testing
- Integrated terminal for running commands

**Advanced Capabilities**:
- Automatic package.json creation and dependency management
- Git repository initialization when appropriate
- Environment setup and configuration
- Test execution and validation

### 4. Cline Workflow Example

**When you request a project, Cline will**:

1. **Phase 1 - Requirements** (Automatic file creation):
   ```
   ✅ Creating Projects/[PROJECT_NAME]/01_Requirements/
   ✅ Generated Project_Brief.md
   ✅ Generated PRD.md
   ✅ Generated PRD_Approval_Form.md
   ```

2. **Phase 2 - Architecture** (After your approval):
   ```
   ✅ Creating Projects/[PROJECT_NAME]/02_Architecture/
   ✅ Generated TDD.md
   ✅ Generated System_Architecture.md
   ✅ Generated UIUX_Spec.md
   ✅ Generated API_Specifications.md
   ```

3. **Phase 3 - Implementation** (After your approval):
   ```
   ✅ Creating Projects/[PROJECT_NAME]/03_Implementation/
   ✅ Setting up Source_Code/ directory
   ✅ Installing dependencies...
   ✅ Generating application code...
   ✅ Creating test files...
   ✅ Setting up deployment scripts...
   ```

### 5. Cline-Specific Best Practices

**File Management**:
- All files are created automatically in your workspace
- Review files as they're created in VS Code
- Use VS Code's built-in Git integration for version control
- Leverage VS Code's terminal for testing and deployment

**Development Flow**:
- Files are created incrementally with validation
- You can modify files during the process
- Use VS Code's IntelliSense and debugging features
- Test code immediately as it's generated

**Quality Assurance**:
- Cline validates each file after creation
- Automatic syntax checking and formatting
- Integration with VS Code's linting and error detection
- Real-time feedback on code quality

### 6. Troubleshooting Cline Setup

**If Cline doesn't respond properly**:
- Ensure you've installed the latest version of Cline
- Check that the custom instructions are properly saved
- Restart VS Code and try again
- Verify your workspace has write permissions

**If files aren't being created**:
- Check VS Code's file explorer for the Projects/ directory
- Ensure your workspace has sufficient disk space
- Verify file permissions in your workspace
- Check the Cline output for any error messages

**If you need to modify the system**:
- Edit the prompt in `multi-agent-synthesis/CLINE_AGENT_PROMPT.md`
- Update the custom instructions in Cline
- Restart the conversation to apply changes

### 7. Cline vs Cursor Comparison

| Feature | Cline (VS Code) | Cursor |
|---------|----------------|---------|
| File Creation | Automatic, real-time | Manual review required |
| IDE Integration | Native VS Code features | Cursor-specific features |
| Extension Ecosystem | Full VS Code extensions | Cursor extensions |
| Debugging | VS Code debugger | Cursor debugger |
| Git Integration | VS Code Git tools | Cursor Git tools |

**Choose Cline when you want**:
- Automatic file creation and management
- Full VS Code ecosystem and extensions
- Integrated terminal and debugging
- Real-time code validation and testing

**Choose Cursor when you want**:
- Cursor's specific AI features
- Cursor's code completion and suggestions
- Cursor's collaborative features
- Cursor's optimized AI workflow

### 8. Cline Example Project Requests

**Full-Stack Web Application**:
```
Build me a full-stack task management app called "TaskMaster" that helps teams collaborate on projects.
Requirements: User authentication, project creation, task assignment, real-time updates, notifications
Tech Stack: React, Node.js, Express, MongoDB, Socket.io
```

**Mobile-First Progressive Web App**:
```
Build me a mobile-first PWA called "FitTracker" for fitness tracking and workout planning.
Requirements: Offline capability, workout logging, progress tracking, social features
Tech Stack: Vue.js, PWA, IndexedDB, Chart.js
```

**Enterprise Dashboard**:
```
Build me an enterprise analytics dashboard called "DataViz" for business intelligence.
Requirements: Data visualization, user roles, export functionality, real-time updates
Tech Stack: Angular, TypeScript, D3.js, PostgreSQL, Docker
```

## Support

- Review agent specifications in `multi-agent-synthesis/Agents/`
- Examine templates and examples in `multi-agent-synthesis/Templates/`


## to start :

- Clone this repo anywhere on your computer
- Follow the steps above and start your projects
- Find your projects built inside the `Projects/` folder 

---

**Ready to build your next project with the Multi-Agent SDLC System!**

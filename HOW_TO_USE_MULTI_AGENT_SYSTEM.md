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

## Support

For questions or issues:
- Check the system documentation in `multi-agent-synthesis/Knowledge_Repository/`
- Review agent specifications in `multi-agent-synthesis/Agents/`
- Examine templates and examples in `multi-agent-synthesis/Templates/`

---

**Ready to build your next project with the Multi-Agent SDLC System!** 
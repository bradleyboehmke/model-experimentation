# ModelOps and Model Experimentation Workshop

## Project Overview

This repository contains materials for creating a 60-90 minute applied workshop titled **"ModelOps and Model Experimentation: From Training Runs to Managed Models"**. The workshop combines conceptual framing, practical workflow demonstrations, and a live demo using MLflow with the Rossmann forecasting project.

## Purpose

Create a Quarto RevealJS presentation that teaches students:
- ModelOps fundamentals and lifecycle management
- Structured experimentation practices
- Experiment tracking with MLflow
- Practical application through real-world examples

## Technology Stack

- **Presentation Format**: Quarto RevealJS
- **Diagrams**: Mermaid
- **Demo Platform**: MLflow
- **Example Project**: Rossmann forecasting

## Key External Dependencies

This project references several external resources on the local machine:

1. **Template Structure**: `~/Desktop/UC/Applied Workshops/notebook-to-production-data`
   - Reference presentation for structural guidance

2. **Conceptual Content**:
   - `~/Desktop/UC/uc-bana-7075/book/05-modelops-role.qmd` - ModelOps concepts
   - `~/Desktop/UC/uc-bana-7075/book/06-modelops-experimenting.qmd` - Model training and experiment tracking

3. **Demo Project**: `~/Desktop/Projects/rossmann-forecasting`
   - Real-world example for MLflow demonstration
   - Relevant documentation:
     - `~/Desktop/UC/uc-bana-7075/docs/modelops/overview.md`
     - `~/Desktop/UC/uc-bana-7075/docs/modelops/tracking.md`

## Design Principles

### Slide Philosophy
- **Minimal text**: Slides should be visual and concise
- **Key takeaway focused**: Each slide has one clear message
- **Instructor-driven**: Slides support verbal explanation, don't replace it

### Speaker Notes
- Medium-light detail
- Talking points, not full scripts
- Support instructor flow

### Visuals
- Use Mermaid diagrams for workflows and processes
- Image placeholders for concepts:
  - `[IMAGE: chaotic notebooks]`
  - `[IMAGE: MLflow dashboard]`
  - etc.

## Content Structure

The workshop follows this progression:

1. **Framing** - Opening hook about current model tracking practices
2. **ModelOps** - Definition and lifecycle management
3. **Experimentation** - From chaos to structured experimentation
4. **MLflow** - Tool introduction and mental models
5. **Rossmann** - Real-world workflow demonstration
6. **Demo** - Live MLflow demonstration
7. **Wrap-Up** - Key takeaways and summary

## Core Learning Goals

Students should be able to:
- Understand ModelOps as lifecycle management
- Recognize the need for structured experimentation
- Understand experiment tracking concepts
- Apply these concepts using MLflow

## File Organization

```
.
├── _quarto.yml                        # Quarto configuration
├── README.md                          # Project overview and workshop description
├── CLAUDE.md                          # This file - detailed context for Claude
├── spec.md                            # Detailed workshop specification
├── .gitignore                         # Git ignore rules
└── workshop/
    └── slides/
        ├── assets/                    # Images and media for slides
        └── modelops-experimentation.qmd  # Main presentation file (to be created)
```

## Development Guidelines

### When Creating Slides

1. **Keep slides minimal** - Let the instructor fill in details
2. **Use speaker notes** - Provide talking points for each slide
3. **Insert Mermaid diagrams** - For workflows and processes
4. **Use image placeholders** - Mark where visuals should go
5. **Align with Rossmann repo** - Ensure demo instructions match actual project

### Content Alignment

- Ensure technical accuracy with referenced materials
- Match terminology from the BANA 7075 course materials
- Verify MLflow workflow matches Rossmann project implementation

## Success Criteria

The workshop is successful when students:
- Understand ModelOps as a lifecycle approach (not just training)
- Recognize the need for structured experimentation
- Can explain what experiment tracking captures
- Can apply these concepts in their own projects

## Working with This Repository

### When Adding Content

1. Reference the specification file for detailed requirements
2. Check external resources for technical accuracy
3. Maintain the minimal slide / detailed notes pattern
4. Test that Mermaid diagrams render correctly
5. Verify demo steps match the actual Rossmann project

### When Updating

1. Keep the specification file synchronized with actual content
2. Update this file if project structure changes
3. Document any new external dependencies

## Notes for Claude Code

- This is an educational/workshop content repository
- Focus on clarity and pedagogical effectiveness
- Slides should support teaching, not replace it
- Always verify technical content against source materials
- Mermaid diagrams should be simple and clear

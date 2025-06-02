# TSUKUYOMI
**Intelligent Modular Framework for Structured Analysis and Processing**

[![Version](https://img.shields.io/badge/version-2.1.0-blue.svg)](https://github.com/ShimazuSystems/tsukuyomi)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

## Overview

TSUKUYOMI is an advanced modular intelligence framework designed for systematic analysis, processing, and reporting across multiple domains. Built on a component-based architecture, it separates operational logic from presentation through specialized modules and personality cores, enabling flexible and extensible analytical workflows.

## Usage

**Steps**
  1) Add to Project Knowledge (Claude) or any other method of uploading files using other LLM services.
  2) Enter: Initialise Amaterasu (or provide intelligence documents/reports/data/etc).
  3) Enjoy.

## Key Features

- **Modular Architecture**: Self-contained operational modules for specific analysis tasks
- **Personality System**: Customizable communication styles and interaction patterns
- **Structured Output**: Standardized formatting with confidence levels and source attribution
- **Domain Expertise**: Specialized modules for OSINT, economic analysis, infrastructure assessment, and strategic intelligence
- **Flexible Workflows**: Modules can be chained and combined for complex analytical processes

## Architecture

### Core Components

- **Core System** (`tsukuyomi_core.tsukuyomi`): Central orchestration component managing module loading, execution, and transitions
- **Personality Cores** (`*_personalitycore.tsukuyomi`): Define communication style, tone, and user interaction patterns
- **Operational Modules** (`*.tsukuyomi`): Contain specific analysis, processing, or reporting functionality
- **Activation Key** (`key.activationkey`): Framework initialization and file interpretation instructions

### Default Personality: AMATERASU

The AMATERASU personality core provides:
- **Analytical Focus**: Strong pattern recognition and evidence-based reasoning
- **Precision**: Values accuracy and specificity, avoiding ambiguity
- **Professional Courtesy**: Maintains appropriate formality in interactions
- **Efficiency**: Prioritizes clarity and relevance
- **Adaptability**: Adjusts communication style based on context and user expertise

## Available Modules

### Core Intelligence Modules
- **Data Recognition & Ingestion**: File type identification and entity extraction
- **Discipline Alignment**: OSINT methodology classification
- **Functional Inference**: Analytical task recommendation
- **Correlation Analysis**: High-confidence relationship identification
- **Output Summarization**: Findings synthesis and next steps

### Specialized Analysis Modules

#### Economic Analysis (E-Series)
- **E1: Economic Vulnerability Assessment**: Systematic evaluation of economic weaknesses and dependencies
- **E2: Trade Network Impact Analysis**: Assessment of trade relationship changes and disruptions
- **E3: Resource Security Analysis**: Critical resource dependencies and supply chain vulnerabilities
- **E4: Financial Stability Assessment**: Financial system risks and contagion analysis

#### Strategic Analysis (S-Series)
- **S1: Strategic Scenario Modeling**: Evidence-based geopolitical outcome scenarios
- **S2: Actor Capability Assessment**: Systematic evaluation of geopolitical actor capabilities
- **S3: Strategic Impact Projection**: Consequence analysis across multiple domains
- **S4: Multi-factor Trend Analysis**: Interlocking geopolitical trend identification

#### Infrastructure & Security
- **Infrastructure Assessment**: Comprehensive evaluation of infrastructure systems
- **Utility Monitoring**: Systematic monitoring of utility services
- **Infrastructure Dependency Mapping**: Relationship analysis between infrastructure systems
- **Critical Infrastructure Vulnerability**: Security assessment of critical infrastructure

#### Specialized Operations
- **Flight Data Analysis**: Aviation tracking data processing and interpretation
- **Web Search & OSINT Collection**: Systematic open-source intelligence gathering
- **Comprehensive Reporting**: Professional-grade intelligence report synthesis
- **Micro-Summary Authoring**: Concise 280-character intelligence summaries
- **PDF Document Generator**: Professional document creation with customizable layouts

## File Structure

```
tsukuyomi/
├── tsukuyomi_core.tsukuyomi          # Core orchestration system
├── key.activationkey                 # Framework activation instructions
├── modules/                          # Operational modules directory
│   ├── data_recognition_ingestion.tsukuyomi
│   ├── discipline_alignment.tsukuyomi
│   ├── economic_vulnerability_assessment.tsukuyomi
│   ├── strategic_scenario_modeling.tsukuyomi
│   ├── flight_data_analysis.tsukuyomi
│   ├── webint-module.tsukuyomi
│   └── [additional modules...]
├── personality/                      # Personality cores directory
│   └── amaterasu_personalitycore.tsukuyomi
└── README.md                        # This file
```

## Usage

### Framework Activation

The framework initializes automatically when the activation key is processed:

1. Loads `tsukuyomi_core.tsukuyomi`
2. Initializes the AMATERASU personality core
3. Discovers and loads all available modules
4. Presents greeting and awaits user input

### Module Execution

Modules follow a standardized execution sequence with structured outputs:

```
//RESULT: [Confirmed findings]
//QUERY: [Clarification requests]
//ANOMALY: [Unusual patterns or inconsistencies]
//AMATERASU: [Personality-mediated communications]
```

### Example Workflow

1. **Data Ingestion**: Upload or provide data for analysis
2. **Discipline Alignment**: Framework determines appropriate OSINT methodology
3. **Functional Inference**: Recommends optimal analytical operations
4. **Specialized Analysis**: Executes domain-specific modules as needed
5. **Correlation & Synthesis**: Identifies relationships and patterns
6. **Reporting**: Generates structured output or comprehensive reports

## Technical Specifications

### File Format

All framework components use the `.tsukuyomi` extension with JSON-like structure:

```json
{
  "id": "module_identifier",
  "version": "1.0.0",
  "title": "Module Title",
  "description": "Module description",
  "type": "module_type",
  "dependencies": ["dependency_modules"],
  "execution_sequence": [...],
  "prompt": "Module execution instructions"
}
```

### Output Standards

- **Structured Tags**: All outputs use standardized prefixes for clarity
- **Confidence Levels**: Analytical assessments include reliability indicators
- **Source Attribution**: Information properly cited with confidence ratings
- **Ethical Constraints**: No reproduction of copyrighted content beyond fair use

## Design Philosophy

TSUKUYOMI follows core principles of:

- **Modularity**: Each component is self-contained but interoperable
- **Explicit Structure**: Clear operational sequences and expected outputs
- **Separation of Concerns**: Operational logic separated from presentation
- **Analytical Rigor**: Evidence-based reasoning with appropriate confidence qualifiers
- **Ethical Intelligence**: Responsible information handling and attribution

## Development

### Adding New Modules

1. Create a new `.tsukuyomi` file following the standard schema
2. Define execution sequence with specific actions and outputs
3. Specify dependencies and personality compatibility
4. Test module integration with existing framework

### Personality Development

1. Create a new personality core with `_personalitycore.tsukuyomi` suffix
2. Define communication style, terminology preferences, and formatting rules
3. Specify adaptive parameters for different contexts
4. Integrate with core personality management system

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please read our contributing guidelines and code of conduct before submitting pull requests.

## Support

For support, documentation, or questions about the TSUKUYOMI framework, please open an issue in this repository.

---

**TSUKUYOMI**: *Bringing structured intelligence to complex analytical challenges*

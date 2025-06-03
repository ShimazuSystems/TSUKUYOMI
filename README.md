# TSUKUYOMI
**Intelligent Modular Framework for Structured Analysis and Processing**

[![Version](https://img.shields.io/badge/version-2.5.0-blue.svg)](https://github.com/ShimazuSystems/tsukuyomi)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

## Overview

TSUKUYOMI is an advanced modular intelligence framework designed for systematic analysis, processing, and reporting across multiple domains. Built on a component-based architecture, it separates operational logic from presentation through specialized modules and personality cores, enabling flexible and extensible analytical workflows.

## Usage



### Loading/Installation

**Claude**
> Note: Paid Subscription is more or less required
* Project Knowledge Methods
   * Adding Files Manually, simple & effective - lacks 'Sync' functionality
   * Adding GitHub Repository (Best Method) - allows usage whilst keeping updated modules, allows hotswapping modules mid-session.
* Individual Chat Method (Janky)
   * If lacking subscription, this is the only method that will work: you will have to manually add the files to the chat via the upload.
   * Can be time extensive with free 'limits'.
   * Only allows 4 Sonnet, Opus performs better.

**Gemini**
> Note: Paid Subscription makes life easier, but isn't entirely necessary, I am not a Gemini user but I have learned this to help others navigate this.
* Project Knowledge Methods
   * Manual File Method, ditto from Claude
   * Cloning the GitHub repository to a Drive folder, and loading it this way. This is the advised method, I lack the One Plus subscription but I imagine this could be automated fairly easily to 'Sync'.

**ChatGPT**
> Note: Paid Subscription more or less mandatory. (Important: GPT seems to be lagging behind in support for this kind of thing, or at least that's what I can see as a 'free' user.)
* Project Knowledge Methods
   * Cloning the GitHub repository to a Drive folder, this should provide basic Sync functionality like Gemini.

**Others**
> Note: 100% speculation here, aided by Claude 4.

***

## AI Models Supporting File Uploads & Project Management

### **Microsoft Copilot - Knowledge Sources & File Upload**
//AMATERASU: Enterprise-focused with extensive Microsoft integration.

**How it works:**
- You can upload your own documents for use as a knowledge source at the agent level, which your agent then uses to generate answers with generative AI
- **Copilot Studio:** Create custom agents with knowledge bases
- **Microsoft 365 Integration:** Access files from SharePoint, OneDrive
- Enterprise knowledge management across Microsoft ecosystem

**File Support:** Files larger than 512 MB aren't supported. Files with encryption, such as sensitivity labels or password protection, aren't supported
**Requirements:** Microsoft 365 Copilot license or Copilot Studio access

**Best for:** Organizations heavily invested in Microsoft ecosystem

***

### **Perplexity AI - File Upload for Research**
//AMATERASU: Research-focused with real-time web integration.

**How it works:**
- Pro users can leverage advanced models like Claude 3 and GPT-4 to handle longer files
- Upload academic papers to extract key insights, summarize findings, and explore related topics
- Combines uploaded documents with real-time web search
- 30-day file retention

**File Support:** PDFs, CSV files, text documents, academic papers
**Requirements:** Perplexity Pro ($20/month) for unlimited file uploads; limited free access

**Best for:** Research-intensive workflows requiring real-time information

***

### **Mistral AI - Le Chat & Document Processing**
//AMATERASU: European AI solution with strong document capabilities.

**How it works:**
- Upload, organize, and analyze arbitrary files using powerful OCR and vision models under the hood
- Mistral OCR is an Optical Character Recognition API that sets a new standard in document understanding
- Advanced document processing and OCR capabilities
- Enterprise knowledge base integration

**File Support:** PDFs, images, documents with OCR capabilities
**Requirements:** Various pricing tiers available

**Best for:** Document-heavy workflows requiring advanced OCR and European data residency

***

## **Quick Deployment Guide for TSUKUYOMI**

### **Easiest Setup (Recommended):**
1. **Claude Projects** - Upload all .tsukuyomi files directly
2. Enter: "Initialise Amaterasu" or provide your data
3. Framework auto-activates with full functionality

### **Alternative Platforms:**
- **ChatGPT Projects:** Upload files, create project-specific instructions
- **Gemini Gems:** Create custom Gem with TSUKUYOMI files as knowledge base  
- **Copilot Studio:** Build custom agent with TSUKUYOMI modules as knowledge sources
- **Perplexity Pro:** Upload for research-focused intelligence analysis

### **Key Considerations:**
- **File Limits:** Vary by platform (Claude: context window, Gemini: 10 files, etc.)
- **Persistence:** Most platforms retain project knowledge across sessions
- **Cost:** Free tiers available but paid plans recommended for full functionality
- **Integration:** Consider your existing tool ecosystem


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

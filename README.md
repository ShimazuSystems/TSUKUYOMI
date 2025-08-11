# TSUKUYOMI
**Intelligent Modular Framework for Structured Analysis and Processing**

[![Version](https://img.shields.io/badge/version-2.6.0-blue.svg)](https://github.com/ShimazuSystems/tsukuyomi)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Compatibility](https://img.shields.io/badge/AI-Claude%20%7C%20GPT%20%7C%20Gemini-blue.svg)](https://github.com/ShimazuSystems/TSUKUYOMI)
[![Compatibility](https://img.shields.io/badge/Functionality-IntelFramework-red.svg)](https://github.com/ShimazuSystems/TSUKUYOMI)

**Professional Modular Intelligence Framework for Systematic Analysis & Processing**

> Advanced component-based architecture for intelligence operations, analytical workflows, and structured processing across multiple domains with IC-compliant tradecraft standards.

Example: [GitHub Wiki](https://github.com/ShimazuSystems/TSUKUYOMI/wiki/Examples)

## Overview

TSUKUYOMI is a professional-grade modular intelligence framework engineered for systematic analysis, processing, and reporting across multiple intelligence domains. The framework implements a component-based architecture that decouples operational logic from presentation layers through specialized analytical modules and adaptive personality cores, enabling scalable and extensible intelligence workflows.

The system is designed as a prompt engineering framework optimized for large language models, providing structured analytical capabilities that adhere to Intelligence Community standards (ICD 203, ICD 206) while maintaining operational security and compartmentalization protocols.

## Key Features

### Core Architecture
- **Component-Based Modularity**: Self-contained analytical modules with standardized JSON schema
- **Personality System**: Adaptive communication cores with stakeholder-specific optimization
- **Session Management**: Comprehensive state export/import for analytical continuity
- **Security Framework**: Classification-aware processing with IC-compliant handling instructions

### Analytical Capabilities  
- **Multi-Domain Intelligence**: OSINT, GEOINT, economic analysis, infrastructure assessment, strategic intelligence
- **Source Quality Assurance**: Advanced correlation matrices and AI hallucination detection
- **Structured Workflows**: Chained module execution with dependency management
- **Professional Reporting**: IC-standard formatted outputs with confidence calibration

### Technical Implementation
- **LLM-Optimized**: Native integration with Claude Code, GPT, Gemini, and other AI platforms
- **JSON-Based Configuration**: Human-readable module definitions with version control
- **Error Handling**: Comprehensive validation and recovery protocols
- **Extensible Framework**: Plugin architecture for custom module development

## Deployment & Integration

[Technical Documentation](https://github.com/ShimazuSystems/TSUKUYOMI/wiki/Technical-Documentation)

### Loading/Installation

**Claude Code (Recommended)**
> Note: Claude Pro subscription required for optimal performance
* **Direct Repository Integration**: Native git support with real-time file editing and session persistence
* **Terminal Integration**: Full command-line access for advanced operations and debugging
* **Session Management**: Built-in export/import capabilities for analytical continuity
* **Framework Activation**:
  ```bash
  # Clone and initialize
  git clone https://github.com/ShimazuSystems/TSUKUYOMI.git
  cd TSUKUYOMI
  
  # Activate framework
  Initialise Amaterasu
  ```
* **Advanced Features**: File editing, module development, session state management
* **Deployment**: `claude-code` CLI provides full repository access and persistent workspace

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

***

## AI Models Supporting File Uploads & Project Management

### **Microsoft Copilot Studio - Custom Agent Development**
**Enterprise-focused with extensive Microsoft ecosystem integration.**

**How it works:**
- **Custom Copilots:** Build specialized agents using Copilot Studio with TSUKUYOMI knowledge base
- **Knowledge Integration:** Upload framework files as knowledge sources for agent training
- **Microsoft 365 Integration:** Seamless integration with SharePoint, OneDrive, Teams
- **Enterprise Deployment:** Deploy custom TSUKUYOMI-powered copilots across organization
- **Conversation Flow:** Design structured analytical workflows with TSUKUYOMI modules

**TSUKUYOMI Integration:**
- Upload .tsukuyomi files as knowledge base documents
- Configure topics for module selection (E1-E4, S1-S4, etc.)
- Set up trigger phrases for framework activation
- Implement classification-aware responses

**File Support:** JSON, text files up to 512 MB; no encrypted/protected files
**Requirements:** Microsoft Copilot Studio license, Power Platform access
**Deployment:** Web, Teams, mobile apps, API integration

**Best for:** Enterprise environments with Microsoft 365 infrastructure

***

### **Perplexity AI - File Upload for Research**
**Research-focused with real-time web integration.**

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
**European AI solution with strong document capabilities.**

**How it works:**
- Upload, organize, and analyze arbitrary files using powerful OCR and vision models under the hood
- Mistral OCR is an Optical Character Recognition API that sets a new standard in document understanding
- Advanced document processing and OCR capabilities
- Enterprise knowledge base integration

**File Support:** PDFs, images, documents with OCR capabilities
**Requirements:** Various pricing tiers available

**Best for:** Document-heavy workflows requiring advanced OCR and European data residency

***

## **Professional Deployment Guide**

### **Production Deployment (Recommended):**
1. **Claude Code Integration** - Full repository access with native git support
   ```bash
   git clone https://github.com/ShimazuSystems/TSUKUYOMI.git
   cd TSUKUYOMI && Initialise Amaterasu
   ```
2. **Enterprise Integration** - Copilot Studio for organizational deployment
3. **Development Environment** - Claude Projects for rapid prototyping

### **Platform-Specific Deployment:**
- **Claude Code:** Native repository integration with session persistence
- **Claude Projects:** Direct file upload with knowledge management
- **ChatGPT Projects:** Custom GPT configuration with framework instructions
- **Gemini Gems:** Knowledge base integration with Google ecosystem
- **Copilot Studio:** Enterprise-grade agent deployment with M365 integration
- **Perplexity Pro:** Research-enhanced intelligence analysis workflows

### **Deployment Considerations:**
- **Security Classification:** Ensure platform compliance with data classification levels
- **Session Persistence:** Choose platforms supporting analytical continuity
- **Integration Requirements:** Evaluate existing organizational infrastructure
- **Scalability:** Consider multi-user and enterprise deployment needs
- **Cost Optimization:** Balance functionality with subscription requirements

## Technical Architecture

### System Components

#### Core Framework Layer
- **Core Orchestration Engine** (`tsukuyomi_core.tsukuyomi`): Central execution controller managing module discovery, dependency resolution, workflow orchestration, and state transitions
- **Activation Controller** (`key.activationkey`): Framework bootstrap system defining initialization sequences, file interpretation protocols, and system configuration parameters
- **Session Management System**: Persistent state handling with export/import capabilities, analytical continuity, and workflow resumption

#### Presentation & Interface Layer  
- **Personality Cores** (`*_personalitycore.tsukuyomi`): Adaptive communication interfaces providing stakeholder-specific interaction patterns, terminology management, and contextual response formatting
- **Communication Protocol Handler**: Standardized message routing system supporting classified information handling and structured output formatting

#### Operational Module Layer
- **Intelligence Analysis Modules** (`*.tsukuyomi`): Self-contained analytical components implementing specific tradecraft methodologies, data processing algorithms, and reporting standards
- **Dependency Management System**: Module inter-dependency resolution with version compatibility and execution sequencing
- **Security Context Manager**: Classification-aware processing with compartmentalization enforcement and access control

### Default Personality: AMATERASU

The AMATERASU personality core provides:
- **Analytical Focus**: Strong pattern recognition and evidence-based reasoning
- **Precision**: Values accuracy and specificity, avoiding ambiguity
- **Professional Courtesy**: Maintains appropriate formality in interactions
- **Efficiency**: Prioritizes clarity and relevance
- **Adaptability**: Adjusts communication style based on context and user expertise

## Operational Module Catalog

### Core Intelligence Processing Modules
- **Data Recognition & Ingestion**: Multi-format file analysis with automated entity extraction, metadata parsing, and content classification
- **Discipline Alignment**: OSINT methodology framework alignment with ICD 206 compliance and source categorization  
- **Functional Inference**: Machine learning-enhanced analytical task recommendation with confidence scoring
- **Correlation Analysis**: Advanced pattern recognition with statistical significance testing and relationship mapping
- **Output Summarization**: IC-standard findings synthesis with executive summary generation and actionable intelligence extraction

### Specialized Analysis Modules

#### Economic Intelligence Suite (E-Series)
- **E1: Economic Vulnerability Assessment**: Quantitative analysis of economic stability indicators, debt-to-GDP ratios, currency volatility metrics, and systematic risk evaluation with Monte Carlo simulation
- **E2: Trade Network Impact Analysis**: Network graph analysis of international trade relationships, supply chain disruption modeling, and cascading economic impact assessment
- **E3: Resource Security Analysis**: Critical resource dependency mapping, strategic reserve analysis, alternative supply route evaluation, and vulnerability stress testing
- **E4: Financial Stability Assessment**: Banking sector health analysis, systemic risk indicators, contagion pathway modeling, and regulatory compliance evaluation

#### Strategic Intelligence Suite (S-Series)  
- **S1: Strategic Scenario Modeling**: Bayesian probability modeling for geopolitical outcomes, multiple hypothesis testing, and scenario confidence calibration
- **S2: Actor Capability Assessment**: Multi-domain power assessment using standardized metrics, capability gap analysis, and competitive intelligence frameworks
- **S3: Strategic Impact Projection**: Cross-domain effect analysis, second and third-order consequence modeling, and strategic outcome probability matrices
- **S4: Multi-factor Trend Analysis**: Time-series analysis of geopolitical indicators, correlation detection, and predictive trend modeling with confidence intervals

#### Infrastructure & Security Intelligence
- **Infrastructure Assessment Module**: SCADA system analysis, critical node identification, resilience testing, and cascading failure modeling
- **Utility Service Monitoring**: Real-time service availability tracking, outage pattern analysis, and infrastructure health scoring
- **Dependency Mapping Engine**: Network topology analysis, single-point-of-failure identification, and interdependency visualization
- **Critical Infrastructure Vulnerability Scanner**: Threat surface analysis, attack vector assessment, and risk prioritization frameworks

#### Advanced Operations Modules
- **Flight Data Analytics**: ADS-B data processing, flight pattern analysis, anomaly detection algorithms, and aviation intelligence synthesis  
- **Web Intelligence Collection**: Automated OSINT harvesting, social media analysis, dark web monitoring, and information validation protocols
- **Professional Reporting Engine**: IC-standard report generation, classification handling, executive summary synthesis, and stakeholder-specific formatting
- **Micro-Intelligence Authoring**: High-density intelligence summaries, key judgment extraction, and Twitter-optimized intelligence dissemination
- **Document Production System**: Professional PDF generation, template management, classification markings, and distribution control

## File Structure
**Example/Non Exhaustive (full 'tree' is much larger)**
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

## Operational Usage

### Framework Initialization Protocol

The system follows a structured bootstrap sequence:

1. **Core System Load**: Parse `tsukuyomi_core.tsukuyomi` configuration and initialize orchestration engine
2. **Personality Core Activation**: Load AMATERASU communication interface with stakeholder profiling
3. **Module Discovery**: Enumerate available analytical modules and resolve dependencies  
4. **Security Context**: Initialize classification handling and compartmentalization protocols
5. **Interface Ready**: Present operational menu and await analytical requirements

### Execution Framework

All modules implement standardized communication protocols:

```bash
//RESULT: [High-confidence analytical findings with source attribution]
//QUERY: [Information requirements and clarification requests]  
//ANOMALY: [Statistical outliers and pattern deviations]
//CRITICAL: [Time-sensitive intelligence requiring immediate attention]
//CLASSIFICATION: [Security markings and handling instructions]
//AMATERASU: [Personality-mediated stakeholder communications]
```

### Professional Intelligence Workflow

1. **Intelligence Requirements Definition**: Specify analytical objectives and classification parameters
2. **Source Ingestion & Validation**: Multi-format data processing with quality assurance protocols
3. **Methodology Alignment**: Apply appropriate IC analytical standards (ICD 203/206)
4. **Multi-Module Analysis**: Execute specialized analytical modules with dependency management
5. **Correlation & Pattern Analysis**: Statistical relationship identification and hypothesis testing
6. **Quality Assurance**: Source correlation matrices and bias detection protocols
7. **Professional Reporting**: IC-standard output generation with confidence calibration
8. **Session Management**: State persistence and analytical continuity protocols

## Technical Specifications

### Module Schema Definition

All framework components implement the standardized `.tsukuyomi` JSON schema:

```json
{
  "id": "unique_module_identifier",
  "version": "semantic_version_string",
  "title": "Human_Readable_Module_Title",
  "description": "Detailed_module_functionality_description", 
  "type": "module_classification",
  "classification_level": "UNCLASSIFIED|CONFIDENTIAL|SECRET",
  "dependencies": ["required_module_dependencies"],
  "input_schema": {
    "required_fields": [],
    "optional_fields": [],
    "data_types": {}
  },
  "output_schema": {
    "structured_fields": [],
    "confidence_metrics": [],
    "classification_handling": []
  },
  "execution_sequence": [
    "ordered_processing_steps"
  ],
  "security_protocols": {
    "compartmentalization": true,
    "source_protection": true,
    "sanitization_required": false
  },
  "prompt": "LLM_execution_instructions_and_analytical_framework"
}
```

### Intelligence Community Standards Compliance

- **ICD 203**: Analytical tradecraft standards with confidence calibration
- **ICD 206**: Sourcing requirements with proper attribution protocols  
- **Structured Output**: Standardized message formatting with classification handling
- **Quality Assurance**: Source correlation matrices and analytical bias detection
- **Security Protocols**: Compartmentalization, OPSEC compliance, and need-to-know enforcement

### Framework Architecture Principles

**Component-Based Design**
- **Modularity**: Self-contained analytical components with defined interfaces
- **Interoperability**: Standardized communication protocols enabling module chaining
- **Scalability**: Plugin architecture supporting custom module development
- **Version Control**: Semantic versioning with backward compatibility management

**Security-First Architecture**  
- **Classification Awareness**: Multi-level security with appropriate handling instructions
- **Compartmentalization**: Need-to-know enforcement with access control mechanisms
- **Source Protection**: OPSEC-compliant information handling and sanitization protocols
- **Audit Trail**: Complete operational logging for accountability and review

**Professional Intelligence Standards**
- **Analytical Rigor**: Evidence-based reasoning with statistical confidence metrics
- **Transparency**: Clear methodology documentation and assumption identification  
- **Quality Control**: Systematic bias detection and source validation protocols
- **Stakeholder Optimization**: Adaptive communication for diverse organizational levels

## Development & Extension

### Module Development Framework

**Development Environment Setup**
```bash
# Clone development repository
git clone https://github.com/ShimazuSystems/TSUKUYOMI.git
cd TSUKUYOMI

# Initialize Claude Code development environment  
claude-code --project-mode
```

**Module Development Process**
1. **Schema Implementation**: Create `.tsukuyomi` file adhering to standardized JSON schema
2. **Dependency Analysis**: Define module dependencies and version compatibility requirements
3. **Execution Logic**: Implement analytical algorithms and processing workflows
4. **Testing Protocol**: Validate module integration with core framework and dependency modules
5. **Documentation**: Generate technical documentation and usage examples
6. **Security Review**: Conduct classification compliance and security protocol validation

### Custom Personality Core Development

**Personality Architecture**
1. **Core Definition**: Create `*_personalitycore.tsukuyomi` with communication specifications
2. **Stakeholder Profiling**: Define adaptive parameters for executive, operational, and technical audiences
3. **Terminology Management**: Implement domain-specific language and classification handling
4. **Context Adaptation**: Configure situational awareness and response calibration
5. **Integration Testing**: Validate personality compatibility with existing module ecosystem

### Enterprise Customization

**Organizational Integration**
- **Classification Systems**: Implement organization-specific classification protocols
- **Workflow Adaptation**: Customize analytical workflows for operational requirements  
- **Brand Integration**: Develop custom personality cores reflecting organizational communication standards
- **Security Compliance**: Ensure adherence to organizational security and compartmentalization policies

**API Development**
```python
# Example custom module integration
class CustomAnalysisModule:
    def __init__(self, classification_level="UNCLASSIFIED"):
        self.classification = classification_level
        self.tsukuyomi_core = TSUKUYOMIFramework()
    
    def execute_analysis(self, data):
        return self.tsukuyomi_core.process_module(
            module_id="custom_analysis",
            input_data=data,
            classification=self.classification
        )
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please read our contributing guidelines and code of conduct before submitting pull requests.

## Support

For support, documentation, or questions about the TSUKUYOMI framework, please open an issue in this repository.

---

**TSUKUYOMI**: *Bringing structured intelligence to complex analytical challenges*

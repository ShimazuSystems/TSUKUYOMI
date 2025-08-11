# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## System Architecture

TSUKUYOMI is an intelligent modular framework for structured analysis and processing, designed for professional intelligence operations. The architecture follows a component-based design with three main layers:

### Core Components
- **tsukuyomi_core.tsukuyomi**: Central orchestration system managing module loading, execution, and workflow transitions
- **key.activationkey**: Framework initialization instructions defining file interpretation rules and activation sequences
- **personality/amaterasu_personalitycore.tsukuyomi**: Communication and interaction management system with stakeholder optimization
- **modules/**: Directory containing specialized operational modules (*.tsukuyomi files)

### File Format
All framework components use `.tsukuyomi` extension containing JSON-like structures. These files are:
- Text files with JSON syntax and custom schema
- Modular prompt engineering components
- Self-contained but interoperable modules
- Processed sequentially during activation

### Framework Operation
The system follows a specific initialization sequence:
1. Load and parse tsukuyomi_core.tsukuyomi
2. Extract configuration parameters (module_path, personality_path)
3. Load AMATERASU personality core
4. Initialize core functions and context management
5. Present greeting and await user input or module selection

## Module System

### Module Types
- **Core Intelligence Modules**: Data recognition, correlation analysis, discipline alignment
- **Economic Analysis (E-Series)**: E1-E4 modules for economic vulnerability and trade analysis
- **Strategic Analysis (S-Series)**: S1-S4 modules for geopolitical scenario modeling and capability assessment
- **Infrastructure & Security**: Critical infrastructure vulnerability and dependency mapping
- **Specialized Operations**: Flight data analysis, OSINT collection, comprehensive reporting
- **Source Quality & Bias Analysis**: Source correlation matrix, bias detection, AI hallucination detection
- **Session Management**: Session export/import modules for analytical continuity

### Module Architecture
Each module contains:
- Standard schema with id, version, title, type, dependencies
- Input requirements and output schema definitions
- Execution sequences with specific actions and conditions
- Error handling and security protocols
- IC-compliant analytical frameworks

## Communication Protocols

The framework uses standardized message prefixes:
- `//AMATERASU:` - System communications
- `//TSUKUYOMI:` - Framework operations  
- `//RESULT:` - Analytical findings
- `//QUERY:` - Clarification requests
- `//ANOMALY:` - Unusual patterns
- `//CRITICAL:` - Urgent information
- `//CLASSIFICATION:` - Security markings
- `//SELECTION:` - Menu option selections

## Framework Activation

### Splash Screen Interface

TSUKUYOMI includes an interactive splash screen that displays upon initialization (when `enable_splash_screen: true` in core configuration). The splash screen presents a compact menu with checkbox-style options (☐) for different operational modes:

1. Standard Analysis Mode - General analytical operations
2. Intelligence Operations Mode - Professional intelligence ops with security
3. Economic Analysis Suite - Economic vulnerability & trade analysis
4. Strategic Analysis Suite - Scenario modeling & capability assessment  
5. Infrastructure & Security Analysis - Critical infrastructure assessment
6. Specialized Operations - OSINT, flight data, custom reporting
6a. Source Quality & Bias Analysis - Source correlation matrix & bias detection
7. Module Browser - View all available modules
8. System Configuration - Configure security & operational parameters
9. Session Management - Export/import session snapshots for continuity

### Activation Methods

**Interactive Menu (with splash screen enabled):**
```
Initialise Amaterasu
```
System responds with menu and: `//AMATERASU: Welcome to TSUKUYOMI. Please select from the options above or provide your analytical requirements directly.`

**Direct Activation:**
```
Initialize TSUKUYOMI for intelligence operations, classification level [UNCLASSIFIED/CONFIDENTIAL/SECRET]
```

**Menu Selection:**
Users can select by number (1-9) or provide analysis requests directly, bypassing the menu.

**Return to Menu:**
Users can return to the main menu at any time by typing:
```
menu
```
System responds: `//AMATERASU: Returning to main menu. Please select from the options below.`

### Configuration Options
- `enable_splash_screen: true/false` - Toggle splash screen display
- `compact_display: true/false` - Use compact formatting
- `menu_return_command: true` - Enable menu return capability
- Menu can be disabled for direct operational use

## Security Considerations

The framework implements comprehensive security protocols:
- Classification-aware processing (UNCLASSIFIED through TOP SECRET)
- Handling instructions (NOFORN, REL TO, EYES ONLY, etc.)
- Source protection and OPSEC compliance
- Compartmentalization and need-to-know enforcement
- IC-standard analytical tradecraft (ICD 203, ICD 206)

## Stakeholder Optimization

AMATERASU personality core adapts communication for:
- **Executive Level**: High-level summaries, strategic implications
- **Operational Commanders**: Mission-focused, actionable intelligence
- **Intelligence Analysts**: Technical depth, methodology transparency
- **Field Operators**: Concise, security-aware communications
- **International Partners**: Cultural sensitivity, legal compliance

## Working with the Framework

When making changes to this repository:
- Preserve the modular architecture and JSON schema compliance
- Maintain security protocols and classification handling
- Follow the established execution sequences and error handling patterns
- Ensure personality core compatibility for new modules
- Test module integration with the core orchestration system
- Ensure system is a 'prompt' framework that can be 'loaded' into LLM's & AI systems, not an 'executable' script

## Session Management

TSUKUYOMI includes comprehensive session management capabilities through dedicated modules that enable analytical continuity across LLM chat interfaces.

### Session Export Module
- **Comprehensive State Capture**: Exports complete operational context, workflow state, analytical findings, and continuation guidance
- **Security-Aware Processing**: Applies appropriate classification handling, sanitization protocols, and source protection
- **JSON Format**: Generates well-structured JSON files that are both human-readable and machine-parseable
- **Flexible Export Options**: Standard exports, sanitized exports for sharing, or findings-only exports

### Session Import Module  
- **Complete Restoration**: Reconstructs full operational context and analytical state from JSON snapshots
- **Validation Framework**: Comprehensive validation of import data for format compliance, security requirements, and data integrity
- **Seamless Continuation**: Enables immediate resumption of analytical operations at the exact point of previous export
- **Security Compliance**: Maintains strict adherence to classification and compartmentalization requirements

### Usage Examples
```
Export current session
Import session from [JSON_DATA]
Export session with sanitization for sharing
```

### Session File Structure
Session exports contain:
- **Metadata**: Session ID, timestamps, framework version
- **Security Context**: Classification levels, handling instructions, compartments
- **Operational State**: Current mode, stakeholder profile, priority level
- **Workflow Context**: Active modules, execution history, completion status
- **Analytical Memory**: Strategic/operational/tactical/technical context
- **Findings Repository**: Confirmed findings, hypotheses, information gaps
- **Continuation Guidance**: Recommended next steps and module suggestions

## Source Quality & Bias Analysis

TSUKUYOMI includes advanced source correlation and bias detection capabilities specifically designed to address challenges in AI-enhanced intelligence operations, including LLM hallucinations and bias propagation.

### Source Correlation Matrix Module
- **Relationship Mapping**: Automatically identifies direct and indirect relationships between intelligence sources
- **Independence Assessment**: Calculates source independence scores and identifies potential echo chambers
- **Network Analysis**: Maps source networks using clustering coefficients, centrality measures, and community detection
- **Bias Detection**: Identifies confirmation bias, cherry-picking, and overconfidence patterns
- **Visual Analytics**: Generates color-coded correlation matrices with bias warning indicators

### AI Hallucination Detection
- **Consistency Checking**: Cross-references AI-generated content for internal consistency and factual accuracy
- **Source Attribution Analysis**: Verifies that attributed sources actually exist and quotes are accurate
- **LLM Artifact Detection**: Identifies characteristic AI language patterns and inappropriate certainty markers
- **Plausibility Assessment**: Evaluates logical coherence and appropriate detail granularity

### Source Quality Monitoring
- **Real-Time Assessment**: Continuously monitors source quality across accuracy, timeliness, and completeness metrics
- **Trend Analysis**: Identifies quality degradation patterns and improvement trends over time
- **Alert System**: Provides prioritized alerts for critical quality issues and emerging bias patterns
- **Predictive Analysis**: Uses statistical methods to predict potential source quality issues

### Key Features for AI-Enhanced Operations
- **Web Search Integration**: Special handling for web-sourced intelligence with enhanced verification
- **LLM Output Validation**: Systematic validation of LLM-generated analysis and research
- **Circular Reference Detection**: Identifies when sources cite each other creating false validation
- **Information Laundering Prevention**: Prevents same information being counted as multiple independent sources

### Usage Examples
```
Generate source correlation matrix for current analysis
Check for confirmation bias in source selection  
Verify AI-generated content for hallucinations
Monitor source quality degradation over time
Assess source independence for high-confidence analysis
```

### Quality Assurance Benefits
- **Analytical Rigor**: Maintains IC-standard analytical tradecraft in AI-enhanced environments
- **Bias Mitigation**: Proactive identification and correction of analytical bias
- **Confidence Calibration**: Proper adjustment of analytical confidence based on source quality
- **Transparency**: Clear documentation of source relationships and quality assessments

The framework is designed for professional intelligence operations with emphasis on analytical rigor, operational security, and stakeholder optimization while maintaining modularity for capability expansion.

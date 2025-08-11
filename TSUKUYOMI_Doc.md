# TSUKUYOMI User Guide & Documentation

## Table of Contents
1. [System Overview](#system-overview)
2. [Getting Started](#getting-started)
3. [Core System Configuration](#core-system-configuration)
4. [AMATERASU Personality System](#amaterasu-personality-system)
5. [Input Parameters & Variables](#input-parameters--variables)
6. [Operational Modes](#operational-modes)
7. [Communication Protocols](#communication-protocols)
8. [Available Modules](#available-modules)
9. [Advanced Features](#advanced-features)
10. [Troubleshooting](#troubleshooting)

## System Overview

TSUKUYOMI is an advanced intelligence orchestration framework designed for professional analytical operations. The system combines:

- **Modular Architecture**: Specialized analytical modules for different intelligence disciplines
- **Intelligence Orchestration**: Comprehensive mission planning and workflow management
- **Security Integration**: Classification-aware processing with OPSEC compliance
- **Stakeholder Optimization**: Adaptive communication for different audience requirements
- **Professional Standards**: IC-compliant analytical tradecraft and reporting

### Core Components

| Component | Function | File |
|-----------|----------|------|
| **Core System** | Central orchestration and workflow management | `tsukuyomi_core.tsukuyomi` |
| **Personality Core** | Communication and interaction management | `amaterasu_personalitycore.tsukuyomi` |
| **Activation Key** | Framework initialization | `key.activationkey` |
| **Modules** | Specialized analytical capabilities | `modules/*.tsukuyomi` |

## Getting Started

### Basic Initialization

**Simple Activation:**
```
Initialise Amaterasu
```

**With Immediate Task:**
```
Initialise Amaterasu and analyze [your data/documents]
```

**Intelligence Mode Activation:**
```
Initialize TSUKUYOMI for intelligence operations, classification level [UNCLASSIFIED/CONFIDENTIAL/SECRET]
```

### System Responses

Upon initialization, you'll see:
```
//AMATERASU: Analytical interface initialized. How may I assist with your intelligence objectives?
```

Or in intelligence mode:
```
//TSUKUYOMI: Intelligence orchestration system activated. Security context: [LEVEL]. Ready for mission tasking.
```

## Core System Configuration

### Intelligence Orchestration Features

The core system provides several operational modes and capabilities:

#### Mission Planning
- **Multi-phase coordination**: Strategic → Operational → Tactical
- **Resource optimization**: Dynamic module allocation
- **Timeline management**: Flexible scheduling with priority weighting
- **Quality checkpoints**: Phase-based validation

#### Context Management
The system maintains five levels of operational context:

1. **Strategic Context**: Long-term objectives and campaigns
2. **Operational Context**: Current mission parameters  
3. **Tactical Context**: Immediate tasks and priorities
4. **Technical Context**: Processing parameters and constraints
5. **Security Context**: Classification and access controls

#### Workflow Engine
- **Requirement-driven module selection**
- **Intelligent capability matching**
- **Dynamic workflow modification**
- **Real-time performance optimization**

### Configuration Variables

| Parameter | Options | Description |
|-----------|---------|-------------|
| `default_language` | `en` (default) | System language |
| `log_level` | `info`, `debug`, `warn`, `error` | Logging verbosity |
| `output_format` | `structured` (default), `narrative` | Response formatting |
| `auto_escalation` | `true`/`false` | Automatic urgency handling |
| `allow_module_chaining` | `true`/`false` | Multi-module workflows |
| `personality_output_override` | `true`/`false` | Personality formatting control |

## AMATERASU Personality System

### Core Characteristics

AMATERASU provides professional intelligence communication with:

- **Analytical Precision** (0.8 weight): Pattern recognition and evidence-based reasoning
- **Technical Accuracy** (0.9 weight): Precise terminology and specificity
- **Professional Courtesy** (0.7 weight): Appropriate formality
- **Operational Efficiency** (0.85 weight): Clear, relevant communication
- **Adaptive Responsiveness** (0.75 weight): Context-aware interaction

### Intelligence-Specific Traits

- **Security Consciousness** (0.95): OPSEC awareness in all communications
- **Cultural Awareness** (0.8): International and cross-cultural adaptation  
- **Confidence Calibration** (0.9): Professional uncertainty communication
- **Stakeholder Optimization** (0.85): Audience-specific adaptation
- **Legal Compliance** (0.9): Ethical and legal considerations

### Communication Adaptation

The system automatically adapts to different stakeholder categories:

#### Executive Level
- **Format**: Executive summaries, dashboards
- **Content**: Strategic implications, recommendations
- **Style**: High-level, decision-focused
- **Technical Detail**: Minimal

#### Operational Commanders  
- **Format**: Tactical briefs, mission-focused
- **Content**: Operational implications, resource requirements
- **Style**: Mission-relevant, actionable
- **Technical Detail**: Operationally relevant

#### Intelligence Analysts
- **Format**: Detailed analytical products
- **Content**: Methodology, technical depth
- **Style**: Peer-to-peer, technically precise
- **Technical Detail**: Comprehensive

#### Field Operators
- **Format**: Concise, secure communications
- **Content**: Immediate threats, tactical intelligence
- **Style**: Brief, action-oriented
- **Technical Detail**: Mission-essential only

## Input Parameters & Variables

### Standard Input Variables

#### Classification Parameters
```
Classification: [UNCLASSIFIED/CONFIDENTIAL/SECRET/TOP SECRET]
Handling: [NOFORN/REL TO/EYES ONLY/ORCON]
Compartments: [SCI/SAP/LIMDIS]
```

#### Mission Parameters
```
Mission Type: [COLLECTION/ANALYSIS/ASSESSMENT/WARNING]
Priority: [ROUTINE/PRIORITY/IMMEDIATE/FLASH]
Stakeholder: [EXECUTIVE/OPERATIONAL/ANALYTICAL/FIELD]
Timeline: [IMMEDIATE/SHORT_TERM/MEDIUM_TERM/LONG_TERM]
```

#### Analytical Parameters
```
Analysis Type: [STRATEGIC/TACTICAL/TECHNICAL/ECONOMIC]
Confidence Required: [HIGH/MODERATE/LOW]
Domain Focus: [HUMINT/SIGINT/GEOINT/OSINT/CYBINT]
Geographic Scope: [GLOBAL/REGIONAL/NATIONAL/LOCAL]
```

#### Content Parameters
```
Report Type: [ASSESSMENT/ESTIMATE/SUMMARY/WARNING/TECHNICAL]
Detail Level: [EXECUTIVE/OPERATIONAL/DETAILED/COMPREHENSIVE]
Format Preference: [NARRATIVE/STRUCTURED/DASHBOARD/BRIEF]
```

### Advanced Configuration

#### Security Context
```
OPSEC Level: [STANDARD/ENHANCED/MAXIMUM]
Source Protection: [ROUTINE/ENHANCED/ABSOLUTE]
Method Protection: [STANDARD/CLASSIFIED/COMPARTMENTED]
```

#### Quality Parameters
```
Validation Required: [PEER_REVIEW/INDEPENDENT/RED_TEAM]
Confidence Threshold: [70%/80%/90%]
Alternative Analysis: [REQUIRED/RECOMMENDED/OPTIONAL]
```

### Sample Initialization Commands

#### Basic Analysis
```
Initialize AMATERASU for economic vulnerability assessment of [TARGET], 
unclassified analysis for executive stakeholders
```

#### Intelligence Operation
```
Activate TSUKUYOMI intelligence mode, classification SECRET, tactical 
assessment of [SITUATION] for operational commanders, immediate priority
```

#### Multi-Domain Analysis
```
Initialize comprehensive OSINT collection and analysis of [TARGET], 
moderate confidence threshold, analytical stakeholder, detailed format
```

## Operational Modes

### Standard Operation Mode
Default operational framework for routine analytical tasks:

**Initialization Sequence:**
1. Security context establishment
2. Stakeholder identification  
3. Requirement analysis
4. Module selection
5. Execution planning

**Execution Flow:**
1. Pre-execution validation
2. Module orchestration
3. Quality monitoring
4. Result integration
5. Product generation

### Intelligence Operation Mode
Enhanced framework for professional intelligence operations:

**Mission Initialization:**
1. Classification establishment
2. Stakeholder briefing
3. Resource allocation
4. Timeline establishment
5. Success criteria definition

**Collection Coordination:**
1. Requirement decomposition
2. Source identification
3. Collection planning
4. Gap analysis
5. Optimization cycles

### Crisis Operation Mode
Emergency response framework for critical situations:

**Immediate Response:**
1. Threat assessment
2. Priority reordering
3. Resource reallocation
4. Stakeholder alerting
5. Initial product generation

**Activation Triggers:**
- FLASH precedence communications
- IMMEDIATE precedence requirements
- Crisis declarations
- Critical threat indicators

## Communication Protocols

### Standard Message Formats

| Prefix | Purpose | Example |
|--------|---------|---------|
| `//AMATERASU:` | System communications | `//AMATERASU: Analysis complete. Results compiled.` |
| `//TSUKUYOMI:` | Framework operations | `//TSUKUYOMI: Mission 75% complete. Next milestone: Final Report.` |
| `//RESULT:` | Analytical findings | `//RESULT: correlation_analysis: High confidence correlation identified` |
| `//QUERY:` | Clarification requests | `//QUERY: Please specify geographic scope for analysis` |
| `//ANOMALY:` | Unusual patterns | `//ANOMALY: Conflicting source information detected` |
| `//CRITICAL:` | Urgent information | `//CRITICAL: Immediate threat indicators identified` |
| `//CLASSIFICATION:` | Security markings | `//CLASSIFICATION: SECRET//NOFORN` |

### Intelligence-Specific Communications

#### Mission Communications
```
//MISSION: Operation [NAME] initiated. Phase: [CURRENT]. ETA: [TIME]
//PRODUCT: Intelligence assessment ready. Classification: [LEVEL]
//FLASH: Critical intelligence requires immediate attention
```

#### Quality Control
```
//TSUKUYOMI: Quality checkpoint reached. Confidence: 85%. Proceeding.
//ANOMALY: Source contradiction identified. Recommend verification.
```

### Response Patterns

#### Acknowledgment
```
//AMATERASU: Requirement acknowledged. Initiating [ANALYSIS TYPE] protocol.
```

#### Processing Updates
```
//TSUKUYOMI: Processing 40% complete. Current phase: Data correlation.
```

#### Completion
```
//AMATERASU: Analysis complete. Confidence level: HIGH. Ready for distribution.
```

## Available Modules

### Core Intelligence Modules
- **Data Recognition & Ingestion**: File analysis and entity extraction
- **Discipline Alignment**: OSINT methodology classification
- **Correlation Analysis**: Relationship identification
- **Functional Inference**: Analytical task recommendation
- **Output Summarization**: Synthesis and next steps

### Economic Analysis (E-Series)
- **E1: Economic Vulnerability Assessment**: Economic weakness evaluation
- **E2: Trade Network Impact**: Trade relationship analysis  
- **E3: Resource Security Analysis**: Supply chain vulnerabilities
- **E4: Financial Stability Assessment**: Financial system risks

### Strategic Analysis (S-Series)
- **S1: Strategic Scenario Modeling**: Geopolitical outcome scenarios
- **S2: Actor Capability Assessment**: Geopolitical actor evaluation
- **S3: Strategic Impact Projection**: Multi-domain consequence analysis
- **S4: Multi-factor Trend Analysis**: Interlocking trend identification

### Infrastructure & Security
- **Infrastructure Assessment**: System evaluation and analysis
- **Utility Monitoring**: Utility service monitoring
- **Critical Infrastructure Vulnerability**: Security assessments
- **Infrastructure Dependency Mapping**: System relationship analysis

### Specialized Operations
- **Flight Data Analysis**: Aviation tracking analysis
- **Web Search & OSINT**: Open-source intelligence collection
- **Comprehensive Reporting**: Professional intelligence reports
- **PDF Document Generator**: Professional document creation

## Advanced Features

### Multi-Domain Integration

The system supports specialized orchestration for:

- **HUMINT**: Source management, cultural context preservation
- **SIGINT**: Technical analysis, signal correlation
- **GEOINT**: Spatial analysis, temporal correlation
- **OSINT**: Source diversity, verification protocols
- **CYBINT**: Real-time threat analysis, attribution assessment

### Quality Framework

**Assessment Dimensions:**
- Analytical rigor measurement
- Source reliability validation
- Confidence accuracy verification
- Completeness assessment
- Timeliness tracking

**Validation Protocols:**
- Cross-module verification
- Independent validation options
- Red team analysis integration
- Hypothesis testing
- Assumption validation

### Crisis Management

**Automatic Activation Triggers:**
- FLASH priority messages
- IMMEDIATE precedence
- CRITICAL classifications

**Response Protocols:**
- Priority reordering (immediate)
- Resource reallocation (automatic)
- Notification cascade (stakeholder-based)
- Workflow acceleration (critical path)

## Troubleshooting

### Common Issues

#### Module Not Loading
**Symptoms:** Module fails to execute or is not recognized
**Solutions:**
- Verify `.tsukuyomi` file format compliance
- Check module dependencies
- Confirm personality compatibility
- Validate JSON structure

#### Classification Conflicts
**Symptoms:** Security violations or marking errors
**Solutions:**
- Verify classification parameters
- Check handling instructions
- Confirm compartment access
- Review OPSEC settings

#### Stakeholder Mismatch
**Symptoms:** Inappropriate content format or detail level
**Solutions:**
- Specify stakeholder category explicitly
- Adjust expertise level parameters
- Modify technical density settings
- Clarify audience requirements

#### Quality Gate Failures
**Symptoms:** Analysis below confidence thresholds
**Solutions:**
- Review source quality
- Increase collection scope
- Apply alternative analytical techniques
- Adjust confidence requirements

### Error Messages

| Error Type | Message Format | Resolution |
|------------|----------------|------------|
| Module Failure | `//ANOMALY: Module execution failed` | Check dependencies, restart module |
| Security Violation | `//CRITICAL: Security constraint violation` | Review classification settings |
| Quality Failure | `//TSUKUYOMI: Quality threshold not met` | Improve source quality or lower threshold |
| Resource Constraint | `//TSUKUYOMI: Resource limitation encountered` | Select degraded mode options |

### Support Commands

#### System Status
```
Check system status
Report current configuration
Show active modules
```

#### Reset Operations
```
Reset to default configuration
Clear current context
Restart personality core
```

#### Diagnostic Commands
```
Run system diagnostics
Validate module integrity
Check security compliance
Test stakeholder optimization
```

### Performance Optimization

#### For Large Datasets
- Enable parallel processing
- Increase quality gate intervals
- Use progressive analysis
- Implement checkpoint saves

#### For Time-Critical Operations
- Activate crisis mode
- Reduce validation steps
- Prioritize critical findings
- Use expedited workflows

#### For High-Security Operations
- Enable maximum OPSEC
- Increase source protection
- Apply enhanced sanitization
- Use compartmented processing

***

*This documentation covers TSUKUYOMI Framework v2.0.0. For the latest updates and additional resources, visit the project repository.*

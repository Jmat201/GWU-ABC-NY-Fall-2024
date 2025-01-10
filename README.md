# SAR Generator using Gen-AI

A sophisticated system for automatically generating Suspicious Activity Reports (SARs) using Generative AI, developed for the Agricultural Bank of China (ABC) New York Branch to enhance their compliance operations.

## Project Overview

This project addresses the critical challenge of automating Suspicious Activity Report generation through locally-hosted Generative AI models. The solution transforms a labor-intensive process that previously took between 2 hours to 2 days into a streamlined 30-minute operation, while achieving a substantial cost reduction from $75 to $20 per report.

### Business Context
- **Client**: Agricultural Bank of China (ABC), New York Branch
- **Challenge**: Manual SAR creation process requiring 2-16 hours per report
- **Previous Issues**: Cloud-based AI systems raising data privacy concerns
- **Implementation Timeline**: Completed December 2024

### Key Achievements
- 70% reduction in operational costs
- Enhanced data privacy through local deployment
- Improved compliance efficiency
- Client satisfaction scores up to 9/10

## Technical Architecture

### 1. Database Implementation
#### PostgreSQL Setup
- Vector search capability through pgvector
- Optimized schema design for:
  - Customer profiles
  - Account management
  - Transaction tracking
  - Alert systems
  - SAR narratives

#### Security Configuration
1. **TLS Encryption**
   - Encrypted database connections
   - Regular certificate updates
   - Secure data transit protocols

2. **Access Control**
   - Role-based authentication
   - Strong password policies
   - Periodic credential rotation

3. **Audit Systems**
   - Comprehensive activity logging
   - Automated alerts for suspicious actions
   - Full accountability tracking

### 2. AI Technology Stack

#### Large Language Models (LLMs)
1. **Supported Models**
   - Llama 3.2-3B (Local deployment)
   - Mistral NeMo 12B (Google Colab Pro)
   - Danube 3-4B (Fallback option)

2. **Model Selection Criteria**
   - Parameter size (3-15B range)
   - Resource requirements
   - Performance metrics
   - Reasoning capabilities

#### Embedding Models
- Vector representation implementation
- Semantic relationship mapping
- Integration with RAG systems

#### Retrieval-Augmented Generation (RAG)
1. **Components**
   - Data retrieval system
   - Embedding model integration
   - Vector storage
   - Generation pipeline

2. **Benefits**
   - Enhanced accuracy
   - Regulatory compliance
   - Contextual depth
   - Efficient processing

## Implementation Approaches

### Approach 1: Template-Based Generation

#### Process Flow
1. **Data Collection**
   - PostgreSQL database queries
   - Alert narrative processing
   - Document parsing

2. **Document Structure**
   - Introduction (static)
   - Transaction details (dynamic)
   - KYC and research findings (dynamic)
   - SAR recommendations (dynamic)
   - Conclusion (static)

3. **Technologies Used**
   - Mistral Nemo LLM
   - Sentence transformers
   - Zero-shot learning
   - RAG implementation

#### Performance Metrics
- Execution time: 6-10 minutes
- Client satisfaction: 9/10
- Accuracy rating: High
- Resource utilization: Optimized

### Approach 2: Structured Narrative Generation

#### Components
1. **Data Processing**
   - PDF guideline integration
   - PostgreSQL transaction data
   - Embedding model implementation
   - Re-ranking system

2. **Generation Process**
   - Zero-shot techniques
   - Chain-of-thought prompting
   - Structured output formatting
   - Quality validation

#### Output Sections
- Introduction
- Customer Information
- Patterns
- Violations
- Conclusion

## Risk Management

### Data Privacy Considerations
1. **Training Data Risks**
   - PII protection measures
   - Data sanitization
   - Access controls

2. **User Interaction Security**
   - Secure logging practices
   - Cache management
   - Access restriction

3. **Storage Protection**
   - Encryption protocols
   - Authorization systems
   - Audit mechanisms

### Model Limitations
1. **Hallucination Prevention**
   - Structured prompting
   - Validation pipelines
   - Quality checks

2. **Information Completeness**
   - Comprehensive data gathering
   - Cross-validation
   - Accuracy verification

## Business Value Proposition

### Cost Analysis
- Processing 10,000 SARs:
  - Previous cost: $370,000 - $5,920,000
  - New cost: Significantly reduced
  - ROI: Substantial positive impact

### Operational Benefits
- Reduced manual workload
- Improved accuracy
- Enhanced compliance
- Faster processing

## Future Recommendations

### Technical Enhancements
1. **Computing Infrastructure**
   - Utilize GWU's High Performance Computing
   - Test 70B parameter models
   - Optimize resource allocation

2. **Model Optimization**
   - Fine-tune query parameters
   - Enhance embedding configurations
   - Improve prompt engineering

3. **Evaluation Framework**
   - Implement automated metrics
   - Enhance quality assessment
   - Develop benchmarking system

## Installation and Setup

*Note: Detailed installation instructions and setup procedures are available in the project documentation.*


### Model Performance
Performance metrics for the implemented models are sourced from the original research:

Mistral NeMo: Achieved 9/10 satisfaction score for comprehensive rule coverage (p.27)
LLaMA model: Exceptional performance on cash structuring rules (p.27)
Danube model: Effective for specific branch requirements (p.27)

Note: Page numbers reference the original research document. For full methodology and implementation details, please refer to the complete research paper.

## Authors and Contributors

### Development Team
- Jeff
- Mohanad
- Nour
- Chao

*Project completed: December 5, 2024*


## References

For detailed technical specifications and implementation details, please refer to the project documentation.

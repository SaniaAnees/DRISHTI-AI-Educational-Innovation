# DRISHTI.AI - Industrial Behavioral Intelligence Engine.
# Drishti.AI Requirements Specification

## Project Overview
Drishti AI is an "Agency-First" behavioral intervention engine designed to bridge the "Digital Intelligence Divide" for Tier-2/3 Indian engineering students. The system transforms users from Low Agency (excuses, passive consumption, certification-seeking) to High Agency (ownership, active shipping, skill-mastery) using AWS-native Generative AI.

## Core Philosophy
**Agency-First Architecture**: The system must move users from passive consumers to active builders through intelligent behavioral interventions and personalized learning paths.

## Priority Features: Industrial Innovation

### 1. Truth-Engine (Quality over Popularity)

#### User Stories
- **As a student**, I want to receive high-signal resources instead of SEO-optimized content, so I can learn from industry-grade materials
- **As a learner**, I want the system to verify my actual progress through code analysis, not just completion clicks
- **As a user**, I want access to "hidden gems" from engineering blogs and niche repositories that aren't in mainstream courses

#### Acceptance Criteria
- System SHALL bypass generic courses and identify foundational logic of skills
- System SHALL use semantic sweep to find Netflix-style engineering blogs over tutorial content
- System SHALL implement commit mechanism - roadmaps become persistent only after user commitment
- System SHALL verify progress through GitHub analysis, not self-reporting
- System SHALL maintain knowledge base of "hidden gems" for instant retrieval

#### Technical Requirements
- Deep Research Agent using AWS Lambda + Tavily/Exa API
- Knowledge Base using Amazon OpenSearch (Serverless) for vector storage
- Code Verification via AWS Lambda + GitHub API
- Reasoning Engine using Amazon Bedrock (Claude 3.5)

### 2. Predictive Digital Twin (2030 Mirror)

#### User Stories
- **As a student**, I want to see my projected career trajectory based on current behaviors, so I understand the long-term impact of my choices
- **As a learner**, I want to visualize both failure and success scenarios to motivate behavioral change
- **As a user**, I want realistic LinkedIn profiles showing my potential future based on current agency score

#### Acceptance Criteria
- System SHALL generate two versions: Failed Self (stagnant profile) and Staff Engineer (high-agency outcome)
- System SHALL use last 30 days of agency score and roadmap progress for predictions
- System SHALL create realistic LinkedIn profiles with bio, experience, and certifications
- System SHALL use "Strict Mentor" tone to explain the gap between versions
- System SHALL trigger predictions based on AQI thresholds (< 400 = Version A, > 800 = Version B)

#### Technical Requirements
- Trajectory Modeling using Amazon SageMaker with regression models
- Profile Generation using Amazon Bedrock for realistic LinkedIn simulation
- Data Feed from Amazon DynamoDB for user behavior analysis
- Visual Delivery via Next.js + Tailwind for tangible future visualization

### 3. Ghost HR Agent (Reverse-Engineering Success)

#### User Stories
- **As a student**, I want to understand the skill gap between my profile and engineers at target companies
- **As a learner**, I want automated roadmap updates when industry requirements change
- **As a user**, I want to shadow successful engineers to identify invisible skills not taught in college

#### Acceptance Criteria
- System SHALL identify 5-10 benchmark engineers from target companies
- System SHALL generate comparative gap graph showing skill radar differences
- System SHALL automatically inject gap-filler modules into active roadmaps
- System SHALL detect emerging tech stacks before they become mainstream
- System SHALL provide "Nuclear Twist" warnings about job-market latency

#### Technical Requirements
- Headless Scraper using AWS Lambda + Playwright for LinkedIn data
- Agentic Reasoning using Amazon Bedrock for skill distillation
- Gap Visualization using Amazon QuickSight for radar charts
- Roadmap Sync via Amazon DynamoDB for automatic updates

## Secondary Features

### 4. Hype-Filter Auditor
- Document parsing via Amazon Textract for course analysis
- Trend scraping for active hiring requirements
- ROI reasoning with "Strict Mentor" assessment
- Audit logs for every evaluation result

### 5. Multi-Track Pivot Logic
- Knowledge Graph using Amazon Neptune for skill relationships
- Cross-track logic mapping for transferable skills
- Multi-track persistence with context-aware storage
- Real-time progress via AWS AppSync GraphQL

### 6. Vernacular Bridge
- Bilingual mastery flow with regional language support
- Cultural context preservation while maintaining technical accuracy
- Logic bridge analogies using local references
- Immutable syntax rule for industry readiness

### 7. Agency Leaderboard
- Real-time ranking using Amazon ElastiCache (Redis)
- Dynamic cohorts (National, Track-Specific, Institutional)
- Semantic benchmarking with actionable insights
- Percentile-based motivation system

### 8. Behavioral Nudge System
- Morning Slap: 15-minute critical path challenges at 9 AM IST
- Year-Decay Clock: Real-time percentage of year elapsed
- Nightly Audit: Proactive notifications for inactivity
- Opportunity cost calculations for missed days

## Non-Functional Requirements

### Performance
- Sub-millisecond leaderboard responses using Redis Sorted Sets
- Real-time progress updates via WebSockets
- Serverless architecture for automatic scaling

### Security
- Multi-provider authentication (Google Social, Email/OTP)
- AWS Secrets Manager for API key management
- Amazon QLDB for immutable transaction records
- Post-confirmation triggers for secure profile creation

### Reliability
- Event-driven architecture using Amazon EventBridge
- Fault-tolerant design with AWS Step Functions
- Automated backup and recovery procedures

### Scalability
- Single-table DynamoDB design for efficient queries
- Microservices architecture using AWS Lambda
- Auto-scaling based on user load

## Success Metrics
- Agency Quotient Index (AQI) improvement over time
- Roadmap completion rates with verification
- Skill transfer accuracy in pivot scenarios
- User retention and engagement metrics
- Industry placement success rates

## Constraints
- Must use AWS-native services for all core functionality
- Regional language support required for Tier-2/3 accessibility
- Mobile-first design for student accessibility
- Cost-effective architecture suitable for Indian market pricing
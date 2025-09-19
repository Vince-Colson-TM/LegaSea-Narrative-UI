# Project Plan – Narrative UI for Fossil Data Collection

## 1. Context and Background

### The LegaSea Project
This research is part of the LegaSea project, a collaborative initiative coordinated by Naturalis Biodiversity Center in partnership with Utrecht University and Fontys ICT. The LegaSea project aims to reconstruct Dutch Ice Age biomes through an AI-assisted citizen science approach, focusing on late-Quaternary vertebrate fossils (130,000 years ago to present) found in the North Sea Basin.

### Scientific Context
The North Sea Basin contains a treasure trove of paleontological and archaeological material. Over the past 150 years, hundreds of thousands of late-Quaternary vertebrate fossils and artifacts have been collected from fishing nets and sand-nourished beaches by fossil enthusiasts. These fossils originate from sediment extracted from the seafloor and "rainbowed" onto Dutch beaches during coastal nourishment projects.

### Current Data Collection Infrastructure
**Existing Platform:** The oervondstchecker.nl citizen science platform currently enables fossil enthusiasts to contribute data by uploading pictures and metadata of their fossil discoveries. Over the past 10 years, this platform has accumulated over 75,000 citizen science images.

- **Current Workflow:**
  - Citizens upload fossil images and metadata through static web forms
  - Records are manually classified by volunteer experts
  - Validated data is preprocessed as training data for AI computer vision models
  - A prototype AI identification system is available at museum.identify.biodiversityanalysis.nl

**Established Datasets:** The project builds upon substantial existing data including:
- Over 47,000 standardized images from museum collections (Naturalis Biodiversity Center, Natural History Museum Rotterdam, Museum of Antiquities Leiden)
- Over 75,000 validated citizen science images from the oervondstchecker.nl platform
- Comprehensive taxonomic classifications and expert validations

### Current System Limitations
- **Process Inefficiencies:**
  - Static, slow manual classification workflow
  - No mobile interactive solution for field identification
  - Form-based inputs limiting data richness and consistency
  - Limited real-time guidance during data collection

- **Data Quality Challenges:**
  - Inconsistent metadata entry due to varying user expertise levels
  - No contextual guidance for capturing research-grade images
  - Limited integration between data collection and AI identification systems
  - No adaptive interface accommodating different user knowledge levels

- **User Experience Gaps:**
  - No real-time AI feedback during image capture and metadata collection
  - Complex scientific terminology creating barriers for non-experts
  - Limited engagement and educational value during submission process
  - Lack of interactive tools for fossil hunting guidance and community consultation

### Research Focus: Narrative-Based User Interfaces
This research specifically investigates narrative-based user interfaces as an alternative to traditional form-based data collection. Unlike existing platforms that rely on static image uploads and generic forms, narrative UIs can have the following advantages:

- **Conversational Data Collection:**
  - Chat-like interactions that guide users through metadata entry
  - Natural language processing to parse responses into structured data
  - Adaptive questioning strategies based on user expertise and context
  - Real-time clarification and educational support during data entry

- **Enhanced User Engagement:**
  - Story-driven conversational flows that make data collection more engaging
  - Integration with community consultation features
  - Interactive guidance for fossil hunting locations and techniques
  - Educational content delivery through conversational interactions

- **AI-Powered Guidance Integration:**
  - Dynamic validation and suggestions during metadata entry
  - Contextual AI assistance that adapts to user knowledge level
  - Transparent communication of AI confidence and decision-making processes

## 2. Problem Statement

### Current System Limitations
The current fossil data collection process on the oervondstchecker.nl platform, while successful in accumulating over 75,000 citizen science images over 10 years, faces significant challenges that limit its effectiveness for scientific research and user engagement.

### Key Challenges

- **Data Collection Process Issues:**
  The current system is static, slow, and limited by inconsistent data quality and form-based inputs. Citizens upload fossil images and metadata through traditional web forms, after which records must be manually classified by volunteer experts before being preprocessed as training data for AI models.

- **Technical and User Experience Gaps:**
  - No mobile interactive solution exists to support fossil identification in the field, limiting real-time data collection during fossil discovery
  - Static forms constrain the richness and consistency of collected data
  - The current workflow separates data collection from AI-powered identification, missing opportunities for real-time feedback and guidance
  - Users receive no contextual assistance during the submission process

- **Impact on Research Objectives:**
  These limitations directly affect the LegaSea project's core scientific goals:
  - **Data Quality:** Inconsistent metadata entry reduces the quality of training data needed for accurate AI fossil identification models
  - **User Engagement:** Traditional form-based interfaces limit broader public participation in citizen science
  - **Research Efficiency:** Manual classification workflows create processing delays that slow scientific discovery
  - **Field Application:** Lack of mobile-optimized, real-time guidance tools limits the platform's utility for active fossil hunters

### The Research Opportunity
Current citizen science platforms rely primarily on static image uploads and generic forms for post-upload processing. However, there is significant potential to transform this approach by integrating AI capabilities directly into the data collection process itself.

This research addresses the gap between traditional form-based data collection and the potential for AI-powered, real-time guidance systems. By investigating narrative-based user interfaces, we can explore how conversational, chat-like interactions might:
- Improve data quality through guided, contextual metadata collection
- Increase user engagement through more natural, educational interactions
- Build trust in AI systems through transparent, interactive identification processes
- Enable real-time consultation and community knowledge sharing

The fundamental question is whether moving from static forms to dynamic, conversational interfaces can simultaneously address the data quality, user engagement, and trust challenges facing current citizen science fossil collection platforms.

## 3. Research Question

### Main Research Question
How can a narrative-based user interface enhance user engagement, data completeness, and trust in AI-powered fossil identification?

### Possible Research Sub-Questions

- **User Engagement**
  - How does conversational interaction design affect user motivation and willingness to participate in fossil data collection compared to traditional forms?
  - How does the perceived enjoyment and educational value of the data collection process differ between narrative and form-based interfaces?

- **Data Completeness and Quality**
  - To what extent does guided, conversational metadata collection improve the completeness of submitted fossil records?
  - How does real-time validation and clarification through narrative UI affect the accuracy of user-provided metadata?

- **Trust in AI Systems**
  - How does transparent, conversational communication of AI confidence and decision-making processes affect user trust?
  - What level of AI explanation and interaction is optimal for building user confidence in automated fossil identification?

- **Usability and Accessibility**
  - How do users with different levels of fossil expertise (novice to expert) experience and navigate narrative-based data collection?
  - What are the optimal conversation patterns, language styles and tones for accommodating diverse user types?

### Research Scope and Focus
This research specifically investigates narrative UI implementation within the context of citizen science fossil data collection, focusing on chat-like, conversational interfaces that can adapt to user expertise levels and provide contextual guidance throughout the data submission process. The study will examine both quantitative metrics (completion rates, accuracy, time-on-task) and qualitative factors (user satisfaction, perceived trust, learning outcomes) to comprehensively evaluate the effectiveness of narrative-based approaches.

## 4. Applied Methods

### Research Design
This study employs a mixed-methods approach combining literature review, prototype development, comparative user testing, and quantitative/qualitative analysis to investigate the effectiveness of narrative-based user interfaces for fossil data collection.

### 1. Literature Study
**Objective:** Establish theoretical foundation and identify best practices for narrative UI design in citizen science contexts.

- **Approach:**
  - Systematic review of sources on conversational UI design, narrative interfaces, and human-computer interaction
  - Analysis of existing research on citizen science platforms and user engagement strategies
  - Investigation of trust-building mechanisms in AI-powered identification systems
  - Review of metadata collection methodologies and data quality assessment techniques

**Deliverable:** Comprehensive and structured background research documentation.

### 2. Prototype Development
**Objective:** Create testable implementations comparing traditional form-based interfaces with different approaches to narrative-based data collection.

- **Prototype Design Strategy:**
  Given the complexity of simulating authentic conversational AI interactions, this research will develop functional web-based prototypes rather than static Figma mockups to ensure realistic user testing conditions.

- **Three-Prototype Approach:**
  - **Prototype A (Baseline):** Traditional form-based interface replicating current oervondstchecker.nl functionality
  - **Prototype B (Basic Conversational):** Simple chat-like interface with straightforward question-answer patterns for metadata collection
  - **Prototype C (Narrative-Enhanced):** Advanced conversational interface incorporating storytelling elements, personalization, and contextual guidance

- **Development Approach:**
  - **AI Integration:** Real-time AI API integration (e.g., OpenAI GPT-4, Claude, or similar) with custom prompting for fossil data collection contexts
  - **AI Configuration:** Domain-specific system prompts trained on fossil terminology, metadata requirements, and conversational patterns appropriate for different user expertise levels
  - **Development Rationale:** Functional prototypes with real AI enable authentic conversational interactions, natural language processing, and adaptive responses that closely mirror production-quality narrative interfaces

- **Prototype Features:**
  - Metadata collection workflows (varying by prototype type)
  - AI-powered conversational interactions with structured data extraction
  - Responsive design optimized for mobile and desktop use
  - Comprehensive interaction logging for analysis

- **Prototype B Specifications (Basic Conversational):**
  - AI-powered chat interface with direct, functional prompting
  - Systematic metadata collection through conversational questions
  - Real-time validation and clarification requests
  - Standard conversational UI patterns with AI natural language processing

- **Prototype C Specifications (Narrative-Enhanced):**
  - Advanced AI prompting incorporating storytelling and contextual awareness
  - Personalized conversational flows adapted to user type (age, expertise,...)
  - Educational content delivery through natural AI responses
  - Dynamic questioning strategies with intelligent follow-up and clarification

**Deliverable:** Three functional web-based prototypes enabling comprehensive comparative user testing across different conversational interface approaches.

### 3. User Testing
**Objective:** Evaluate user engagement, data completeness, and trust across different interface approaches.

- **Participants:**
  - Target groups: Fossil enthusiasts, citizen scientists, and students
  - Recruitment: Through fossil collecting communities, educational institutions, and Naturalis networks

- **Testing Protocol:**
  - **Within-subjects design:** Each participant uses all three prototypes with randomized order to control for learning effects
  - **Task scenarios:** Standardized fossil submission tasks with varying complexity levels
  - **Session structure:**
    1. Pre-test questionnaire (experience, expectations)
    2. Prototype interaction sessions (screen recording + think-aloud protocol)
    3. Post-test questionnaires and interviews
    4. Comparative preference assessment

- **Data Collection Methods:**
  - **Quantitative Metrics:**
    - Task completion rates and accuracy
    - Time on task and interaction efficiency
    - Metadata completeness scores
    - System Usability Scale ratings
    - Trust in AI questionnaire
  - **Qualitative Data:**
    - Semi-structured post-test interviews
    - Comparative preference explanations
    - Suggestions for improvement

### 4. Data Analysis
**Objective:** Systematically evaluate the effectiveness of narrative UI across research dimensions.

- **Quantitative Analysis:**
  - **Statistics:** Calculate averages, percentages, and counts for all measurements (completion rates, time spent, accuracy scores)
  - **Comparisons:** Use statistical tests to compare the three prototypes and see which performs better
  - **Effect Size:** Measure how big the differences are between prototypes
  - **Relationships:** Look for connections between different factors (e.g., does user experience level affect completion rates?)

- **Qualitative Analysis:**
  - **User Feedback Review:** Read through user comments and suggestions to identify common themes
  - **Behavior Patterns:** Look for patterns in how different types of users (beginners vs. experts) interact with the system
  - **Common Issues:** Identify recurring problems or positive aspects mentioned by users

- **Comparative Analysis:**
  - **Three-Way Comparison:** Directly compare all three prototypes on key measurements
  - **User Type Analysis:** See which prototype works best for different types of users
  - **Trade-off Assessment:** Understand the balance between making the interface more conversational and keeping it easy to use
  - **Incremental Benefits:** Determine if the advanced narrative features provide meaningful improvements over basic chat


### Ethical Considerations
- Informed consent procedures for all participants
- Data anonymization and secure storage protocols
- Voluntary participation with right to withdraw
- Transparent communication about research purposes and data use


## 5. Stakeholder Overview

### Stakeholder Roles and Interests

- **Primary Stakeholders:**
  - **Naturalis Biodiversity Center** - Isaak Eijkelboom: Project sponsor and domain expertise provider
  - **Project Coaches** - Georgiana Manolache & Gerard Schouten: Project coaching
  - **Study coaches** - Luuk Derkx & Wouter Boendermaker: Academic oversight and coaching

- **Secondary Stakeholders:**
  - **Research Team:** Integration dependencies for other LegaSea project components
  - **Citizen Scientists:** User testing participants and long-term platform adopters

### Stakeholder Engagement Strategy
- **Regular Progress Updates:** Weekly status reports to research team, study coaches and project coaches. Monthly updates to project sponsor.
- **Prototype Review Sessions:** Stakeholder feedback collection during prototype development phases
- **User Testing Coordination:** Collaboration with Naturalis networks for participant recruitment
- **Research Validation:** Expert research review sessions with study and project coaches

### Stakeholder Power-Interest Grid

![Stakeholder Power-Interest Matrix](mermaid-images/stakeholder-matrix.png)

## 6. Planning (indicative)

| Phase | Period | Activities | Deliverables |
|-------|--------|------------|--------------|
| **Phase 1: Background research** | Week 1–10 | Systematic review of relevant sources | Comprehensive background research documentation |
| **Phase 2: Prototype Development** | Week 10–18 | Design & develop three functional prototypes | Three functional prototypes with comprehensive logging capabilities |
| **Phase 3: User Testing Preparation** | Week 18–20 | Recruit participants from fossil collecting communities, prepare testing scenarios and standardized tasks | Test plan, participant recruitment, and testing materials |
| **Phase 4: User Testing Execution** | Week 20–24 | Conduct user testing with all three prototypes | Complete user testing data including quantitative metrics and qualitative feedback |
| **Phase 5: Data Analysis** | Week 24–28 | Statistical analysis of quantitative data, thematic analysis of qualitative feedback, three-way prototype comparison, and incremental benefit assessment | Comprehensive analysis report with statistical findings and qualitative insights |
| **Phase 6: Research Documentation** | Week 28–36 | Write research paper and make research poster | Final research paper and research poster |
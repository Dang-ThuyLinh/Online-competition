**Indonesian Robothon Competition (IRC) 2025 - Round 1 Online Quiz Framework**

**Version:** 1.5 (Approved)
**Date:** February 22, 2025

**Revision History:**

| Version | Date        | Author (Role)      | Description of Changes                                                                                                                                                                                                                                                                                                                                               |
| :------ | :---------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1.0     | Oct 26, 2023 | [Your Name]     | Initial Approved Version                                                                                                                                                                                                                                                                                                                                         |
| 1.1     | Feb 22, 2025  | L (Lead Editor)   | Revised Section: **Section 5, Question Types and Rationale**: Removed partial credit scoring for Multiple-choice (Multiple) questions. Revised Section: **Section 7, scoring and filtering rules**: Modified question type weightage, Removed partial credit scoring, Removed per-question time limits, Added Programming Questions. Revised Section: **Section 8, Platform Requirement**: Updated to reflect confirmed platform capabilities (no partial credit, no per-question time limits, but with Randomisation), Section **3. Target Audience and Quiz Structure** and combined, added new content.Added **Section 9. Question Bank Development Process and Deliverables**. Removed Section 10 : Next step. |
| 1.2     | Feb 22, 2025  | L (Lead Editor)    | Revised Section 3.2 and 3.4 to reflect increased question totals per age group, clarified Common vs. Unique question bank structure, added question distribution per Focus Area within Unique question banks, confirmed Coding questions for all groups, removed "Time Limit" column from Section 5, and kept Scoring and Filtering rules unchanged, include course information|
| 1.3     | Feb 22, 2025  | L (Lead Editor)    | Re-instated partial credit for Multiple Choice (Multiple) in Section 5. Added Cocreate Competency Points and PISA Scores sections to Section 6 (formerly 7). Updated scoring examples in Section 6. Updated Question Type Weight in Section 10.3.                                                                                                                                                   |
| 1.4     | Feb 22, 2025  | L (Lead Editor)    | Re-instated partial credit for Multiple Choice(Multiple). Added a new subsection (6.6) within Section 6: Scoring and filtering rules.	|
| 1.5     | Feb 22, 2025  | L (Lead Editor)   | Update the tie-breaker rule.|

**1. Introduction**

This document outlines the complete and approved framework for the Round 1 online quiz of the Indonesian Robothon Competition (IRC) 2025. The quiz is designed to assess K-12 students' knowledge and skills in Artificial Intelligence (AI), Internet of Things (IoT), Robotics, Computational Thinking, and Logical Reasoning. This framework serves as the single source of truth for all aspects of the quiz, including objectives, target audience, competencies, question types, scoring, filtering, platform requirements, and question bank development. The quiz also is used to evaluate students after they have finished the courses created.

**2. Objectives**

*   **Assessment:** Evaluate students' understanding and application of key concepts in AI, IoT, Robotics, Computational Thinking, and Logical Reasoning.
*   **Filtering:** Identify the top 20% of participants (approximately 10,000 out of 50,000, proportionally across age groups) to advance to Round 2.
*   **Competency-Based Evaluation:** Measure students' abilities against clearly defined competencies and sub-competencies.
*   **Fairness and Validity:** Ensure the quiz is fair, unbiased, and accurately reflects students' abilities.
*   **Platform Compatibility:** Operate within the confirmed capabilities of the Pcontest platform.

**3. Target Audience and Quiz Structure**

**3.1 Target Audience**

K-12 students in Indonesia, divided into four age groups:

*   Group A: 6-9 years old
*   Group B: 10-12 years old
*   Group C: 13-15 years old
*   Group D: 16-18 years old

**3.2 Quiz Structure**

The Round 1 online quiz will consist of two main question banks:

1.  **Common Base Question Bank:** Contains questions that are general and fundamental, suitable for *all* age groups. These questions focus on core concepts in:
    *   Robotics Basics
    *   IoT Basics
    *   AI Ethics
    *   AI Fundamentals

    This bank will contain *more than* 10 questions (likely 15-20).  Each age group's quiz will *randomly select* 10 questions from this bank.  A maximum of 20% overlap (2 questions) is allowed between any two age groups' selections from this common bank.

2.  **Unique Question Banks:** Four separate question banks, one for each age group (A, B, C, D). These questions are tailored to the specific age group and cover a wider range of topics, with increasing complexity.

**3.3 Question Breakdown and Time Limits**

The following table summarizes the question breakdown and time limits for each age group:

| Age Group | Total Questions | Common Base Questions (Selected from Common Bank) | Unique Questions | Total Time Limit (minutes) | Focus Areas                                                                                                                                                                       |
| :-------- | :-------------- | :---------------------------------------------- | :--------------- | :------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| A (6-9)   | 25              | 10                                              | 15               | 20                        | Computational Thinking, Basic Robotics, AI Ethics, AI Fundamentals, IoT Basics                                                                                        |
| B (10-12) | 30              | 10                                              | 20               | 25                        | Programming Logic, IoT Basics, AI Fundamentals, AI Applications, Computational Thinking                                                                           |
| C (13-15) | 40              | 10                                              | 30               | 35                        | Advanced Robotics, AI Applications in Data Science, Predictive AI, Computational Thinking, IoT Applications, Basic programming logic                                    |
| D (16-18) | 40              | 10                                              | 30               | 40                        | Complex Coding, IoT Integration, AI Automation, Advanced AI Ethics, Advanced Robotics, AI applications in Data Science, Predictive AI, Computational Thinking |

*Note:* Programming questions are included *within* the Unique Questions for *all* age groups, though the complexity will increase with age.

**3.4 Unique Question Bank: Focus Area Breakdown and Scoring**

This section provides a *suggested* breakdown of questions per Focus Area within each age group's *Unique Question Bank*. The point values assigned to each Focus Area reflect a combination of the number of questions and the assumed difficulty/importance of the topic for that age group. This breakdown is a *guideline* and can be adjusted during the question development phase, but the *total* number of Unique Questions for each group must be maintained.

| Age Group | Focus Area                                 | Suggested # of Questions | Question Types (Examples)                     | Points per Question (Example) | Total Points (Example) |
| :-------- | :----------------------------------------- | :----------------------- | :-------------------------------------------- | :--------------------------: | :--------------------: |
| **A (6-9)** | Computational Thinking                     | 5                       | True/False, Multiple Choice, Drag-and-Drop   |              2              |          10          |
|           | Basic Robotics                             | 5                       | True/False, Multiple Choice, Matching        |              2              |          10          |
|           | AI Fundamentals & Ethics                    | 4                       | True/False, Multiple Choice                  |             2               |          8          |
|           | IoT Basics                                   | 0                      |                                               |              -              |            0            |
|           | Coding (very basic)                          | 1                       | Fill-in-the-Blank, Drag-and-Drop (sequencing) |              2              |             2          |
|          | **Total Unique Questions**                  |      **15**                   |          |              |    **30**     |

| Age Group | Focus Area                               | Suggested # of Questions | Question Types (Examples)                    | Points per Question (Example) | Total Points (Example) |
| :-------- | :--------------------------------------- | :----------------------- | :------------------------------------------- | :--------------------------: | :--------------------: |
| **B (10-12)** | Computational Thinking                     | 5                       | Multiple Choice, Drag-and-Drop, Matching   |              2              |          10          |
|           | Basic IoT (Applications & Sensors)         | 5                       | Multiple Choice, Fill-in-the-Blank           |           2              |          10          |
|           | AI Fundamentals & Applications             | 5                    | True/False, Multiple Choice, Matching       |              2              |          10          |
|           | Programming Logic (Pseudocode/Blockly) | 5                      | Multiple Choice, Fill-in-the-Blank, Drag-and-Drop |            2                |          10          |
|           | **Total Unique Questions**                 |    **20**                |          |               |          **40**     |

| Age Group | Focus Area                            | Suggested # of Questions | Question Types (Examples)                                            | Points per Question (Example) | Total Points (Example) |
| :-------- | :------------------------------------ | :----------------------- | :------------------------------------------------------------------- | :--------------------------: | :--------------------: |
| **C (13-15)** | Advanced Robotics                    | 7                        | Multiple Choice, Drag-and-Drop, Matching, Fill-in-the-Blank     |             2              |          14          |
|           | AI Applications in Data Science       | 7                        | Multiple Choice, Fill-in-the-Blank, Matching                     |              2              |          14          |
|           | Predictive AI                         | 6                        | Multiple Choice, Fill-in-the-Blank                               |           2            |          12          |
|           | Computational Thinking                 | 5                        | Multiple Choice, Drag-and-Drop, Matching                           |             2              |          10          |
           | Basic Programming Logic               | 5                       |  Multiple Choice, Fill-in-the-Blank                                   |        2                  |           10          |
|          | **Total Unique Questions**              |  **30**             |              |            |      **60**            |

| Age Group | Focus Area                                 | Suggested # of Questions | Question Types (Examples)                                                                       | Points per Question (Example) | Total Points (Example) |
| :-------- | :----------------------------------------- | :----------------------- | :-------------------------------------------------------------------------------------------------- | :--------------------------: | :--------------------: |
| **D (16-18)** | Complex Coding                           | 8                        | Multiple Choice, Fill-in-the-Blank, Drag-and-Drop (code blocks), Matching (code to output) |             2              |          16          |
|           | IoT Integration                            | 7                        | Multiple Choice, Fill-in-the-Blank, Matching, Drag-and-Drop                                 |              2              |          14         |
|           | Advanced AI Ethics                         | 5                        | Multiple Choice, Fill-in-the-Blank                                                              |              2              |          10          |
|           | Advanced Robotics/AI Applications         | 5                       | Multiple Choice, Fill-in-the-Blank, Matching, Drag-and-Drop,                                 |            2                |             10          |
          |Computational Thinking/Predictive AI           | 5                       | Multiple Choice, Fill-in-the-Blank                                                              |           2                |     10               |
|           | **Total Unique Questions**                 |       **30**              |                                          |       |    **60**          |

**3.5 Highly Selective Questions:**

Within each age group, 3-5 questions will be designed to be particularly challenging, requiring higher-order thinking skills (analysis, evaluation, creation). These questions will *not* be a separate question type but will be embedded within the standard question types (e.g., a complex multi-step reasoning problem presented as a multiple-choice question, a drag-and-drop question requiring a deep understanding of a process). These questions are crucial for differentiating the top performers.

**4. Competency Framework**

*(This section would include the *full*, detailed Competency Framework table, as presented in earlier drafts.  I am *not* repeating it here to save space, but it is a *crucial* part of the document.  It maps Competencies, Sub-Competencies, Definitions, Learning Outcomes, Examples of Observable Behaviors, PISA Domains, CoCreate Competencies, and SWRP.)*

**5. Question Types and Rationale**

This table explains why each question type is suitable for assessing specific competencies and sub-competencies within the IRC 2025 Round 1 quiz. It also indicates the primary cognitive level targeted by each question type, according to Bloom's Taxonomy (Remember, Understand, Apply, Analyze, Evaluate, Create).

| Question Type              | Rationale                                                                                                                                                                                                                                                             | Scoring                                                                                                     | Targeted Competencies and Sub-Competencies (Examples - Not Exhaustive)                                                                                                                                                                                                                           |
| :------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| True/False                 | Assesses basic factual knowledge and understanding of fundamental concepts. Efficient for covering a broad range of topics within a limited time. Can test understanding of definitions, principles, and simple relationships. Low cognitive load, suitable for younger age groups. | 1 point per question                                                                                     | - Computational Thinking: Algorithm Design (basic steps) - AI: AI Fundamentals (definitions) - IoT: IoT Fundamentals (basic components) - Robotics: Robotics Fundamentals (types of robots) - Logical Reasoning: Deductive Reasoning (basic rules) |
| Multiple Choice (Single)    | Assesses understanding of specific concepts and the ability to apply knowledge to choose the correct answer from a set of options. Requires more than simple recall; students must discriminate between similar options. Can be used to assess both lower-order and higher-order thinking skills. | 2 points per question                                                                                    | - Computational Thinking: Pattern Recognition, Abstraction - AI: AI Applications, Ethical Considerations in AI - IoT: IoT Applications, Data Collection and Analysis in IoT - Robotics: Robotics Applications, Robot Programming - Logical Reasoning: Inductive Reasoning, Problem Solving |
| Multiple Choice (Multiple) | Assesses deeper understanding and the ability to identify *multiple* correct answers, reflecting a more nuanced comprehension of the topic. Requires careful analysis and evaluation of all options.  Can be used to assess complex relationships and interdependencies.  Allows for partial credit, rewarding partial understanding. | Points per question depend on the number of choices and correct answers. Partial credit is awarded for each correct option selected. | - Computational Thinking: Decomposition, Algorithm Design - AI: AI Fundamentals, Ethical Considerations in AI - IoT: IoT Fundamentals, Data Collection and Analysis in IoT - Robotics: Robotics Fundamentals, Robot Programming - Logical Reasoning: Deductive Reasoning, Problem Solving |
| Drag-and-Drop             | Assesses understanding of processes, sequences, or relationships between concepts. Requires students to actively organize information and demonstrate their understanding of the order or connection of elements. Can be used to assess procedural knowledge and logical thinking. More engaging and interactive than traditional question types. | 4 points per question                                                                                    | - Computational Thinking: Algorithm Design, Decomposition - AI: AI Applications (process flow) - IoT: IoT Fundamentals (system setup), Data Collection and Analysis in IoT (data flow) - Robotics: Robot Programming (sequencing instructions), Robotics Fundamentals (component connections) |
| Matching                   | Assesses understanding of relationships between concepts, terms, definitions, or applications. Requires students to make connections and demonstrate their understanding of how different elements are related. Efficient for assessing knowledge of vocabulary and associations. | 4-5 points per question                                                                                | - Computational Thinking: Abstraction (matching concepts to examples) - AI: AI Fundamentals (matching terms to definitions), AI Applications (matching AI tools to tasks) - IoT: IoT Fundamentals (matching sensors to their functions) - Robotics: Robotics Fundamentals (matching robot types to applications) - Logical Reasoning: (matching logical fallacies to examples) |
| Fill-in-the-Blank          | Assesses recall of specific information, understanding of terminology, and ability to apply knowledge in a specific context. Requires students to generate the answer, rather than simply selecting it. Can be used to assess understanding of code syntax (pseudocode or simple code snippets), algorithms, or technical procedures. | 3 points per question                                                                                    | - Computational Thinking: Algorithm Design (filling in steps in an algorithm), Coding concepts - AI: AI Fundamentals (key terms), AI Applications (specific tools or techniques) - IoT: IoT Fundamentals (technical terms), Data Collection and Analysis in IoT (formulas) - Robotics: Robot Programming (code syntax), Robotics Fundamentals (technical specifications) |

**Key Considerations for Using this Table:**

*   **Balance:** Ensure a balanced distribution of question types across the quiz to assess the full range of competencies.
*   **Age Appropriateness:** Adapt the complexity of questions within each type to suit the target age group. Younger students should have simpler True/False and Multiple Choice questions, while older students can handle more complex scenarios and reasoning tasks.
*   **Cognitive Level:** Strive for a mix of cognitive levels. While foundational knowledge (Remember, Understand) is important, include questions that require Application, Analysis, and (for older students) Evaluation and Creation.
*   **Specificity:** When writing questions, refer back to the Competency Framework and this table to ensure each question is clearly aligned with a specific sub-competency and cognitive level.

**6. Scoring and Filtering**

**6.1 Scoring:**

*   True/False: 1 point per question
*   Multiple Choice (Single): 2 points per question
*   Multiple Choice (Multiple): Points will be assigned to each correct answer, with a clear indication in the question instructions. There will be no negative marking for incorrect options. The specific point distribution may vary depending on the complexity of the question and the number of correct answers.
*   Drag-and-Drop: 4 points per question
*   Matching: 4-5 points per question
*   Fill-in-the-Blank: 3 points per question

**6.2 No Negative Marking:** Incorrect answers will *not* result in a deduction of points.

**6.3 Total Score:** The total score for each student is the sum of the points earned across all questions.

**6.4. Cocreate Competency points**: Calculate competency points to understand students main competency gained and potential growth area. Key in competency mapping.
    * Introductory level: +1 point
    * Intermediate level: +2 points
    * Advanced level: +3 points
**6.5. PISA scores**: Calculate PISA scores measure students' performance in reading, mathematics and science literacy. Align PISA scoring methodology with international assessment standard.

**6.6 PISA-Aligned Performance Indicators**

*   **Purpose:** To provide an indication of student performance aligned with the internationally recognized PISA (Programme for International Student Assessment) frameworks for Reading, Mathematics, and Science literacy. This will allow for a broader understanding of student capabilities beyond the specific competition topics.

*   **Important Note:** This framework will *not* produce true PISA scaled scores. PISA uses a complex Item Response Theory (IRT) model that requires a large, representative dataset and specialized psychometric analysis. We will be calculating *performance indicators* that are *aligned* with the PISA domains and cognitive processes, but they are *not* directly comparable to official PISA scores.

*   **Methodology:**

    1.  **Question Tagging:** Each question in the question bank will be tagged with the following metadata:
        *   **Primary PISA Domain:** Reading, Mathematics, or Science. (While some questions may touch on multiple domains, a *primary* domain will be assigned based on the main focus of the question.)
        *   **PISA Content Sub-domain:**  The relevant content sub-domain within the primary PISA domain (e.g., within Mathematics: Space and Shape, Change and Relationships, Quantity, Uncertainty and Data.  Within Reading: Access and Retrieve, Integrate and Interpret, Reflect and Evaluate).  This will require consulting the official PISA framework documents.
        *   **PISA Cognitive Process:** The primary cognitive process assessed by the question (e.g., accessing information, interpreting information, applying knowledge, analyzing relationships, evaluating arguments). This will be determined based on the PISA framework definitions for each domain.
        *   **Difficulty Level:** Each question will be assigned a difficulty level:
            *   **Level 1 (Basic):**  Questions primarily requiring recall of facts, definitions, or simple procedures.
            *   **Level 2 (Intermediate):** Questions requiring application of knowledge to new situations, interpretation of information, or simple inferences.
            *   **Level 3 (Advanced):** Questions requiring higher-order thinking skills (analysis, evaluation, creation, synthesis), integration of multiple concepts, or complex reasoning.

        *Note:* The difficulty level is an *approximation* and will be adjusted based on the target age group. A Level 2 question for Group A will be easier than a Level 2 question for Group D.

    2.  **Score Calculation:** For each PISA domain (Reading, Mathematics, Science), a *weighted percentage correct* will be calculated for each student. This will take into account both the number of questions answered correctly and the *difficulty level* of those questions.

        *   **Example:**
            A student answers 10 questions tagged with the "Reading" PISA domain.
            *   Correct Answers:
                *   Level 1: 4 questions (4 * 1 point = 4 points)
                *   Level 2: 3 questions (3 * 2 points = 6 points)
                *   Level 3: 1 question (1 * 3 points = 3 points)
            *   Total Earned Points: 4 + 6 + 3 = 13 points
            *   Maximum Possible Points (if all questions were Level 3): 10 questions * 3 points/question = 30 points
            *   Weighted Percentage Correct: (13 / 30) * 100% = 43.3%

        This 43.3% is *not* a PISA score, but a *relative indicator* of performance within the Reading domain, weighted by difficulty.  Separate percentages will be calculated for Reading, Mathematics, and Science.

    3.  **Reporting:** The Pcontest platform must be able to:
        *   Track the PISA domain, sub-domain, and difficulty level for each question answered by each student.
        *   Calculate the weighted percentage correct for each PISA domain (Reading, Mathematics, Science) for each student.
        *   Report these percentages as *performance indicators* (e.g., "Reading Performance: 43.3%"), *not* as official PISA scores.

**6.7 Minimum Qualifying Scores:**

| Age Group | Total Possible Score (Example) | Minimum Qualifying Score | Rationale                                                                                                                                                                                                                                                                                                       |
| :-------- | :----------------------------- | :----------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 6–9       | 50                             | 35                       | This score represents 70% of the total possible score. It is set at a level that allows students with a solid grasp of fundamental concepts to advance, while still providing a meaningful filter.                                                                                                   |
| 10–12     | 60                             | 42                       | This score represents 70% of the total possible score. It reflects the increased complexity of the questions for this age group, while still being attainable for students who have demonstrated sufficient competency.                                                                                      |
| 13–15     | 80                             | 56                       | This score represents 70% of the total possible score. It acknowledges the more advanced content covered in this age group, requiring a higher level of understanding and application for qualification.                                                                                              |
| 16–18     | 80                             | 56                       | This score represents 70% of the total possible score. It reflects that this age group having the most complex concepts and require the student to demonstrate their understanding.                                                                                                                    |

**Rationale for 70% Threshold:** The 70% threshold is chosen as a balance between ensuring a sufficient level of competency and allowing a reasonable number of students to progress. It's a common benchmark used in many educational assessments. This threshold may be adjusted *after* pilot testing if the data suggests it's too high or too low.

**6.8 Ranking:**

*   **Primary Ranking:** By total score.
*   **Secondary Ranking:** By completion time (faster time = higher rank).

**6.9 Tie-Breaker Rules (applied in order):**

In the event of ties in the overall ranking (after considering total score and completion time), the following tie-breaker rules will be applied *in order*:

1.  **Higher Weighted Percentage Correct Across All Question Types:** Students with a higher *weighted percentage correct* across *all* questions, calculated as follows, will be ranked higher:

    *   Each correct answer to a question tagged as "Level 1 (Basic)" difficulty receives 1 point.
    *   Each correct answer to a question tagged as "Level 2 (Intermediate)" difficulty receives 2 points.
    *   Each correct answer to a question tagged as "Level 3 (Advanced)" difficulty receives 3 points.
    *   The total points earned are divided by the maximum possible points (if all questions were answered correctly at Level 3), and the result is multiplied by 100% to get the weighted percentage.

    This prioritizes accuracy *and* the ability to answer more challenging questions.

2.  **Higher Combined Cocreate Competency Points:** If a tie still exists after step 1, students with a higher total of Cocreate Competency points (earned across all correctly answered questions) will be ranked higher. This prioritizes students who have demonstrated mastery of more advanced competencies.

3.  **Higher Average PISA-Aligned Performance:** If a tie still exists after step 2, the average of the weighted percentage scores across the three PISA domains (Reading, Mathematics, Science) will be used. This provides a broader measure of cognitive skills, aligned with international standards.

4.  **Faster Completion Time (Last Resort):** If a tie remains after step 3, the faster completion time will be used.

5.  **Random Selection (Ultimate Tie-Breaker):** If a tie *still* remains after all the above steps, a random selection will be made by the platform.

**Rationale:** These tie-breaker rules are designed to be as fair as possible, prioritizing demonstrated understanding and competency over speed. They leverage all available data points (question difficulty, Cocreate Competency mapping, PISA alignment) before resorting to completion time or random selection.

**Implementation Note:** The Pcontest platform must be configured to track the necessary data (difficulty level, Cocreate Competency points per question/answer, PISA domain/sub-domain) and to calculate the weighted percentages and total Cocreate points.

**6.10 Selection for Round 2:** The top 20% of students in *each age group*, based on the final ranking, will advance to Round 2.

**7. Platform Requirements**

The Pcontest platform has been confirmed by Pythaverse to support all required functionalities, including:

*   All defined question types.
*   Configurable scoring weights.
*   Automated scoring, ranking, and tie-breaker application.
*   Randomization of questions from a larger pool.
*   Anti-cheating measures (tab-switch detection, copy-paste prevention, screen capture prevention).
*   Real-time leaderboard.
*   Comprehensive reporting capabilities (individual and overall performance data), including the reporting as described in 6.6
*   Scalability to handle 50,000+ concurrent users.
*   Data integration capabilities with PLearn.
*   Support for the Indonesian language (Bahasa Indonesia).
*   Time limit per quiz.

**8. Course context**

This quiz is designed after finishing 2 courses to prepare the students to be ready for the competition. There are 2 courses created for this competition purpose:

*   **AI & Coding Kickoff (Introductory):** Basic (Free), 6-7 hours
*   **AI & Blockly Coding Workshop:** Advanced (Paid), 8-9 hours

**9. Question Bank Development Process and Deliverables**

The development of the question bank will follow a multi-stage process, as outlined in Section 10 of this document. The key deliverables for this process are:

*   **Common Base Question Bank:** A set of questions (more than 10), suitable for all age groups, covering fundamental concepts in AI, IoT, and Robotics. (Format: Spreadsheet/Database)
*   **Unique Question Banks (x4):** Four separate question banks, one for each age group (A, B, C, D), containing age-specific questions. (Format: Spreadsheet/Database)
*   **Reviewed Question Banks:** Each question bank (Common and Unique) after undergoing self-review, peer review, and SME review.
*   **Final Approved Question Bank:** The complete, reviewed, and approved question bank, ready for import into the Pcontest platform.
*   **Question Bank in Platform-Compatible Format:** The question bank exported in CSV format.

These deliverables will be tracked using a shared project management tool, and all question writing and review will adhere to the guidelines specified in this framework document and the associated *Question Writing Guidelines* document.

**10. Question Bank Development Process**

1.  **Question Writing Guidelines:** Detailed guidelines will be developed, including a style guide, examples of good and bad questions for each type, instructions for mapping questions to competencies, and emphasis on avoiding bias.
2.  **Question Writer Training (if applicable):** If external question writers are used, they will be trained on the framework and guidelines.
3.  **Common Base Question Bank Development:** Create the common base questions.
4.  **Age-Specific Question Bank Development:** Create the age-specific questions for each group.
5.  **Multi-Stage Review Process:**
    *   **Peer Review:** Question writers will review each other's work.
    *   **SME Review:** Subject Matter Experts (SMEs) in AI, IoT, Robotics, Computational Thinking, and Logical Reasoning will review the questions for accuracy, relevance, and difficulty.
    *   **Final Review:** The core project team will conduct a final review to ensure consistency and quality.
6.  **Pilot Testing:** The quiz will be pilot tested with a representative sample of students from each age group.
7.  **Final Revisions:** Questions and platform settings will be adjusted based on pilot test feedback.

**Approvals**

____________________________     _______________________     ____________
Project Manager (W)               Date

____________________________     _______________________     ____________
Project Sponsor (Asaba)            Date

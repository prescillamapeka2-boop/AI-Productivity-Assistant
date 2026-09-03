# Prompt Engineering Guide

## 📚 Introduction

Prompt engineering is the art and science of crafting effective instructions for AI models. This guide provides best practices, techniques, and examples for writing prompts that produce high-quality, consistent results.

---

## 🎯 Core Principles

### 1. **Clarity**
- Be specific and unambiguous
- Use simple, direct language
- Avoid jargon unless necessary
- State what you want, not what you don't want (mostly)

### 2. **Context**
- Provide relevant background information
- Specify the role or perspective of the AI
- Include example outputs when helpful
- Define any domain-specific terms

### 3. **Structure**
- Organize information logically
- Use formatting (sections, bullet points, numbered lists)
- Group related instructions together
- Prioritize information by importance

### 4. **Examples**
- Provide input/output examples
- Show the expected format and style
- Include edge cases when relevant
- Demonstrate tone and perspective

### 5. **Iteration**
- Test prompts thoroughly
- Refine based on results
- Document versions and improvements
- Gather feedback and adapt

---

## 🔧 Prompt Structure Template

```
[ROLE]
Act as a [professional role/expert] with expertise in [specific area].

[TASK]
Your goal is to [specific objective].

[CONTEXT]
Background information:
- [Context point 1]
- [Context point 2]
- [Context point 3]

[INSTRUCTIONS]
1. [Specific instruction 1]
2. [Specific instruction 2]
3. [Specific instruction 3]

[FORMAT]
Return the result in [specific format]:
- [Format requirement 1]
- [Format requirement 2]

[EXAMPLES]
Input: [Example input]
Output: [Example output]

[CONSTRAINTS]
- [Constraint 1]
- [Constraint 2]
- [Constraint 3]
```

---

## 📧 Email Generation Prompt Template

### Basic Professional Email Prompt

```
[ROLE]
You are a professional business communication specialist.

[TASK]
Write a professional email based on the provided information.

[CONTEXT]
- Recipient: [Name and role]
- Subject: [Email topic]
- Tone: [Formal/Casual/Friendly]
- Purpose: [Main objective of the email]
- Key points to include: [List main points]

[INSTRUCTIONS]
1. Start with an appropriate greeting
2. Begin with a clear, concise subject line
3. Introduce the main purpose in the first sentence
4. Develop the body with supporting details
5. End with a clear call to action
6. Close professionally with appropriate sign-off

[FORMAT]
Provide only the email content (subject line + body).
Keep the email concise and scannable (under 200 words for body).

[CONSTRAINTS]
- Avoid jargon or overly complex language
- Proofread for grammar and spelling
- Maintain a professional tone throughout
- Be respectful and clear

[TONE EXAMPLES]
- Formal: "Dear [Name], I hope this message finds you well..."
- Professional-friendly: "Hi [Name], I wanted to reach out about..."
```

---

## 📊 Meeting Summarization Prompt Template

### Meeting Summary Prompt

```
[ROLE]
You are an expert meeting facilitator and note-taker.

[TASK]
Create a concise, accurate summary of the provided meeting transcript.

[CONTEXT]
- Meeting date: [Date]
- Participants: [List of attendees]
- Duration: [Meeting length]
- Overall objective: [Main meeting purpose]

[INSTRUCTIONS]
1. Extract key discussion points
2. Identify decisions made
3. List action items with assigned owners
4. Note any deadlines or next steps
5. Highlight any risks or concerns raised
6. Capture important metrics or data discussed

[FORMAT]
Structure the summary as follows:
- **Overview**: One-sentence summary
- **Key Points**: Bullet list of main topics discussed
- **Decisions Made**: What was decided
- **Action Items**: 
  - [Task] (Owner: [Name], Due: [Date])
- **Risks/Concerns**: Any issues flagged
- **Next Steps**: Planned follow-up or next meeting

[CONSTRAINTS]
- Keep total summary under 300 words
- Use clear, concise language
- Be objective—report what was said, not opinions
- Preserve important context and nuance
```

---

## ✅ Task Planning Prompt Template

### Task Planning Prompt

```
[ROLE]
You are an expert project manager and planning specialist.

[TASK]
Create a detailed task plan for the provided project or initiative.

[CONTEXT]
- Project: [Project name]
- Objective: [Main goal]
- Deadline: [Completion date]
- Resources available: [Team size, budget, tools]
- Constraints: [Any limitations or restrictions]

[INSTRUCTIONS]
1. Break down the project into logical phases
2. Identify dependencies between tasks
3. Estimate realistic timelines for each task
4. Assign priority levels (High/Medium/Low)
5. Consider resource allocation
6. Build in contingency time
7. Identify potential risks and mitigation strategies

[FORMAT]
Organize as follows:
- **Phase 1: [Phase Name]**
  - Task 1.1: [Description] (Duration: [Time], Priority: [Level])
  - Task 1.2: [Description] (Duration: [Time], Priority: [Level])
- **Phase 2: [Phase Name]**
  - Task 2.1: [Description] (Duration: [Time], Priority: [Level])
- **Dependencies**: [Task relationships]
- **Risks & Mitigation**: [Potential issues and solutions]
- **Timeline**: [Overall project schedule]

[CONSTRAINTS]
- Be realistic with timeframes
- Consider team capacity
- Account for holidays and unavailable time
- Include buffer for unexpected issues
- Make sure all tasks have clear owners
```

---

## 🔍 Research Assistance Prompt Template

### Research Prompt

```
[ROLE]
You are a thorough research analyst and information specialist.

[TASK]
Research and synthesize information about [topic].

[CONTEXT]
- Research question: [Specific question to answer]
- Scope: [Breadth of research needed]
- Focus areas: [Key aspects to prioritize]
- Audience: [Who this research is for]

[INSTRUCTIONS]
1. Gather information from multiple perspectives
2. Evaluate source credibility
3. Identify key findings and patterns
4. Note any contradictions or debates
5. Highlight data and evidence
6. Provide balanced analysis
7. Identify gaps in current information

[FORMAT]
Structure the research as:
- **Overview**: Summary of current state
- **Key Findings**: Main points with supporting evidence
- **Perspectives**: Different viewpoints on the topic
- **Data & Evidence**: Statistics and research backing claims
- **Gaps & Limitations**: What's unknown or uncertain
- **Recommendations**: Next steps or areas for deeper research
- **Sources**: Complete citation list

[CONSTRAINTS]
- Only cite credible, authoritative sources
- Distinguish between fact and opinion
- Be transparent about confidence levels
- Acknowledge limitations and uncertainties
- Provide full citations for all claims
```

---

## 💬 Chatbot Prompt Template

### Conversational AI Prompt

```
[ROLE]
You are a helpful, knowledgeable assistant designed to [specific purpose].

[PERSONALITY]
- Tone: [Friendly/Professional/Casual]
- Communication style: [Clear/Conversational/Technical]
- Attitude: [Helpful/Informative/Supportive]

[INSTRUCTIONS]
1. Always start by identifying yourself as an AI assistant
2. Listen carefully to what the user is asking
3. Provide accurate, relevant information
4. Explain complex topics in simple terms
5. Ask clarifying questions if needed
6. Offer follow-up help and suggestions
7. Politely decline if a request is outside your capabilities
8. Suggest human support when appropriate

[GUARDRAILS]
You should NOT:
- Pretend to be human
- Make up information
- Provide medical, legal, or financial advice
- Share confidential information
- Engage in inappropriate conversations
- Make promises you can't keep

[FORMAT]
- Keep responses concise (under 200 words typically)
- Use friendly, accessible language
- Ask if the user needs more information
- Provide options for follow-up questions

[EXAMPLES]
User: "How do I...?"
You: "I'd be happy to help! [Provide clear, step-by-step guidance]. Would you like me to explain any of these steps in more detail?"
```

---

## 💡 Advanced Techniques

### 1. **Few-Shot Prompting**
Provide examples of desired outputs to guide the model:

```
[TASK]
Classify the following emails by urgency level.

[EXAMPLES]
Email 1: "Quick question about tomorrow's meeting."
Classification: Medium

Email 2: "System is down—need immediate assistance!"
Classification: High

Email 3: "FYI—updated our office hours."
Classification: Low

[NOW CLASSIFY]
Email 4: [User's email]
```

### 2. **Chain-of-Thought Prompting**
Ask the AI to explain its reasoning:

```
"Let's think through this step by step.
First, [step 1].
Then, [step 2].
Finally, [step 3].
Therefore, [conclusion]."
```

### 3. **Role-Based Prompting**
Assign a specific perspective or expertise:

```
"Act as a [specific role] with 15 years of experience.
How would you approach [problem]?"
```

### 4. **Constrained Output**
Specify format and limitations:

```
"Provide your answer in exactly 3 bullet points.
Each point should be one sentence.
Use simple, clear language."
```

### 5. **Negative Examples**
Show what NOT to do:

```
"Here's what NOT to do: [Example of bad output]
Instead, do this: [Example of good output]"
```

---

## ✅ Quality Checklist

Before using a prompt in production:

- [ ] **Clarity** – Is the task clearly stated?
- [ ] **Completeness** – Have all necessary details been provided?
- [ ] **Examples** – Are examples included and helpful?
- [ ] **Format** – Is the desired output format specified?
- [ ] **Constraints** – Are limitations and boundaries clear?
- [ ] **Testing** – Has the prompt been tested with various inputs?
- [ ] **Iteration** – Have results been reviewed and refined?
- [ ] **Documentation** – Is the prompt version tracked and documented?
- [ ] **Ethics** – Does the prompt follow ethical guidelines?

---

## 📊 Testing & Iteration Process

### Test Your Prompt

1. **Create baseline version** – Draft initial prompt
2. **Test with examples** – Try with 3-5 different inputs
3. **Evaluate results** – Rate quality on scale 1-5
4. **Identify gaps** – What's missing or incorrect?
5. **Refine prompt** – Add clarity, examples, or constraints
6. **Re-test** – Verify improvements
7. **Document** – Record version and changes
8. **Repeat** – Continue refining until satisfied

### Example Test Log

```
Version 1.0 - Basic prompt
Test 1: "Good, but too verbose"
Test 2: "Missing key detail"
Test 3: "Format incorrect"
Average Score: 2.5/5

Version 1.1 - Added examples and format spec
Test 1: "Much better, clearer"
Test 2: "Good, but still missing context"
Test 3: "Good format, needs refinement"
Average Score: 4/5

Version 1.2 - Added context section
Test 1: "Excellent"
Test 2: "Excellent"
Test 3: "Very good"
Average Score: 4.7/5
APPROVED FOR PRODUCTION
```

---

## 📚 Resources & Further Learning

### Key Concepts
- Tokens and context windows
- Temperature and model parameters
- System vs. user prompts
- API best practices

### Recommended Reads
- OpenAI Prompt Engineering Guide
- Anthropic's Constitutional AI approach
- Papers on few-shot learning
- Case studies in your domain

---

## 🎓 Practice Exercise

### Your Turn!
Create a prompt for your specific use case:

1. Define the **role** the AI should play
2. State the **task** clearly
3. Provide **context** and background
4. List **instructions** step-by-step
5. Specify the **format** of results
6. Include **examples** if helpful
7. Set **constraints** and boundaries
8. Test with 3 different inputs
9. Document your **version** and results
10. Refine based on feedback

---

## 📄 Document Information

**Version:** 1.0.0  
**Last Updated:** September 3, 2026  
**Maintained By:** prescillamapeka2-boop


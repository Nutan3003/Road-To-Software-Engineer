# Day 10 - Common Prompt Engineering Mistakes and Best Practices

## Today's Learning

Today, I learned about the common mistakes people make while writing prompts and the best practices to create effective prompts.

Even powerful AI models can produce poor results if the prompt is unclear or incomplete.

---

## Common Prompt Engineering Mistakes

### 1. Writing Vague Prompts

❌ Example:

```
Explain Python.
```

This prompt is too broad and may generate a generic response.

---

### 2. Not Providing Context

❌ Example:

```
Write a resume.
```

Without context, AI doesn't know:
- Who the resume is for
- Which role you're applying for
- What skills or experience to include

---

### 3. Not Specifying the Output Format

❌ Example:

```
Explain DBMS.
```

The response format is undefined.

A better prompt would specify:

```
Explain DBMS in a table with:
- Concept
- Description
- Example
```

---

### 4. Asking Multiple Questions in One Prompt

❌ Example:

```
Explain Java, SQL, React, System Design, and DSA.
```

Large prompts often lead to incomplete or less focused responses.

It is better to divide them into separate prompts.

---

### 5. Not Defining the Audience

The same topic should be explained differently for:
- Beginners
- Students
- Developers
- Interview preparation

Mentioning the target audience helps AI provide more relevant responses.

---

## Best Practices

- Be specific about your request.
- Provide enough context.
- Assign a role when needed.
- Mention the expected output format.
- Break complex tasks into smaller prompts.
- Refine your prompt if the first response isn't satisfactory.

---

## Example

### Basic Prompt

```
Explain SQL Joins.
```

### Improved Prompt

```
Act as a database instructor.

Explain SQL Joins for beginners.

Include:
- Definition
- Types of Joins
- SQL syntax
- Real-world example
- Comparison table
```

The improved prompt is more detailed and produces a higher-quality response.

---

## Key Takeaways

- Good prompts lead to better AI responses.
- Specificity and context are essential.
- Defining the role, audience, and output format improves the quality of responses.
- Prompt Engineering is a skill that improves with practice.

---

## Reflection

Today, I realized that most AI mistakes are not caused by the model itself but by unclear instructions. Writing effective prompts is similar to communicating with a teammate—the clearer the instructions, the better the outcome.

---

#100DaysOfSoftwareEngineering
#PromptEngineering
#LearningInPublic
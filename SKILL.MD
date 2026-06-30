---
name: "ui-copy-tone-system"
description: "This skill defines how AI should generate user-facing copy across the product."
author: "Danny A. Mosquera | DALE"
---

# UI Copy & Tone System

## Purpose

This skill defines how AI should generate user-facing copy across the product.

It ensures every message is:

- Human
- Clear
- Concise
- Consistent
- Helpful
- Aligned with the product's personality

The goal is not only to inform users.

Every piece of UI copy should reduce friction, build confidence, and guide users toward the next action.

---

# Core Principles

## Write for humans

Write like someone helping another person.

Avoid sounding like documentation, an API, or a system log.

Instead of:

> Operation completed successfully.

Prefer:

> Changes saved.

---

## Focus on outcomes

Users care about results, not internal implementation.

Avoid describing technical processes.

❌

> Database updated.

✅

> Changes saved.

---

## Every word should add value

People scan interfaces.

Keep messages as short as possible while preserving clarity.

Remove unnecessary words.

Instead of:

> Your profile has been successfully updated.

Prefer:

> Profile updated.

---

## Be specific

Avoid vague messages.

Instead of:

> Something went wrong.

Prefer:

> We couldn't upload your file.

Specific messages reduce anxiety and help users recover.

---

## Never expose technical details

Users should never see:

- HTTP errors
- Stack traces
- Database failures
- Internal identifiers
- Exception names
- API terminology

Those belong in logs, not in the UI.

---

# Message Structure

Every message should answer three questions.

## 1. What happened?

Describe the outcome.

## 2. What does it mean?

Provide just enough context.

## 3. What should the user do next?

When appropriate, guide the next action.

Example:

Title

Workspace created

Body

Your workspace is ready.
You can now invite your team.

---

# Writing Guidelines

## Use simple language

Prefer everyday words.

Instead of:

- Execute
- Persist
- Validate
- Initiate
- Terminate

Use:

- Run
- Save
- Check
- Start
- Stop

---

## Sound natural

Use conversational language.

Instead of:

> The requested action has been completed.

Prefer:

> Everything's ready.

---

## Prefer contractions

English sounds warmer with contractions.

Use:

- You're
- We'll
- It's
- Couldn't
- Didn't

Instead of:

- You are
- We will
- It is
- Could not
- Did not

---

## Avoid robotic wording

Never write:

- Operation successful
- Process completed
- Unexpected error occurred
- Request executed
- Fatal error

---

## Don't blame the user

Avoid:

> You entered an invalid email.

Prefer:

> That email doesn't look valid.

The problem is described without assigning blame.

---

## Write positively

Instead of:

> Password invalid.

Prefer:

> That password doesn't look right.

---

# Length Guidelines

## Titles

2–5 words

Examples:

- Profile updated
- File uploaded
- Payment received
- Workspace created

---

## Body

8–20 words whenever possible.

Keep explanations concise.

---

## Toast Notifications

Ideally under 15 words.

Examples:

✓ Changes saved.

✓ Invitation sent.

✓ Payment completed.

---

# Tone System

The same message can be written in different voices.

Choose the tone that matches the product.

---

# Corporate

Characteristics

- Professional
- Clear
- Reliable
- Direct
- Neutral

Example

Workspace created

Your workspace is ready.
You can now invite your team.

---

# Friendly

Characteristics

- Warm
- Human
- Conversational
- Calm
- Encouraging

Example

You're all set!

Your workspace is ready whenever you are.

---

# Motivational

Characteristics

- Positive
- Energetic
- Celebrates progress

Example

Nice work!

Everything's ready for your next step.

---

# Playful

Use sparingly.

Avoid during critical flows.

Example

Success!

Your workspace has a new home.

---

# Calm

Characteristics

- Reassuring
- Gentle
- Relaxed

Example

Everything is safely saved.

Take your time—we'll be here when you return.

---

# Success Messages

Success messages should do more than celebrate.

Whenever useful, tell users what happens next.

Instead of:

> Invitation sent.

Prefer:

> Invitation sent.
>
> We'll let you know when they join.

---

# Error Messages

Good error messages should:

- Explain what happened.
- Avoid technical language.
- Suggest recovery.

Example

We couldn't connect.

Check your internet connection and try again.

---

# Empty States

Never leave empty screens unexplained.

Every empty state should answer:

- Why is this empty?
- What can I do now?

Example

No projects yet.

Create your first project to start organizing your work.

---

# Confirmation Dialogs

Be direct.

Delete project?

This action can't be undone.

---

# Consistency Rules

Within the same product:

- Keep the same vocabulary.
- Keep the same tone.
- Reuse common expressions.
- Don't mix corporate and playful language randomly.
- Build familiarity through consistency.

---

# Words to Avoid

Avoid generic system language.

Examples:

- Operation
- Process
- Execution
- Successfully completed
- Unexpected error
- Fatal error
- Internal error
- Invalid operation

Prefer natural alternatives.

---

# AI Generation Checklist

Before producing any UI copy, verify that it:

- Sounds human.
- Is concise.
- Uses simple vocabulary.
- Focuses on user outcomes.
- Doesn't expose technical details.
- Matches the selected tone.
- Guides the next step when appropriate.
- Avoids robotic language.
- Doesn't blame the user.
- Reduces friction.

---

# Examples

## Success

❌

Operation completed successfully.

✅

Changes saved.

---

## Error

❌

Unexpected error occurred.

✅

We couldn't upload your file.

Please try again.

---

## Empty State

❌

No data.

✅

Nothing here yet.

Create your first project to get started.

---

## Confirmation

❌

Confirm deletion.

✅

Delete project?

This action can't be undone.

---

# Prompt Template

Whenever generating UI copy, follow these rules:

- Sound human, never robotic.
- Be concise.
- Prefer simple everyday words.
- Explain outcomes instead of internal processes.
- Never expose technical details.
- Focus on what users need to know.
- Reduce friction.
- Match the requested tone consistently.
- Titles should be 2–5 words.
- Body copy should usually stay between 8–20 words.
- Toasts should ideally remain under 15 words.
- Success messages should suggest the next step when helpful.
- Error messages should explain the issue and how users can recover.
- Empty states should encourage the first meaningful action.
- Avoid generic phrases like "Operation successful", "Unexpected error", or "Process completed".
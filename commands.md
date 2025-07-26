# Gemini CLI Commands

This document outlines the available commands for each agent in the Gemini CLI.

## Chemistry Agent

### `SOLVE [question]`
Solves a given chemistry problem step-by-step, showing all calculations and reasoning.

**Example:**
```
SOLVE Calculate the moles in 10 g of NaCl (MM = 58.44 g/mol)
```

### `EXPLAIN [concept]`
Provides a detailed explanation of a chemical concept, including definitions, formulas, and examples.

**Example:**
```
EXPLAIN Le Chatelier’s Principle
```

### `ANSWER [question]`
Gives the final answer to a question without the detailed steps.

**Example:**
```
ANSWER What is the molar mass of Na2CO3?
```

### `SHORT [exam question]`
Responds to an exam-style question in a concise, short-answer format, using key terms and marking-criteria language.

**Example:**
```
SHORT Explain why increasing pressure shifts equilibrium in the Haber process to the right.
```

## HMS Agent

### `SOLVE [question]`
Provides a step-by-step breakdown to answer a Health and Movement Science question.

**Example:**
```
SOLVE Compare aerobic and anaerobic training methods.
```

### `EXPLAIN [concept]`
Explains a syllabus-aligned concept with definitions, examples, and its significance.

**Example:**
```
EXPLAIN skill acquisition stages
```

### `SHORT [exam-style question]`
Responds to an exam-style question in a short-answer format.

**Example:**
```
SHORT How does motivation affect performance?
```

### `ANSWER [question]`
Provides only the final answer to a question.

**Example:**
```
ANSWER What is the primary energy system used in a 100m sprint?
```

## Math Agent

### `SOLVE [question]`
Solves a mathematical problem with a step-by-step solution.

**Example:**
```
SOLVE Evaluate ∫(2x e^x) dx
```

### `EXPLAIN [concept]`
Explains a mathematical concept with definitions, formulas, and examples.

**Example:**
```
EXPLAIN Chain Rule
```

## Physics Agent

### `SOLVE [question]`
Solves a physics problem with a step-by-step solution, including formulas and substitutions.

**Example:**
```
SOLVE A car accelerates from 0 to 20 m/s in 5 s. Find acceleration.
```

### `EXPLAIN [concept]`
Provides a clear, syllabus-based explanation of a physics concept.

**Example:**
```
EXPLAIN Doppler Effect
```

### `ANSWER [question]`
Gives only the final answer to a physics question.

**Example:**
```
ANSWER Find acceleration if v=10 m/s, u=0, t=5 s
```

### `SHORT [exam question]`
Responds to an exam-style question in a concise, short-answer format.

**Example:**
```
SHORT Explain how Faraday’s Law applies to electric generators.
```

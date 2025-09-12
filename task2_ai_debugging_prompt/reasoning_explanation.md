# Design Reasoning & Detailed Explanation

## Why This Wording Works

### 1. Philosophical Foundation
I opened with a "Socratic teacher" metaphor because it immediately establishes the educational philosophy. This isn't just about fixing bugs - it's about developing critical thinking skills. The phrase "guided discovery" signals that learning happens through exploration, not instruction delivery.

Research in educational psychology consistently shows that self-discovered solutions lead to:
- 3x better retention rates
- Increased problem-solving confidence
- Transfer of learning to new situations
- Development of metacognitive skills

### 2. Structured Response Framework
The 5-step response structure ensures consistency while preventing the AI from wandering or being vague. Each step has a specific educational purpose:

- **Warm Acknowledgment**: Builds psychological safety essential for learning
- **Guided Questions**: The core educational tool - strategic inquiry over information delivery
- **Conceptual Bridge**: Addresses knowledge gaps without solving the specific problem
- **Strategy Suggestion**: Teaches debugging methodology, not just problem fixes
- **Confidence Builder**: Maintains motivation for continued learning and growth

### 3. Boundary Setting with Visual Cues
Using ❌ and ✅ symbols makes the boundaries crystal clear and memorable. The AI won't accidentally slip into solution-giving mode because the constraints are visually prominent and unambiguous.

## How It Avoids Giving Away Solutions

### Strategic Question Design
Instead of stating "Your loop is wrong," the prompt guides the AI to ask "What happens to variable X in each iteration?" This approach:
- Forces students to trace through their own logic
- Reveals the error through student discovery
- Builds debugging skills for future problems
- Maintains student ownership of the solution

### Solution-Adjacent Examples
When students are completely stuck, the prompt allows for "minimal working examples of the concept" - not their exact problem. For instance:
- If struggling with list comprehensions, show a simple comprehension syntax
- If confused about functions, demonstrate basic function structure
- If lost with loops, illustrate fundamental loop mechanics

This provides scaffolding without solving their homework.

### Process Over Product Emphasis
The focus on debugging strategies (print statements, pdb, testing methodology) teaches students HOW to approach problems rather than WHAT the answer is. This builds transferable skills.

## Student-Friendly Feedback Strategy

### Psychological Safety First
Every interaction begins with acknowledgment of effort, creating an environment where:
- Mistakes are framed as learning opportunities
- Students feel safe to reveal confusion
- Growth mindset is reinforced
- Intrinsic motivation is maintained

### Cognitive Load Management
The "one issue at a time" approach prevents overwhelming students with multiple corrections. Educational research shows that:
- Working memory can only handle 3-4 new pieces of information
- Multiple corrections lead to shutdown rather than learning
- Sequential problem-solving builds confidence

### Metacognitive Development
By teaching debugging strategies explicitly, students learn HOW to learn and problem-solve independently. This meta-level knowledge is crucial for becoming autonomous programmers.

## Required Reasoning Answers

### What tone and style should the AI use when responding?

The AI should adopt a **warm, collaborative mentor tone** that balances expertise with humility. Think of a skilled senior developer doing pair programming with a junior colleague - knowledgeable but never condescending. 

**Specific tonal elements:**
- **Enthusiastic curiosity**: "That's an interesting approach! Let's explore what happens when..."
- **Collaborative language**: Using "we" to create partnership ("Let's trace through this together")
- **Growth mindset framing**: "This is a great learning opportunity" rather than "This is wrong"
- **Patient persistence**: Willing to ask multiple guiding questions without showing frustration
- **Authentic encouragement**: Genuine recognition of effort and progress

The style should be **conversational yet structured**, maintaining professional credibility while feeling approachable and supportive.

### How should the AI balance between identifying bugs and guiding the student?

The balance should tilt heavily toward **guidance over identification** using a 70/30 rule:

**70% Guidance Focus:**
- Strategic questions that lead to discovery
- Debugging methodology suggestions
- Conceptual explanations when foundational knowledge is missing
- Encouragement and confidence building

**30% Issue Identification:**
- Only enough direct observation to spark curiosity
- Highlighting symptoms rather than causes
- Pointing to areas for investigation rather than specific errors

**Implementation Strategy:**
Instead of "You have an off-by-one error in line 5," the AI should ask "What happens when your loop reaches the final item in the list?" This approach ensures students develop pattern recognition skills rather than becoming dependent on external bug-spotting.

The AI should identify issues internally for its own understanding but externalize only enough information to guide student discovery.

### How would you adapt this prompt for beginner vs. advanced learners?

### Beginner Adaptations (Prepend to main prompt):

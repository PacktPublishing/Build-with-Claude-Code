# Build with Claude Code — Prompt Collection

Copy and paste the prompts for each chapter as you follow along with the book.

---

## 📖 Table of Contents

- [Chapter 1: My First Vibe Coding](#chapter-1-my-first-vibe-coding)
- [Chapter 2: Maximizing AI's Potential by 200% with Effective Prompts](#chapter-2-maximizing-ais-potential-by-200-with-effective-prompts)
- [Chapter 3: Getting Started with Claude Code](#chapter-3-getting-started-with-claude-code)
- [Chapter 4: Practical Use of Claude Code](#chapter-4-practical-use-of-claude-code)
- [Chapter 5: Systematic Development and Management Through Game Building](#chapter-5-systematic-development-and-management-through-game-building)
- [Chapter 6: Giving Claude Code Wings with APIs](#chapter-6-giving-claude-code-wings-with-apis)
- [Chapter 7: Building a Development Team with Claude Code AI Agents](#chapter-7-building-a-development-team-with-claude-code-ai-agents)
- [Chapter 8: Extending Claude Code with MCP, Skills, and Plugins](#chapter-8-extending-claude-code-with-mcp-skills-and-plugins)

---

### Chapter 1: My First Vibe Coding

#### 01-2: Create My Own First Webpage

```
I want to create my own personal start homepage with today's date and time and a search bar.
```

Then answer the follow-up questions to complete your first artifact.

Editing the design:

```
Please modify this design to match the Google style.
```

---

### Chapter 2: Maximizing AI's Potential by 200% with Effective Prompts

#### 02-1: The Secrets of Prompts That Awaken AI

An example of a vague prompt (don't expect good results from this one):

```diff
- Create a cool, personalized homepage for me. (X)
```

An improved, specific version:

```
I want to create my own homepage with a clean, light-mode design that includes today's date and time, and a Google search bar.
```

The basic question template:

```
I'm trying to build [what]. The main feature is [specific feature description]. It's for [who], and it's needed to [why/solve a specific problem]. Please write a detailed PRD with technical guidance on how to implement it.
```

Writing the portfolio PRD:

```
I'm trying to build a portfolio webpage. The main feature is an impactful layout that allows recruiters to grasp my capabilities within 30 seconds. It is designed for a marketer preparing to transition into freelancing, and is essential for presenting myself as a competitive candidate. Please write a detailed PRD, including technical direction on how to implement it.
```

#### 02-2: Real-World Application: Completing Your Marketing Portfolio

```
Convert the given PRD into a 5-step prompt for use with Claude Code.
```

```
I'm going to proceed according to this PRD. First, please write an HTML document based on the PRD. Divide it into sections and assign a unique name to each section to make future edits easier. Don't implement any features yet; just show me the overall structure.
```

```
Please revise the [Result label] items in the 'proof-strip' section to be a list that specifically details the performance over the past three years.
```

```
Apply a modern and sophisticated design to the HTML document.
```

```
Move the [One-line result] metrics from the 'case-studies' section to the 'hero' section and present them as a chart.
```

```
Here is my career portfolio. Please update it by section based on the following information.
I am a third-year performance/content marketing specialist.
- Key achievements: ROAS of 200%, 25 campaigns, and contributing $600K in annual revenue
- Position changes over 3 years: Junior (2023) → Performance Marketer (2024) → Manager + Consultant (2025)
- Skill Levels: Performance Marketing: 75%, Content Marketing: 70%, Data Analysis (GA4): 65%
Here are my key case studies.
- E-commerce: Monthly ad spend of $8K, ROAS of 200%
- Startup: Instagram followers increased from 2,000 to 8,000 (in 6 months)
- Local brand: Blog visitors increased from 500 to 3,000 (in 4 months)
```

```
Select one WordPress theme that best suits this portfolio and restyle the entire page after it, updating the colors and fonts to match the theme. Use different color tones for each section to make them easily distinguishable. Apply the design directly to the HTML document.
```

```
Please review whether every part of the portfolio webpage is properly implemented. Check that it was built according to the PRD and that each link works without any issues.
```

```
Address and fix the three areas for improvement that were identified, and complete a perfect portfolio for transitioning to freelance work.
```

---

### Chapter 3: Getting Started with Claude Code

#### 03-1: Installing Claude Code

Windows (PowerShell):

```
irm https://claude.ai/install.ps1 | iex
```

macOS / Linux:

```
curl -fsSL https://claude.ai/install.sh | bash
```

For macOS/Linux details, see the **[installation guide](install-guide/INSTALL.md)**.

Your first conversation with Claude Code:

```
Hello! Please describe what features you have.
```

#### 03-2: Building a Handwriting Recognition Program

```
Create and run code that recognizes numbers entered as handwriting.
```

```
Make it so I can run the digit recognition program by clicking it in Windows Explorer.
```

#### 03-3: Expanding the Program with CLAUDE.md

```
I want to develop the handwriting recognition program as both a web version and a desktop version. Please create the web_version and desktop_version folders, and generate a CLAUDE.md file for each folder.
```

```
Run the web version program in the browser.
```

---

### Chapter 4: Practical Use of Claude Code
#### 04-1 Learning Claude Code Commands with Step-by-Step Prompts
#### Requesting a PRD

```
I want to create a to-do management app. Please write a PRD for me.
It's a personal app to manage about 10-20 tasks per day. The main features are:
- Add, edit, and delete tasks
- Completion check feature
- Category classification (work/personal/study)
- View progress
I want it to run directly in the browser, and I'd like the data to persist even after refreshing. I want to build it with pure JavaScript without technical complexity.
```

#### Generating Step-by-Step Prompts

```
Convert this PRD into step-by-step prompts for use in Claude Code.
Summarize it into 5 key steps and create clear instructions for each step.
```

#### Step 1: Implement the basic structure and core features

```
Step 1: Implement basic structure and core functions
Create the basic structure of a to-do management app.

Requirements:
1. Consist of three files: index.html, style.css, script.js
2. HTML structure:
   - App title "My Tasks"
   - To-do input field (input + add button)
   - Container to display the to-do list
3. JavaScript features:
   - Add to-do (support both Enter key and button click)
   - Delete to-do (X button for each item)
   - Toggle complete/incomplete with checkbox
   - Change style when completed
4. Store data in localStorage
   - Automatically save when adding/deleting/changing completion status
   - Keep data when page is refreshed
5. Basic CSS styling:
   - Clean card-style layout
   - Center alignment, max width 600px
   - Hover effects and transitions

Store each to-do with the structure { id, text, completed, createdAt }.
```

#### Step 2: Add category functionality and improve the UI

```
Step 2: Category function and UI improvement
Add category functionality to the existing code and improve the UI.

Requirements:
1. Category function:
   - Three categories: work, personal, study
   - Category selection dropdown when adding a task
   - Display category color tag on each task item
   - Category filter buttons (All/Work/Personal/Study)
2. UI improvement:
   - Category colors: Work (blue #4A90E2), Personal (green #27AE60), Study (purple #8E44AD)
   - Selected button has a border
   - Highlight background of selected button
   - Display creation time on task item (e.g., '2 hours ago')
3. Data structure update:
   - Add category field
   - Save the filter state in localStorage as well

Sort completed items automatically to the bottom of the list.
```

#### Step 3: Add a progress dashboard

```
Step 3: Add a progress dashboard
Add a progress dashboard and implement inline edit functionality.

Requirements:
1. Progress dashboard:
   - Add a statistics section at the top of the app
   - Overall progress: '5/10 completed (50%)' format + progress bar
   - Show mini progress by category (completed/total for each category)
   - Show the number of tasks added today
2. Inline edit functionality:
   - Edit mode on double-clicking a task
   - Change to input field for editing
   - Save with Enter, cancel with ESC
   - Selectable box to change category during editing
3. UI animation:
   - Smooth transition effect for progress bar
   - Fade animation when adding/deleting items
   - Slide animation when checking complete

The dashboard must update in real time.
```

#### Step 4: Dark Mode and Advanced Features

```
Step 4: Dark mode and advanced features
Implement dark mode and additional features.

Requirements:
1. Dark mode:
   - Dark/Light mode toggle switch at the top right
   - Dark mode colors: background (#1A1A1A), card (#2D2D2D), text (#E0E0E0)
   - Save selected theme in localStorage
   - Animation when switching modes
2. Additional features:
   - Delete all completed items button (including confirmation dialog)
   - Task search function (real-time filtering)
   - Show delete button after task completion
   - Empty state message ('No tasks. Try adding some!')
3. Keyboard shortcuts:
   - Alt+N: Focus new task input field
   - Alt+1,2,3,4: Switch category filter
   - Alt+D: Toggle dark mode
4. Responsive design:
   - Optimize for mobile (max-width: 480px)
   - Touch-friendly button sizes

Provide appropriate feedback for every interaction.
```

#### Step 5: Final completion and optimization

```
Step 5: Final completion and optimization
Complete the app and maximize usability.

Requirements:
1. Export/Import Data:
   - Button to export data in JSON format
   - Import data via file upload
   - Check backup of current data before importing
2. Sorting options:
   - Sort by creation date, category, completion status
   - Save sorting state
   - Manual sorting by drag and drop (sortable)
3. Performance optimization:
   - Smooth performance even with more than 100 items
   - Apply debouncing (search, save)
   - Efficient DOM manipulation
4. Accessibility improvements:
   - Add ARIA labels
   - Focus management
   - Screen reader support
5. Additional improvements:
   - Duplicate to-do warning
   - Undo for recently deleted items
   - Random quote of the day
   - Encouragement message based on completion rate

Handle all edge cases and add error handling.
Add detailed comments to the code.
```

#### 04-2 Resuming Work and Boosting Efficiency

```
Please add a keyword-based automatic category classification feature to the current to-do management app.
```

#### 04-3 Improving Projects and Managing Your Work

```
[Image #1] The current design seems optimized for mobile. Please modify the design so that the UI can be viewed in full screen on a desktop environment. Save the revised design in a new folder called 'web_version'.
```

```
Find and explain the functions related to dark mode in the @script.js file.
```

```
Please analyze the files in the @web_version folder and check if the to-do app is optimized for the desktop environment.
```

---

### Chapter 5: Systematic Development and Management Through Game Building

#### 05-1 Creating reliable AI content

```
I want to create a general knowledge quiz game. Please write a PRD.
Game Rules:
- Multiple-choice quiz with four options
- Categories: History, Science, Geography, Arts & Culture
- 10 questions per category, total of 40 questions
- Immediate feedback on correct/incorrect answers
- Record final score and ranking
```

```
Summarize the 3-phase project based on the PRD so that the general knowledge quiz game can be implemented with Claude Code.
```

#### Step 1: Core Quiz System

```
Step 1: Build the core quiz system
Goal
Implement an MVP (Minimum Viable Product) that supports basic quiz play
Scope
1.1 Initial project setup
- Set up the project structure (React or Vanilla JS)
- Build the basic HTML/CSS layout
- Design the state management structure
1.2 Question data structure and management
javascript// Example question data structure
{
  id: 1,
  category: "History",
  difficulty: "medium",
  question: "Who founded the Mongol Empire?",
  options: ["Genghis Khan", "Kublai Khan", "Ogedei Khan", "Tamerlane"],
  correctAnswer: 0,
  explanation: "Genghis Khan united the Mongol tribes and founded the Mongol Empire in 1206."
}

Hardcode 10 questions per category (40 total)
Question loading and management system
Filtering questions by category

1.3 Game flow logic
javascript// Key functions to implement
- initGame(): initialize the game
- loadQuestion(): load and display a question
- handleAnswer(): process an answer
- showFeedback(): show correct/incorrect feedback
- nextQuestion(): move to the next question
- endGame(): handle game over
1.4 Basic UI

Start screen (start button)
Quiz screen (question, 4 options, progress)
Instant feedback UI (correct/incorrect indicator)
Simple results screen (total score, number correct)

Test checklist

 Are all 40 questions presented in sequence?
 Is correct/incorrect judged accurately?
 Is feedback shown immediately?
 Are results displayed when the game ends?
```

#### Step 2: Scoring System and Game Modes

```
 Step 2: Scoring system and game mode expansion
Goal
Implement multiple game modes and a refined scoring system
Scope
2.1 Scoring system
javascript// Score calculation logic
class ScoreManager {
  calculateScore(isCorrect, timeSpent, consecutiveCorrect, hintUsed) {
    let score = 0;
    if (isCorrect) {
      score += 10; // base score
      if (timeSpent < 10) score += 3; // time bonus
      if (!hintUsed) score += 2; // no-hint bonus
      score += this.getConsecutiveBonus(consecutiveCorrect);
    }
    return score;
  }
}
2.2 Game modes
javascript// Game mode settings
const gameModes = {
  full: { questions: 40, timeLimit: null },
  category: { questions: 10, timeLimit: null },
  speed: { questions: 20, timeLimit: 15 } // 15 seconds per question
};

Full challenge mode (40 questions)
Per-category challenge mode
Speed quiz mode (time limit)

2.3 Advanced features

Hint system (remove 2 wrong options, 3 uses per game)
Pause feature
Per-question timer
Consecutive-correct combo system

2.4 Detailed result analysis
javascript// Result data structure
{
  totalScore: 350,
  correctAnswers: 32,
  totalQuestions: 40,
  accuracy: 80,
  categoryStats: {
    "History": { correct: 8, total: 10 },
    "Science": { correct: 7, total: 10 },
    // ...
  },
  averageResponseTime: 12.5,
  longestStreak: 7
}
Test checklist

 Is the score calculated correctly?
 Does each game mode work properly?
 Does the hint feature work correctly?
 Does the timer run accurately?
 Is the result analysis accurate?
```

#### Step 3: Data Persistence and Ranking System

```
Step 3: Data persistence and ranking system
Goal
Complete user record storage and the leaderboard feature
Scope
3.1 Using local storage
javascript// Local data management
class LocalDataManager {
  saveGameResult(result) {
    const history = this.getGameHistory();
    history.push({
      ...result,
      timestamp: new Date().toISOString()
    });
    localStorage.setItem('gameHistory', JSON.stringify(history));
  }
  
  getBestScore() {
    const history = this.getGameHistory();
    return Math.max(...history.map(h => h.totalScore));
  }
}
3.2 Ranking system
javascript// Leaderboard structure
const leaderboard = {
  daily: [],
  weekly: [],
  allTime: [],
  byCategory: {
    "History": [],
    "Science": [],
    // ...
  }
};

Local leaderboard (in the browser)
Ranking display (top 10)
Personal best tracking

3.3 Statistics and progress

Track play counts
Per-category accuracy statistics
Growth graph (score trend over time)
Personal dashboard

3.4 UI/UX improvements

Add CSS animations
Apply responsive design
Dark mode support
Mobile optimization
Accessibility improvements (keyboard navigation)

3.5 Additional features

Expand the question pool (20+ questions per category)
Difficulty options
Sound effects (optional)
Result sharing (copy to clipboard)

Test checklist

 Are game results saved?
 Are rankings calculated correctly?
 Are statistics displayed correctly?
 Does the responsive design work?
 Does the data persist after a browser refresh?
```

#### Quiz Verification and Improvement

```
Quiz Question Validation Guidelines
Checklist for every question you write
1. Is there exactly one correct answer?
- If other interpretations are possible, state the criteria (e.g., by area, as of 2024)
2. Do superlative expressions have a stated basis?
- Specify the measurement basis for "largest," "first," etc.
3. Are the time frame and scope clear?
- State the point in time for information that can change
- Limit the geographic and categorical scope
4. Has it been verified?
- Check at least two sources for questionable information
- For contested topics, follow mainstream scholarship
```

```
Please check the contents of the current project's CLAUDE.md.
```

```
Please review the questions created so far with reference to the guidelines you just saved. If there are any quizzes or answers that do not comply with the guidelines, please revise them accordingly.
```

#### 05-2 Boosting development efficiency through automation

```
Create a custom command folder for the current project.
Create the .claude/commands directory and show the structure.
```

```
Create a .claude/commands/quiz-validate.md file.
Find any superlative expressions such as 'most', 'first', or 'largest' in the quiz questions and display them as a list.
```

```
Modify .claude/commands/quiz-validate.md as follows.
If the user specifies a category, validate only the questions in that category; if not specified, validate all questions.
Use the value entered in $ARGUMENTS as the category.
When validating, check for ambiguous expressions such as 'most', 'first', or 'maximum', and indicate what criteria need to be specified.
```

```
Create .claude/commands/quiz-range.md.
Create a function to review questions from $1 to $2.
Make it possible to check the difficulty and answer distribution of the questions.
```

```
Create .claude/commands/quiz-add.md.
Create a command to add new quizzes.
Receive $1 as the category and $2 as the difficulty, and process them.
Make it in the same format as the existing quizzes, and ensure that the verification guidelines are strictly followed.
Continue while checking the intermediate steps.
```

#### 05-3 Maintenance strategies learned through the use of custom commands

```
Create .claude/commands/quiz-check.md. It should perform the function of verifying the accuracy of all quiz answers.
Create .claude/commands/quiz-stats.md. It should perform the function of managing quiz game statistics.
Create .claude/commands/quiz-leaderboard.md. It should perform the function of managing the ranking system.
```

```
Use /quiz-check to verify all questions, /quiz-stats to analyze statistics, and /quiz-leaderboard to update the leaderboard, all in a single request.
```

```
.claude/commands/quiz-daily.md Create it and perform the following tasks in order.
1. Read and understand the structure of the file containing the quizzes
2. Check the current number and distribution of questions
3. Identify insufficient parts by category
4. Check for duplicates before adding new questions
5. Validate the format after adding questions
6. Back up all data
7. Report detailed execution results
Verify at each step, and if it fails, stop immediately and report the error.
```

```
Now I want to create a teacher mode that allows you to view and compare the scores of multiple students who have taken the quiz at a glance.
Please devise and create the custom commands needed for this feature.
And please also create an integrated command that collects and executes these commands together.
All commands must be saved as .md files in the '.claude/commands/' folder.
After execution, list and report the created custom commands and their functions.
```

```
Please modify .claude/commands/create-report.md as follows.
Change the grade display to a relative evaluation based on the top percentage and display it as follows.
- Top 20%: A
- Top 40%: B
- Top 70%: C
- Bottom 30%: D
```

```
Create a new file, .claude/commands/export-report.md.
It should read teacher_report.html and save it as CSV or PDF,
and add this command to teacher-dashboard.md.
```

---

### Chapter 6: Giving Claude Code Wings with APIs

```
I saved the API key I received from OpenRouter in the .env file. Please set it up so I can use this key securely.
```

```
Now test whether the prepared API actually works.
For image recognition, use the google/gemma-4-26b-a4b-it model,
For text generation, use the openai/gpt-oss-20b model.
Test both text and image recognition via the API and let me know the results.
```

#### Building the FridgeChef App (3 Steps)


```
Using the previously created OpenRouter API, I want to build a web application that recognizes ingredients from a refrigerator photo and recommends recipes. Please create a PRD divided into three steps as follows.
Step 1: Receive an image as input and use the google/gemma-4-26b-a4b-it model to recognize the image.
Step 2: Use the information obtained in Step 1 and the openai/gpt-oss-20b model to generate recipes.
Step 3: Create a user profile and save the recipes.
Save each step as PRD_step1.md, PRD_step2.md, and PRD_step3.md.
```

```
Run PRD_step1.md
```

```
The app works, but it still looks like a default Streamlit page. Give all three steps one shared look.
Put the styling in a single ui.py module so every step imports the same theme.
Use a warm cooking palette: orange #FF6B35 for accents, a cream background, white cards with soft shadows, and rounded corners.
Add a gradient title, a three-step "how it works" strip so the first screen is not mostly empty,
and hide the Streamlit toolbar, Deploy button, and sidebar collapse arrow so screenshots show only the app.
Keep every screen compact enough to fit a wide browser window without scrolling:
one-line page header, tight spacing, a capped height on the photo preview,
and the recognized ingredients in a two-column grid rather than a stack of expanders.
```

```
Run the main application and let me test the results of Step 1.
```

```
Now run PRD_step2.md.
```

```
Run the main application and test the results of step 2.
```

```
Now run PRD_step3.md.
```

---

### Chapter 7: Building a Development Team with Claude Code AI Agents

#### Creating AI Agents

**Code quality reviewer agent:**
```
Create a subagent called code-bug-analyzer that works only in this project. It is a code quality reviewer that checks for bugs, coding rule violations, and performance problems. Give it read-only access, and run it on Opus. Save it as .claude/agents/code-bug-analyzer.md
```

```
Have code-bug-analyzer review the code of the FridgeChef application.
```

**System optimization engineer agent:**
```
Create a second subagent called performance-optimizer. It is a performance engineer that speeds the app up and removes bottlenecks. Save it as .claude/agents/performance-optimizer.md
```

**User experience expert agent:**
```
Create a third subagent called ux-design-advisor. It is a user experience designer that reviews the layout and the interface and makes the app easier to use. Save it as .claude/agents/ux-design-advisor.md
```

#### Multi-Agent Collaboration

```
Have code-bug-analyzer review the entire FridgeChef application code, then have performance-optimizer fix the identified issues and optimize performance, and finally have ux-design-advisor improve the user experience.
```

```
Run the improved app so I can check it in the browser
```

```
Back up the current state.
```

```
Restore from backup.
```

#### Creating the Five-Agent Team

```
Create five subagents in the .claude/agents/ folder. product-manager-prd writes the PRD and manages the schedule, backend-architect designs the server and the APIs, frontend-developer builds the interface, qa-engineer handles testing and code review, and ai-integration-specialist connects the OpenRouter API. Set the model to sonnet for each of them.
```

#### AI Empathy Diary

```
Please create an AI empathy diary application, where, if the user writes a one-line summary of their day, the AI analyzes their emotions, offers empathy, and provides words of comfort.
The backend architect should implement the features for emotion analysis and empathetic message generation by integrating the OpenRouter API. Please use the openai/gpt-oss-20b model and the API key stored in the .env file within the current directory.
The frontend developer should design a diary UI that evokes a warm and comforting atmosphere.
Finally, the QA engineer should test the application to ensure it functions smoothly across various scenarios. Any issues found must be fully resolved, and the final version should be delivered as an index.html file that can be opened directly in a web browser.
```


#### PDF Summarizer App

```
We're going to create a web application where you can upload a PDF document and the AI will summarize it.
First, product-manager-prd will write a detailed PRD and feature specifications for the PDF document summary app and then the backend-architect will implement the PDF file upload and text extraction features.
The ai-integration-specialist will integrate the OpenRouter API to summarize the extracted text.
Use the openai/gpt-oss-20b model, and use the API key stored in the '.env' file in the current folder. The frontend-developer will implement a drag-and-drop file upload UI and a clean interface to display the summary results.
The qa-engineer should test to ensure everything works smoothly in various scenarios. If any issues are found, fix them completely, and create the final version as an 'index_pdf.html' file that can be opened directly in the browser.
```

---

### Chapter 8: Extending Claude Code with MCP, Skills, and Plugins

#### Installing and Using MCP Servers

**Notion MCP:**
```bash
claude mcp add --transport http notion https://mcp.notion.com/mcp
```

```
Summarize the latest changes in Claude Code and save them to 'Self-Study Vibe Notion Example' via Notion MCP.
```

**Sequential Thinking MCP:**

When running in Windows **PowerShell**:
```powershell
claude mcp add sequential-thinking -s local -- npx -y @modelcontextprotocol/server-sequential-thinking@latest
```

(Reference) When running in the Windows Command Prompt (cmd):
```cmd
claude mcp add sequential-thinking -s local -- cmd /c npx -y @modelcontextprotocol/server-sequential-thinking@latest
```

```
I want to double the time visitors spend on my web portfolio. Please create two documents:
1. Devise a way to achieve this goal and use the Notion MCP to save it as "Increase Dwell Time".
2. Use the Sequential Thinking MCP to systematically devise a way to achieve this goal, and then use the Notion MCP to save it as "Increase Dwell Time – Systematic Structure".
```

**Creating a skill:**
```
Create a skill that automatically reviews code.
```

**Recommending skills, MCP, and plugins:**
```
Recommend skills, MCP, or plugins needed for the current project.
```


**Playwright plugin:**

Run the `/plugin` command in Claude Code, find **Playwright** in the list, and select **Install for all collaborators on this repository (project scope)**.

```
Create a shopping list app. Make it a simple web UI that can add, delete, and check items, and runs locally in the browser.
```

```
Automatically test all the features of this shopping list app. Please check that adding, deleting, and checking all items work correctly.
```

**GitHub MCP:**
```bash
claude mcp add --transport http github https://api.githubcopilot.com/mcp -H "Authorization: Bearer YOUR_GITHUB_PAT"
```

```
I want to save the shopping list app created in the current folder to GitHub. Use github mcp to create a repository named shopping-list-app and upload it.
```

**Vercel:**
```
Rename the shopping-list.html file of the shopping list app to index.html and upload it to GitHub.
```

**Supabase MCP:**

```bash
claude mcp add supabase -s local -e SUPABASE_ACCESS_TOKEN=<Supabase API token> -- cmd /c npx -y @supabase/mcp-server-supabase@latest
```

```
Use Supabase MCP to connect our shopping list app to the database. Create a table called shopping_items, and modify the code so that the data previously stored in local storage is now saved to the Supabase database. Once the changes are complete, commit and push to GitHub.
```

---

Great work — you made it to the end!

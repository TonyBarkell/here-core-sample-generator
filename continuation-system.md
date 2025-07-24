# Conversation Continuity System - HERE Core PoC

## 🔄 CONTINUATION PROMPT TEMPLATE

**Use this to resume development in a new Claude conversation:**

```
I am continuing development of a HERE Core Container sample generator PoC with previous Claude conversations.

**PROJECT CONTEXT**:
- Goal: Create standardized prompt that reliably generates runnable HERE Core Container samples
- Focus: Understanding what information AI needs to succeed consistently
- Team: HERE Core Container support team
- Repository: https://github.com/TonyBarkell/here-core-sample-generator

**CURRENT STATE**:
Please review our current prompt and test results:
- Current Prompt: https://raw.githubusercontent.com/TonyBarkell/here-core-sample-generator/main/poc-prompt.md
- Test Results: https://raw.githubusercontent.com/TonyBarkell/here-core-sample-generator/main/results-log.md
- Iteration Notes: https://raw.githubusercontent.com/TonyBarkell/here-core-sample-generator/main/iteration-notes.md

**WHAT WE'VE LEARNED SO FAR**:
[COPY LATEST FINDINGS FROM ITERATION-NOTES.MD]

**TODAY'S OBJECTIVE**: 
[SPECIFIC GOAL: Test scenario X / Analyze results / Refine prompt / Add new pattern]

**SPECIFIC ISSUE** (if applicable):
[DESCRIBE ANY SPECIFIC PROBLEM YOU'RE TRYING TO SOLVE]

Please analyze our current state and help me continue the PoC development with full context.
```

## 📋 CONTINUATION CHECKLIST

**Before Starting New Conversation:**
- [ ] Update all GitHub files with latest results
- [ ] Commit changes with clear commit message
- [ ] Identify specific objective for new conversation
- [ ] Copy any specific error messages or issues
- [ ] Note which test scenarios still need completion

**In New Conversation:**
- [ ] Use continuation prompt above
- [ ] Replace [COPY LATEST FINDINGS] with actual content
- [ ] Specify exact objective for the session
- [ ] Reference specific files/results

## 🚨 CONVERSATION LIMIT WARNING SIGNS

**Watch for these indicators that limits may be approaching:**
- Responses becoming shorter or less detailed
- Claude mentioning conversation length
- Reduced ability to reference previous context
- General decrease in response quality

**When you suspect limits approaching:**
1. **Immediately update GitHub** with all current progress
2. **Document any active issues** in iteration-notes.md
3. **Prepare continuation prompt** with latest findings
4. **Note exactly where you left off**

## 📊 REGULAR CHECKPOINT PROCESS

**Every 10-15 messages, update GitHub with:**
- Latest test results in results-log.md
- New learnings in iteration-notes.md  
- Any prompt refinements in poc-prompt.md
- Clear notes about current focus/issues

**Commit message format:**
```
"PoC Progress: [Brief description] - Test X completed, found Y issue, next: Z"
```

## 🎯 SESSION PLANNING

**Structure each conversation session with clear objectives:**

### Testing Sessions
- **Goal**: Complete specific test scenario
- **Success**: Working sample + documented results
- **Handoff**: Updated results-log.md with findings

### Analysis Sessions  
- **Goal**: Analyze patterns from test results
- **Success**: Identified improvements for prompt
- **Handoff**: Updated iteration-notes.md with insights

### Refinement Sessions
- **Goal**: Update prompt based on learnings
- **Success**: New prompt version with improvements
- **Handoff**: Updated poc-prompt.md with changes

## 🔧 EMERGENCY RECOVERY

**If conversation ends abruptly with unsaved progress:**

1. **Check GitHub** for last committed state
2. **Use continuation prompt** with "URGENT: Lost progress on [describe what was happening]"
3. **Reconstruct from memory** and add to appropriate files
4. **Continue from last stable point**

## 📈 PROGRESS TRACKING

**Maintain these files as conversation continuity anchors:**

### /results-log.md
- **Purpose**: Test results and findings
- **Update**: After each test completion
- **Critical for**: Understanding what works/doesn't work

### /iteration-notes.md
- **Purpose**: Learning synthesis and prompt evolution
- **Update**: After analysis sessions
- **Critical for**: Prompt improvement decisions

### /poc-prompt.md
- **Purpose**: Current working prompt version
- **Update**: After refinement sessions
- **Critical for**: Maintaining latest improvements

## 🚀 OPTIMAL WORKFLOW

**For maximum continuity and progress:**

1. **Start each session** with clear, specific objective
2. **Work in focused bursts** on single goals
3. **Update GitHub regularly** (every 10-15 messages)
4. **End sessions cleanly** with status documentation
5. **Begin new sessions** with continuation prompt + latest state

---

**INTEGRATION**: Add this file to your repository as `/continuation-system.md`  
**PURPOSE**: Ensure zero progress loss due to conversation limits  
**MAINTENANCE**: Update the continuation prompt as the project evolves

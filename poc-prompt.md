# HERE Core Container - PoC Sample Generator Prompt

## 📋 STANDARD PROMPT

```
I am a HERE Core Container customer support manager. I need you to create a complete, runnable HERE Core Container sample application.

**REQUIREMENT**: [DESCRIBE_WHAT_THE_SAMPLE_SHOULD_DEMONSTRATE]

**DELIVERABLES REQUIRED**:
1. Complete file structure with all necessary files
2. Proper HERE Core Container manifest configuration  
3. Setup script to run the sample locally
4. Clear instructions for testing

**FOUNDATION KNOWLEDGE**:
- HERE Core Container documentation: https://resources.here.io/docs/core/
- API documentation: https://cdn.openfin.co/docs/javascript/stable/
- Example patterns: https://github.com/built-on-openfin/container-starter

**CRITICAL REQUIREMENTS**:
- Sample must launch successfully on HERE Core Container
- Include only features necessary for the demonstration
- Keep implementation as simple as possible
- Provide step-by-step setup instructions
- Include basic error handling and console logging

**OUTPUT FORMAT**: 
Please provide all files needed with clear file names and complete content for each file.

**VALIDATE BEFORE DELIVERING**: 
- Manifest uses correct HERE Core Container syntax
- Platform API uses "providerUrl" not "url" 
- All HTML files are complete and valid
- Setup instructions are clear and actionable
```

## 🔄 Usage Instructions

1. **Copy the prompt above**
2. **Replace the [REQUIREMENT] section** with specific needs
3. **Run with AI** (Claude, ChatGPT, etc.)
4. **Test the generated sample**
5. **Document results** in results-log.md

## 📝 Example Requirements

### Basic Platform Window
"Create a sample that opens a Platform API window with 2 views showing different web pages"

### Notification Testing
"Create a sample that demonstrates HERE Core Container notifications with test buttons"

### Performance Measurement
"Create a sample that opens 10 views and measures their loading time"

---
**Status**: Initial PoC version  
**Last Updated**: 2025-01-23

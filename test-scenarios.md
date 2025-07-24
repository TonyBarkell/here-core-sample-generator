# Test Scenarios for PoC Validation

## 🧪 Standard Test Cases

### Test 1: Basic Platform Window
**Requirement**: "Create a sample that opens a Platform API window with 2 views showing different web pages"

**Expected Files**:
- manifest.fin.json
- provider.html  
- app.html (or similar)
- setup script
- README with instructions

**Success Criteria**:
- [ ] Manifest syntax correct
- [ ] Platform provider initializes
- [ ] Window opens with 2 views
- [ ] Views load different content
- [ ] No console errors

### Test 2: Notification Center
**Requirement**: "Create a sample that demonstrates HERE Core Container notifications with test buttons"

**Expected Files**:
- manifest.fin.json with notification permissions
- app.html with notification controls
- setup script
- README with instructions

**Success Criteria**:
- [ ] Notification permissions configured
- [ ] Test buttons work
- [ ] Notifications appear correctly
- [ ] No permission errors

### Test 3: Performance Testing
**Requirement**: "Create a sample that opens 10 views and measures their loading time"

**Expected Files**:
- manifest.fin.json
- provider.html with performance measurement
- app.html or views
- setup script
- README with instructions

**Success Criteria**:
- [ ] 10 views create successfully
- [ ] Loading time measurement works
- [ ] Performance data logs to console
- [ ] No memory/performance issues

### Test 4: Basic Interop
**Requirement**: "Create a sample that demonstrates basic context sharing between 2 views"

**Expected Files**:
- manifest.fin.json
- provider.html
- view1.html and view2.html
- interop/messaging code
- setup script

**Success Criteria**:
- [ ] 2 views can communicate
- [ ] Context sharing works
- [ ] Message passing functions
- [ ] Clear demonstration of interop

## 📊 Testing Process

### For Each Test:
1. **Run the prompt** with the requirement
2. **Generate sample** using AI
3. **Create local test** of the generated files
4. **Document results** in results-log.md
5. **Note any issues** or missing information

### Evaluation Criteria:
- **File Completeness**: All necessary files generated
- **Syntax Accuracy**: Correct HERE Core Container configuration
- **Functional Success**: Sample runs without errors
- **Requirement Match**: Demonstrates what was requested
- **Instruction Quality**: Setup instructions work

---
**Last Updated**: 2025-01-23

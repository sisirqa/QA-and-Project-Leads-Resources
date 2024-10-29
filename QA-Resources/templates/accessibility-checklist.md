# Accessibility Testing Checklist

## Project Information
- **Project Name:** [Project Name]
- **Version:** [Version Number]
- **Test Date:** [Date]
- **Tester:** [Name]

## WCAG 2.1 Compliance Checklist

### 1. Perceivable
#### 1.1 Text Alternatives
- [ ] All images have meaningful alt text
- [ ] Complex images have detailed descriptions
- [ ] Decorative images use empty alt attributes
- [ ] Form controls have descriptive labels
- [ ] Icons have accessible names
- [ ] SVGs have proper ARIA labels

#### 1.2 Time-based Media
- [ ] Videos have captions
- [ ] Audio content has transcripts
- [ ] Auto-playing media can be paused
- [ ] Media players have keyboard controls
- [ ] Videos have audio descriptions where needed

#### 1.3 Adaptable
- [ ] Content can be presented in different ways
- [ ] Correct HTML semantic structure
- [ ] Meaningful sequence of content
- [ ] Instructions don't rely on sensory characteristics
- [ ] Form fields have proper labels and relationships
- [ ] Tables have proper headers and structure

#### 1.4 Distinguishable
- [ ] Color is not the only means of conveying information
- [ ] Text color contrast meets minimum ratios:
  - Regular text: 4.5:1
  - Large text: 3:1
  - UI components: 3:1
- [ ] Text can be resized up to 200% without loss of functionality
- [ ] Images of text are avoided where possible
- [ ] Content is responsive and reflows
- [ ] Spacing between elements is sufficient

### 2. Operable
#### 2.1 Keyboard Accessible
- [ ] All functionality available via keyboard
- [ ] No keyboard traps
- [ ] Keyboard focus is visible
- [ ] Keyboard shortcuts are documented
- [ ] Skip links for navigation
- [ ] Focus order is logical

#### 2.2 Enough Time
- [ ] Time limits can be adjusted
- [ ] Moving content can be paused
- [ ] Auto-updates can be controlled
- [ ] Session timeout warnings
- [ ] No interruptions unless necessary

#### 2.3 Seizures and Physical Reactions
- [ ] No content flashes more than 3 times per second
- [ ] Animation can be disabled
- [ ] Reduced motion options available

#### 2.4 Navigable
- [ ] Clear page titles
- [ ] Descriptive headings and labels
- [ ] Clear focus order
- [ ] Purpose of links is clear from context
- [ ] Multiple ways to find content
- [ ] Descriptive breadcrumbs

#### 2.5 Input Modalities
- [ ] Touch targets are at least 44x44 pixels
- [ ] Gestures have alternatives
- [ ] Motion control can be disabled
- [ ] Labels match corresponding input fields

### 3. Understandable
#### 3.1 Readable
- [ ] Page language is specified
- [ ] Language changes are marked
- [ ] Unusual words are explained
- [ ] Abbreviations are explained
- [ ] Reading level is appropriate
- [ ] Pronunciation is provided where needed

#### 3.2 Predictable
- [ ] Navigation is consistent
- [ ] Components behave consistently
- [ ] Changes of context are user-initiated
- [ ] Error identification is clear
- [ ] Labels are consistent

#### 3.3 Input Assistance
- [ ] Error prevention on important data
- [ ] Clear error messages
- [ ] Error suggestions provided
- [ ] Form validation
- [ ] Input format examples
- [ ] Help text is available

### 4. Robust
#### 4.1 Compatible
- [ ] Valid HTML/ARIA usage
- [ ] Name, role, value available for all UI components
- [ ] Status messages can be programmatically determined
- [ ] Custom controls have proper roles

## Testing Tools and Methods
- [ ] Automated testing tools used:
  - WAVE
  - Axe
  - Lighthouse
  - NVDA
  - VoiceOver
- [ ] Manual keyboard navigation testing
- [ ] Screen reader testing
- [ ] Browser zoom testing
- [ ] Mobile device testing

## Compliance Notes

### WCAG Conformance Levels
1. **Level A (Must Support)**
   - Minimum level of accessibility
   - Basic web accessibility features
   - Essential for legal compliance
   
2. **Level AA (Should Support)**
   - Addresses major accessibility barriers
   - Standard level for most commercial websites
   - Required by many government regulations
   
3. **Level AAA (May Support)**
   - Highest level of accessibility
   - May not be achievable for all content
   - Recommended for specialized applications

### Legal Requirements by Region

#### United States
- **ADA (Americans with Disabilities Act)**
  - Applies to all public accommodations
  - Web content should be accessible
  - WCAG 2.1 Level AA recommended
  
- **Section 508**
  - Mandatory for federal websites
  - Requires WCAG 2.0 Level AA compliance
  - Applies to government contractors

#### European Union
- **EN 301 549**
  - EU-wide accessibility standard
  - Based on WCAG 2.1 Level AA
  - Required for public sector websites

#### Other Considerations
- Mobile accessibility guidelines
- PDF/document accessibility
- Third-party content compliance
- Regular audit requirements

### Testing Documentation Requirements
1. **Test Reports Must Include:**
   - Compliance level tested against
   - Tools and methods used
   - Issues found and severity
   - Remediation recommendations
   
2. **Evidence Required:**
   - Screenshots of issues
   - Screen reader test results
   - Contrast analyzer reports
   - Keyboard navigation recordings

3. **Periodic Reviews:**
   - Quarterly compliance checks
   - Annual full audits
   - Change impact assessments
   - User feedback incorporation

### Common Exemptions
1. **Content Types:**
   - Archive content (pre-2018)
   - Third-party content not under control
   - Live audio/video content
   
2. **Temporary Exemptions:**
   - Beta/testing features
   - Emergency content
   - Time-limited promotions

### Best Practices for Development
1. **Design Phase:**
   - Include accessibility in wireframes
   - Review color schemes for contrast
   - Plan semantic structure
   
2. **Development Phase:**
   - Use semantic HTML
   - Implement ARIA where needed
   - Test early and often
   
3. **Testing Phase:**
   - Automated and manual testing
   - User testing with assistive technologies
   - Documentation of findings

### Remediation Priority Levels
1. **Critical (P0)**
   - Blocks access for users
   - Legal compliance issues
   - Fix immediately
   
2. **High (P1)**
   - Major usability impact
   - Affects many users
   - Fix within sprint
   
3. **Medium (P2)**
   - Moderate impact
   - Workarounds available
   - Plan for next release
   
4. **Low (P3)**
   - Minor issues
   - Minimal impact
   - Schedule as resources allow

## Sign-off Requirements
- [ ] All Level A criteria met
- [ ] All Level AA criteria met
- [ ] Selected Level AAA criteria met
- [ ] Legal compliance verified
- [ ] Documentation complete

## Change Log
| Date | Version | Changes | Author |
|------|----------|---------|---------|
| [Date] | 1.0 | Initial version | [Name] |

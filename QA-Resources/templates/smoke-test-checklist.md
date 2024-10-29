# Smoke Test Checklist

## Project Information
- **Project Name:** [Project Name]
- **Version/Build:** [Version Number]
- **Environment:** [Dev/QA/Staging/Production]
- **Tester:** [Name]
- **Date:** [Test Date]
- **Build/Release:** [Build Number]

## 1. Authentication & Authorization
### User Login
- [ ] Login with valid credentials
- [ ] Login with SSO (if applicable)
- [ ] Password reset functionality
- [ ] Remember me functionality
- [ ] Session timeout handling
- [ ] Logout functionality

### User Permissions
- [ ] Admin access verification
- [ ] Regular user access verification
- [ ] Role-based access controls
- [ ] Feature access based on user type

## 2. Core Features
### Navigation
- [ ] Main menu functionality
- [ ] Navigation between key pages
- [ ] Breadcrumb navigation
- [ ] Back button behavior
- [ ] Menu item permissions

### Search Functionality
- [ ] Basic search
- [ ] Advanced search filters
- [ ] Search results display
- [ ] Sort/filter functionality

### Data Operations
- [ ] Create new record
- [ ] Read existing record
- [ ] Update record
- [ ] Delete record
- [ ] Bulk operations (if applicable)

## 3. UI/UX Components
### Forms
- [ ] Form validation
- [ ] Required fields
- [ ] Error messages
- [ ] Form submission
- [ ] Form reset/cancel

### Display Elements
- [ ] Tables/Lists loading
- [ ] Pagination
- [ ] Sorting
- [ ] Filtering
- [ ] Data refresh/reload

### Interactive Elements
- [ ] Buttons functionality
- [ ] Links functionality
- [ ] Dropdowns/Select menus
- [ ] Modal dialogs
- [ ] Tooltips/Help text

## 4. Data Integration
### Database
- [ ] Database connectivity
- [ ] CRUD operations
- [ ] Data integrity
- [ ] Transaction handling

### API Integration
- [ ] API endpoints accessibility
- [ ] Basic API responses
- [ ] Error handling
- [ ] API authentication

### Third-party Services
- [ ] External service connections
- [ ] Payment gateway (if applicable)
- [ ] Email service
- [ ] File storage service

## 5. File Operations
- [ ] File upload
- [ ] File download
- [ ] File preview
- [ ] Supported file types
- [ ] File size limitations

## 6. Notifications
- [ ] System notifications
- [ ] Email notifications
- [ ] Push notifications
- [ ] Alert messages
- [ ] Error messages

## 7. Mobile Responsiveness
- [ ] Desktop view
- [ ] Tablet view
- [ ] Mobile view
- [ ] Critical features on mobile
- [ ] Touch interactions

## 8. Performance Checks
- [ ] Page load times
- [ ] Transaction response times
- [ ] Search response times
- [ ] Report generation
- [ ] Concurrent user actions

## 9. Security Checks
- [ ] SSL/TLS verification
- [ ] Security headers
- [ ] Session management
- [ ] Access controls
- [ ] Input validation

## 10. Error Handling
- [ ] 404 page
- [ ] Error messages
- [ ] Validation messages
- [ ] System errors
- [ ] Network error handling

## Test Results Summary
### Issues Found
| ID | Description | Severity | Status |
|----|-------------|----------|---------|
| 1  | [Issue description] | [High/Medium/Low] | [Open/Fixed] |

### Performance Notes
- Load time observations:
- Response time issues:
- System behavior under load:

### Browser/Device Coverage
| Browser/Device | Version | Status |
|---------------|---------|---------|
| Chrome | [Version] | [Pass/Fail] |
| Firefox | [Version] | [Pass/Fail] |
| Safari | [Version] | [Pass/Fail] |
| Mobile iOS | [Version] | [Pass/Fail] |
| Mobile Android | [Version] | [Pass/Fail] |

## Sign-off
### Test Completion
- [ ] All critical tests completed
- [ ] No blocking issues found
- [ ] Performance is acceptable
- [ ] Security requirements met

### Approvals
- **QA Engineer:** [Name & Date]
- **Product Owner:** [Name & Date]
- **Development Lead:** [Name & Date]

## Notes
- Test environment details:
- Known issues:
- Recommendations:

## Change Log
| Version | Date | Changes | Author |
|---------|------|----------|---------|
| 1.0 | [Date] | Initial version | [Name] |

---

**Instructions for Use:**
1. Copy this template for each smoke test cycle
2. Update project information
3. Check each item as it's tested
4. Document any issues found
5. Add relevant screenshots/evidence
6. Get required sign-offs
7. Store in project documentation

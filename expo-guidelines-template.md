# Technical Guidelines
## Expo Project Specifications

### Technology Stack
- **Expo Platform**: All development must follow Expo best practices
- **TypeScript**: All code must be written in TypeScript
- **Testing**: Jest and Detox for unit and integration testing

### 1. Expo-Specific Commands
- Use `npx expo` for all Expo CLI commands
- For package installation, use `npx expo install` for Expo-compatible dependencies
- For running the app, use `npx expo start`
- For building, use `npx expo prebuild` or `npx expo run:[platform]`

### 2. Project Organization
- Respect the established folder structure (see project root and `src/` organization)
- Follow existing naming conventions for new files and folders
- Reference `docs/` folder for specific structure guidance

### 3. Technical Documentation
- Refer to `docs/glossary.md` for domain-specific terminology
- Consult `docs/tech-doc.md` for technical specifications and requirements
- Review `docs/tech-stack.md` for technology decisions and dependencies

### 4. Offline & Synchronization
- All features must support offline mode and data synchronization
- Implement robust conflict resolution for synced data
- Review offline requirements in `docs/tech-doc.md`

### 5. AI & Personalization
- Follow AI prompt structure documentation when modifying AI-driven features
- Test AI-driven routine generation for expected outputs
- Ensure personalization logic follows guidelines in AI integration documentation

### 6. Accessibility & UX
- Follow accessibility best practices (touch targets, contrast, text scaling)
- Test UI changes on both iOS and Android for consistency
- Adhere to UX guidelines in `docs/tech-doc.md`

### 7. Security & Privacy
- Protect user data privacy in all features handling sensitive information
- Follow security guidelines in `docs/tech-doc.md`
- Document any new security considerations or mitigations

### 8. API & Backend
- Document API endpoints and backend logic changes
- Ensure API changes maintain backward compatibility where possible
- Clearly document any breaking changes

### 9. Testing Requirements
- Cover new code with tests using Jest/Detox
- Follow established testing patterns in `src/__tests__/`
- Document any new testing approaches

### 10. Error Handling & Logging
- Implement user-friendly error messages for all user-facing features
- Add appropriate error logging for debugging and support
- Test error scenarios and recovery processes

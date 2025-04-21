# Interactive Post Component

A React Native component for displaying social media posts with like liking and commenting.

## How to Run the Project

1. Clone this repository
2. Install dependencies:
   \`\`\`
   yarn
   \`\`\`

3. Run on iOS or Android:
   \`\`\`
   yarn android
   \`\`\`
   

### Component Structure
- Used a functional component with hooks for modern React Native.

### State Management
- Used local state with `useState` for managing the like status and count
- Implemented optimistic UI updates for likes to improve perceived performance

### Styling
- Used StyleSheet for performance optimization rather than inline styles
- Created a visually cohesive design that matches standard social media post patterns

## Future Improvements

- Add proper TypeScript typing for better code safety
- Implement a more sophisticated image loading system with placeholders and error states
- Add animation for the like button interaction
- Implement comment threading and display

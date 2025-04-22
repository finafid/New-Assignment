# New-Assignment
 
### Interactive Post Component

A reusable React Native component for displaying social media posts with interactive features like liking and commenting.

## How to Run the Project

1. Clone this repository
2. Install dependencies:
   \`\`\`
   yarn install
   \`\`\`
4. Run on iOS or Android:
   \`\`\`
   yarn ios
   \`\`\`
   or
   \`\`\`
   yarn android
   \`\`\`

### Component Structure
- Used a functional component with hooks for modern React Native .
- Used expo vector-icon for icons.

### State Management
- Used local state with `useState` for managing the like status and count
- Implemented optimistic UI updates for likes to improve perceived performance

### Styling
- Used StyleSheet for performance optimization rather than inline styles

## Libraries

This implementation is intentionally minimalist and doesn't rely on external libraries to demonstrate core React Native concepts. In a production app, I would consider adding:

- **date-fns** for date handling 
- **expo vector-icon** for better icon 
- **react-navigation** for navigation between screens



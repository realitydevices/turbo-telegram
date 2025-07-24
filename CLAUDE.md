# Claude Development Guidelines

This file contains development guidelines and best practices for the Turbo Telegram Snake Game project.

## Project Overview

This is a browser-based Snake game implemented in pure HTML, CSS, and JavaScript. The game runs entirely in the browser without any backend dependencies.

## Development Patterns

### File Structure
- Keep the project simple and focused
- Use semantic HTML structure
- Organize CSS with logical sections (reset, layout, game-specific, responsive)
- Structure JavaScript with clear separation of concerns (game logic, rendering, input handling)

### Code Style
- Use modern JavaScript (ES6+) features
- Prefer const/let over var
- Use descriptive variable and function names
- Keep functions small and focused on single responsibilities
- Add comments for complex game logic

### Game Development Practices
- Maintain consistent frame rate for smooth gameplay
- Handle edge cases (wall collisions, self-collision)
- Implement proper game state management (playing, paused, game over)
- Use requestAnimationFrame for smooth animations
- Ensure responsive design for different screen sizes

### Testing
- Test across different browsers (Chrome, Firefox, Safari, Edge)
- Verify mobile responsiveness and touch controls
- Test game mechanics thoroughly (scoring, collision detection, food generation)

### Git Workflow
- Use descriptive commit messages
- Keep commits focused on single features or fixes
- Tag releases for stable versions

### Deployment
- GitHub Pages is configured for automatic deployment
- The game should work as a static site with no build process required
- Ensure all assets are properly referenced with relative paths

## Commands

Since this is a pure client-side project, there are no build commands needed. The game runs directly by opening index.html in a browser.

For development:
- Simply open `index.html` in your browser
- Use browser developer tools for debugging
- No package manager or build tools required

## Browser Compatibility

Target modern browsers with ES6+ support:
- Chrome 60+
- Firefox 55+  
- Safari 12+
- Edge 79+

## Performance Considerations

- Keep the game loop efficient
- Minimize DOM manipulations during gameplay
- Use CSS transforms for smooth animations
- Optimize collision detection algorithms
- Consider using Canvas API for better performance if needed

## Future Enhancements

When adding new features, consider:
- High score persistence (localStorage)
- Multiple difficulty levels
- Sound effects and music
- Power-ups and special food items
- Different snake skins/themes
- Multiplayer support
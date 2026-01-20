# Task
Build an emoji tracing feature for lesson.html to help Henry practice drawing.

## Feature Requirements
Add a new section below the existing name learning sections with:

1. **Emoji Tracing Area**
   - Create a canvas drawing area overlaid on top of a monkey face emoji (🐵)
   - The emoji should be large and clearly visible under the transparent drawing canvas
   - Drawing should be in blue color (stroke)
   - Canvas must work with both mouse (desktop) and touch (mobile/tablet)
   
2. **Drawing Controls**
   - Clear button to erase and start over
   - The monkey emoji should remain visible after clearing
   
3. **Styling**
   - Match the existing colorful, child-friendly design
   - Add appropriate spacing and borders consistent with the name sections
   - Include a title like "✏️ Trace the Emoji! ✏️"

4. **Mobile Touch Support**
   - Prevent scrolling while drawing
   - Support single-finger touch drawing
   - Ensure smooth lines on both mouse and touch devices

5. **Testing Requirements**
   - Test mouse drawing works
   - Test touch drawing works on mobile
   - Test clear button resets canvas but keeps emoji visible
   - Test that page doesn't scroll while drawing on mobile
   - Verify it works on different screen sizes

# Completion Criteria
When ALL of these are true, output COMPLETE:
- All tests passing
- No TypeScript errors
- Feature works as specified
- Documentation updated

# Current State
Read progress.txt to see what's been done.

# Instructions
1. Check progress.txt
2. Work on the next incomplete item
3. Update progress.txt with what you did
4. If all done, output COMPLETE
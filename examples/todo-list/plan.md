# Plan: Todo List Component

## Goal
Build a functional todo list with add, complete, and delete operations using React hooks.

## Tasks

1. **Create `src/components/TodoList.tsx`**
   - Main component with input field and list rendering
   - State management with useState
   - Acceptance: Renders input + list of todos

2. **Create `src/components/TodoItem.tsx`**
   - Individual todo item with complete toggle and delete button
   - Visual strikethrough for completed items
   - Acceptance: Can toggle complete and delete

3. **Create `src/hooks/useTodos.ts`**
   - Custom hook for todo state logic
   - Functions: addTodo, toggleTodo, deleteTodo
   - Acceptance: All operations work, handles empty state

4. **Create `src/components/TodoList.css`**
   - Basic flex layout
   - Strikethrough for completed items
   - Acceptance: Looks decent, responsive

## Constraints
- Use React useState and useCallback hooks only
- No external state management libraries
- Must handle empty state gracefully
- No backend/storage needed

## Risks
- Hook complexity could grow — keep it simple
- Styling might clash with existing app — use scoped CSS

## Success Criteria
- Can add todos via input + Enter
- Can mark complete (visual strikethrough)
- Can delete todos
- Empty state shows friendly message
- No console errors

# Telos Product Structure Map

## 1. Dashboard (Home)
- **Functionality:** Central life board featuring quote, date, week view, timeline, top three tasks, and habit tracking.
- **Interface Logic:** Apple Calendar-inspired horizontal timeline with layered typography: collapsible quote header, bold weekday, large numeric date, and blurred month/year background.
- **Widgets & Layout:**
  1. Quote panel
  2. Date & 7-day week strip (horizontal scroll)
  3. Drag-and-drop timeline
  4. "Top 3" tasks block
  5. Habit rings (up to five)
  6. Statistics icon adjacent to date that opens overlay
- **AI Behavior:** Prioritizes top tasks, auto-positions items by time/energy, generates motivational quotes, tracks completion.
- **Interaction & Navigation:** Swipe horizontally to switch days, tap date to open statistics overlay, long-press timeline to create task.

## 2. Statistics Overlay
- **Functionality:** Visualizes balance between focus, habits, mood, and gratitude.
- **Interface Logic:** Semi-transparent overlay sliding from top above blurred dashboard.
- **Widgets & Layout:**
  1. Four color rings (Focus / Habits / Mood / Gratitude)
  2. Insight card with AI-generated note
  3. Weekly trend chart
- **AI Behavior:** Correlates productivity with emotion and provides daily insight (e.g., peak focus periods).
- **Interaction & Navigation:** Swipe down to close; auto-refreshes on open.

## 3. Journal Page
- **Functionality:** Daily reflection space capturing gratitude and victories.
- **Interface Logic:** Minimal centered layout with mood-responsive blurred glass gradient background.
- **Widgets & Layout:**
  1. Mood selector (emoji row)
  2. AI question placeholder
  3. Journal text area
  4. "Three Gratitudes" block
  5. "Three Wins" block
  6. Archive timeline (lower section)
- **AI Behavior:** Analyzes emotional tone, stores metrics, and offers reflection prompts.
- **Interaction & Navigation:** Swipe down to access archive; tapping mood recolors background.

## 4. Task Bank
- **Functionality:** Repository for all unscheduled tasks.
- **Interface Logic:** Todoist-style cards with soft shadow and category bar.
- **Widgets & Layout:**
  1. Quick-add bar ("+ Task")
  2. Tabs: Today / Week / Later / Ideas
  3. Drag-enabled task cards
- **AI Behavior:** Predicts urgency, auto-assigns tags, suggests scheduling windows.
- **Interaction & Navigation:** Drag tasks to timeline or priority blocks; tap card to open detail editor.

## 5. Projects Page
- **Functionality:** Thematic project spaces with contextual AI assistance.
- **Interface Logic:** Grid of glass cards leading to split view (tasks on left, AI chat on right).
- **Widgets & Layout:**
  1. Project cards (title, progress ring, last updated)
  2. Split view containing subtasks list and AI assistant chat
- **AI Behavior:** Provides scoped reasoning, creates subtasks, goals, and insights.
- **Interaction & Navigation:** Tap project to enter split view; swipe right to return.

## 6. Habits Page
- **Functionality:** Track and visualize habit consistency.
- **Interface Logic:** Apple Fitness-inspired rings with matte glass styling.
- **Widgets & Layout:**
  1. Up to five habit rings
  2. Add habit button
  3. Weekly streak graph
- **AI Behavior:** Suggests optimal times, detects patterns, correlates with tasks.
- **Interaction & Navigation:** Tap ring to mark complete; hold to edit habit.

## 7. AI Chat (Telos Engine)
- **Functionality:** Universal command center integrating all modules.
- **Interface Logic:** Fullscreen glass interface with green glow cursor and typing effects.
- **Widgets & Layout:**
  1. Chat thread
  2. Quick-command row (e.g., "Summarize day", "Plan tomorrow", "Analyze week")
  3. Voice input button
- **AI Behavior:** Central intelligence summarizing, planning, and shifting focus based on data.
- **Interaction & Navigation:** Swipe up from bottom to open; supports voice or text input.

## 8. Settings
- **Functionality:** Customization hub for layout and preferences.
- **Interface Logic:** iOS-style list with toggles and drag handles.
- **Widgets & Layout:**
  1. Widget toggles
  2. Block reorder handles
  3. Theme selector
  4. Backup / Restore controls
- **AI Behavior:** Learns user patterns and suggests layout optimizations.
- **Interaction & Navigation:** Access via bottom-right gear; drag to reorder blocks.

## 9. Notes (Smart Notes)
- **Functionality:** Quick capture and AI clustering of ideas.
- **Interface Logic:** Compact card grid with green accent glow on hover.
- **Widgets & Layout:**
  1. Quick note input
  2. Tag bar
  3. AI summary section
- **AI Behavior:** Groups notes by topic and links ideas to projects or tasks.
- **Interaction & Navigation:** Swipe left to delete; tap to expand note.

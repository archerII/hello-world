# CLAUDE.md

## Skills

### 1. React Performance Optimization

- Identify and fix unnecessary re-renders using `React.memo`, `useMemo`, and `useCallback`
- Implement code splitting with `React.lazy` and `Suspense` for faster initial load
- Use virtualization (e.g., `react-window`, `react-virtuoso`) for large lists and tables
- Profile components with React DevTools and diagnose bottleneck renders
- Optimize state management: colocate state, avoid lifting state unnecessarily, prefer granular context providers
- Apply best practices for `useEffect` dependencies to prevent infinite loops and stale closures
- Prefer server components and streaming where applicable (Next.js / React 19+)
- Minimize bundle size: tree-shake imports, audit dependencies, use dynamic imports

### 2. Writing Clearly and Concisely

- Use short, direct sentences; eliminate filler words and redundant phrases
- Lead with the main point — don't bury it
- Prefer active voice over passive voice
- One idea per paragraph; use bullet points for lists of 3+ items
- Replace jargon with plain language unless the audience expects technical terms
- Cut adverbs and weak qualifiers ("very", "really", "somewhat") — use precise words instead
- Re-read and trim: if removing a word doesn't change the meaning, remove it
- Structure longer pieces with clear headings and logical flow

### 3. Brainstorming

- Generate ideas without judgment first — quantity before quality
- Use divergent thinking: explore multiple angles, analogies, and "what if" scenarios
- Apply structured frameworks: SCAMPER, mind maps, reverse brainstorming, six thinking hats
- Challenge assumptions explicitly — ask "why does it have to be this way?"
- Combine and remix ideas from different domains for novel solutions
- Set constraints to spark creativity (e.g., "solve this with zero budget", "in one sentence")
- Organize and prioritize output: group related ideas, rank by feasibility and impact
- Always conclude with a shortlist of the top 3-5 actionable ideas

### 4. Agentation

- Design and orchestrate multi-agent workflows where specialized agents handle distinct subtasks
- Define clear agent roles, responsibilities, and boundaries to avoid duplication
- Implement effective handoff protocols between agents (input/output contracts, context passing)
- Use planning agents to decompose complex goals into sequenced or parallel sub-goals
- Apply reflection and self-critique loops: agents evaluate their own output before passing it forward
- Handle failure gracefully — retry logic, fallback strategies, and escalation paths
- Monitor agent execution with structured logging and observability
- Optimize for token efficiency: minimize redundant context, summarize intermediate results

### 5. Tailwind Design System

- Build consistent, reusable UI components using Tailwind CSS utility classes
- Define and enforce a design token system: colors, spacing, typography, border radius, shadows
- Use `@apply` sparingly — prefer utility-first composition over custom CSS abstractions
- Configure `tailwind.config.js` with a custom theme that reflects the brand's design language
- Implement responsive design with Tailwind breakpoints (`sm`, `md`, `lg`, `xl`, `2xl`)
- Use Tailwind plugins for forms, typography, and aspect-ratio when needed
- Maintain dark mode support using Tailwind's `dark:` variant with a toggle mechanism
- Ensure accessibility: sufficient color contrast, focus-visible states, semantic HTML alongside Tailwind classes

### 6. UI/UX ProMax

- Apply user-centered design principles: research, prototype, test, iterate
- Design clear visual hierarchy using size, color, contrast, and whitespace
- Ensure intuitive navigation and information architecture
- Follow established UX heuristics (Nielsen's 10 heuristics) and accessibility standards (WCAG 2.1 AA)
- Create micro-interactions and transitions that feel responsive and purposeful, not decorative
- Design for edge cases: empty states, error states, loading states, and long content
- Use consistent patterns for common UI elements (modals, forms, toasts, tables)
- Optimize for mobile-first and touch interactions; test across devices and screen sizes
- Validate designs with real user feedback — usability testing over assumptions

### 7. Writing Skills (Obra Superpowers)

- Adapt tone and style to the target audience and medium (blog, docs, email, marketing, technical)
- Structure writing with a clear beginning (hook), middle (substance), and end (call to action or summary)
- Use storytelling techniques: concrete examples, analogies, and narrative arcs to make content engaging
- Apply the "so what?" test to every paragraph — ensure the reader understands why it matters
- Edit ruthlessly: remove cliches, tighten prose, replace vague language with specifics
- Use formatting strategically: headers, bold, lists, and callouts to improve scannability
- Maintain a consistent voice across all content — define and follow a style guide
- Write with empathy: anticipate reader questions, objections, and knowledge gaps

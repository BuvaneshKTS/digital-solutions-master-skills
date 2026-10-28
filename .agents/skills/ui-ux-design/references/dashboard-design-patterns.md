# Dashboard Design Patterns

Design dashboards around user decisions and recurring tasks, not around a collection of cards.

## Start with the dashboard's job
Identify the user, how often they visit, the decision or action they need to take, what must be understood in the first five seconds, and which information is actionable versus informational.

## Choose an information architecture
Choose the smallest structure that serves the task. Useful patterns include:
- Action-first: next step or task, then supporting context.
- Overview-first: status summary, then drill-down.
- Workflow-first: queues, stages, and work requiring attention.
- Performance-first: trends and comparisons with context.
- Learning-first: next learning action, progress, weak areas, and assessment entry points.

Do not assume every dashboard needs KPI cards, charts, feeds, and shortcuts.

## Create hierarchy
Prioritize the primary action or alert, core progress or performance, and supporting details. This is a guide, not a fixed sequence. Reorder based on user value and urgency.

## Avoid the card-wall problem
Do not put every item in its own card. Use typography, whitespace, section backgrounds, dividers, and layout variation to create groups. Reserve strong color and elevation for meaningful priority. Avoid redundant headings and repeated labels.

## Design metrics responsibly
Every metric needs a clear label and, where relevant, unit, period, status meaning, and comparison context. Never invent targets, trends, or comparisons. Distinguish no data from zero.

## Education dashboards
Consider the next learning action, today's task, progress with context, weak topics or revision, mock exam entry points, and recent activity only when it helps the learner resume. Be encouraging without childish styling, shame, or alarm fatigue.

## Responsive behavior
Keep global navigation distinct from content. Adapt sidebars to compact navigation when appropriate. Reflow content by priority, preserve reading order, and provide usable alternatives for wide tables and dense controls. Never allow important content to clip.

## States and data integrity
Design loading, empty, error, stale-data, and success states. Do not imply live updates unless supported. Use status text and non-color indicators.

## Review
- Can users tell where they are and what to do next?
- Is there one obvious primary action when appropriate?
- Are metrics understandable without guessing?
- Is the layout more than a monotonous card grid?
- Does it feel specific to the product?
- Does it adapt intentionally to mobile?

# ValueStream Mapper

A lightweight single-page MVP for end-to-end value stream mapping across business and technology value streams.

## Run
Open index.html in a modern browser. No build step or external dependency is required.

## Features
- Multiple Business and Technology value stream workspaces
- Stream charter: customer, trigger, outcome, scope start/end and assumptions
- Eight discovery pillars: customer/value, people, process, technology, data, governance, measures and finance
- Stakeholder register and workshop records
- Current-state and future-state activity maps
- Processing, waiting, lead time, flow efficiency, queue and rework capture
- Waste observations and improvement backlog
- Lean portfolio roadmap view
- JSON and CSV exports
- Local browser persistence

## MVP limitations
Data is stored in browser localStorage; there is no shared database, authentication or multi-user collaboration yet. Time calculations sum activity processing and waiting durations; overlapping or parallel work can overstate actual elapsed lead time. Future-state times are targets, not achieved benefits.

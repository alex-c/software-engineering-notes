---
attachments: [Agile Burndown.svg, Cumulative Flow Diagram.svg]
tags: [Software Development Methodologies - Agile]
title: Agile Metrics
created: '2020-06-07T12:58:17.380Z'
modified: '2020-06-07T13:08:24.480Z'
---

# Agile Metrics

The agile metrics discussed below focus on the delivery of software. Whether you are a scrum or kanban team, each of these agile metrics will help the team better understand their development process, making releasing software easier.

## Sprint Burndown

Scrum teams organize development into time-boxed sprints. At the outset of the sprint, the team forecasts how much work they can complete during a sprint. A sprint burndown report then tracks the completion of work throughout the sprint. The x-axis represents time, and the y-axis refers to the amount of work left to complete, measured in either story points or hours. The goal is to have all the forecasted work completed by the end of the sprint.

![](@attachment/Agile Burndown.svg)


Anti-patterns to watch for:

- The team finishes early sprint after sprint because they aren't committing to enough work. 
- The team misses their forecast sprint after sprint becase they're committing to too much work. 
- The burndown line makes steep drops rather than a more gradual burndown because the work hasn't been broken down into granular pieces.
- The product owner adds or changes the scope mid-sprint.

## Velocity

Velocity is the average amount of work a scrum team completes during a sprint, measured in either story points or hours, and is very useful for forecasting. The product owner can use velocity to predict how quickly a team can work through the backlog, because the report tracks the forecasted and completed work over several iterations–the more iterations, the more accurate the forecast.

## Cumulative Flow Diagram

The cumulative flow diagram is a key resource for kanban teams, helping them ensure the flow of work across the team is consistent. With number of issues on the Y axis, time on the X axis, and colors to indicate the various workflow states, it visually points out shortages and bottlenecks and works in conjunction with WIP limits.

The cumulative flow diagram should look smooth(ish) from left to right. Bubbles or gaps in any one color indicate shortages and bottlenecks, so when you see one, look for ways to smooth out color bands across the chart.

![](@attachment/Cumulative Flow Diagram.svg)

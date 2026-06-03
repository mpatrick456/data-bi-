# Project 03 – Learning & Development Analytics Dashboard

## Background

Learning and Development teams often need to manage mandatory training, course participation, learner engagement, feedback and operational follow-up. In many organisations, this data is available but spread across LMS exports, HR data, spreadsheets and manual tracking files.

The purpose of this portfolio project is to demonstrate how Power BI can turn learning records into management insight. The dashboard is designed for L&D managers, HR business partners, compliance owners and learning systems analysts.

## Business problem

The key problem is not simply reporting how many people completed training. The real business question is:

> Which teams, courses and learner groups need attention, and what action should the L&D team take next?

Common pain points include:

- Mandatory training overdue risk is difficult to prioritise.
- Managers need clearer visibility of their team completion status.
- Course attendance, cancellations and no-shows are often reviewed too late.
- Feedback data is collected but not always connected to improvement actions.
- Manual LMS reporting can take too much time and may not be repeatable.

## Dashboard objectives

The dashboard is designed to help users:

1. Track learning compliance and overdue risk.
2. Identify engagement gaps by course, department, location or learner group.
3. Understand demand, attendance and cancellation behaviour.
4. Review feedback and learning effectiveness indicators.
5. Create targeted follow-up actions for managers and L&D teams.

## Suggested data model

Example tables:

- `FactLearningActivity` – learner, course, enrolment date, completion date, status, score, attendance status.
- `FactFeedback` – course, learner, feedback date, rating, comments theme, confidence score.
- `DimEmployee` – employee, department, manager, role, location, employment type.
- `DimCourse` – course, category, mandatory flag, delivery method, duration.
- `DimDate` – date, month, quarter, year, financial period.

## Example KPIs

- Completion rate %
- Overdue learners
- Average days overdue
- No-show rate %
- Cancellation rate %
- Training hours per learner / FTE
- Average feedback score
- Compliance risk category

## Insight examples

- A department may have a high completion rate overall but still contain a small group of long-overdue mandatory learners.
- A course with high demand but repeated cancellations may need better scheduling rather than more reminders.
- A mandatory course with low feedback may need redesign because attendance is driven by compliance rather than perceived value.
- Learner engagement may differ by delivery method, location or job role.

## Recommended actions

- Create a weekly overdue learning exception list for managers.
- Separate compliance risk reporting from general learning engagement reporting.
- Review courses with repeated no-shows or cancellations.
- Use feedback trends to prioritise course improvement.
- Automate repeat reporting to reduce manual LMS export work.

## Skills demonstrated

- Power BI report storytelling
- KPI design for learning operations
- DAX measures for completion, overdue status and engagement analysis
- Power Query data preparation and standardisation
- HR / learning systems understanding
- Translating dashboard output into business action

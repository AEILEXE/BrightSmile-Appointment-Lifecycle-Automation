# Evidence Index

These are genuine captures from the BrightSmile GoHighLevel portfolio environment. BrightSmile and the test contacts are fictional. The project documents a demonstration, not a live clinic deployment.

| File | What it supports | Notes |
|---|---|---|
| `01-workflow-inventory.png` | Workflow inventory and visible status/count columns | Cropped to the workflow table; review unrelated workflow names before public upload. |
| `02-appointment-reminder-workflow.png` | Reminder workflow canvas and wait/checkpoint logic | Checkpoints are notes, not real outbound messages. |
| `03-reminder-enrollment-history-redacted.png` | Enrollment history and waiting states | Contact-name column obscured. |
| `04-reminder-enrollment-waiting-until-oct20.jpg` | T1 reminder enrollment awaiting its scheduled checkpoint | T1 was pending in the project record; this is not a passing result. |
| `05-reminder-execution-log-redacted.png` | Reminder actions and wait status | Contact-name area obscured. |
| `06-cancellation-handling-workflow.png` | Cancellation workflow canvas | Shows contact-level tag/removal actions and a note action. |
| `07-appointment-booking-execution-logs-redacted.png` | Appointment booking workflow execution | Contact-name column obscured. |
| `08-cancellation-execution-logs-redacted.png` | Cancellation action sequence and statuses | Contact-name column obscured. |
| `09-no-show-execution-logs-redacted.png` | No-show follow-up actions and statuses | Contact-name column obscured. |
| `10-lifecycle-workflow-status-overview.jpg` | Visible final workflow statuses | Status snapshot only; not proof of production readiness. |

## Not included in this public selection

- The original two-page reminder execution-log PDF includes contact names. Redact it before public use.
- Appointment booking form/details/status captures include test-contact details and are not necessary for the initial public evidence set.
- The contact record/note and team inbox screenshots are omitted because they add little to the core project story.
- Draft/template inventory screenshots include unrelated workflows and are not essential.

## Evidence interpretation

- T1 remained pending at the time represented in the project notes; do not call it passed until the actual checkpoint log confirms the outcome.
- T2, T3, T4, T5, T7, and T8 were recorded as passed in the project notes.
- T9 revealed a multiple-appointment limitation: cancellation for one appointment could end reminder runs for another appointment belonging to the same contact.
- Attendance/no-show handling left `demo-appt-confirmed` on the contact, and rescheduling produced a duplicate confirmation note.
- Reminder checkpoints are notes, not actual email/SMS messages. Real outbound messaging, message templates, and consent handling were not tested.

# Workflow Documentation by vince

flow tools: Google Forms → Google Sheets → Zapier/formatter → Google Calendar

## Step-by-step

### 1. Collect assignment information
The student submits assignment information using Google Forms, including the assignment title, subject and deadline details.

### 2. Store the response
Google Sheets stores the submitted form response in a new row. A combined date-time helper field is used to prepare the deadline for the next step.

### 3. Trigger the Zap
Zapier watches the configured Google Sheets worksheet for a new row.

### 4. Process the deadline
Formatter steps prepare the deadline date/time for Google Calendar. The exact configuration depends on the spreadsheet's date and time formats and the account's time zone.

### 5. Create a calendar event
The Google Calendar action creates an event using the assignment title and processed deadline. The calendar's reminder settings determine how the user is notified.

---


## Testing checklist

- [x] A new form response appears in the intended spreadsheet worksheet.
- [x] The deadline date and time are combined correctly.
- [x] Zapier History shows a successful run for the new response.
- [x] The event appears in the intended Google Calendar.
- [x] The event's date and time match the submitted deadline.
- [x] No private information or credentials appear in screenshots.

## Disclaimer and project purpose

This project is a personal learning project created for educational purposes and skill development. Its primary goal is to help me understand how automation workflows are designed, connected, tested, and implemented using no-code tools.

This project is not intended to cause harm, misuse data, or violate the terms and policies of any platform or service used. All tools and integrations are used for learning and experimentation purposes.

More automation projects will be developed and shared in the future as part of my continuous learning journey in automation, system integration, and intelligent automation.

This project represents one of my first steps toward understanding real-world automation workflows and improving my technical skills.

**Note:** This project is an independent personal project and is not affiliated with, endorsed by, or officially connected to Google, Zapier, or any other third-party service mentioned.

---




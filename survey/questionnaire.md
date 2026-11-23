# Questionnaire

The 39 questions of the survey with their options, under the section headings of the online form. The form opened with a presentation of the study and its terms of participation, followed by the request for consent. All questions except the last one were mandatory.

## Electronic consent

1. I consent to participate in this research study *(one answer)* "No" ends the questionnaire.
   - Yes
   - No

## Scope of the study

2. Have you ever worked on a software project where architectural decisions were documented, or where you felt they should have been? *(one answer)* "No" ends the questionnaire.
   - Yes
   - No

## Background

3. How many years of experience do you have working in the software development industry? *(one answer)*
   - Less than 3
   - 3–5
   - 6–10
   - 11–20
   - More than 20

4. How many years of experience do you have working on the design of software architectures in industry? *(one answer)*
   - Less than 3
   - 3–5
   - 6–10
   - 11–20
   - More than 20

5. When did you last work on designing or enhancing the design of a software architecture? *(one answer)*
   - Last year
   - Last six months
   - Last month
   - Last week

6. Please specify your gender identity: *(one answer)*
   - Male
   - Female
   - Prefer not to say
   - Other (free text)

7. Which best describes your current role? *(one answer)*
   - Software engineer / developer
   - Tech lead
   - Software architect / principal engineer
   - Engineering manager or above
   - Researcher / academic
   - Consultant / independent
   - Other (free text)

8. Which best describes your organisation? *(one answer)*
   - Startup (fewer than 50 people)
   - Mid-size product company
   - Large enterprise
   - Consultancy / services firm
   - Government or public sector
   - Research institute or university
   - Other (free text)

9. Roughly how many people work in your organisation's software function? *(one answer)*
   - Fewer than 10
   - 10–50
   - 51–200
   - 201–1000
   - More than 1000

10. How is your immediate team distributed? *(one answer)*
   - Co-located in one office
   - Distributed within one country
   - Distributed across countries / time zones
   - Other (free text)

11. Which domains do you mainly work in? *(multiple answers)*
   - Web / SaaS applications
   - Enterprise / back-office systems
   - Finance, banking or insurance
   - Embedded, industrial or robotics
   - Data platforms / ML / AI systems
   - Cloud or developer platforms
   - Public sector / government systems
   - Other (free text)

12. Where has your understanding of architecture decision records come from? *(multiple answers)*
   - University or formal course
   - Professional certification (e.g. TOGAF, iSAQB, SEI)
   - Books or published articles
   - Blog posts / conference talks
   - A senior colleague or mentor
   - Company-internal guidance or templates
   - Trial and error on projects
   - AI assistants / LLM tools
   - I'm not familiar with the concept

13. Does your team currently produce ADRs (or equivalent decision records under another name)? *(one answer)* "No" skips to question 18.
   - Yes, consistently
   - Yes, but inconsistently / only some teams
   - We used to, but stopped
   - No

## Current practice

14. Roughly how many ADRs does your team produce? *(one answer)*
   - More than one a week
   - About one a week
   - One or two a month
   - A few a year
   - Fewer than a few a year
   - Not applicable

15. Where do your team's decision records live? *(multiple answers)*
   - Markdown or text files in the code repository
   - A wiki (Confluence, Notion, SharePoint or similar)
   - Shared documents (Google Docs, Word)
   - An issue tracker (Jira, GitHub Issues)
   - Slides / diagrams
   - Chat threads (Slack, Teams) with no separate document
   - Nowhere formal — decisions are made verbally
   - Other (free text)

16. What typically makes your team write a decision record? *(multiple answers)*
   - The decision is expensive or hard to reverse
   - The decision affects multiple teams or components
   - The choice is not the obvious or default one
   - A technology or product selection is being made
   - Someone requests it (review board, manager, process)
   - A required process step / compliance gate
   - We only realise afterwards that a decision was made
   - Other (free text)

17. Does your team use a template for decision records? *(one answer)*
   - Yes, a required template
   - Yes, a template used as a loose guide
   - No template, but a shared informal habit
   - No, everyone writes them differently

## What a good ADR contains

*The next questions ask what you personally think a good decision record should contain — not necessarily what your team does today.*

18. How important is each of the following in a decision record? *(one answer per row; scale: very unimportant, somewhat unimportant, neutral, somewhat important, very important)*
   - The problem or issue that required a decision
   - The context and constraints in force at the time
   - The reasoning that led to the choice (the "why")
   - The alternatives that were considered
   - Why the rejected alternatives were rejected
   - The trade-offs knowingly accepted
   - The consequences of the decision
   - The quality attributes or use cases the decision serves
   - The decision's current status (proposed / accepted / superseded)
   - Who made the decision, and when
   - A title that names the decision, not just the topic
   - Links to related or superseding decision records
   - Links or references to the implementation
   - Diagrams where they aid understanding
   - Conditions under which the decision should not be applied

19. Of the elements above, which three would you keep if a record could contain nothing else? *(multiple answers)* The options are the 15 elements of question 18.

20. Please indicate how much you agree or disagree with the following? *(one answer per row; scale: strongly disagree, somewhat disagree, neutral, somewhat agree, strongly agree)*
   - A decision record without its reasoning is of little value
   - A record should cover exactly one decision
   - Stating a quality goal (e.g. "good performance") without a concrete, checkable criterion makes a record weaker
   - Consequences should be stated as neutral facts, not as advantages and disadvantages
   - A structured table of pros and cons is good practice in a decision record
   - A record should be honest about what gets worse as a result of the decision
   - A record should state the decision assertively ("we will do X"), not tentatively
   - A record should explain the decision, not argue for it
   - Code-level implementation detail does not belong in a decision record

## Length, form and threshold

21. What is the longest a decision record should normally be? *(one answer)*
   - A few sentences
   - About half a page
   - About one page
   - About two pages
   - Up to five pages
   - However long the decision requires — length shouldn't be prescribed

22. Which statement is closest to your view on templates? *(one answer)*
   - A strict template should be followed, so records are consistent
   - A template is useful as a reminder, but should be adapted freely
   - Experienced writers don't need a template; the structure can be implicit
   - Templates do more harm than good

23. Which decisions deserve a record? *(one answer)*
   - Only decisions that are hard or expensive to reverse
   - Any decision that affects more than one team or component
   - Any decision where the choice was not obvious
   - All architectural decisions, regardless of size
   - It depends entirely on project size and context

24. How much do the following contribute to whether a decision record is worth writing? *(one answer per row; scale: not at all, slightly, moderately, strongly, decisively)*
   - How hard the decision would be to reverse later
   - How many teams or components it affects
   - How long the system is expected to live
   - How large the team is
   - How non-obvious the chosen option is
   - Whether a process or auditor requires it

## Problems

25. Which of these have you experienced with architecture decision records? *(multiple answers)*
   - Records go out of date and are never revisited
   - Records state the decision but not the reasoning
   - Records are too long, closer to a design document
   - Records are hard to find when you need them
   - Quality goals stated too vaguely to check
   - The stated reason isn't the real reason
   - Records written only to satisfy a process
   - Several unrelated decisions crammed into one record
   - The template is filled in but says nothing substantive
   - Records written long after the fact, and cleaned up in hindsight
   - Writing is careless, inconsistent or unproofread
   - None of these
   - Other (free text)

26. Of those, which is the single biggest problem in your experience? *(one answer)* The options are those of question 25.

27. How much does each of the following prevent decision records from being written or kept current? *(one answer per row; scale: not a barrier, minor barrier, moderate barrier, major barrier, the main barrier)*
   - Time pressure and deadlines
   - No clear ownership of the records
   - Lack of individual discipline or habit
   - The process feels too heavy or bureaucratic
   - No management support or budget for documentation
   - Ownership moved to another team
   - People don't see the value
   - No good tool or place to put them

28. When a decision changes, what should happen to the original record? *(one answer)*
   - Leave it unchanged; write a new record that supersedes it
   - Leave the content, but update its status to point to the new record
   - Edit the original record to reflect the new decision
   - Add commentary to the original without rewriting it
   - It doesn't matter much in practice

29. Does your team review existing decision records on any regular basis? *(one answer)*
   - Yes, on a fixed cadence (e.g. each release)
   - Yes, but only when something prompts it
   - No, we only read them when a question arises
   - No, never
   - I don't know

## Storage and discoverability

30. Which matters more for decision records? *(one answer)*
   - Keeping them next to the code, so they stay current and versioned
   - Keeping them in a shared wiki, so non-developers can find them
   - Both matter equally
   - Neither — what matters is that they're searchable, wherever they live

31. How easy is it to find the decision record you need in your organisation? *(one answer)*
   - Very difficult (1)
   - Difficult (2)
   - Neutral (3)
   - Easy (4)
   - Very easy (5)

32. Which would most improve decision records for you? *(multiple answers)*
   - Better search across records
   - Automatic linking between related records
   - Automatic detection when a record is out of date
   - Links from code to the decisions that shaped it
   - Templates or checklists that improve quality
   - Notification when a record you rely on changes
   - Better organisation as the number of records grows
   - Nothing — the tooling isn't the problem
   - Other (free text)

## Impact

33. From your experience, what effect do decision records have on each of the following? *(one answer per row; scale: no effect, slight improvement, moderate improvement, large improvement)*
   - Onboarding new team members
   - Avoiding re-litigating settled decisions
   - Long-term maintainability of the system
   - Consistency across teams solving similar problems
   - The quality of the decisions themselves
   - Code quality
   - Software reliability

34. Have you seen decisions re-made or solved inconsistently because no record existed? *(one answer)*
   - Yes, frequently
   - Yes, occasionally
   - No
   - I don't know

35. How critical are decision records to a project's long-term success? *(one answer)* Scale from 0 (not at all critical) to 5 (absolutely critical).

## AI and LLM tools

*The last section asks about AI coding assistants and their relationship to decision records.*

36. How often do you use AI coding assistants or agents in your work? *(one answer)*
   - Daily
   - Weekly
   - Occasionally
   - Tried but don't use
   - Never

37. Do you use AI tools for any of the following? *(multiple answers)*
   - Drafting the structure of a decision record
   - Writing the content of a decision record
   - Reviewing or critiquing a draft record
   - Summarising or querying existing records
   - Generating architecture documentation from code
   - Feeding existing records to a coding agent as context
   - None of these
   - Other (free text)

38. Please indicate how much you agree or disagree with the following? *(one answer per row; scale: strongly disagree, disagree, neither, agree, strongly agree)*
   - Decision records are valuable as context for AI coding assistants
   - I would trust a rationale written by an AI tool
   - AI-generated decision records tend to be too long and unfocused
   - AI tools default to one way of architecting and rarely offer alternatives
   - AI tools reinterpret our terminology toward their own conventions
   - Relying on AI risks reducing the number of experienced architects in future
   - AI assistance makes keeping records up to date easier
   - Writing records is not worth automating — it's cheaper to do by hand

## Final thoughts

39. Anything else you'd like to add about what makes a good decision record? *(open, optional)*

# Allegheny AI Perspectives: Interview Protocol

Each interview takes five to ten minutes. Agree inside your group on who is approaching whom.

**No recordings.** Take notes. Tell people what the notes are for, and that you will not attach their name
to anything.

**Say this first:**

> I am in a CMPSC 303 Artificial Intelligence class. We are collecting perspectives on AI from across
> campus for a class exercise. It takes about five minutes, your name will not be attached to anything,
> nothing leaves the course, and you can skip any question. Is now an okay time?

---

## Part 1: the same questions we answered in class

Ask these in this wording, so the answers can be compared against ours.

1. In one word, what is AI?
2. How often do you use AI tools? *(never / a few times a month / weekly / daily / constantly)*
3. What do you use them for? *(writing, coding, studying or explaining things, search, images or media,
   something else)*
4. How well do you understand how they actually work, one to five? *(one means no idea, five means you
   could explain it to someone else)*
5. More excited, or more worried, one to five? *(one means mostly worried, five means mostly excited)*
6. Should AI be allowed for coursework? *(never / only when the instructor says so / yes if you disclose it
   / yes with no restrictions)*
7. When an AI tool gives you an answer, how often do you check whether it is right? *(never / rarely /
   sometimes / usually / always / I do not use AI tools)*
8. Which of these have you used or run into in the past week? *(read the list aloud, check all that apply)*
   - A chatbot you opened on purpose
   - AI features inside an app they were already using: autocomplete, summaries, search answers
   - AI-generated images, video, or audio in a feed
   - Recommendations picked for them: what to watch, buy, or listen to
   - Translation or automatic captions
   - None of these, as far as they know

   > **Read every option out loud, even if they already said they never use AI.**

9. *(Optional, ask if there is time)* What is one thing AI should never do?

## Part 2: questions only for the community

10. What is your role here? *(student, with class year and division / faculty, with division / staff or
    administrator)*
11. Has AI changed how you work or study in the past year? How?
12. Has anyone at Allegheny told you what is and is not allowed with AI? Who, and what did they say?
13. Is there anything about AI at a college specifically that you think people are not talking about
    enough?

---

## Recording your data

Put **one row per interview** in `interviews.csv`. Do not use names. Use your group number and an interview
number, like `G3-02`. Leave out a department, job title, or quote that would tell a reader who this person
is.

| Column | Notes |
| :--- | :--- |
| `id` | Your group and interview number |
| `role` | Student, class year, division; faculty, division; or staff or administrator |
| `q1_definition` | Their one word, exactly as they said it |
| `q2_frequency` | One of the five options |
| `q3_uses` | All that apply, separated by semicolons |
| `q4_understanding` | 1 to 5 |
| `q5_excited_worried` | 1 to 5 |
| `q6_coursework` | One of the four options |
| `q7_verifies` | One of the six options |
| `q8_encountered` | All that apply, separated by semicolons |
| `q9_never` | Short phrase, or blank if you ran out of time |
| `q11_changed` | Yes or no, plus one line |
| `q12_told` | Yes or no, plus who |
| `q13_open` | One line, or blank |
| `quote` | One thing worth reading aloud, or blank |

Put double quotes around any answer that contains a comma.

---

## Questions worth checking

- Did the people you interviewed define AI differently than we did?
- Do people use AI as often as we do? Do they think they understand it as well as we think we do?
- **Compare Q2 against Q8.** Did anyone report barely using AI, then check several boxes on the list? Compare
  that against the class.
- **Compare Q4 against Q7.** Do people who say they understand these tools well check the output more often,
  or less?
- Did people know what the college expects of them?

# Allegheny AI Perspectives: Interview Protocol

Each interview takes five to ten minutes. Before you start, agree as a group on who is approaching whom, so
that two of you do not end up asking the same person.

Please take notes rather than recording the conversation.

**Begin by saying this:**

> I am in a CMPSC 303 Artificial Intelligence class, and we are asking people around campus how they think
> about AI. It takes about five minutes, and you can skip any question. Our group writes down your name for
> our own record, and our instructor can see that record, but your name will not be published or said in
> class. Our class may publish what we learn on the course website, without names. Is now an okay time?

---

## Part 1: the questions we answered in class

Please use this wording, so that the answers can be compared with ours.

1. In one or two words, what is AI?
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

   Please read each option aloud, even if the person has already told you they do not use AI.

9. *(Optional, if there is time)* What is one thing AI should never do?

## Part 2: questions for the people you interview

10. What is your role here? *(student, with class year and major / faculty, with department / staff or
    administrator)*
11. Has AI changed how you work or study in the past year? How?
12. Has anyone at Allegheny told you what is and is not allowed with AI? Who, and what did they say?
13. Is there anything about AI at a college specifically that you think people are not talking about
    enough?

---

## Areas of study

Allegheny groups its majors and departments into these six areas of study. A student counts under their
major, and a faculty member counts under their department. If a student has two majors, use the first one
they mention. The full listing is in the
[Academic Bulletin](https://catalog.allegheny.edu/content.php?catoid=58&navoid=2463).

| Area of study | Majors and programs |
| :--- | :--- |
| Interdisciplinary Studies | Black Studies; Community and Justice Studies; Data Science; Education Studies; Energy and Society; Environmental Science and Sustainability; Global Health Studies; Healthcare Management; Informatics; International Studies; Jewish Studies; Latin and Caribbean Studies; Middle East and North African Studies; Public Humanities; Women's, Gender, and Sexuality Studies |
| Languages, Literature, and Culture | Arabic; English; French; German; Journalism and Documentary Storytelling; Spanish |
| Mathematics and Natural Sciences | Astronomy; Biochemistry; Biology; Chemistry; Computer Science; Engineering Physics; Mathematics; Neuroscience; Physics; Software Engineering |
| Social and Behavioral Sciences | Business; Economics; Political Science; Psychology |
| Values and Societies | Communication and Media; History; Philosophy |
| Visual and Performing Arts | Art, Science, and Innovation; Dance and Movement Studies; Filmmaking; Industrial Design; Music; Studio Art; Theatre |

---

## Recording your data

Please add one row to `interviews.csv` for each interview. This file stays in your private repository.

| Column | What to write |
| :--- | :--- |
| `name` | The person's name |
| `role` | Student, faculty, staff, or administrator |
| `class_year` | The student's class year, or blank for anyone else |
| `area_of_study` | One of the six areas above. Write `undeclared` for a student without a major, and `none` for staff or an administrator |
| `q1_definition` | Their words, exactly as they said them |
| `q2_frequency` | One of the five options |
| `q3_uses` | All that apply, separated by semicolons |
| `q4_understanding` | 1 to 5 |
| `q5_excited_worried` | 1 to 5 |
| `q6_coursework` | One of the four options |
| `q7_verifies` | One of the six options |
| `q8_encountered` | All that apply, separated by semicolons |
| `q9_never` | A short phrase, or blank if you ran out of time |
| `q11_changed` | Yes or no, plus a line about how |
| `q12_told` | Yes or no, plus who told them |
| `q13_open` | A line, or blank |
| `quote` | Something worth repeating, or blank |

Please put double quotes around any answer that contains a comma.

---

## Questions worth exploring

- Did the people you interviewed define AI differently than we did?
- Do they use AI as often as we do? Do they feel they understand it as well as we feel we do?
- **Compare Q2 with Q8.** Did anyone say they barely use AI, and then check several boxes on the list? How
  does that compare with this class?
- **Compare Q4 with Q7.** Do people who say they understand these tools well check the answers more often or
  less often?
- Did people know what the college expects of them?

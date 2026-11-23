Class Coordinator: the live files
=================================

These are the files the real Class Coordinator uses, in the order the
walkthrough builds it. Each build screen adds only the files its task needs.
project-instructions.md and review-contract.md grow task by task: each
build folder has the next version, and it replaces the one in the project.
Every name and number in the data files is invented. For a real class,
Ms. Khan's own data goes in the same tabs.
A brief has a prompt part, between the lines "Prompt starts" and "Prompt
ends". Paste only that part into the scheduled task.

Each file has a label in [ ] from screen 4 of the walkthrough:
  [KSoR]           what the worker knows: the class documents.
  [SSoR]           where the work stands: the work record and its Log.
  [Current state]  what is true now: the working copy. The worker reads
                   it only through the DSoR, the Google Sheets connector.
  [Instructions]   not one of the three records. The project and task
                   instructions, the briefs and the Review Contract put
                   the Role Contract into words that the worker follows.
                   A task instructions file sits in the knowledge of the
                   project, but it is not part of the KSoR.

1-build-t1 (screen 6.1b)
  full-sheet/students.csv, homework.csv, dues.csv, notes.csv
      [Never reaches the worker]
      Step 1. Stays on Ms. Khan's computer. It never goes into Google or
      Claude. You copy from it to make the working copy: in Build T1, and
      again in Build T2 (Notes) and Build T3 (Dues).
  working-copy/students.csv, homework.csv, updated.csv   [Current state]
      Step 1. The Google Sheet "Class 7B working copy", one tab for each
      file. These are the tabs T1 reads. Share it by its link, as Editor
      (IMPORTANT).
  work-record/log.csv   [SSoR]
      Step 1. The Google Sheet "Class 7B work record", tab Log: the seven
      headings, no rows. Share it by its link, as Editor (IMPORTANT).
  project-instructions.md   [Instructions]
      Step 3. The instructions of the project, the T1 version. Paste the
      whole file, then put in the links of your two sheets (IMPORTANT).
      Each later build replaces it with the next version.
  class-rules.md   [KSoR]
      Step 4. The knowledge of the project. T1 reads only this class
      document.
  t1-instructions.md   [Instructions]
      Step 4. The knowledge of the project.
  review-contract.md   [Instructions]
      Steps 4 and 6. The knowledge of the project: the checks for every
      task, and the T1 part. Ms. Khan keeps her own copy too.
  brief-t1-friday-list.md   [Instructions]
      Step 7. The prompt of the scheduled task "T1 Friday list", every
      Friday at 7:00.

2-build-t2 (screen 6.2b)
  t2-instructions.md   [Instructions]
      Step 1. The knowledge of the project.
  working-copy/notes.csv   [Current state]
      Step 1. A new tab, Notes, in the Google Sheet "Class 7B working copy".
  project-instructions.md   [Instructions]
      Step 2. The instructions of the project, for T1 and T2. Paste it in
      place of the version from Build T1, and put in the two sheet links
      again.
  review-contract.md   [Instructions]
      Step 3. It replaces review-contract.md in the knowledge of the project:
      the T1 and T2 parts. Ms. Khan replaces her own copy too.
  brief-t2-progress-notes.md   [Instructions]
      Step 5. The prompt of the scheduled task "T2 Progress notes".

3-build-t3 (screen 6.3b)
  t3-instructions.md   [Instructions]
      Step 1. The knowledge of the project.
  term-plan.md, dues-schedule.md   [KSoR]
      Step 1. The knowledge of the project. T3 answers questions from them.
  working-copy/dues.csv   [Current state]
      Step 1. A new tab, Dues, in the Google Sheet "Class 7B working copy".
  (no file)   [SSoR]
      Step 2. Two new headings in the Log tab of the work record, after
      Next: Origin and Source.
  project-instructions.md   [Instructions]
      Step 3. The instructions of the project, for T1 to T3. Paste it in
      place of the version from Build T2, and put in the two sheet links
      again.
  review-contract.md   [Instructions]
      Step 4. It replaces review-contract.md in the knowledge of the project:
      the T1 to T3 parts. Ms. Khan replaces her own copy too.
  brief-t3-questions.md   [Instructions]
      Step 6. The prompt of the scheduled task "T3 Questions", every weekday
      at 7:30.

4-build-t4 (screen 6.4b)
  t4-instructions.md   [Instructions]
      Step 1. The knowledge of the project.
  review-contract.md   [Instructions]
      Step 3. It replaces review-contract.md in the knowledge of the project:
      the final version, with all four parts and
      the checklist "Start a new term". Ms. Khan replaces her own copy too.
  project-instructions.md   [Instructions]
      Step 2. The instructions of the project, the final version for T1 to
      T4. Paste it in place of the version from Build T3, and put in the
      two sheet links again.
  brief-t4-dues-reminders.md   [Instructions]
      Step 5. The prompt of the scheduled task "T4 Dues reminders".
      Then check the two IMPORTANT settings again (Step 4).

Go live (screen 6.5)
  No new file. Clear the test data. Run each task once on its first real
  date: paste its brief with no test line, after 8:00, and Ms. Khan checks
  it. Then resume its scheduled task with "Skip all approvals". T4 may wait
  for the first reminder day of the next term.

5-role-contract (screen 7)
  role-contract.pdf   [Role Contract]
      Ms. Khan keeps it. It does not go into the project.

6-skills (screen 8, only after every dry run passes)
  start-and-end-a-run.zip, check-the-working-copy.zip,
  save-a-draft-to-a-parent.zip
      Steps 1 to 3. One zip for each skill, as Claude expects: the skill
      folder at the root of the zip, with SKILL.md in it. Do not unzip it.
      Upload each zip under Customize > Skills, test it in the test
      project, then turn it on. Ms. Khan keeps the approved copy.
  after/t1-instructions.md, t2-instructions.md, t3-instructions.md,
  t4-instructions.md
      Step 4. The task files with the skills. They replace the old task
      files in the knowledge of the project, only after the skills pass
      their tests.

# Local application evidence

These screenshots were captured from the actual locally running application on 19 October 2026. They document a real browser CRUD check; they are not generated mockups.

| File | What it shows |
| --- | --- |
| `01-running-application.jpg` | The initial catalogue with three sample books. |
| `02-create-book-form.jpg` | Filled form for The Adventures of Sherlock Holmes. |
| `03-book-created.jpg` | The new book in the catalogue and a successful create message. |
| `04-book-updated.jpg` | The book changed from Available to Borrowed. |
| `05-book-deleted.jpg` | The test book removed, with a successful delete message and updated counts. |
| `06-startup-output.jpg` | An unaltered startup-log excerpt displayed in a local evidence viewer. This is a screenshot of captured stdout, not a terminal window. |
| `07-persistence-after-restart.jpg` | Pride and Prejudice remains Borrowed after the application process is restarted. |
| `startup-output.txt` | The corresponding real stdout lines showing H2, Tomcat on port 8080, and successful Spring Boot startup. |
| `test-results.txt` | Actual Maven test summaries: 12 tests, zero failures, errors, or skips. |

The application was built with `mvnw.cmd clean verify`, running on Java 25 and compiling for Java 17. The project uses Spring Boot 3.5.16, MVC, Thymeleaf, JPA, validation, and a file-backed H2 database.

The application was started from the project folder using `java -jar target/library-desk-1.0.0.jar`.

## Remaining collaboration evidence

After the real partner pull request has been reviewed and merged, add a screenshot named `08-github-history-both-students.jpg` showing commits linked to **alisher74014** and **Moemen74378**. That screenshot cannot be prepared honestly until the partner contribution exists. No partner commit has been invented.

Both students must capture evidence from their own locally running applications and commit it into their own repository's `doc` folder. The supplied images document A's prepared local run and are a reference for B; they do not prove B ran the app.

Upload the history screenshot showing both students and a running-application screenshot to Platon. Read [PAIR-WORK-GUIDE.md](PAIR-WORK-GUIDE.md) for each person's exact steps.
<img width="1080" height="821" alt="WhatsApp Image 2026-10-26 at 01 00 10" src="https://github.com/user-attachments/assets/0003abab-5eb4-4b3d-971e-8d8e76a443cd" />
<img width="1080" height="672" alt="WhatsApp Image 2026-10-26 " src="https://github.com/user-attachments/assets/aa6b32c8-384d-4af2-b41a-a5f09a2104e3" />

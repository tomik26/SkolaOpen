# SkolaOpen 🎓

**An early-stage, open-source school information system prototype for Czech schools.**

SkolaOpen explores a clean, accessible alternative interface for school communication and administration. It takes inspiration from common workflows in Czech school information systems, including Bakaláři, but is independent and unaffiliated.

> **Project status:** Proof of concept (frontend only). All students, teachers, grades, and groups are fictional. There are no real users, real adoption metrics, or production deployments yet.

## Live demo (local)

Open `index.html` in a modern browser; no dependencies are needed. You can also run `python3 -m http.server 8000` in the project directory and open `http://localhost:8000`.

## Implemented in the prototype

- Student/parent grade view with vertical subject headings, weighted averages, and clickable grade details.
- Teacher classroom table mock-up and admin grade-access restriction in the demonstration UI.
- Single-vote polls with results displayed after voting (in-memory demo only).
- Group membership request interaction (in-memory demo only).
- Role switcher, responsive layouts, and illustrative content.

## Planned roadmap

- [ ] Secure backend, database, authentication, per-object authorization and audit logs.
- [ ] Administrator-managed base roles (student, teacher, parent, admin), classroom assignments and teacher-subject mappings.
- [ ] Parent–student binding and class-teacher visibility.
- [ ] Teacher grade-entry workflows, editable assessment columns, statistics, and grade action history.
- [ ] Poll permissions, group organizers, invitations, and approvals.
- [ ] Profiles, timetables, notifications, localization, tests and accessibility review.
- [ ] Privacy and security review before any real-school pilot.

## Technology

Vanilla JavaScript, HTML5 and CSS. The technology choices for a secure production backend are not finalized.

## Security and privacy

**Do not enter real student information.** This is a client-side prototype without login or server-side access controls; switching the role in the UI is not authentication. Any production version must implement server-side authorization, data minimization, and privacy safeguards.

## Contributing

Issues and PRs are welcome. Start by proposing a focused improvement in an issue. Please do not include personal data from real schools in bug reports or screenshots.

## License

MIT — see `LICENSE`.

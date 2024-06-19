# 2024-06-07 Narwhals community meeting

- Time: 2:30 pm UTC
- [Narwhals community events calendar](https://calendar.google.com/calendar/embed?src=27ff6dc5f598c1d94c1f6e627a1aaae680e2fac88f848bda1f2c7946ae74d5ab%40group.calendar.google.com&ctz=Europe%2FLondon)
- [Join via Google Meet](https://meet.google.com/igm-dtqg-mrz)
- [Community meetings notes archive](https://github.com/narwhals-dev/archive/tree/main/community-meetings)

**Code of Conduct**
All attendees of Narwhals community events must adhere to the [Narwhals Code of Conduct](https://github.com/narwhals-dev/narwhals?tab=coc-ov-file#readme).

**Present:**

- Francesco Bruzzesi
- Magdalena Kowalczuk
- Marco Gorelli
- Inessa Pawson
- Nwabueze Ugoh
- Uchenna Ugoh
- Mfon Ekpo
- Dea Léon

## Follow-up from the last meeting / discussions

None as this is the first community meeting.

## New topics

- We should have Narwhals meeting on a calendar. (Bi-weekly, on Fridays, 2:30 pm UTC). This could be set up via a public Google calendar.

- Frameworks for the Narwhals documentation and website:

    - MkDocs for the documentation works great
    - GitHub pages for the website get the job done

- Discussion on Issue [Perfect backwards compatibility policy #259](https://github.com/narwhals-dev/narwhals/issues/259)

    - Polars API has already changed. A good pitch would be that if people use Narwhals, their code will keep working.
    - Narwhals must be super stable for the users.
    - Follow what Rust does: code will always run. A way to handle this is to instantiate a stable API object.
    - Manageable if we don't expand Narwhals API too much.
    - Don't know of any other Python project that does this.

- If someone wants the API of one Polars version, but they have a different one. Should Narwhals take care of this? – Yes, the objective is to have things stable for users.

- PR for decorator: Pushed forward.

- Parallelism? Difficult to tell within pandas if something can run in parallel. Narwhals being more restricted than pandas, we could evaluate all the series in parallel and Narwhals would be faster than running pandas directly -> negative overhead for the use of Narwhals: powerful pitch.

- Creating an extension for dataframe libraries directly in Narwhals. [Issue #267](https://github.com/narwhals-dev/narwhals/issues/267)

## Action items

- Set up a public Google calendar for Narwhals community meetings.

---

### Let's connect and keep the conversation going!

Join us on Discord: https://discord.gg/XwBMXd6X

---
Remember to archive this file by committing it to [github.com/narwhals-dev/archive/community-meetings](https://github.com/narwhals-dev/archive/tree/main/community-meetings)

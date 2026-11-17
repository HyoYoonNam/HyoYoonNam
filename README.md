<p align="center">
  <img src="./assets/banner.svg" alt="Hyo Yoon Nam, Backend Developer — Java, Spring Boot, SQL" width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/hyoyoonnam"><img src="./assets/linkedin.svg" alt="LinkedIn" height="28" /></a>
  <a href="https://HyoYoonNam.github.io"><img src="./assets/blog.svg" alt="Blog" height="28" /></a>
  <a href="mailto:dev.rudevico@gmail.com"><img src="./assets/email.svg" alt="Email" height="28" /></a>
</p>

## About Me

I'm Hyo Yoon Nam, a backend developer working with Java, Spring Boot, and MySQL.
I'm part of the 8th backend cohort of Woowacourse, a software development training program.
My recent work includes SQL query optimization, bookshelf data modeling, and API documentation generated from tests.

## Selected Projects

### [ChaekChaek](https://github.com/woowacourse-teams/2026-chaekchaek)

<p>
  <img align="right" src="./assets/chaekchaek-mascot.png" alt="ChaekChaek mascot, a white bird sitting on an orange book" width="112" height="112" />
</p>

**Team project, backend developer**

A reading platform for discovering books, organizing personal bookshelves, and sharing reviews.

- Redesigned a MySQL covering index, reducing average first-page feed latency from **376 ms to 196 ms** in a development-database test with 3 concurrent clients and 100,018 reviews. [PR #712](https://github.com/woowacourse-teams/2026-chaekchaek/pull/712)
- Moved popular-review ranking and pagination from Java to MySQL, increasing successful throughput from **2.6 to 12.9 requests/s** and reducing p95 latency from **4.8 s to 1.0 s**. Measured on a development server with 10 concurrent clients, 5,000 synthetic reviews, and a 256 MiB JVM heap. [PR #519](https://github.com/woowacourse-teams/2026-chaekchaek/pull/519)
- Separated bookshelf placement from shared reading records so a book can appear on multiple shelves without duplicating reading progress or ratings. [PR #598](https://github.com/woowacourse-teams/2026-chaekchaek/pull/598)
- Connected Spring REST Docs tests to OpenAPI generation and Swagger UI. [PR #23](https://github.com/woowacourse-teams/2026-chaekchaek/pull/23)

### [Image Paste on GitHub](https://github.com/HyoYoonNam/image-paste-on-github)

**Personal project, Obsidian plugin**

Uploads pasted or dropped images to GitHub and embeds their URLs in Obsidian notes.
Supports browser-based GitHub sign-in and converts HEIC images locally before upload.

## Open Source

### [es-toolkit: Semaphore performance](https://github.com/toss/es-toolkit/pull/2149)

**Merged contribution**

Contributed a fix for quadratic queue draining in V8 using a linked-list FIFO queue.
Added regression tests for task order and queue reuse, plus benchmarks.

For 30,000 calls, the PR's Node.js 24.13 benchmark reduced `limitAsync` runtime from **555 ms to 30 ms**, using the median of five runs.

## Tech Stack

<p>
  <img src="https://skillicons.dev/icons?i=java,spring,mysql&amp;theme=light" alt="Java, Spring Boot, MySQL" height="48" />
  <br />
  <img src="https://skillicons.dev/icons?i=aws,docker,nginx,githubactions,grafana,prometheus&amp;theme=light" alt="AWS, Docker, Nginx, GitHub Actions, Grafana, Prometheus" height="48" />
</p>

| Area | Technologies |
| --- | --- |
| Backend | Java, SQL, Spring Boot, Spring Data JPA, MySQL, Flyway |
| Testing | JUnit, AssertJ, Mockito, Spring REST Docs |
| DevOps | AWS (EC2, RDS), Docker, Nginx, GitHub Actions, Grafana, Loki, Prometheus |

## Writing & Learning

- [When an HTTP 200 response still fails a documentation test](https://github.com/HyoYoonNam/woowacourse-8-archive/blob/main/writing/spring-rest-docs/README.md) — a Spring REST Docs case study, in Korean.
- [Woowacourse archive](https://github.com/HyoYoonNam/woowacourse-8-archive) — my backend course archive, in Korean.

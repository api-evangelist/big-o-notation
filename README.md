# Big O Notation (big-o-notation)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Big O Notation is a mathematical notation used in computer science to describe the performance or complexity of algorithms, providing a way to classify algorithms by how their runtime or space requirements grow as input size grows. It is foundational to algorithm design, API performance benchmarking, and software engineering education.

**URL:** [https://en.wikipedia.org/wiki/Big_O_notation](https://en.wikipedia.org/wiki/Big_O_notation)

## Tags:

 - Algorithms, Big O Notation, Complexity, Computer Science, Performance, Data Structures

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-21

## Complexity Classes

| Notation | Name | Description |
|----------|------|-------------|
| O(1) | Constant Time | Runtime does not change with input size. Example: hash table lookups. |
| O(log n) | Logarithmic Time | Runtime grows logarithmically with input. Example: binary search. |
| O(n) | Linear Time | Runtime grows linearly with input size. Example: linear search. |
| O(n log n) | Linearithmic Time | Runtime grows as n multiplied by log n. Example: merge sort. |
| O(n²) | Quadratic Time | Runtime grows quadratically with input size. Example: bubble sort. |
| O(2^n) | Exponential Time | Runtime doubles with each additional input element. Example: recursive Fibonacci. |
| O(n!) | Factorial Time | Runtime grows factorially. Example: brute-force traveling salesman. |

## Use Cases

| Name | Description |
|------|-------------|
| Algorithm Selection | Choosing the most efficient algorithm for a given problem based on complexity class. |
| API Performance Benchmarking | Analyzing API endpoint performance characteristics under varying data sizes. |
| Code Review | Evaluating the time and space complexity of code changes during review. |
| Database Query Optimization | Understanding complexity of database operations to optimize query performance. |
| Scalability Analysis | Predicting how software will perform as data volumes grow at scale. |
| Interview Preparation | Preparing for technical interviews requiring algorithm complexity analysis. |

## Vocabulary

| Term | Definition |
|------|------------|
| Time Complexity | Measure of computation time as a function of input size. |
| Space Complexity | Measure of memory usage as a function of input size. |
| Best Case | Minimum time required for algorithm execution (Omega notation). |
| Worst Case | Maximum time required for algorithm execution (Big O notation). |
| Average Case | Expected time required for algorithm execution (Theta notation). |
| Asymptotic Analysis | Behavior of algorithm as input size approaches infinity. |
| Amortized Analysis | Average performance of operations over time accounting for occasional expensive operations. |

## References

- [Wikipedia - Big O Notation](https://en.wikipedia.org/wiki/Big_O_notation)
- [Big O Cheat Sheet](https://www.bigocheatsheet.com)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com

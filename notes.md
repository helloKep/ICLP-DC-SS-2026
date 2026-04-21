# Meeting notes

**2026-03-19**

Key takeaways:
* We agree on a consistent output format of `drive(Z,C,C',T)`
* We need a "source of truth" to verify whether new encodings are correct
* We need to begin benchmarking to see what narratives emerge
* Let's begin investigating the approaches of former teams as well as the scoring methodology of the Flatland competition
* Let's explore the counterexample tool

General notes:
* We need to engage in quality control and develop a method for determining whether our encodings are correct
* In our ASPOCP paper, we will discuss this two-step approach of 1) finding paths and 2) avoiding collisions
* In future papers, we can:
  * discuss Flatland as an extension of MAPF and perform benchmarking on existing encodings (from Klaus)
  * incorporate malfunctions and compare our results to those of previous teams
  * pursue "greedy" approaches, such as a form of prioritized planning where we commit to a set of drives
* We need to visualize our results as a sanity check on potential encodings
  * Let's opt for using an in-house solution (e.g. clingraph) as opposed to the official Flatland visualizer
* Let's explore what other groups have done in the past, while taking into account that we don't handle malfunctions

---

# Voice-native LLM agents in XR

[← Back to profile](../README.md)

**Collaborators:** Günter Alce, Lund University (with colleagues at Lund University)
**Status:** Conference paper published · journal paper under review

## What it is
A line of work on spoken, real-time AI agents inside virtual reality. Instead of chaining
separate speech-to-text, language model and text-to-speech services, the prototypes stream
voice directly between a Unity VR application and a real-time LLM, so the agent can answer
while the user is still working on the task.

The first prototype is a VR tutor for a block-based programming task: the agent reads the
logic the user has assembled and gives short, spoken, context-aware feedback.

## Questions we look at
- How low does latency need to be for a spoken agent to feel like part of the task?
- How brief and how frequent should spoken feedback be?
- What does it cost to run such an agent per interaction?

## Publications
- Geriş, A., & Alce, G. (2026). Real-time voice-based LLM integration for XR tutoring: A prototype
  implementation. In *Proceedings of the 2026 IEEE International Conference on Artificial
  Intelligence and eXtended and Virtual Reality (AIxVR)* (pp. 285–289). IEEE.
  https://doi.org/10.1109/AIxVR67263.2026.00050
- A follow-up journal article is under review.

## Code
- [gemini-proxy](https://github.com/gerisali/gemini-proxy): a lightweight voice proxy
  (Unity → speech-to-text → Gemini → text-to-speech) used in related prototypes.
- The Unity project will be released after the journal paper is accepted.

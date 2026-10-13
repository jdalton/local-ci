---
"run-local-ci": patch
"dtu-github-actions": patch
---

Install Alpine's gcompat package before starting the injected Actions runner so musl-based job containers can run its .NET listener. Closes #400.

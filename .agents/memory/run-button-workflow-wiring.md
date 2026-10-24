---
name: Run-button workflow wiring
description: Replit Run-button behavior when configuring a custom console workflow in this workspace.
---

When using a custom console workflow as the Run target, Replit may normalize `.replit` to a `Project` wrapper whose task invokes that named workflow. Validate the final configuration and run the custom workflow once to confirm its output.

**Why:** A validated `.replit` replacement removed the custom workflow until it was configured again; the final Run-button target was represented through a wrapper rather than the requested workflow name directly.

**How to apply:** Configure the Java console workflow, use the supported `.replit` validation flow, then inspect `.replit` and the workflow list before finishing.

# Example General Order

**Kyle Daniel Webster · InUtero / INNERSPACE Handoff Protocol**

The General Order defines how work moves through the stack. Read the active [Working Order](WORKING_ORDER.md) for the assignment and acceptance gate. Start from the current repository, verified build, and test receipts. Present measured state outranks remembered state.

## Stack and rung cadence

- Work from the stack’s A–Z plan. Give each major component its own A–Z plan and put routine fixes on its current rung.
- Complete one bounded rung at a time. Read the relevant source and evidence before changing it. Preserve accepted behavior outside the assignment and reuse the existing SDK and adapter routes.
- At module acceptance, record its SDK contract and adapter endpoint. Confirm the host can call that endpoint and verify the owning component’s result. Track module acceptance and host integration acceptance separately.
- Close a rung when the evidence satisfies its gate. Record failures and partial results with their exact scope.

## Directory and delivery practice

- Give source, SDK installations, build candidates, incoming handoff ZIPs, and evidence distinct, agreed locations. Keep one active copy of each. Reuse existing directories and record where older copies were archived. Protect working roots and verified artifacts during cleanup.
- For a Windows handoff, send one ZIP, its expected SHA-256, and one complete PowerShell block. The block verifies the ZIP, extracts it into a fresh directory within the agreed handoff root, and runs the included entry point. The runner checks the expected source or build before modifying it.
- Use PowerShell as the terminal entry point so the run can be copied and reproduced. Print the result and the path to the review evidence. Preserve evidence from a failed run and inspect it before making a fix.
- A reading handoff is documentation. An executable handoff identifies the files it changes, the checks it runs, and the evidence it returns.

## Git, GitHub, and handoff

1. Before work, check the local branch and commit, the working-tree state, and the GitHub target. Inspect differences and preserve unrelated changes.
2. After verification, update affected project records with the result and evidence. Stage only the reviewed scope. Commit locally, push through the agreed GitHub workflow, and verify that local and remote commits match. Record the commit and receipt in the Working Order.
3. At the end of each substantive pass, record the accepted scope, pending or failed gates, exact next action, and paused work. Keep one current Working Order. Retain superseded orders as history.
4. Open a new chat with the current General Order and Working Order. Have it verify the checkpoint before continuing. If a check requires another environment, record what evidence is missing and how to obtain it.

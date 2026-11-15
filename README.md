# How to create a General Order

**Kyle Daniel Webster · InUtero / INNERSPACE**

I developed this protocol during InUtero and INNERSPACE development so a fresh chat could pick up engineering work without asking me to reconstruct the project from memory. It starts with an A–Z stack plan and uses verified checkpoints to carry the work across chats, modules, and machines. Adapt the method to what your own team actually runs and verifies.

| Document | What it owns |
| --- | --- |
| **1 · How to create a General Order** | How to plan the stack, develop modules, and derive the standing procedure. This is the document you are reading. |
| **2 · [Example General Order](GENERAL_ORDER.md)** | The stack cadence and standing procedure for implementation, delivery, verification, and handoff. |
| **3 · [Example Working Order](WORKING_ORDER.md)** | The current assignment, verified starting point, acceptance gate, and next action. |

## Start with the A–Z stack plan

1. **Define the finished stack.** Name the host project, its modules, what each module owns, how data crosses between them, and where the combined system must prove itself.
2. **Break the plan into rungs.** A rung is a bounded increment with a starting point, a specific change, and a test result you can inspect. Give it a stable ID. A fix keeps the rung ID and adds a revision so its evidence remains traceable.
3. **Give every major new component its own A–Z development plan.** Carry it from inventory and implementation through tests, integration, and acceptance. Track dependencies and paused work so a new component can fit into the stack without resetting earlier progress.
4. **Give a completed module its own SDK and adapter endpoint.** The SDK exposes the supported operations. The adapter connects the host project to those operations. Record the contract version, what the adapter translates, which component has authority, and how the host verifies the result. Fit the adapters together in one project and verify the combined behavior.
5. **Write the General Order from repeatable practice.** Document the stack cadence, clean directory rules, ZIP and PowerShell delivery, acceptance evidence, and local Git and GitHub synchronization. Update these rules when the team changes its method.
6. **Write a Working Order for the active assignment.** Carry forward the accepted baseline, choose the next rung, name its pass criteria, and record paused work. Update the Working Order at the end of each substantive pass and before each chat handoff.

## Try it with one real assignment

Pick a feature that crosses a module boundary. Record the last verified commit and one acceptance check. Give the General Order and Working Order to a fresh chat. Ask it to verify local and remote Git, read the evidence, and identify the next action before editing anything. If it still needs you to retell the assignment, improve the documents where the information was missing.

The examples use a Houston engineering scenario, with private paths, evidence links, and source omitted. This is one project’s protocol. If you adapt it, credit the original approach to Kyle Daniel Webster and describe what you changed for your own stack.

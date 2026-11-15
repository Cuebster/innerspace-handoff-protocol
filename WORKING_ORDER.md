# Example Working Order

**Kyle Daniel Webster · InUtero / INNERSPACE Handoff Protocol**

This example shows how a current assignment fits under the [General Order](GENERAL_ORDER.md). It uses descriptive checkpoint names so it can be read without the private repository.

| Field | Current assignment |
| --- | --- |
| Workstream | Houston dedicated-server integration |
| Last accepted rung | Native peer restart and replay |
| Verified starting point | Windows local Git and GitHub main matched at the native peer checkpoint. In a live Working Order, give the full commit and link the Windows receipt. |
| Evidence carried forward | The signed transport accepted operation 17, denied operation 18, and returned the same receipt on replay after receiver restart. The inbox held one unchanged record. |
| Active rung | Connect operation 17 to its authoritative Unreal handler through the existing adapter and persist the world result. |
| Paused work | Y7 physical loader step 4. Resume when the Working Order explicitly assigns it. |

## End-of-rung acceptance

- The dedicated server handles the signed request with zero connected clients.
- The world-action result records the request identity and the outcome observed by the server.
- Replay retrieves the original result, and the evidence shows a single world effect.
- The evidence identifies the source commit and tested candidate. The record distinguishes signed transport delivery from authoritative world execution.

## End-of-pass handoff

Replace the status below with observed results as the pass runs. Record the exact local and GitHub commit, link the evidence, and write one concrete next action. Carry the Y7 pause forward.

| Handoff field | Example at the start of this pass |
| --- | --- |
| Accepted | Native peer restart, signed transport replay, same receipt, one inbox record |
| Pending | Authoritative world action and durable result |
| Next action | Verify the starting commits and trace operation 17 through the existing Unreal adapter before editing the handler |
| Evidence to return | Signed request and replay records, authoritative result receipt, and dedicated-server acceptance output |

**Opening instruction for a fresh chat**

> Read the General Order and this Working Order. Verify the local and GitHub checkpoint and inspect the accepted native peer evidence. Continue the assigned Houston rung through the existing adapter. Preserve the Y7 pause at physical loader step 4. End by updating the Working Order with the evidence and exact next action.

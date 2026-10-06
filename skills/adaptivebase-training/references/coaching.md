# Human coaching

`get_coaching` action `workspace` discovers the authenticated coach's consented
roster. Use roster IDs with action `athlete`; a pasted ID is not proof of permission.
Review client constraints, baselines, history, recovery and equipment first.

`propose_client_program` action `propose` sends a program for explicit athlete
portal approval, never activates it. Action `note` is private to the coach. Never
claim acceptance, override revoked sharing, or assume administrative membership
permits unrestricted athlete access.

Athletes use `get_coaching` action `relationships` to review sharing/proposals.
Invitations, consent/revocation and proposal application happen in the portal.
`manage_training_plan` action `save_template` stores a reusable starting point and
adaptation policy; it does not activate or push a plan. Propose separately for each
consenting client and let them approve.

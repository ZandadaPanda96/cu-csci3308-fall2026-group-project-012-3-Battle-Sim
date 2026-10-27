# Battle and result drafts - Team 012-3

Design story: #17. Wireframes parent: #18.

- `battle.png`: two fighters, health bars, current-turn label, illustrative move buttons, last-action feedback, and Leave.
- `battle-result.png`: two alternative states, victory and defeat, each identifying winner/loser and offering Choose fighter plus Log out. The two frames are alternative screen states, not simultaneously displayed results.

These are interface designs only. They do not implement damage, turn execution, game rules, persistence, or routing. Results may be a state within the battle screen rather than a separate route.

## Review notes

Roster, health, opponent behavior, and the proposed Quick hit/Heavy hit/Guard moves remain unconfirmed examples. The battle sketch now shows a waiting/resolving state with disabled actions until the player's turn returns. Leave opens a confirmation: Stay returns to the battle; Leave returns Home. That exit behavior is explicitly marked for team confirmation.

Victory identifies Fighter A as winner and Fighter B as defeated; defeat identifies Fighter B as winner and Fighter A as defeated. Both Choose fighter actions return to selection. Mobile layout and a real teammate/user walkthrough remain pending. These drafts do not establish that every criterion in #17 is complete.

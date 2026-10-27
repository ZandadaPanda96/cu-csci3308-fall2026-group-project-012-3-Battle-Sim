# Wireframe notes - Team 012-3

## Login and registration

- `login.png`: email/password fields, Log in, and registration link.
- `register.png`: name/email/password/confirmation fields, Sign up, and return-to-login link.

These are low-fidelity design concepts. They do not implement authentication or routes. The proposed destination after sign-in is Home. Confirm fields and navigation with the team before implementing them.

### Review notes

- Register is a navigation link to registration, not another input.
- Blank password fields stand for masked password entry.
- Login annotates missing-field and invalid-credential errors, preserves email after an error, and identifies Home as the success destination.
- Registration annotates missing fields, existing email, and mismatched passwords. Name/email are retained after errors, and success returns to login.
- The error annotations describe alternative states, not messages permanently displayed together.
- Fields and registration behavior still need team confirmation and a recorded teammate review.
- Desktop layout only; responsive behavior is not defined here.

## Battle and results

- `battle.png`: two fighters, health bars, current-turn label, illustrative move buttons, last-action feedback, and Leave.
- `battle-result.png`: two alternative states, victory and defeat, each identifying winner/loser and offering Choose fighter plus Log out. The two frames are alternative screen states, not simultaneously displayed results.

These are interface designs only. They do not implement damage, turn execution, game rules, persistence, or routing. Results may be a state within the battle screen rather than a separate route.

### Review notes

Roster, health, opponent behavior, and the proposed Quick hit/Heavy hit/Guard moves remain unconfirmed examples. The battle sketch now shows a waiting/resolving state with disabled actions until the player's turn returns. Leave opens a confirmation: Stay returns to the battle; Leave returns Home. That exit behavior is explicitly marked for team confirmation.

Victory identifies Fighter A as winner and Fighter B as defeated; defeat identifies Fighter B as winner and Fighter A as defeated. Both Choose fighter actions return to selection. Mobile layout and a real teammate/user walkthrough remain pending. These drafts do not establish that every completion criterion has been met.

# Account wireframe drafts — Team 012-3

Design story: #15. Wireframes parent: #18.

- `login.png`: email/password fields, Log in, and registration link.
- `register.png`: name/email/password/confirmation fields, Sign up, and return-to-login link.

These are low-fidelity design concepts. They do not implement authentication or routes. The proposed destination after sign-in is Home, whose design is tracked in #16. Confirm fields and navigation with the team before implementing them.

## Review notes

- Register is a navigation link to registration, not another input.
- Blank password fields stand for masked password entry.
- Login annotates missing-field and invalid-credential errors, preserves email after an error, and identifies Home as the success destination.
- Registration annotates missing fields, existing email, and mismatched passwords. Name/email are retained after errors, and success returns to login.
- The error annotations describe alternative states, not messages permanently displayed together.
- Fields and registration behavior still need team confirmation and a recorded teammate review.
- Desktop layout only; responsive behavior is not defined here.

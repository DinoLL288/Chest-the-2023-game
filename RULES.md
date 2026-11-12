# Chest — Current Implemented Rules

Board: 9×9. White moves first; Black moves second. Sides are decided by a coin flip.

## Pieces

- **Prawn (×9)** — 1 HP. Moves 1 square forward. From its starting row it may move 2 squares forward if both squares are empty. Captures by jumping over a forward-diagonal enemy into an empty square beyond it (checkers-style). Cannot promote. Reaching the far end triggers The Dash.
- **Castle (×2)** — 3 HP. Slides in any of the 8 directions until blocked; captures by landing on an enemy. Can use Insta Movement once.
- **Horsey (×3)** — 2 HP. Slides diagonally any distance and may jump over pieces; captures by landing on an enemy (only adjacent diagonal unless using Charge). Can use The Charge (twice) and The What? (once).
- **King (×1)** — 5 HP. Normally only moves when capturing (1 step any direction). When in "Chest" (enemy adjacent) it may move 1 step in any direction, including to empty squares.
- **Queen (×1)** — 3 HP. Moves 1 step diagonally; cannot capture. Can be protected by Royal Guard prawns.
- **Staff (×2)** — 1 HP. Slides up to 5 squares orthogonally; captures by landing. Each royal has its own Staff (king's or queen's). Holding a Staff lets that royal also move like the Staff. Staff can be ejected to an adjacent empty square and reattached later. Breaks if its holder is attacked.

## Special Moves

- **The Rooky** — King and a friendly Castle swap places. Max 5 per game. Not usable while the king is in Chest.
- **The Dash** — When a Prawn reaches the far end, it dashes back to its starting row in the same file, dealing 1 damage to every enemy piece in that file.
- **Insta Movement** — A Castle moves to any empty square (even obstructed). Once per castle. Usable only after move 10. Cannot land on the King.
- **Queen of Hungary** — Queen moves backward along a straight line to any empty square, dealing 2 damage to enemies in the path. Max 3 per game.
- **The Charge** — Horsey charges in a diagonal direction over multiple turns; each charge adds 3 squares of range. Releasing attacks along that diagonal, eliminating enemies and knocking friendly pieces aside. Max 2 releases per Horsey.
- **The What?** — Horsey moves to an orthogonally adjacent square of the opposite colour. Once per Horsey.

## Faction Abilities

### White
- **Leap** — Grant a friendly piece a one-use jump over one piece. Max 5 per match.
- **Royal Guard** — White Queen orders the 3 nearest front prawns to protect the King or Queen. Max 2 per match. Shield prawns take damage for the royal until destroyed or reassigned.
- **Staff Empowerment** — Staff strengthens a friendly piece for 2 turns: 2× damage and pass-through. Max 3 per match.
- **Staff Annihilation** — While holding its Staff, the King blasts up to 5 squares forward (Queen: 3), annihilating enemies except the enemy King. Once per match each.
- **Staff Teleportation** — While holding its Staff, King teleports to any empty square (3 uses); Queen (2 uses).
- **Staff Breakage** — If the holder is attacked, the Staff breaks.

### Black
- **Invincibility** — Make a non-King piece invincible for 2 turns; it may move only 1 square. Max 2 per match.
- **Necromancy** — Black Queen lands on a piece's death square to revive it onto an adjacent empty square. Max 5 per match.
- **Staff Healing** — Staff heals a Dash-damaged friendly piece by 1 HP when adjacent.
- **Staff Absorption** — Staff eats an adjacent enemy, gaining its movement (and some abilities) for 2 turns. Max 5 per Staff.
- **Time Stop** — While holding its Staff, Black King (3 turns) or Queen (2 turns) takes consecutive turns; the enemy King cannot be captured during stopped time. Once per match.
- **Staff Breakage** — If the holder is attacked, the Staff breaks.

## Notes
- Pieces have HP; attacks deal 1 damage unless boosted or using a special attack.
- Capturing the enemy King ends the match.
- "Chest" means an enemy piece is adjacent to the King.

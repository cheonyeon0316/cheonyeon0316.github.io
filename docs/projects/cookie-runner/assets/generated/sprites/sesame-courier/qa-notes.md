# Sesame Courier animation QA

- `idle`: pass. Four frames retain the approved design and read as a subtle breathing/blink loop.
- `run`: experimental. Eight frames show alternating gait poses; the first and last poses closely match for loop closure. The strip reads as running, but exact foot-contact timing should be checked in the game at runtime.
- `jump`: pass. The frames progress from crouch through takeoff and airborne poses to landing recovery.
- `slide`: pass. The row has a clear anticipation, low slide, held pose, and rise.
- `attack`: pass. The row reads as windup, forward strike, held extension, and recovery.

All five rows extracted at their requested frame counts. The transparent atlas and manifest composed successfully. The contact sheets show full, separate characters without visible chroma residue or clipped limbs. Automated inspection reported no errors or warnings.

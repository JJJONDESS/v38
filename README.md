# Melt9 AR Menu - simple pizza + LIVE smoke (v38)

Based on v37. No dome, no glass box, no cylinder - just
the pizza, appearing on the target photo, with live smoke.

Why v37 looked dead:
- All wisps used the SAME big cloud picture, same size,
  same speed, same curl (-18 to +18, 2 s, all in sync).
  They all shook left-right together, ended in the middle
  together, and started again together - one dead machine.
- In the reference video every puff is different: different
  place, speed, drift, curl, brightness, and they never
  move as one block. That is what makes it look live.

Live smoke in v38 (dishes/steam.png = thin wisps from
smoke.jpg, dishes/steam-cloud.png = soft cloud from
smoke2.jpg, both with black turned into transparency):
- 8 wisps, 16 small crossed planes (0.24 wide x 0.45 tall)
- Every wisp has its OWN speed (5.8-8.5 s), OWN start
  delay (0-5.6 s), OWN drift (left / right / straight),
  OWN curl angle and curl speed (2.2-3.8 s), OWN opacity
  (0.38-0.55) - so they never shake in sync
- Smoke rises 2x high (to Y=1.30), starts low over the
  pizza face, grows as it rises (0.5 to 1.7x)
- Still outside #spin / inside #tilt, so it stays on top
  while the pizza spins, and tilts with the pizza.
  Crossed planes, so it never goes flat from the side.

Shadow: soft shadow 1.10 / 0.65, dark shadow 0.80 / 0.85
(v37). No smoke under the pizza.

Kept: fixed AR label, Add to cart + Photo in AR,
1-second flash, auto-spin, self-hosted libs/ engine.
iOS (Quick Look) + Android (MindAR camera scan).

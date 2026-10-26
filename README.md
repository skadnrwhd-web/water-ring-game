# 🐠 Water Ring Toss

A browser version of the classic handheld water ring game. Play it on your phone.

- Press the two buttons to shoot water jets and float the rings up
- Tilt your phone and the rings drift through the water
- Shake your phone to slosh the water around
- Hook all 6 rings onto the fish horns to clear the game. Your best time is saved on your phone.

## Deploy with GitHub Pages (iPhone motion sensors need https)

1. Create a public repository on GitHub, e.g. `water-ring-game`
2. Put `index.html` at the top level of the repository
3. Settings → Pages → Branch `main`, folder `/ (root)` → Save
4. After 1–2 minutes the game is live at `https://skadnrwhd-web.github.io/water-ring-game/`
5. Open it in iPhone Safari → tap "Start" → allow motion access

## Tips

- If you denied motion access by mistake, fully close Safari, reopen the link and tap "Start" again.
- Turn on the iPhone's portrait orientation lock for comfortable play.
- If tilting feels wrong, add `#debug` to the end of the address to show the live sensor values on screen.
- On a PC: arrow keys tilt, Z / X fire the left and right jets, and dragging the screen also tilts.

## Tuning the feel (numbers at the top of the script in index.html)

| Name | Meaning |
|---|---|
| `GRAV` | Higher = rings sink faster |
| `DRAG` | Higher = thicker, slower water |
| `JET` | Strength of the water jets |
| `N_RINGS` | Number of rings |
| `PEG_CAP` | Max rings per horn |

## Support

https://buymeacoffee.com/ujnam80

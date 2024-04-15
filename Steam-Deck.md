**WIP**<br>
<br>
Getting this started for documentation on optimising the games for Steam Deck. Refer to individual settings guides for each game.<br>
<br>
- Unlock FPS via Steam; the additional latency is far from inconsequential. Lock FPS via MangoHUD in launch options. It's reasonably better. (Is there a way to lock via dxvk.conf, and without adding the file to game directory?)
- TLC videos are broken due to gstreamer. I have no idea why, they used to work. I have not gotten Proton GE to work with TLC on Steam Deck, so I've no idea if that helps. Or if it should even be run-legal.
- Use integer scaling.
- Lock GPU clock. 1200+ MHz is fine for TLC. Consider higher for Anniversary.
- Disable overlay if in desktop mode.
- Use recent, non-experimental version of Proton.

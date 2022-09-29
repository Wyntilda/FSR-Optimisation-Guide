Resolution: ≤1366x768x32<br>
Refresh rate: 100 Hz<br>
Vertical sync: Off<br>
Antialiasing: 0x<br>
Mesh detail: 3<br>
Texture detail: 0<br>
Effects detail: 0<br>
Shadow detail: 0<br>

Vertical resolution should be no more than 768 to eliminate unnecessary mouse travel distance. Lower resolutions will lead to less travel distance, but will require higher mouse precision due to UI scaling with a vertical resolution less than 768. 1024x768 (default) seems to be most common among runners. Aspect ratio is up to you. There have been no observed benefits from using 16-bit over 32-bit colour [further testing needed].

Refresh rate does not have any apparent effect outside of Windows fullscreen (for example, with DxWnd or Proton), as the game will bypass this limit. If running in fullscreen on Windows, set the game's refresh rate to your native display refresh rate or an equal division of it (i.e. 240 ÷ 4 = 60; the options are very limited for modern displays), or adjust your monitor's refresh rate to the game. If you're on a CRT, consider sacrificing resolution to achieve 100 hz if necessary.

Vertical sync adds unnecessary latency. It should always be off. If you're running via DxWnd on Windows 8 or newer, you already have desktop compositing doing that for you.

Antialiasing adds unnecessary overhead. If you insist on using it because you want the game to wook pwetty (i.e. for an event), there's extreme diminishing returns after 4x. Avoid entirely if on TeraScale cards before the HD 4000 series.

Mesh detail should always be set to max, as it affects render distance. This is important in long range attack scenarios such as Orchard Farm, Jackshit, and the Ice Troll (mostly Orchard Farm, to my knowledge).

Everything else, optimally, should be low/off. Even with how well this game runs on basically any hardware in the last 10 years, your x% lows will objectively benefit from doing less work. Most runners on modern hardware don't care, so it's up to you how important that is. Do some testing and see what you're comfortable with. If you are consistently hitting above your target refresh rate 100% of the time, you may have a bit more wiggle room, but that's harder to achieve than you'd think.

On Nvidia GPUs at least since Kepler (600 series onwards) and likely Fermi (400 series onwards), Fable experiences a flickering bug with the glow shader that's active on Effects settings past 1.

Effects setting at 0 will lead to improved clarity while using the Slow Time spell.

The settings with the most performance impact on older hardware are Antialiasing and Effects [further testing needed].

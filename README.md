# Crabpad firmware

One ZMK firmware supports both Codex and Claude CLI profiles.

| Profile | Bottom-middle model key |
| --- | --- |
| Codex (0, default) | Types `/model`, without pressing Enter |
| Claude (1) | Sends Option+P (left Alt+P) |

Hold **Fn** (bottom-left) and tap the **top-middle** key to switch profiles:
Codex → Claude → Codex. This replaces Shift+Tab while Fn is held; ordinary
top-middle presses still send Shift+Tab. Other keys and encoder actions are
shared between profiles.

The selected profile is saved immediately to keyboard flash and restored after
restart or a normal firmware update. A full settings reset clears it and restores
Codex. Selection applies to the whole keyboard and does not follow the active
application or Bluetooth host. There is no profile indicator.

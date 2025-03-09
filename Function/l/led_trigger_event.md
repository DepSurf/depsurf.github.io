# Function: <code>led_trigger_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585981504,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:254",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_propagate_led_state",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585981504,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586387216,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:275",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_propagate_led_state",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/power_supply_leds.c:power_supply_update_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586387216,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586596016,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:282",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_propagate_led_state",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586596016,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586722688,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:282",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_propagate_led_state",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_any_led_trigger_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586722688,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587206976,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:282",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_propagate_led_state",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_any_led_trigger_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587206976,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587507536,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:282",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_propagate_led_state",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587507536,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587687152,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:320",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_propagate_led_state",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587687152,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587966368,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:316",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_propagate_led_state",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587966368,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588173504,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:317",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_propagate_led_state",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588173504,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589039056,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:363",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_start",
        "drivers/tty/vt/keyboard.c:kbd_bh",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_gen_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_gen_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_set_states",
        "net/rfkill/core.c:rfkill_set_states",
        "net/rfkill/core.c:rfkill_set_sw_state",
        "net/rfkill/core.c:rfkill_set_sw_state",
        "net/rfkill/core.c:rfkill_set_hw_state",
        "net/rfkill/core.c:rfkill_set_hw_state",
        "net/rfkill/core.c:rfkill_set_block",
        "net/rfkill/core.c:rfkill_set_block",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_led_trigger_activate",
        "net/rfkill/core.c:rfkill_led_trigger_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589039056,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589047920,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:377",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_start",
        "drivers/tty/vt/keyboard.c:kbd_bh",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_gen_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_gen_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_set_states",
        "net/rfkill/core.c:rfkill_set_states",
        "net/rfkill/core.c:rfkill_set_sw_state",
        "net/rfkill/core.c:rfkill_set_sw_state",
        "net/rfkill/core.c:rfkill_set_hw_state_reason",
        "net/rfkill/core.c:rfkill_set_hw_state_reason",
        "net/rfkill/core.c:rfkill_set_block",
        "net/rfkill/core.c:rfkill_set_block",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_led_trigger_activate",
        "net/rfkill/core.c:rfkill_led_trigger_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589047920,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588935312,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:377",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_start",
        "drivers/tty/vt/keyboard.c:kbd_bh",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_set_states",
        "net/rfkill/core.c:rfkill_set_states",
        "net/rfkill/core.c:rfkill_set_sw_state",
        "net/rfkill/core.c:rfkill_set_sw_state",
        "net/rfkill/core.c:rfkill_set_hw_state_reason",
        "net/rfkill/core.c:rfkill_set_hw_state_reason",
        "net/rfkill/core.c:rfkill_set_block",
        "net/rfkill/core.c:rfkill_set_block",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_led_trigger_activate",
        "net/rfkill/core.c:rfkill_led_trigger_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588935312,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589643056,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:377",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_start",
        "drivers/tty/vt/keyboard.c:kbd_bh",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_led_trigger_activate",
        "net/rfkill/core.c:rfkill_led_trigger_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589643056,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591144320,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:380",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_start",
        "drivers/tty/vt/keyboard.c:kbd_bh",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_led_trigger_activate",
        "net/rfkill/core.c:rfkill_led_trigger_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591144320,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592870272,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:380",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_start",
        "drivers/tty/vt/keyboard.c:kbd_bh",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_led_trigger_activate",
        "net/rfkill/core.c:rfkill_led_trigger_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592870272,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593308944,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:381",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_start",
        "drivers/tty/vt/keyboard.c:kbd_bh",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_led_trigger_activate",
        "net/rfkill/core.c:rfkill_led_trigger_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593308944,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594065296,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:368",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_start",
        "drivers/tty/vt/keyboard.c:kbd_bh",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_bat_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_led_trigger_activate",
        "net/rfkill/core.c:rfkill_led_trigger_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594065296,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501469128,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:317",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_propagate_led_state",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501469128,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234020376,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:317",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_propagate_led_state",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_no_link",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_no_link",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234020376,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295005184,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:317",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_propagate_led_state",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_no_link",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_no_link",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295005184,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278059336,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:317",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_propagate_led_state",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_no_link",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_no_link",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278059336,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587792976,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:317",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587792976,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587496400,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:317",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587496400,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588128032,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:317",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_propagate_led_state",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588128032,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void led_trigger_event(struct led_trigger * trig, enum led_brightness brightness)
```

```json
{
  "name": "led_trigger_event",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588245568,
      "name": "led_trigger_event",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:317",
      "file": "drivers/leds/led-triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/keyboard.c:kbd_propagate_led_state",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/power/supply/power_supply_leds.c:power_supply_update_leds",
        "drivers/mmc/core/core.c:mmc_start_request",
        "drivers/mmc/core/core.c:mmc_request_done",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu",
        "drivers/leds/trigger/ledtrig-panic.c:led_panic_blink",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker",
        "net/rfkill/core.c:rfkill_global_led_trigger_worker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588245568,
      "name": "led_trigger_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

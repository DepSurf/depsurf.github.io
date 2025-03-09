# Function: <code>led_trigger_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585982656,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:228",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585982656,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586388256,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:221",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586388256,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586597104,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:228",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586597104,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586721712,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:228",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721712,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587206000,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:228",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587206000,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587506544,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:228",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587506544,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587686784,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:266",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587686784,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587966000,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:262",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587966000,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588173136,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:263",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588173136,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589038112,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:309",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589038112,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589047424,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:323",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589047424,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588934816,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:323",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588934816,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589642560,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:323",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589642560,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591143568,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:326",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591143568,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592869424,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:326",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592869424,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593307952,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:327",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593307952,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594064544,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:314",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_exit",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594064544,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501472032,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:263",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501472032,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234019068,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:263",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234019068,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295004592,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:263",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295004592,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278058994,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:263",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278058994,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587792608,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:263",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587792608,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587496032,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:263",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587496032,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588127664,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:263",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588127664,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger * trig)
```

```json
{
  "name": "led_trigger_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588245200,
      "name": "led_trigger_unregister",
      "external": true,
      "loc": "drivers/leds/led-triggers.c:263",
      "file": "drivers/leds/led-triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register",
        "drivers/leds/led-triggers.c:led_trigger_unregister_simple",
        "drivers/leds/led-triggers.c:devm_led_trigger_release",
        "net/rfkill/core.c:rfkill_init",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister",
        "net/rfkill/core.c:rfkill_global_led_trigger_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588245200,
      "name": "led_trigger_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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

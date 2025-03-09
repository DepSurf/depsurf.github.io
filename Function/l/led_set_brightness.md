# Function: <code>led_set_brightness</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585979472,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:190",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_event",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585979472,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586385280,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:228",
      "file": "drivers/leds/led-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_event",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586385280,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586594064,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:229",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_event",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586594064,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586718496,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:229",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718496,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587202768,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:229",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587202768,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587503312,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:229",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587503312,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587683312,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:229",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587683312,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587962528,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:227",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587962528,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588169296,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:241",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588169296,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589033712,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:241",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589033712,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589043184,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:243",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589043184,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void led_set_brightness(struct led_classdev * led_cdev, unsigned int brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588930784,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:241",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588930784,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void led_set_brightness(struct led_classdev * led_cdev, unsigned int brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589638496,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:241",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589638496,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void led_set_brightness(struct led_classdev * led_cdev, unsigned int brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591138944,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:241",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591138944,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void led_set_brightness(struct led_classdev * led_cdev, unsigned int brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592864160,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:241",
      "file": "drivers/leds/led-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592864160,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void led_set_brightness(struct led_classdev * led_cdev, unsigned int brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593300720,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:281",
      "file": "drivers/leds/led-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593300720,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void led_set_brightness(struct led_classdev * led_cdev, unsigned int brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594057120,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:286",
      "file": "drivers/leds/led-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:led_classdev_unregister",
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594057120,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501464840,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:241",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501464840,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234015308,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:241",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234015308,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294998464,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:241",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294998464,
      "name": "led_set_brightness",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278055550,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:241",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278055550,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587790864,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:241",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587790864,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587494288,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:241",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587494288,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588123824,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:241",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588123824,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void led_set_brightness(struct led_classdev * led_cdev, enum led_brightness brightness)
```

```json
{
  "name": "led_set_brightness",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588241360,
      "name": "led_set_brightness",
      "external": true,
      "loc": "drivers/leds/led-core.c:241",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-class.c:brightness_store",
        "drivers/leds/led-triggers.c:led_trigger_set",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588241360,
      "name": "led_set_brightness",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum led_brightness brightness</code> ➡️ <code>unsigned int brightness</code>
</li>
</ul>
</details>
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

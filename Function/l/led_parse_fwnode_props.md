# Function: <code>led_parse_fwnode_props</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "led_parse_fwnode_props",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588167780,
      "name": "led_parse_fwnode_props",
      "external": false,
      "loc": "drivers/leds/led-core.c:368",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:led_compose_name"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void led_parse_fwnode_props(struct device * dev, struct fwnode_handle * fwnode, struct led_properties * props)
```

```json
{
  "name": "led_parse_fwnode_props",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "led_parse_fwnode_props",
      "external": false,
      "loc": "drivers/leds/led-core.c:368",
      "file": "drivers/leds/led-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589031968,
      "name": "led_parse_fwnode_props",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071589034035,
      "name": "led_parse_fwnode_props.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void led_parse_fwnode_props(struct device * dev, struct fwnode_handle * fwnode, struct led_properties * props)
```

```json
{
  "name": "led_parse_fwnode_props",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "led_parse_fwnode_props",
      "external": false,
      "loc": "drivers/leds/led-core.c:370",
      "file": "drivers/leds/led-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589041408,
      "name": "led_parse_fwnode_props",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071591605056,
      "name": "led_parse_fwnode_props.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void led_parse_fwnode_props(struct device * dev, struct fwnode_handle * fwnode, struct led_properties * props)
```

```json
{
  "name": "led_parse_fwnode_props",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "led_parse_fwnode_props",
      "external": false,
      "loc": "drivers/leds/led-core.c:364",
      "file": "drivers/leds/led-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588928752,
      "name": "led_parse_fwnode_props",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071591548625,
      "name": "led_parse_fwnode_props.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void led_parse_fwnode_props(struct device * dev, struct fwnode_handle * fwnode, struct led_properties * props)
```

```json
{
  "name": "led_parse_fwnode_props",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "led_parse_fwnode_props",
      "external": false,
      "loc": "drivers/leds/led-core.c:364",
      "file": "drivers/leds/led-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589636112,
      "name": "led_parse_fwnode_props",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071592667456,
      "name": "led_parse_fwnode_props.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void led_parse_fwnode_props(struct device * dev, struct fwnode_handle * fwnode, struct led_properties * props)
```

```json
{
  "name": "led_parse_fwnode_props",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "led_parse_fwnode_props",
      "external": false,
      "loc": "drivers/leds/led-core.c:364",
      "file": "drivers/leds/led-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591136608,
      "name": "led_parse_fwnode_props",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
    },
    {
      "addr": 18446744071594552758,
      "name": "led_parse_fwnode_props.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void led_parse_fwnode_props(struct device * dev, struct fwnode_handle * fwnode, struct led_properties * props)
```

```json
{
  "name": "led_parse_fwnode_props",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592861568,
      "name": "led_parse_fwnode_props",
      "external": false,
      "loc": "drivers/leds/led-core.c:364",
      "file": "drivers/leds/led-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592861568,
      "name": "led_parse_fwnode_props",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
void led_parse_fwnode_props(struct device * dev, struct fwnode_handle * fwnode, struct led_properties * props)
```

```json
{
  "name": "led_parse_fwnode_props",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593298784,
      "name": "led_parse_fwnode_props",
      "external": false,
      "loc": "drivers/leds/led-core.c:419",
      "file": "drivers/leds/led-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593298784,
      "name": "led_parse_fwnode_props",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
void led_parse_fwnode_props(struct device * dev, struct fwnode_handle * fwnode, struct led_properties * props)
```

```json
{
  "name": "led_parse_fwnode_props",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594055200,
      "name": "led_parse_fwnode_props",
      "external": false,
      "loc": "drivers/leds/led-core.c:424",
      "file": "drivers/leds/led-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/leds/led-core.c:led_compose_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594055200,
      "name": "led_parse_fwnode_props",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "led_parse_fwnode_props",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501462776,
      "name": "led_parse_fwnode_props",
      "external": false,
      "loc": "drivers/leds/led-core.c:368",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:led_compose_name"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "led_parse_fwnode_props",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234013484,
      "name": "led_parse_fwnode_props",
      "external": false,
      "loc": "drivers/leds/led-core.c:368",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:led_compose_name"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "led_parse_fwnode_props",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294995820,
      "name": "led_parse_fwnode_props",
      "external": false,
      "loc": "drivers/leds/led-core.c:368",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:led_compose_name"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "led_parse_fwnode_props",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278053902,
      "name": "led_parse_fwnode_props",
      "external": false,
      "loc": "drivers/leds/led-core.c:368",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:led_compose_name"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "led_parse_fwnode_props",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587789348,
      "name": "led_parse_fwnode_props",
      "external": false,
      "loc": "drivers/leds/led-core.c:368",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:led_compose_name"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "led_parse_fwnode_props",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587492772,
      "name": "led_parse_fwnode_props",
      "external": false,
      "loc": "drivers/leds/led-core.c:368",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:led_compose_name"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "led_parse_fwnode_props",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588122308,
      "name": "led_parse_fwnode_props",
      "external": false,
      "loc": "drivers/leds/led-core.c:368",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:led_compose_name"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "led_parse_fwnode_props",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588239844,
      "name": "led_parse_fwnode_props",
      "external": false,
      "loc": "drivers/leds/led-core.c:368",
      "file": "drivers/leds/led-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:led_compose_name"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void led_parse_fwnode_props(struct device * dev, struct fwnode_handle * fwnode, struct led_properties * props)
```
</details>
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

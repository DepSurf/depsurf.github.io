# Function: <code>dummycon_register_output_notifier</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void dummycon_register_output_notifier(struct notifier_block * nb)
```

```json
{
  "name": "dummycon_register_output_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584843136,
      "name": "dummycon_register_output_notifier",
      "external": true,
      "loc": "drivers/video/console/dummycon.c:35",
      "file": "drivers/video/console/dummycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fb_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584843136,
      "name": "dummycon_register_output_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void dummycon_register_output_notifier(struct notifier_block * nb)
```

```json
{
  "name": "dummycon_register_output_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585539072,
      "name": "dummycon_register_output_notifier",
      "external": true,
      "loc": "drivers/video/console/dummycon.c:35",
      "file": "drivers/video/console/dummycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585539072,
      "name": "dummycon_register_output_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void dummycon_register_output_notifier(struct notifier_block * nb)
```

```json
{
  "name": "dummycon_register_output_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585673360,
      "name": "dummycon_register_output_notifier",
      "external": true,
      "loc": "drivers/video/console/dummycon.c:35",
      "file": "drivers/video/console/dummycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585673360,
      "name": "dummycon_register_output_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void dummycon_register_output_notifier(struct notifier_block * nb)
```

```json
{
  "name": "dummycon_register_output_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585554064,
      "name": "dummycon_register_output_notifier",
      "external": true,
      "loc": "drivers/video/console/dummycon.c:35",
      "file": "drivers/video/console/dummycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fb_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585554064,
      "name": "dummycon_register_output_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void dummycon_register_output_notifier(struct notifier_block * nb)
```

```json
{
  "name": "dummycon_register_output_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dummycon_register_output_notifier",
      "external": true,
      "loc": "drivers/video/console/dummycon.c:35",
      "file": "drivers/video/console/dummycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fb_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592394498,
      "name": "dummycon_register_output_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586025152,
      "name": "dummycon_register_output_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void dummycon_register_output_notifier(struct notifier_block * nb)
```

```json
{
  "name": "dummycon_register_output_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dummycon_register_output_notifier",
      "external": true,
      "loc": "drivers/video/console/dummycon.c:35",
      "file": "drivers/video/console/dummycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fb_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594259270,
      "name": "dummycon_register_output_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587244928,
      "name": "dummycon_register_output_notifier",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void dummycon_register_output_notifier(struct notifier_block * nb)
```

```json
{
  "name": "dummycon_register_output_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dummycon_register_output_notifier",
      "external": true,
      "loc": "drivers/video/console/dummycon.c:35",
      "file": "drivers/video/console/dummycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fb_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596213080,
      "name": "dummycon_register_output_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588483696,
      "name": "dummycon_register_output_notifier",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void dummycon_register_output_notifier(struct notifier_block * nb)
```

```json
{
  "name": "dummycon_register_output_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dummycon_register_output_notifier",
      "external": true,
      "loc": "drivers/video/console/dummycon.c:35",
      "file": "drivers/video/console/dummycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fb_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596738232,
      "name": "dummycon_register_output_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588763328,
      "name": "dummycon_register_output_notifier",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void dummycon_register_output_notifier(struct notifier_block * nb)
```

```json
{
  "name": "dummycon_register_output_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dummycon_register_output_notifier",
      "external": true,
      "loc": "drivers/video/console/dummycon.c:36",
      "file": "drivers/video/console/dummycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fb_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597647029,
      "name": "dummycon_register_output_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589066544,
      "name": "dummycon_register_output_notifier",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void dummycon_register_output_notifier(struct notifier_block * nb)
```

```json
{
  "name": "dummycon_register_output_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497239200,
      "name": "dummycon_register_output_notifier",
      "external": true,
      "loc": "drivers/video/console/dummycon.c:35",
      "file": "drivers/video/console/dummycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fb_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497239200,
      "name": "dummycon_register_output_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void dummycon_register_output_notifier(struct notifier_block * nb)
```

```json
{
  "name": "dummycon_register_output_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230424992,
      "name": "dummycon_register_output_notifier",
      "external": true,
      "loc": "drivers/video/console/dummycon.c:35",
      "file": "drivers/video/console/dummycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fb_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230424992,
      "name": "dummycon_register_output_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void dummycon_register_output_notifier(struct notifier_block * nb)
```

```json
{
  "name": "dummycon_register_output_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291188176,
      "name": "dummycon_register_output_notifier",
      "external": true,
      "loc": "drivers/video/console/dummycon.c:35",
      "file": "drivers/video/console/dummycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fb_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291188176,
      "name": "dummycon_register_output_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void dummycon_register_output_notifier(struct notifier_block * nb)
```

```json
{
  "name": "dummycon_register_output_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275777136,
      "name": "dummycon_register_output_notifier",
      "external": true,
      "loc": "drivers/video/console/dummycon.c:35",
      "file": "drivers/video/console/dummycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fb_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275777136,
      "name": "dummycon_register_output_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void dummycon_register_output_notifier(struct notifier_block * nb)
```

```json
{
  "name": "dummycon_register_output_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584900880,
      "name": "dummycon_register_output_notifier",
      "external": true,
      "loc": "drivers/video/console/dummycon.c:35",
      "file": "drivers/video/console/dummycon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fb_console_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584900880,
      "name": "dummycon_register_output_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void dummycon_register_output_notifier(struct notifier_block * nb)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void dummycon_register_output_notifier(struct notifier_block * nb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void dummycon_register_output_notifier(struct notifier_block * nb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
void dummycon_register_output_notifier(struct notifier_block * nb)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

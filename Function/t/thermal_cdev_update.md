# Function: <code>thermal_cdev_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585681136,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1617",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:power_actor_set_power"
      ],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/step_wise.c:step_wise_throttle",
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585681136,
      "name": "thermal_cdev_update.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071585681488,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586073616,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1623",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/step_wise.c:step_wise_throttle",
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586073616,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586291456,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:169",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/step_wise.c:step_wise_throttle",
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586291456,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586390448,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:169",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/step_wise.c:step_wise_throttle",
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586390448,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586853632,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:169",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/step_wise.c:step_wise_throttle",
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586853632,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587147696,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:166",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/step_wise.c:step_wise_throttle",
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587147696,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587327632,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:166",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/step_wise.c:step_wise_throttle",
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587327632,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587598480,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:166",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/step_wise.c:step_wise_throttle",
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587598480,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587801920,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:166",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/step_wise.c:step_wise_throttle",
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587801920,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588647920,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:178",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/gov_fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/gov_step_wise.c:step_wise_throttle",
        "drivers/thermal/gov_power_allocator.c:allow_maximum_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588647920,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588670096,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:188",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/gov_fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/gov_step_wise.c:step_wise_throttle",
        "drivers/thermal/gov_power_allocator.c:allow_maximum_power",
        "drivers/thermal/gov_power_allocator.c:allocate_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588670096,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588553408,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:222",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/gov_step_wise.c:step_wise_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588553408,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:222",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/gov_step_wise.c:step_wise_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592636217,
      "name": "thermal_cdev_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589227488,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:222",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/gov_step_wise.c:step_wise_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594519889,
      "name": "thermal_cdev_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590691120,
      "name": "thermal_cdev_update",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:248",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/gov_step_wise.c:step_wise_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596309196,
      "name": "thermal_cdev_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592361248,
      "name": "thermal_cdev_update",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:188",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/gov_step_wise.c:step_wise_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596838550,
      "name": "thermal_cdev_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592788816,
      "name": "thermal_cdev_update",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:195",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/gov_step_wise.c:step_wise_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597762707,
      "name": "thermal_cdev_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593537744,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501004104,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:166",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/step_wise.c:step_wise_throttle",
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501004104,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233516444,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:166",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/step_wise.c:step_wise_throttle",
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233516444,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294481888,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:166",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/step_wise.c:step_wise_throttle",
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294481888,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277754136,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:166",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/step_wise.c:step_wise_throttle",
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277754136,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587432896,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:166",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/step_wise.c:step_wise_throttle",
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587432896,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587201104,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:166",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/step_wise.c:step_wise_throttle",
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587201104,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587758064,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:166",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/step_wise.c:step_wise_throttle",
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587758064,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void thermal_cdev_update(struct thermal_cooling_device * cdev)
```

```json
{
  "name": "thermal_cdev_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587871264,
      "name": "thermal_cdev_update",
      "external": true,
      "loc": "drivers/thermal/thermal_helpers.c:166",
      "file": "drivers/thermal/thermal_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:power_actor_set_power",
        "drivers/thermal/fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:bang_bang_control",
        "drivers/thermal/step_wise.c:step_wise_throttle",
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587871264,
      "name": "thermal_cdev_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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

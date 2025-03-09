# Function: <code>hv_ce_shutdown</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int hv_ce_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "hv_ce_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588005728,
      "name": "hv_ce_shutdown",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:64",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588005728,
      "name": "hv_ce_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int hv_ce_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "hv_ce_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588213296,
      "name": "hv_ce_shutdown",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:65",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588213296,
      "name": "hv_ce_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int hv_ce_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "hv_ce_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589081784,
      "name": "hv_ce_shutdown",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:75",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589081488,
      "name": "hv_ce_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int hv_ce_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "hv_ce_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589082792,
      "name": "hv_ce_shutdown",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:75",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589082496,
      "name": "hv_ce_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int hv_ce_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "hv_ce_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588968939,
      "name": "hv_ce_shutdown",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:87",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup",
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588968624,
      "name": "hv_ce_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hv_ce_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "hv_ce_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589678709,
      "name": "hv_ce_shutdown",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:87",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589678640,
      "name": "hv_ce_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071592676592,
      "name": "hv_ce_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hv_ce_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "hv_ce_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591183875,
      "name": "hv_ce_shutdown",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:87",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591183808,
      "name": "hv_ce_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071594561837,
      "name": "hv_ce_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hv_ce_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "hv_ce_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592910371,
      "name": "hv_ce_shutdown",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:88",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592910304,
      "name": "hv_ce_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071596318659,
      "name": "hv_ce_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hv_ce_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "hv_ce_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593349751,
      "name": "hv_ce_shutdown",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:88",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593349696,
      "name": "hv_ce_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071596848289,
      "name": "hv_ce_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hv_ce_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "hv_ce_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594103751,
      "name": "hv_ce_shutdown",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:88",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594103696,
      "name": "hv_ce_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071597773214,
      "name": "hv_ce_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int hv_ce_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "hv_ce_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587825152,
      "name": "hv_ce_shutdown",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:65",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587825152,
      "name": "hv_ce_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int hv_ce_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "hv_ce_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587535712,
      "name": "hv_ce_shutdown",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:65",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587535712,
      "name": "hv_ce_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int hv_ce_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "hv_ce_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588167776,
      "name": "hv_ce_shutdown",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:65",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588167776,
      "name": "hv_ce_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int hv_ce_shutdown(struct clock_event_device * evt)
```

```json
{
  "name": "hv_ce_shutdown",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588285632,
      "name": "hv_ce_shutdown",
      "external": false,
      "loc": "drivers/clocksource/hyperv_timer.c:65",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588285632,
      "name": "hv_ce_shutdown",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int hv_ce_shutdown(struct clock_event_device * evt)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int hv_ce_shutdown(struct clock_event_device * evt)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int hv_ce_shutdown(struct clock_event_device * evt)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int hv_ce_shutdown(struct clock_event_device * evt)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int hv_ce_shutdown(struct clock_event_device * evt)
```
</details>
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

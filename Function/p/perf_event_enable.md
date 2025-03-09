# Function: <code>perf_event_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580408528,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2359",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580408528,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580483440,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2453",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580483440,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580548832,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2517",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:watchdog_nmi_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580548832,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580580608,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2600",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:watchdog_nmi_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580580608,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580660336,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2512",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660336,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580791184,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2721",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791184,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857552,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2721",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857552,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580950704,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2739",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580950704,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003616,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2824",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003616,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581175136,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2993",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581175136,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581216000,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:3037",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216000,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237600,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:3039",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237600,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581476032,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:3081",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581476032,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802944,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2992",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802944,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582232592,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2993",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232592,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582433424,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2993",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_perf.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_perf.c:watchdog_hardlockup_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582433424,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582601808,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:3031",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_perf.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_perf.c:watchdog_hardlockup_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582601808,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492346744,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2824",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492346744,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226226488,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2824",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226226488,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285596192,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2824",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285596192,
      "name": "perf_event_enable",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272469538,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2824",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272469538,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580972416,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2824",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580972416,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580918816,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2824",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918816,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963664,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2824",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963664,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void perf_event_enable(struct perf_event * event)
```

```json
{
  "name": "perf_event_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581024704,
      "name": "perf_event_enable",
      "external": true,
      "loc": "kernel/events/core.c:2824",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_restart",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_enable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581024704,
      "name": "perf_event_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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

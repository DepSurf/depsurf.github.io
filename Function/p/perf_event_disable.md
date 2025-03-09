# Function: <code>perf_event_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580408944,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:1824",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580408944,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580483264,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:1957",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:watchdog_nmi_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580483264,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580548656,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:1989",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:watchdog_nmi_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580548656,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580580432,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2002",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:watchdog_nmi_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580580432,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580660160,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:1995",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660160,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580791008,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2192",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791008,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857376,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2192",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857376,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580950640,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2194",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580950640,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003552,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2279",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003552,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581174832,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2426",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581174832,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581215664,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2466",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581215664,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237264,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2468",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237264,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581475696,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2543",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475696,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581803184,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2456",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803184,
      "name": "perf_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582232864,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2461",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232864,
      "name": "perf_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582433696,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2461",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_perf.c:hardlockup_detector_perf_stop",
        "kernel/watchdog_perf.c:watchdog_hardlockup_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582433696,
      "name": "perf_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582602080,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2499",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_perf.c:hardlockup_detector_perf_stop",
        "kernel/watchdog_perf.c:watchdog_hardlockup_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602080,
      "name": "perf_event_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492354440,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2279",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/pmu.c:kvm_pmu_release_perf_event",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492354440,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226226540,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2279",
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
      "addr": 3226226540,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285595792,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2279",
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
      "addr": 13835058055285595792,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272469232,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2279",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272469232,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580972352,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2279",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580972352,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580918752,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2279",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918752,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963600,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2279",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963600,
      "name": "perf_event_disable",
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
void perf_event_disable(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581024640,
      "name": "perf_event_disable",
      "external": true,
      "loc": "kernel/events/core.c:2279",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog_hld.c:hardlockup_detector_perf_stop",
        "kernel/watchdog_hld.c:hardlockup_detector_perf_disable",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581024640,
      "name": "perf_event_disable",
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

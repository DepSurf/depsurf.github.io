# Function: <code>modify_user_hw_breakpoint_check</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580828000,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:482",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580828000,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580894656,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:474",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580894656,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:461",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992922,
      "name": "modify_user_hw_breakpoint_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071580992176,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046192,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:461",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046192,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581225920,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:477",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581225920,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
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
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581268496,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:477",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268496,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
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
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581287136,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:477",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287136,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 666
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
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581531472,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:478",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581531472,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 666
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
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581879760,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:478",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879760,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 712
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
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582311920,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:789",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582311920,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 724
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
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582513168,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:789",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582513168,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582681648,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:761",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582681648,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492402624,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:461",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492402624,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226287488,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:461",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226287488,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285665840,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:461",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285665840,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "modify_user_hw_breakpoint_check",
      "external": false,
      "loc": "include/linux/hw_breakpoint.h:104",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581015040,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:461",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581015040,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580961168,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:461",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580961168,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581006240,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:461",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006240,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```

```json
{
  "name": "modify_user_hw_breakpoint_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581067440,
      "name": "modify_user_hw_breakpoint_check",
      "external": true,
      "loc": "kernel/events/hw_breakpoint.c:461",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl",
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581067440,
      "name": "modify_user_hw_breakpoint_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int modify_user_hw_breakpoint_check(struct perf_event * bp, struct perf_event_attr * attr, bool check)
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

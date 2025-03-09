# Function: <code>perf_event_disable_local</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580503334,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:1948",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580488416,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580567430,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:1980",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580551616,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580597702,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:1993",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580582800,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580677949,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:1986",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580662528,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580809713,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2183",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580794000,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580876351,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2183",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860496,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580972627,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2185",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580957152,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581026755,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2270",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581009360,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581208323,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2417",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581190112,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581250729,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2457",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581231744,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581267232,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2459",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247472,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581508000,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2534",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581483296,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581854544,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2447",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581828272,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582280853,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2452",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_irq"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582255568,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582481813,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2452",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_irq"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582456176,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582650485,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2490",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_irq"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624880,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492387560,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2270",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492361864,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226265212,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2270",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226246960,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285636220,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2270",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285614096,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272491594,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2270",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272486870,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580995603,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2270",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580978208,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580941795,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2270",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580924336,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580986803,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2270",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969408,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void perf_event_disable_local(struct perf_event * event)
```

```json
{
  "name": "perf_event_disable_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581047747,
      "name": "perf_event_disable_local",
      "external": true,
      "loc": "kernel/events/core.c:2270",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pending_event"
      ],
      "caller_func": [
        "kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030192,
      "name": "perf_event_disable_local",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void perf_event_disable_local(struct perf_event * event)
```
</details>
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

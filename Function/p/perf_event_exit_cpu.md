# Function: <code>perf_event_exit_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580391365,
      "name": "perf_event_exit_cpu",
      "external": false,
      "loc": "kernel/events/core.c:9318",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580459109,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:10518",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580512032,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580521557,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:10792",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576048,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580553237,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:11089",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580606720,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580634309,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:11122",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687456,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580760869,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:11674",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580819440,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580827477,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:11717",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886112,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580922158,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:12082",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983424,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580975614,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:12199",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037552,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581142670,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:12802",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216192,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581182622,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:13085",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259024,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581201006,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:13278",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277776,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581441502,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:13399",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581521616,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581782449,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:13369",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581869120,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582219150,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:13596",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296528,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582418302,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:13638",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582497296,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582586014,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:13736",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665808,
      "name": "perf_event_exit_cpu",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492340280,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:12199",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492390064,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226219072,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:12199",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226277920,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285571044,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:12199",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285652224,
      "name": "perf_event_exit_cpu",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272501142,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:12199",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272501142,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580944414,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:12199",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006400,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580890478,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:12199",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952528,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580935662,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:12199",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997600,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int perf_event_exit_cpu(unsigned int cpu)
```

```json
{
  "name": "perf_event_exit_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580997198,
      "name": "perf_event_exit_cpu",
      "external": true,
      "loc": "kernel/events/core.c:12199",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_reboot"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581058688,
      "name": "perf_event_exit_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int perf_event_exit_cpu(unsigned int cpu)
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

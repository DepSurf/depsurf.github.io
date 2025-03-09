# Function: <code>unregister_sched_domain_sysctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579565275,
      "name": "unregister_sched_domain_sysctl",
      "external": false,
      "loc": "kernel/sched/core.c:5467",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:partition_sched_domains"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579678912,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:355",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:partition_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678912,
      "name": "unregister_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579703536,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:355",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:partition_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579703536,
      "name": "unregister_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579699696,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:356",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699696,
      "name": "unregister_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579731152,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:403",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579731152,
      "name": "unregister_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579760960,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:378",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760960,
      "name": "unregister_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803840,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:379",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803840,
      "name": "unregister_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579831984,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:366",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831984,
      "name": "unregister_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579880288,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:366",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880288,
      "name": "unregister_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579923184,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:366",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579923184,
      "name": "unregister_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579917056,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:420",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917056,
      "name": "unregister_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491081600,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:366",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491081600,
      "name": "unregister_sched_domain_sysctl",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225085820,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:366",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225085820,
      "name": "unregister_sched_domain_sysctl",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283966576,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:366",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283966576,
      "name": "unregister_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271670490,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:366",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271670490,
      "name": "unregister_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579852432,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:366",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852432,
      "name": "unregister_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579787344,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:366",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787344,
      "name": "unregister_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579840656,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:366",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579840656,
      "name": "unregister_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void unregister_sched_domain_sysctl()
```

```json
{
  "name": "unregister_sched_domain_sysctl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579885712,
      "name": "unregister_sched_domain_sysctl",
      "external": true,
      "loc": "kernel/sched/debug.c:366",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579885712,
      "name": "unregister_sched_domain_sysctl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void unregister_sched_domain_sysctl()
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void unregister_sched_domain_sysctl()
```
</details>
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

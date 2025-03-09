# Function: <code>update_sched_domain_debugfs</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void update_sched_domain_debugfs()
```

```json
{
  "name": "update_sched_domain_debugfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_sched_domain_debugfs",
      "external": true,
      "loc": "kernel/sched/debug.c:387",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/debug.c:sched_init_debug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591230310,
      "name": "update_sched_domain_debugfs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579924400,
      "name": "update_sched_domain_debugfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
void update_sched_domain_debugfs()
```

```json
{
  "name": "update_sched_domain_debugfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_sched_domain_debugfs",
      "external": true,
      "loc": "kernel/sched/debug.c:393",
      "file": "kernel/sched/debug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/debug.c:sched_init_debug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592117141,
      "name": "update_sched_domain_debugfs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580047472,
      "name": "update_sched_domain_debugfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
void update_sched_domain_debugfs()
```

```json
{
  "name": "update_sched_domain_debugfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "update_sched_domain_debugfs",
      "external": true,
      "loc": "kernel/sched/debug.c:393",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_debug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593886330,
      "name": "update_sched_domain_debugfs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580180336,
      "name": "update_sched_domain_debugfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
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
void update_sched_domain_debugfs()
```

```json
{
  "name": "update_sched_domain_debugfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580365136,
      "name": "update_sched_domain_debugfs",
      "external": true,
      "loc": "kernel/sched/debug.c:394",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_debug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580365136,
      "name": "update_sched_domain_debugfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 815
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
void update_sched_domain_debugfs()
```

```json
{
  "name": "update_sched_domain_debugfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580461146,
      "name": "update_sched_domain_debugfs",
      "external": true,
      "loc": "kernel/sched/debug.c:432",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_verbose_write"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_verbose_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580427936,
      "name": "update_sched_domain_debugfs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 988
    },
    {
      "addr": 18446744071596501256,
      "name": "update_sched_domain_debugfs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580434496,
      "name": "update_sched_domain_debugfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void update_sched_domain_debugfs()
```

```json
{
  "name": "update_sched_domain_debugfs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580520816,
      "name": "update_sched_domain_debugfs",
      "external": true,
      "loc": "kernel/sched/debug.c:430",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_verbose_write"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:partition_sched_domains_locked",
        "kernel/sched/build_utility.c:sched_init_debug",
        "kernel/sched/build_utility.c:sched_verbose_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580487424,
      "name": "update_sched_domain_debugfs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1023
    },
    {
      "addr": 18446744071597398932,
      "name": "update_sched_domain_debugfs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580493552,
      "name": "update_sched_domain_debugfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void update_sched_domain_debugfs()
```
</details>
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

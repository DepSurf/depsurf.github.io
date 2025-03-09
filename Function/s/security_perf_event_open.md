# Function: <code>security_perf_event_open</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int security_perf_event_open(struct perf_event_attr * attr, int type)
```

```json
{
  "name": "security_perf_event_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583746672,
      "name": "security_perf_event_open",
      "external": true,
      "loc": "security/security.c:2992",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "kernel/trace/trace_event_perf.c:perf_trace_event_perm",
        "kernel/trace/trace_event_perf.c:perf_trace_event_perm",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_copy_attr",
        "kernel/events/core.c:find_get_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583746672,
      "name": "security_perf_event_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_perf_event_open(struct perf_event_attr * attr, int type)
```

```json
{
  "name": "security_perf_event_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583866992,
      "name": "security_perf_event_open",
      "external": true,
      "loc": "security/security.c:3010",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "kernel/trace/trace_event_perf.c:perf_trace_event_perm",
        "kernel/trace/trace_event_perf.c:perf_trace_event_perm",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_copy_attr",
        "kernel/events/core.c:find_get_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583866992,
      "name": "security_perf_event_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_perf_event_open(struct perf_event_attr * attr, int type)
```

```json
{
  "name": "security_perf_event_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583893152,
      "name": "security_perf_event_open",
      "external": true,
      "loc": "security/security.c:3073",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_copy_attr",
        "kernel/events/core.c:find_get_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583893152,
      "name": "security_perf_event_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_perf_event_open(struct perf_event_attr * attr, int type)
```

```json
{
  "name": "security_perf_event_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584256976,
      "name": "security_perf_event_open",
      "external": true,
      "loc": "security/security.c:3081",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_copy_attr",
        "kernel/events/core.c:find_get_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584256976,
      "name": "security_perf_event_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_perf_event_open(struct perf_event_attr * attr, int type)
```

```json
{
  "name": "security_perf_event_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584868944,
      "name": "security_perf_event_open",
      "external": true,
      "loc": "security/security.c:3159",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_copy_attr",
        "kernel/events/core.c:find_get_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584868944,
      "name": "security_perf_event_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_perf_event_open(struct perf_event_attr * attr, int type)
```

```json
{
  "name": "security_perf_event_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585574208,
      "name": "security_perf_event_open",
      "external": true,
      "loc": "security/security.c:3139",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_copy_attr",
        "kernel/events/core.c:find_get_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585574208,
      "name": "security_perf_event_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_perf_event_open(struct perf_event_attr * attr, int type)
```

```json
{
  "name": "security_perf_event_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585805472,
      "name": "security_perf_event_open",
      "external": true,
      "loc": "security/security.c:5611",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_copy_attr",
        "kernel/events/core.c:find_get_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805472,
      "name": "security_perf_event_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_perf_event_open(struct perf_event_attr * attr, int type)
```

```json
{
  "name": "security_perf_event_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586053920,
      "name": "security_perf_event_open",
      "external": true,
      "loc": "security/security.c:5752",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/bts.c:bts_event_init",
        "arch/x86/events/intel/p4.c:p4_hw_config",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "kernel/events/core.c:perf_copy_attr",
        "kernel/events/core.c:find_get_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586053920,
      "name": "security_perf_event_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int security_perf_event_open(struct perf_event_attr * attr, int type)
```
</details>
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

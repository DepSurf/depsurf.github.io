# Function: <code>trace_probe_init</code>

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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group)
```

```json
{
  "name": "trace_probe_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580727552,
      "name": "trace_probe_init",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:904",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:alloc_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580727552,
      "name": "trace_probe_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group, bool alloc_filter)
```

```json
{
  "name": "trace_probe_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580776640,
      "name": "trace_probe_init",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:988",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:alloc_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580776640,
      "name": "trace_probe_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group, bool alloc_filter)
```

```json
{
  "name": "trace_probe_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580893760,
      "name": "trace_probe_init",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:988",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:alloc_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893760,
      "name": "trace_probe_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group, bool alloc_filter)
```

```json
{
  "name": "trace_probe_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580888048,
      "name": "trace_probe_init",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:988",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:alloc_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888048,
      "name": "trace_probe_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group, bool alloc_filter)
```

```json
{
  "name": "trace_probe_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580891776,
      "name": "trace_probe_init",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:988",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:alloc_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580891776,
      "name": "trace_probe_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group, bool alloc_filter)
```

```json
{
  "name": "trace_probe_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581093184,
      "name": "trace_probe_init",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1020",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:alloc_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093184,
      "name": "trace_probe_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group, bool alloc_filter)
```

```json
{
  "name": "trace_probe_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581354960,
      "name": "trace_probe_init",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1027",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:alloc_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581354960,
      "name": "trace_probe_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group, bool alloc_filter)
```

```json
{
  "name": "trace_probe_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581689696,
      "name": "trace_probe_init",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1050",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:alloc_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581689696,
      "name": "trace_probe_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group, bool alloc_filter)
```

```json
{
  "name": "trace_probe_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581834320,
      "name": "trace_probe_init",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1531",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:alloc_trace_uprobe",
        "kernel/trace/trace_fprobe.c:alloc_trace_fprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581834320,
      "name": "trace_probe_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group, bool alloc_filter)
```

```json
{
  "name": "trace_probe_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581957040,
      "name": "trace_probe_init",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1768",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:alloc_trace_uprobe",
        "kernel/trace/trace_fprobe.c:alloc_trace_fprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581957040,
      "name": "trace_probe_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group, bool alloc_filter)
```

```json
{
  "name": "trace_probe_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492088392,
      "name": "trace_probe_init",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:988",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:alloc_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492088392,
      "name": "trace_probe_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group, bool alloc_filter)
```

```json
{
  "name": "trace_probe_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225988496,
      "name": "trace_probe_init",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:988",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:alloc_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225988496,
      "name": "trace_probe_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group, bool alloc_filter)
```

```json
{
  "name": "trace_probe_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285283856,
      "name": "trace_probe_init",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:988",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:alloc_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285283856,
      "name": "trace_probe_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
    }
  ]
}
```
</details>
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group, bool alloc_filter)
```

```json
{
  "name": "trace_probe_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580745440,
      "name": "trace_probe_init",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:988",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:alloc_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580745440,
      "name": "trace_probe_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group, bool alloc_filter)
```

```json
{
  "name": "trace_probe_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580691632,
      "name": "trace_probe_init",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:988",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:alloc_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580691632,
      "name": "trace_probe_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group, bool alloc_filter)
```

```json
{
  "name": "trace_probe_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580736688,
      "name": "trace_probe_init",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:988",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:alloc_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580736688,
      "name": "trace_probe_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group, bool alloc_filter)
```

```json
{
  "name": "trace_probe_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580794640,
      "name": "trace_probe_init",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:988",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:alloc_trace_kprobe",
        "kernel/trace/trace_uprobe.c:alloc_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580794640,
      "name": "trace_probe_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool alloc_filter</code>
</li>
</ul>
</details>
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
int trace_probe_init(struct trace_probe * tp, const char * event, const char * group, bool alloc_filter)
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

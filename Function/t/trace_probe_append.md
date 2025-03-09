# Function: <code>trace_probe_append</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
```

```json
{
  "name": "trace_probe_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580776320,
      "name": "trace_probe_append",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:955",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580776320,
      "name": "trace_probe_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
```

```json
{
  "name": "trace_probe_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580893344,
      "name": "trace_probe_append",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:955",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580893344,
      "name": "trace_probe_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
```

```json
{
  "name": "trace_probe_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580887632,
      "name": "trace_probe_append",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:955",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580887632,
      "name": "trace_probe_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
```

```json
{
  "name": "trace_probe_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580891360,
      "name": "trace_probe_append",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:955",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580891360,
      "name": "trace_probe_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
```

```json
{
  "name": "trace_probe_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581092768,
      "name": "trace_probe_append",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:987",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581092768,
      "name": "trace_probe_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
```

```json
{
  "name": "trace_probe_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581354496,
      "name": "trace_probe_append",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:994",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581354496,
      "name": "trace_probe_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
```

```json
{
  "name": "trace_probe_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581689184,
      "name": "trace_probe_append",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1017",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581689184,
      "name": "trace_probe_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
```

```json
{
  "name": "trace_probe_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581833808,
      "name": "trace_probe_append",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1498",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe",
        "kernel/trace/trace_fprobe.c:append_trace_fprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833808,
      "name": "trace_probe_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
```

```json
{
  "name": "trace_probe_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956528,
      "name": "trace_probe_append",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1735",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe",
        "kernel/trace/trace_fprobe.c:append_trace_fprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956528,
      "name": "trace_probe_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
```

```json
{
  "name": "trace_probe_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492088040,
      "name": "trace_probe_append",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:955",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492088040,
      "name": "trace_probe_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
```

```json
{
  "name": "trace_probe_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225988196,
      "name": "trace_probe_append",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:955",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225988196,
      "name": "trace_probe_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
```

```json
{
  "name": "trace_probe_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285283360,
      "name": "trace_probe_append",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:955",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285283360,
      "name": "trace_probe_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
```

```json
{
  "name": "trace_probe_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580745120,
      "name": "trace_probe_append",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:955",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580745120,
      "name": "trace_probe_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
```

```json
{
  "name": "trace_probe_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580691312,
      "name": "trace_probe_append",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:955",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580691312,
      "name": "trace_probe_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
```

```json
{
  "name": "trace_probe_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580736368,
      "name": "trace_probe_append",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:955",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580736368,
      "name": "trace_probe_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
```

```json
{
  "name": "trace_probe_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580794320,
      "name": "trace_probe_append",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:955",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580794320,
      "name": "trace_probe_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
```
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
int trace_probe_append(struct trace_probe * tp, struct trace_probe * to)
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

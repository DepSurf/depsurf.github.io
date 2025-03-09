# Function: <code>trace_probe_create</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int trace_probe_create(const char * raw_command, int (*)(int, const char * *) createfn)
```

```json
{
  "name": "trace_probe_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580892944,
      "name": "trace_probe_create",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1138",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kprobe_event_delete",
        "kernel/trace/trace_kprobe.c:trace_kprobe_run_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580892944,
      "name": "trace_probe_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int trace_probe_create(const char * raw_command, int (*)(int, const char * *) createfn)
```

```json
{
  "name": "trace_probe_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581094496,
      "name": "trace_probe_create",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1195",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:eprobe_dyn_event_create",
        "kernel/trace/trace_kprobe.c:kprobe_event_delete",
        "kernel/trace/trace_kprobe.c:trace_kprobe_run_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581094496,
      "name": "trace_probe_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int trace_probe_create(const char * raw_command, int (*)(int, const char * *) createfn)
```

```json
{
  "name": "trace_probe_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581356368,
      "name": "trace_probe_create",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1201",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:eprobe_dyn_event_create",
        "kernel/trace/trace_kprobe.c:kprobe_event_delete",
        "kernel/trace/trace_kprobe.c:trace_kprobe_run_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356368,
      "name": "trace_probe_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int trace_probe_create(const char * raw_command, int (*)(int, const char * *) createfn)
```

```json
{
  "name": "trace_probe_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581691216,
      "name": "trace_probe_create",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1224",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:eprobe_dyn_event_create",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:kprobe_event_delete",
        "kernel/trace/trace_kprobe.c:trace_kprobe_run_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581691216,
      "name": "trace_probe_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int trace_probe_create(const char * raw_command, int (*)(int, const char * *) createfn)
```

```json
{
  "name": "trace_probe_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581835840,
      "name": "trace_probe_create",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1705",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:eprobe_dyn_event_create",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:kprobe_event_delete",
        "kernel/trace/trace_kprobe.c:trace_kprobe_run_command",
        "kernel/trace/trace_fprobe.c:trace_fprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835840,
      "name": "trace_probe_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int trace_probe_create(const char * raw_command, int (*)(int, const char * *) createfn)
```

```json
{
  "name": "trace_probe_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958608,
      "name": "trace_probe_create",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1942",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:eprobe_dyn_event_create",
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:kprobe_event_delete",
        "kernel/trace/trace_kprobe.c:trace_kprobe_run_command",
        "kernel/trace/trace_fprobe.c:trace_fprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958608,
      "name": "trace_probe_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int trace_probe_create(const char * raw_command, int (*)(int, const char * *) createfn)
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

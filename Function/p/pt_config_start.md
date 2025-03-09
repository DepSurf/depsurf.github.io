# Function: <code>pt_config_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pt_config_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578927360,
      "name": "pt_config_start",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:274",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_stop",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578927360,
      "name": "pt_config_start.constprop.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pt_config_start(struct perf_event * event)
```

```json
{
  "name": "pt_config_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578937912,
      "name": "pt_config_start",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:398",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_config"
      ],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578936656,
      "name": "pt_config_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void pt_config_start(struct perf_event * event)
```

```json
{
  "name": "pt_config_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578939096,
      "name": "pt_config_start",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:398",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_config"
      ],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578937840,
      "name": "pt_config_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void pt_config_start(struct perf_event * event)
```

```json
{
  "name": "pt_config_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578942672,
      "name": "pt_config_start",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:398",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578942672,
      "name": "pt_config_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void pt_config_start(struct perf_event * event)
```

```json
{
  "name": "pt_config_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578954320,
      "name": "pt_config_start",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:398",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578954320,
      "name": "pt_config_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void pt_config_start(struct perf_event * event)
```

```json
{
  "name": "pt_config_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578964576,
      "name": "pt_config_start",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:416",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578964576,
      "name": "pt_config_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
void pt_config_start(struct perf_event * event)
```

```json
{
  "name": "pt_config_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578981984,
      "name": "pt_config_start",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:416",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578981984,
      "name": "pt_config_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
void pt_config_start(struct perf_event * event)
```

```json
{
  "name": "pt_config_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578981296,
      "name": "pt_config_start",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:416",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578981296,
      "name": "pt_config_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pt_config_start",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579008779,
      "name": "pt_config_start",
      "external": false,
      "loc": "arch/x86/events/intel/pt.c:416",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_event_snapshot_aux",
        "arch/x86/events/intel/pt.c:pt_event_start",
        "arch/x86/events/intel/pt.c:intel_pt_interrupt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void pt_config_start(struct perf_event * event)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void pt_config_start(struct perf_event * event)
```
</details>
</li>
</ul>

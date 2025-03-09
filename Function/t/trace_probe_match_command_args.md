# Function: <code>trace_probe_match_command_args</code>

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
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
```

```json
{
  "name": "trace_probe_match_command_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580777616,
      "name": "trace_probe_match_command_args",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1120",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_match",
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580777616,
      "name": "trace_probe_match_command_args",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
```

```json
{
  "name": "trace_probe_match_command_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580894784,
      "name": "trace_probe_match_command_args",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1120",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_match",
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580894784,
      "name": "trace_probe_match_command_args",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
```

```json
{
  "name": "trace_probe_match_command_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889072,
      "name": "trace_probe_match_command_args",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1120",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_match",
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889072,
      "name": "trace_probe_match_command_args",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
```

```json
{
  "name": "trace_probe_match_command_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580892784,
      "name": "trace_probe_match_command_args",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1120",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_match",
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580892784,
      "name": "trace_probe_match_command_args",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
```

```json
{
  "name": "trace_probe_match_command_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581094336,
      "name": "trace_probe_match_command_args",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1177",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:eprobe_dyn_event_match",
        "kernel/trace/trace_kprobe.c:trace_kprobe_match",
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581094336,
      "name": "trace_probe_match_command_args",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
```

```json
{
  "name": "trace_probe_match_command_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581356176,
      "name": "trace_probe_match_command_args",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1183",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:eprobe_dyn_event_match",
        "kernel/trace/trace_kprobe.c:trace_kprobe_match",
        "kernel/trace/trace_uprobe.c:trace_uprobe_match_command_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356176,
      "name": "trace_probe_match_command_args",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
```

```json
{
  "name": "trace_probe_match_command_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581691008,
      "name": "trace_probe_match_command_args",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1206",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:eprobe_dyn_event_match",
        "kernel/trace/trace_kprobe.c:trace_kprobe_match",
        "kernel/trace/trace_uprobe.c:trace_uprobe_match_command_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581691008,
      "name": "trace_probe_match_command_args",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
```

```json
{
  "name": "trace_probe_match_command_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581835632,
      "name": "trace_probe_match_command_args",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1687",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:eprobe_dyn_event_match",
        "kernel/trace/trace_kprobe.c:trace_kprobe_match",
        "kernel/trace/trace_uprobe.c:trace_uprobe_match_command_head",
        "kernel/trace/trace_fprobe.c:trace_fprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835632,
      "name": "trace_probe_match_command_args",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
```

```json
{
  "name": "trace_probe_match_command_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581958400,
      "name": "trace_probe_match_command_args",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1924",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:eprobe_dyn_event_match",
        "kernel/trace/trace_kprobe.c:trace_kprobe_match",
        "kernel/trace/trace_uprobe.c:trace_uprobe_match_command_head",
        "kernel/trace/trace_fprobe.c:trace_fprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581958400,
      "name": "trace_probe_match_command_args",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
```

```json
{
  "name": "trace_probe_match_command_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492089392,
      "name": "trace_probe_match_command_args",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1120",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_match",
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492089392,
      "name": "trace_probe_match_command_args",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
```

```json
{
  "name": "trace_probe_match_command_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225989404,
      "name": "trace_probe_match_command_args",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1120",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_match",
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225989404,
      "name": "trace_probe_match_command_args",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
```

```json
{
  "name": "trace_probe_match_command_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285285664,
      "name": "trace_probe_match_command_args",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1120",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_match",
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285285664,
      "name": "trace_probe_match_command_args",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
```

```json
{
  "name": "trace_probe_match_command_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580746416,
      "name": "trace_probe_match_command_args",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1120",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_match",
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580746416,
      "name": "trace_probe_match_command_args",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
```

```json
{
  "name": "trace_probe_match_command_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692608,
      "name": "trace_probe_match_command_args",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1120",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_match",
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692608,
      "name": "trace_probe_match_command_args",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
```

```json
{
  "name": "trace_probe_match_command_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580737664,
      "name": "trace_probe_match_command_args",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1120",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_match",
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580737664,
      "name": "trace_probe_match_command_args",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
```

```json
{
  "name": "trace_probe_match_command_args",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580795616,
      "name": "trace_probe_match_command_args",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:1120",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_match",
        "kernel/trace/trace_uprobe.c:trace_uprobe_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580795616,
      "name": "trace_probe_match_command_args",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
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
bool trace_probe_match_command_args(struct trace_probe * tp, int argc, const char * * argv)
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

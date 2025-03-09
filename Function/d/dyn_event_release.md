# Function: <code>dyn_event_release</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int dyn_event_release(int argc, char * * argv, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580657072,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:34",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580657072,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int dyn_event_release(int argc, char * * argv, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580718656,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:34",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580718656,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int dyn_event_release(int argc, char * * argv, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580767024,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:34",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767024,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int dyn_event_release(int argc, char * * argv, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580883360,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:34",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580883360,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int dyn_event_release(int argc, char * * argv, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580877776,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:34",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580877776,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int dyn_event_release(const char * raw_command, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580881664,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:34",
      "file": "kernel/trace/trace_dynevent.c",
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
      "addr": 18446744071580881664,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
int dyn_event_release(const char * raw_command, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581082784,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:72",
      "file": "kernel/trace/trace_dynevent.c",
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
      "addr": 18446744071581082784,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
int dyn_event_release(const char * raw_command, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581344368,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:72",
      "file": "kernel/trace/trace_dynevent.c",
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
      "addr": 18446744071581344368,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
int dyn_event_release(const char * raw_command, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581678144,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:72",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:kprobe_event_delete",
        "kernel/trace/trace_kprobe.c:trace_kprobe_run_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581678144,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
int dyn_event_release(const char * raw_command, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581819664,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:72",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:kprobe_event_delete",
        "kernel/trace/trace_kprobe.c:trace_kprobe_run_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581819664,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
int dyn_event_release(const char * raw_command, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581941280,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:72",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:init_kprobe_trace",
        "kernel/trace/trace_kprobe.c:kprobe_event_delete",
        "kernel/trace/trace_kprobe.c:trace_kprobe_run_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581941280,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
int dyn_event_release(int argc, char * * argv, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492078384,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:34",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492078384,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int dyn_event_release(int argc, char * * argv, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225978704,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:34",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225978704,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int dyn_event_release(int argc, char * * argv, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285265312,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:34",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285265312,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int dyn_event_release(int argc, char * * argv, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580735824,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:34",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580735824,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int dyn_event_release(int argc, char * * argv, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580682016,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:34",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580682016,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int dyn_event_release(int argc, char * * argv, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580727072,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:34",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580727072,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int dyn_event_release(int argc, char * * argv, struct dyn_event_operations * type)
```

```json
{
  "name": "dyn_event_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580785024,
      "name": "dyn_event_release",
      "external": true,
      "loc": "kernel/trace/trace_dynevent.c:34",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580785024,
      "name": "dyn_event_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int dyn_event_release(int argc, char * * argv, struct dyn_event_operations * type)
```
</details>
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
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char * raw_command</code>
</li>
<li>
<b>Param removed. </b>
<code>int argc</code>
</li>
<li>
<b>Param removed. </b>
<code>char * * argv</code>
</li>
<li>
<b>Param reordered. </b>
<code>argc, argv, type</code> ➡️ <code>raw_command, type</code>
</li>
</ul>
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
int dyn_event_release(int argc, char * * argv, struct dyn_event_operations * type)
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

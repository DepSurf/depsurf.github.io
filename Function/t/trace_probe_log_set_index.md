# Function: <code>trace_probe_log_set_index</code>

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
void trace_probe_log_set_index(int index)
```

```json
{
  "name": "trace_probe_log_set_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580725552,
      "name": "trace_probe_log_set_index",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:158",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580725552,
      "name": "trace_probe_log_set_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
void trace_probe_log_set_index(int index)
```

```json
{
  "name": "trace_probe_log_set_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580774464,
      "name": "trace_probe_log_set_index",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:158",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774464,
      "name": "trace_probe_log_set_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
void trace_probe_log_set_index(int index)
```

```json
{
  "name": "trace_probe_log_set_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580891488,
      "name": "trace_probe_log_set_index",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:158",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580891488,
      "name": "trace_probe_log_set_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
void trace_probe_log_set_index(int index)
```

```json
{
  "name": "trace_probe_log_set_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580885776,
      "name": "trace_probe_log_set_index",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:158",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580885776,
      "name": "trace_probe_log_set_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
void trace_probe_log_set_index(int index)
```

```json
{
  "name": "trace_probe_log_set_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889504,
      "name": "trace_probe_log_set_index",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:158",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889504,
      "name": "trace_probe_log_set_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
void trace_probe_log_set_index(int index)
```

```json
{
  "name": "trace_probe_log_set_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090880,
      "name": "trace_probe_log_set_index",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:158",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090880,
      "name": "trace_probe_log_set_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
void trace_probe_log_set_index(int index)
```

```json
{
  "name": "trace_probe_log_set_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581348560,
      "name": "trace_probe_log_set_index",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:158",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581348560,
      "name": "trace_probe_log_set_index",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void trace_probe_log_set_index(int index)
```

```json
{
  "name": "trace_probe_log_set_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581682896,
      "name": "trace_probe_log_set_index",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:165",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581682896,
      "name": "trace_probe_log_set_index",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_probe_log_set_index(int index)
```

```json
{
  "name": "trace_probe_log_set_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581832315,
      "name": "trace_probe_log_set_index",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:169",
      "file": "kernel/trace/trace_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_probe.c:traceprobe_expand_meta_args",
        "kernel/trace/trace_probe.c:traceprobe_expand_meta_args"
      ],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "kernel/trace/trace_fprobe.c:register_trace_fprobe",
        "kernel/trace/trace_fprobe.c:append_trace_fprobe",
        "kernel/trace/trace_fprobe.c:append_trace_fprobe",
        "kernel/trace/trace_fprobe.c:append_trace_fprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581825232,
      "name": "trace_probe_log_set_index",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void trace_probe_log_set_index(int index)
```

```json
{
  "name": "trace_probe_log_set_index",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581954990,
      "name": "trace_probe_log_set_index",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:170",
      "file": "kernel/trace/trace_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_probe.c:traceprobe_expand_meta_args",
        "kernel/trace/trace_probe.c:traceprobe_expand_meta_args"
      ],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe",
        "kernel/trace/trace_uprobe.c:register_trace_uprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe",
        "kernel/trace/trace_uprobe.c:append_trace_uprobe",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "kernel/trace/trace_fprobe.c:register_trace_fprobe",
        "kernel/trace/trace_fprobe.c:append_trace_fprobe",
        "kernel/trace/trace_fprobe.c:append_trace_fprobe",
        "kernel/trace/trace_fprobe.c:append_trace_fprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946448,
      "name": "trace_probe_log_set_index",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void trace_probe_log_set_index(int index)
```

```json
{
  "name": "trace_probe_log_set_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492085984,
      "name": "trace_probe_log_set_index",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:158",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492085984,
      "name": "trace_probe_log_set_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
void trace_probe_log_set_index(int index)
```

```json
{
  "name": "trace_probe_log_set_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225986192,
      "name": "trace_probe_log_set_index",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:158",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225986192,
      "name": "trace_probe_log_set_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void trace_probe_log_set_index(int index)
```

```json
{
  "name": "trace_probe_log_set_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285279776,
      "name": "trace_probe_log_set_index",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:158",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285279776,
      "name": "trace_probe_log_set_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void trace_probe_log_set_index(int index)
```

```json
{
  "name": "trace_probe_log_set_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580743264,
      "name": "trace_probe_log_set_index",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:158",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580743264,
      "name": "trace_probe_log_set_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
void trace_probe_log_set_index(int index)
```

```json
{
  "name": "trace_probe_log_set_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580689456,
      "name": "trace_probe_log_set_index",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:158",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580689456,
      "name": "trace_probe_log_set_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
void trace_probe_log_set_index(int index)
```

```json
{
  "name": "trace_probe_log_set_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580734512,
      "name": "trace_probe_log_set_index",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:158",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580734512,
      "name": "trace_probe_log_set_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
void trace_probe_log_set_index(int index)
```

```json
{
  "name": "trace_probe_log_set_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580792464,
      "name": "trace_probe_log_set_index",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:158",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580792464,
      "name": "trace_probe_log_set_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
void trace_probe_log_set_index(int index)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void trace_probe_log_set_index(int index)
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

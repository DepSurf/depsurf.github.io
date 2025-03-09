# Function: <code>__trace_probe_log_err</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __trace_probe_log_err(int offset, int err_type)
```

```json
{
  "name": "__trace_probe_log_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580726559,
      "name": "__trace_probe_log_err",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:163",
      "file": "kernel/trace/trace_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name"
      ],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
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
      "addr": 18446744071580721504,
      "name": "__trace_probe_log_err.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071580725568,
      "name": "__trace_probe_log_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __trace_probe_log_err(int offset, int err_type)
```

```json
{
  "name": "__trace_probe_log_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580775456,
      "name": "__trace_probe_log_err",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:163",
      "file": "kernel/trace/trace_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name"
      ],
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
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
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
      "addr": 18446744071580770080,
      "name": "__trace_probe_log_err.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071580774480,
      "name": "__trace_probe_log_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __trace_probe_log_err(int offset, int err_type)
```

```json
{
  "name": "__trace_probe_log_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580892481,
      "name": "__trace_probe_log_err",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:163",
      "file": "kernel/trace/trace_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:__parse_imm_string",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name"
      ],
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
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:__parse_imm_string",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
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
      "addr": 18446744071580886976,
      "name": "__trace_probe_log_err.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071580891504,
      "name": "__trace_probe_log_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __trace_probe_log_err(int offset, int err_type)
```

```json
{
  "name": "__trace_probe_log_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580886769,
      "name": "__trace_probe_log_err",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:163",
      "file": "kernel/trace/trace_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:__parse_imm_string",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name"
      ],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:trace_kprobe_create",
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
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:__parse_imm_string",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
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
      "addr": 18446744071580881264,
      "name": "__trace_probe_log_err.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071580885792,
      "name": "__trace_probe_log_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __trace_probe_log_err(int offset, int err_type)
```

```json
{
  "name": "__trace_probe_log_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580890499,
      "name": "__trace_probe_log_err",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:163",
      "file": "kernel/trace/trace_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name"
      ],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
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
      "addr": 18446744071580885152,
      "name": "__trace_probe_log_err.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071580889520,
      "name": "__trace_probe_log_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __trace_probe_log_err(int offset, int err_type)
```

```json
{
  "name": "__trace_probe_log_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581091905,
      "name": "__trace_probe_log_err",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:163",
      "file": "kernel/trace/trace_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name"
      ],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
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
      "addr": 18446744071581086352,
      "name": "__trace_probe_log_err.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071581090896,
      "name": "__trace_probe_log_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __trace_probe_log_err(int offset, int err_type)
```

```json
{
  "name": "__trace_probe_log_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581348576,
      "name": "__trace_probe_log_err",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:163",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
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
      "addr": 18446744071581348576,
      "name": "__trace_probe_log_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void __trace_probe_log_err(int offset, int err_type)
```

```json
{
  "name": "__trace_probe_log_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581682928,
      "name": "__trace_probe_log_err",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:170",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:trace_eprobe_parse_filter",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
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
      "addr": 18446744071581682928,
      "name": "__trace_probe_log_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void __trace_probe_log_err(int offset, int err_type)
```

```json
{
  "name": "__trace_probe_log_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581825264,
      "name": "__trace_probe_log_err",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:174",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:trace_eprobe_parse_filter",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_probe.c:traceprobe_expand_meta_args",
        "kernel/trace/trace_probe.c:traceprobe_expand_meta_args",
        "kernel/trace/trace_probe.c:traceprobe_expand_meta_args",
        "kernel/trace/trace_probe.c:traceprobe_expand_meta_args",
        "kernel/trace/trace_probe.c:traceprobe_expand_meta_args",
        "kernel/trace/trace_probe.c:sprint_nth_btf_arg",
        "kernel/trace/trace_probe.c:sprint_nth_btf_arg",
        "kernel/trace/trace_probe.c:sprint_nth_btf_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
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
      "addr": 18446744071581825264,
      "name": "__trace_probe_log_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
void __trace_probe_log_err(int offset, int err_type)
```

```json
{
  "name": "__trace_probe_log_err",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581946480,
      "name": "__trace_probe_log_err",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:175",
      "file": "kernel/trace/trace_probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:__trace_eprobe_create",
        "kernel/trace/trace_eprobe.c:trace_eprobe_parse_filter",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:__trace_kprobe_create",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_kprobe.c:append_trace_kprobe",
        "kernel/trace/trace_probe.c:traceprobe_expand_meta_args",
        "kernel/trace/trace_probe.c:traceprobe_expand_meta_args",
        "kernel/trace/trace_probe.c:traceprobe_expand_meta_args",
        "kernel/trace/trace_probe.c:traceprobe_expand_meta_args",
        "kernel/trace/trace_probe.c:traceprobe_expand_meta_args",
        "kernel/trace/trace_probe.c:sprint_nth_btf_arg",
        "kernel/trace/trace_probe.c:sprint_nth_btf_arg",
        "kernel/trace/trace_probe.c:sprint_nth_btf_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:parse_btf_arg",
        "kernel/trace/trace_probe.c:parse_btf_arg",
        "kernel/trace/trace_probe.c:parse_btf_arg",
        "kernel/trace/trace_probe.c:parse_btf_arg",
        "kernel/trace/trace_probe.c:parse_btf_arg",
        "kernel/trace/trace_probe.c:parse_btf_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:__trace_uprobe_create",
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
      "addr": 18446744071581946480,
      "name": "__trace_probe_log_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void __trace_probe_log_err(int offset, int err_type)
```

```json
{
  "name": "__trace_probe_log_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492087044,
      "name": "__trace_probe_log_err",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:163",
      "file": "kernel/trace/trace_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name"
      ],
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
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
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
      "addr": 18446603336492081896,
      "name": "__trace_probe_log_err.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446603336492086000,
      "name": "__trace_probe_log_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void __trace_probe_log_err(int offset, int err_type)
```

```json
{
  "name": "__trace_probe_log_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225987256,
      "name": "__trace_probe_log_err",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:163",
      "file": "kernel/trace/trace_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name"
      ],
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
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
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
      "addr": 3225981864,
      "name": "__trace_probe_log_err.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 3225986220,
      "name": "__trace_probe_log_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void __trace_probe_log_err(int offset, int err_type)
```

```json
{
  "name": "__trace_probe_log_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285281376,
      "name": "__trace_probe_log_err",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:163",
      "file": "kernel/trace/trace_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name"
      ],
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
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
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
      "addr": 13835058055285272128,
      "name": "__trace_probe_log_err.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    },
    {
      "addr": 13835058055285279808,
      "name": "__trace_probe_log_err",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __trace_probe_log_err(int offset, int err_type)
```

```json
{
  "name": "__trace_probe_log_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580744256,
      "name": "__trace_probe_log_err",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:163",
      "file": "kernel/trace/trace_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name"
      ],
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
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
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
      "addr": 18446744071580738880,
      "name": "__trace_probe_log_err.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071580743280,
      "name": "__trace_probe_log_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __trace_probe_log_err(int offset, int err_type)
```

```json
{
  "name": "__trace_probe_log_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580690448,
      "name": "__trace_probe_log_err",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:163",
      "file": "kernel/trace/trace_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name"
      ],
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
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
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
      "addr": 18446744071580685072,
      "name": "__trace_probe_log_err.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071580689472,
      "name": "__trace_probe_log_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __trace_probe_log_err(int offset, int err_type)
```

```json
{
  "name": "__trace_probe_log_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580735504,
      "name": "__trace_probe_log_err",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:163",
      "file": "kernel/trace/trace_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name"
      ],
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
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
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
      "addr": 18446744071580730128,
      "name": "__trace_probe_log_err.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071580734528,
      "name": "__trace_probe_log_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __trace_probe_log_err(int offset, int err_type)
```

```json
{
  "name": "__trace_probe_log_err",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580793456,
      "name": "__trace_probe_log_err",
      "external": true,
      "loc": "kernel/trace/trace_probe.c:163",
      "file": "kernel/trace/trace_probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name"
      ],
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
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_kprobe.c:register_trace_kprobe",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_probe.c:traceprobe_parse_event_name",
        "kernel/trace/trace_uprobe.c:trace_uprobe_create",
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
      "addr": 18446744071580788080,
      "name": "__trace_probe_log_err.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071580792480,
      "name": "__trace_probe_log_err",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __trace_probe_log_err(int offset, int err_type)
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
void __trace_probe_log_err(int offset, int err_type)
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

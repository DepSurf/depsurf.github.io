# Function: <code>clear_ftrace_pids</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580213007,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5341",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_pid_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580253772,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5390",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_pid_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array * tr)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580242144,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6161",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580242144,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array * tr)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580293504,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6460",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293504,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array * tr)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580354624,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6446",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580354624,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array * tr)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580410592,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6385",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580410592,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void clear_ftrace_pids(struct trace_array * tr)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580464000,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6439",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580464000,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void clear_ftrace_pids(struct trace_array * tr)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580512944,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6472",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580512944,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void clear_ftrace_pids(struct trace_array * tr, int type)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580600368,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6980",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580600368,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
void clear_ftrace_pids(struct trace_array * tr, int type)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580590400,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:7150",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580590400,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
void clear_ftrace_pids(struct trace_array * tr, int type)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580593408,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:7155",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580593408,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
void clear_ftrace_pids(struct trace_array * tr, int type)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580764576,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:7156",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764576,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
void clear_ftrace_pids(struct trace_array * tr, int type)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580981824,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:7596",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981824,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
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
void clear_ftrace_pids(struct trace_array * tr, int type)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581281056,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:7710",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581281056,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
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
void clear_ftrace_pids(struct trace_array * tr, int type)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581376640,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:7525",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581376640,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
void clear_ftrace_pids(struct trace_array * tr, int type)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581483504,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:7525",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_no_pid_open",
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581483504,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
void clear_ftrace_pids(struct trace_array * tr)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491792088,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6472",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491792088,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void clear_ftrace_pids(struct trace_array * tr)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225742232,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6472",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225742232,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void clear_ftrace_pids(struct trace_array * tr)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284844080,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6472",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284844080,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array * tr)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272106540,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6472",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272106540,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array * tr)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580481744,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6472",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580481744,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void clear_ftrace_pids(struct trace_array * tr)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580428816,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6472",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580428816,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void clear_ftrace_pids(struct trace_array * tr)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580472992,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6472",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580472992,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void clear_ftrace_pids(struct trace_array * tr)
```

```json
{
  "name": "clear_ftrace_pids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580529200,
      "name": "clear_ftrace_pids",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6472",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_pid_open",
        "kernel/trace/ftrace.c:ftrace_clear_pids"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580529200,
      "name": "clear_ftrace_pids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void clear_ftrace_pids(struct trace_array * tr)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int type</code>
</li>
</ul>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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

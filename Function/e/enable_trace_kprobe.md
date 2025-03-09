# Function: <code>enable_trace_kprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580322114,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:350",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:kprobe_register"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580377042,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:356",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:kprobe_register"
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
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580424802,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:371",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:kprobe_register"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580436498,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:377",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:kprobe_register"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580493026,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:377",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:kprobe_register"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int enable_trace_kprobe(struct trace_kprobe * tk, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580576416,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:401",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:kprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576416,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int enable_trace_kprobe(struct trace_kprobe * tk, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580634880,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:303",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:kprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580634880,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580699025,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:299",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:kprobe_register"
      ],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:kprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580695744,
      "name": "enable_trace_kprobe.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580741680,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:351",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580741680,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857056,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:350",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:kprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857056,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580849200,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:352",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:kprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580849200,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580852928,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:352",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:kprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852928,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581053184,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:348",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:kprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581053184,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581311824,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:347",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:kprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581311824,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581640560,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:349",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:kprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581640560,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581781792,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:349",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:kprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781792,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581903120,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:349",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:kprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581903120,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492054688,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:351",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492054688,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225954528,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:351",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225954528,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285231536,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:351",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285231536,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580710480,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:351",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580710480,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580656688,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:351",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580656688,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580701728,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:351",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701728,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
```

```json
{
  "name": "enable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580759680,
      "name": "enable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:351",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580759680,
      "name": "enable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int enable_trace_kprobe(struct trace_kprobe * tk, struct trace_event_file * file)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int enable_trace_kprobe(struct trace_kprobe * tk, struct trace_event_file * file)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
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
int enable_trace_kprobe(struct trace_event_call * call, struct trace_event_file * file)
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

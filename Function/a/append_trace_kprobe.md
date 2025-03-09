# Function: <code>append_trace_kprobe</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580744149,
      "name": "append_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:588",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int append_trace_kprobe(struct trace_kprobe * tk, struct trace_kprobe * to)
```

```json
{
  "name": "append_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "append_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:587",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866880,
      "name": "append_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    },
    {
      "addr": 18446744071580870657,
      "name": "append_trace_kprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int append_trace_kprobe(struct trace_kprobe * tk, struct trace_kprobe * to)
```

```json
{
  "name": "append_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "append_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:589",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580859056,
      "name": "append_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    },
    {
      "addr": 18446744071591322659,
      "name": "append_trace_kprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int append_trace_kprobe(struct trace_kprobe * tk, struct trace_kprobe * to)
```

```json
{
  "name": "append_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "append_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:589",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580855504,
      "name": "append_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
    },
    {
      "addr": 18446744071591264523,
      "name": "append_trace_kprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int append_trace_kprobe(struct trace_kprobe * tk, struct trace_kprobe * to)
```

```json
{
  "name": "append_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "append_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:589",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055696,
      "name": "append_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    },
    {
      "addr": 18446744071592178380,
      "name": "append_trace_kprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int append_trace_kprobe(struct trace_kprobe * tk, struct trace_kprobe * to)
```

```json
{
  "name": "append_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "append_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:585",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581314656,
      "name": "append_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
    },
    {
      "addr": 18446744071593952089,
      "name": "append_trace_kprobe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int append_trace_kprobe(struct trace_kprobe * tk, struct trace_kprobe * to)
```

```json
{
  "name": "append_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581644064,
      "name": "append_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:587",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581644064,
      "name": "append_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 614
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
int append_trace_kprobe(struct trace_kprobe * tk, struct trace_kprobe * to)
```

```json
{
  "name": "append_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581785520,
      "name": "append_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:587",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785520,
      "name": "append_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
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
int append_trace_kprobe(struct trace_kprobe * tk, struct trace_kprobe * to)
```

```json
{
  "name": "append_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581906864,
      "name": "append_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:587",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581906864,
      "name": "append_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492057112,
      "name": "append_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:588",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225959576,
      "name": "append_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:588",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285235520,
      "name": "append_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:588",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580712949,
      "name": "append_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:588",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580659157,
      "name": "append_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:588",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580704197,
      "name": "append_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:588",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "append_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580762149,
      "name": "append_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:588",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:register_trace_kprobe"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int append_trace_kprobe(struct trace_kprobe * tk, struct trace_kprobe * to)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

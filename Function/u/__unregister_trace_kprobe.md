# Function: <code>__unregister_trace_kprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580320400,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:474",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:unregister_trace_kprobe"
      ],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:unregister_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580320400,
      "name": "__unregister_trace_kprobe.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580376640,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:478",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:unregister_trace_kprobe"
      ],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:unregister_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375248,
      "name": "__unregister_trace_kprobe.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580424400,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:493",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:unregister_trace_kprobe"
      ],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:unregister_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580422848,
      "name": "__unregister_trace_kprobe.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580436128,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:499",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:unregister_trace_kprobe"
      ],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:unregister_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580434240,
      "name": "__unregister_trace_kprobe.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580492656,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:499",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:unregister_trace_kprobe"
      ],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:unregister_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580490912,
      "name": "__unregister_trace_kprobe.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580578864,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:540",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:unregister_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580578864,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580633792,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:460",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:unregister_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580633792,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580693872,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:422",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe",
        "kernel/trace/trace_kprobe.c:unregister_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580693872,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580741120,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:519",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580741120,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856832,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:518",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856832,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580848976,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:520",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848976,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580852672,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:520",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852672,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581052928,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:516",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581052928,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581311536,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:514",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581311536,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581640224,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:516",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581640224,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581781456,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:516",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781456,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902784,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:516",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902784,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492054128,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:519",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492054128,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225954324,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:519",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225954324,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285230656,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:519",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285230656,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580709920,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:519",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580709920,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580656128,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:519",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580656128,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580701168,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:519",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701168,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```

```json
{
  "name": "__unregister_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580759120,
      "name": "__unregister_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:519",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580759120,
      "name": "__unregister_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
```
</details>
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
void __unregister_trace_kprobe(struct trace_kprobe * tk)
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

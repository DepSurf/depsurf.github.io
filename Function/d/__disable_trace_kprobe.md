# Function: <code>__disable_trace_kprobe</code>

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
void __disable_trace_kprobe(struct trace_probe * tp)
```

```json
{
  "name": "__disable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580741552,
      "name": "__disable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:331",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:enable_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580741552,
      "name": "__disable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void __disable_trace_kprobe(struct trace_probe * tp)
```

```json
{
  "name": "__disable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856944,
      "name": "__disable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:330",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:enable_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856944,
      "name": "__disable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void __disable_trace_kprobe(struct trace_probe * tp)
```

```json
{
  "name": "__disable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580849088,
      "name": "__disable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:332",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:enable_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580849088,
      "name": "__disable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void __disable_trace_kprobe(struct trace_probe * tp)
```

```json
{
  "name": "__disable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580852816,
      "name": "__disable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:332",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:enable_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852816,
      "name": "__disable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void __disable_trace_kprobe(struct trace_probe * tp)
```

```json
{
  "name": "__disable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581053072,
      "name": "__disable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:328",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:enable_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581053072,
      "name": "__disable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void __disable_trace_kprobe(struct trace_probe * tp)
```

```json
{
  "name": "__disable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581311680,
      "name": "__disable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:329",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:enable_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581311680,
      "name": "__disable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void __disable_trace_kprobe(struct trace_probe * tp)
```

```json
{
  "name": "__disable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581640400,
      "name": "__disable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:331",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:enable_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581640400,
      "name": "__disable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void __disable_trace_kprobe(struct trace_probe * tp)
```

```json
{
  "name": "__disable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581781632,
      "name": "__disable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:331",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:enable_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781632,
      "name": "__disable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void __disable_trace_kprobe(struct trace_probe * tp)
```

```json
{
  "name": "__disable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902960,
      "name": "__disable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:331",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:kprobe_register",
        "kernel/trace/trace_kprobe.c:enable_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902960,
      "name": "__disable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void __disable_trace_kprobe(struct trace_probe * tp)
```

```json
{
  "name": "__disable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492054576,
      "name": "__disable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:331",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:enable_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492054576,
      "name": "__disable_trace_kprobe",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __disable_trace_kprobe(struct trace_probe * tp)
```

```json
{
  "name": "__disable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225954432,
      "name": "__disable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:331",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:enable_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225954432,
      "name": "__disable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void __disable_trace_kprobe(struct trace_probe * tp)
```

```json
{
  "name": "__disable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285231360,
      "name": "__disable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:331",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:enable_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285231360,
      "name": "__disable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void __disable_trace_kprobe(struct trace_probe * tp)
```

```json
{
  "name": "__disable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580710352,
      "name": "__disable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:331",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:enable_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580710352,
      "name": "__disable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void __disable_trace_kprobe(struct trace_probe * tp)
```

```json
{
  "name": "__disable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580656560,
      "name": "__disable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:331",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:enable_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580656560,
      "name": "__disable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void __disable_trace_kprobe(struct trace_probe * tp)
```

```json
{
  "name": "__disable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580701600,
      "name": "__disable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:331",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:enable_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701600,
      "name": "__disable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void __disable_trace_kprobe(struct trace_probe * tp)
```

```json
{
  "name": "__disable_trace_kprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580759552,
      "name": "__disable_trace_kprobe",
      "external": false,
      "loc": "kernel/trace/trace_kprobe.c:331",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:disable_trace_kprobe",
        "kernel/trace/trace_kprobe.c:enable_trace_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580759552,
      "name": "__disable_trace_kprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void __disable_trace_kprobe(struct trace_probe * tp)
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
void __disable_trace_kprobe(struct trace_probe * tp)
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

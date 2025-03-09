# Function: <code>trace_hwlat_sample</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580341974,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:104",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
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
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580354686,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:105",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
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
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580408398,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:105",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580470319,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:105",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580526391,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:103",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580582686,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:103",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580629790,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:103",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void trace_hwlat_sample(struct hwlat_sample * sample)
```

```json
{
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580728496,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:104",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580728496,
      "name": "trace_hwlat_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void trace_hwlat_sample(struct hwlat_sample * sample)
```

```json
{
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580717824,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:104",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580717824,
      "name": "trace_hwlat_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void trace_hwlat_sample(struct hwlat_sample * sample)
```

```json
{
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580722944,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:104",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580722944,
      "name": "trace_hwlat_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void trace_hwlat_sample(struct hwlat_sample * sample)
```

```json
{
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580902512,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:130",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580902512,
      "name": "trace_hwlat_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void trace_hwlat_sample(struct hwlat_sample * sample)
```

```json
{
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581138544,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:130",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581138544,
      "name": "trace_hwlat_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void trace_hwlat_sample(struct hwlat_sample * sample)
```

```json
{
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581450352,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:130",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581450352,
      "name": "trace_hwlat_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void trace_hwlat_sample(struct hwlat_sample * sample)
```

```json
{
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581547408,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:130",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581547408,
      "name": "trace_hwlat_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void trace_hwlat_sample(struct hwlat_sample * sample)
```

```json
{
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581659632,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:130",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581659632,
      "name": "trace_hwlat_sample",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491933184,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:103",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
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
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225869204,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:103",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
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
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285032424,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:103",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272209268,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:103",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580598590,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:103",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
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
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580545064,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:103",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
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
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580589838,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:103",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
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
  "name": "trace_hwlat_sample",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580646734,
      "name": "trace_hwlat_sample",
      "external": false,
      "loc": "kernel/trace/trace_hwlat.c:103",
      "file": "kernel/trace/trace_hwlat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_hwlat.c:kthread_fn"
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
void trace_hwlat_sample(struct hwlat_sample * sample)
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

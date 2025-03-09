# Function: <code>array_map_alloc_check</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580694064,
      "name": "array_map_alloc_check",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:57",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580694064,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580766400,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:57",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580766400,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580850320,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:49",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580850320,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580901360,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:49",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580901360,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581051642,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:49",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check"
      ],
      "caller_func": [
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046448,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581057024,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:51",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581057024,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071872,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:51",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071872,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581299184,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:51",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581299184,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581596688,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:52",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581596688,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581977552,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:52",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977552,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582169088,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:52",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582169088,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582317776,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:52",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582317776,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492230256,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:49",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492230256,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226126068,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:49",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226126068,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285454736,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:49",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285454736,
      "name": "array_map_alloc_check",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272376744,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:49",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272376744,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580870160,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:49",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580870160,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816288,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:49",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816288,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580861408,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:49",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580861408,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int array_map_alloc_check(union bpf_attr * attr)
```

```json
{
  "name": "array_map_alloc_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919888,
      "name": "array_map_alloc_check",
      "external": true,
      "loc": "kernel/bpf/arraymap.c:49",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:fd_array_map_alloc_check",
        "kernel/bpf/reuseport_array.c:reuseport_array_alloc_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919888,
      "name": "array_map_alloc_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int array_map_alloc_check(union bpf_attr * attr)
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

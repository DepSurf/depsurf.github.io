# Function: <code>btf_int128_print</code>

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
void btf_int128_print(struct seq_file * m, void * data)
```

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580869024,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:1323",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_int_seq_show",
        "kernel/bpf/btf.c:btf_bitfield_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580869024,
      "name": "btf_int128_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void btf_int128_print(struct seq_file * m, void * data)
```

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919984,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:1323",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_int_seq_show",
        "kernel/bpf/btf.c:btf_bitfield_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919984,
      "name": "btf_int128_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581074655,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:1429",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_int_seq_show",
        "kernel/bpf/btf.c:btf_bitfield_seq_show"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void btf_int128_print(struct btf_show * show, void * data)
```

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581098272,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:2058",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_bitfield_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581098272,
      "name": "btf_int128_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
void btf_int128_print(struct btf_show * show, void * data)
```

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581117488,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:2060",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_bitfield_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581117488,
      "name": "btf_int128_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
void btf_int128_print(struct btf_show * show, void * data)
```

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581348784,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:2060",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_bitfield_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581348784,
      "name": "btf_int128_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
void btf_int128_print(struct btf_show * show, void * data)
```

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581661264,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:2189",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_bitfield_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581661264,
      "name": "btf_int128_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
void btf_int128_print(struct btf_show * show, void * data)
```

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582053856,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:2213",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_bitfield_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582053856,
      "name": "btf_int128_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
void btf_int128_print(struct btf_show * show, void * data)
```

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582248800,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:2243",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_bitfield_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582248800,
      "name": "btf_int128_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
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
void btf_int128_print(struct btf_show * show, void * data)
```

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582404464,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:2244",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_int_show",
        "kernel/bpf/btf.c:btf_bitfield_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582404464,
      "name": "btf_int128_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
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
void btf_int128_print(struct seq_file * m, void * data)
```

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492255280,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:1323",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_int_seq_show",
        "kernel/bpf/btf.c:btf_bitfield_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492255280,
      "name": "btf_int128_print",
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
void btf_int128_print(struct seq_file * m, void * data)
```

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226146496,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:1323",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_int_seq_show",
        "kernel/bpf/btf.c:btf_bitfield_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226146496,
      "name": "btf_int128_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void btf_int128_print(struct seq_file * m, void * data)
```

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285484512,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:1323",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_int_seq_show",
        "kernel/bpf/btf.c:btf_bitfield_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285484512,
      "name": "btf_int128_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void btf_int128_print(struct seq_file * m, void * data)
```

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272396168,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:1323",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_int_seq_show",
        "kernel/bpf/btf.c:btf_bitfield_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272396168,
      "name": "btf_int128_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void btf_int128_print(struct seq_file * m, void * data)
```

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580888784,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:1323",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_int_seq_show",
        "kernel/bpf/btf.c:btf_bitfield_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888784,
      "name": "btf_int128_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void btf_int128_print(struct seq_file * m, void * data)
```

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580834848,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:1323",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_int_seq_show",
        "kernel/bpf/btf.c:btf_bitfield_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580834848,
      "name": "btf_int128_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void btf_int128_print(struct seq_file * m, void * data)
```

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580880032,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:1323",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_int_seq_show",
        "kernel/bpf/btf.c:btf_bitfield_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580880032,
      "name": "btf_int128_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void btf_int128_print(struct seq_file * m, void * data)
```

```json
{
  "name": "btf_int128_print",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580938672,
      "name": "btf_int128_print",
      "external": false,
      "loc": "kernel/bpf/btf.c:1323",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_int_seq_show",
        "kernel/bpf/btf.c:btf_bitfield_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580938672,
      "name": "btf_int128_print",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void btf_int128_print(struct seq_file * m, void * data)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void btf_int128_print(struct seq_file * m, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void btf_int128_print(struct btf_show * show, void * data)
```
</details>
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

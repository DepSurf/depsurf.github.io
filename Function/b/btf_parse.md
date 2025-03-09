# Function: <code>btf_parse</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580715054,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:2146",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd"
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
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580796542,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:2797",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd"
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
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580884432,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:3287",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd"
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
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580935392,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:3286",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd"
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
struct btf * btf_parse(void * btf_data, u32 btf_data_size, u32 log_level, char * log_ubuf, u32 log_size)
```

```json
{
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581091216,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:3396",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091216,
      "name": "btf_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
struct btf * btf_parse(void * btf_data, u32 btf_data_size, u32 log_level, char * log_ubuf, u32 log_size)
```

```json
{
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581117968,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:4187",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581117968,
      "name": "btf_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 726
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
struct btf * btf_parse(void * btf_data, u32 btf_data_size, u32 log_level, char * log_ubuf, u32 log_size)
```

```json
{
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136896,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:4260",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136896,
      "name": "btf_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
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
struct btf * btf_parse(bpfptr_t btf_data, u32 btf_data_size, u32 log_level, char * log_ubuf, u32 log_size)
```

```json
{
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369696,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:4309",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369696,
      "name": "btf_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 758
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
struct btf * btf_parse(bpfptr_t btf_data, u32 btf_data_size, u32 log_level, char * log_ubuf, u32 log_size)
```

```json
{
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581685744,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:4856",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581685744,
      "name": "btf_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 828
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
struct btf * btf_parse(bpfptr_t btf_data, u32 btf_data_size, u32 log_level, char * log_ubuf, u32 log_size)
```

```json
{
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582099232,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:5395",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582099232,
      "name": "btf_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1076
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
struct btf * btf_parse(const union bpf_attr * attr, bpfptr_t uattr, u32 uattr_size)
```

```json
{
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582293376,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:5473",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582293376,
      "name": "btf_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1208
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
struct btf * btf_parse(const union bpf_attr * attr, bpfptr_t uattr, u32 uattr_size)
```

```json
{
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582450896,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:5481",
      "file": "kernel/bpf/btf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/btf.c:btf_new_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582450896,
      "name": "btf_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1302
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
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492274980,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:3286",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd"
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
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226163972,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:3286",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd"
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
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285506800,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:3286",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd"
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
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272410930,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:3286",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd"
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
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580904192,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:3286",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd"
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
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580850256,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:3286",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd"
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
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580895440,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:3286",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd"
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
  "name": "btf_parse",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580954080,
      "name": "btf_parse",
      "external": false,
      "loc": "kernel/bpf/btf.c:3286",
      "file": "kernel/bpf/btf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/btf.c:btf_new_fd"
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
struct btf * btf_parse(void * btf_data, u32 btf_data_size, u32 log_level, char * log_ubuf, u32 log_size)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void * btf_data</code> ➡️ <code>bpfptr_t btf_data</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const union bpf_attr * attr</code>
</li>
<li>
<b>Param added. </b>
<code>bpfptr_t uattr</code>
</li>
<li>
<b>Param added. </b>
<code>u32 uattr_size</code>
</li>
<li>
<b>Param removed. </b>
<code>bpfptr_t btf_data</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 btf_data_size</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 log_level</code>
</li>
<li>
<b>Param removed. </b>
<code>char * log_ubuf</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 log_size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

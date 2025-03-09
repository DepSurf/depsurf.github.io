# Function: <code>copy_sysctl_value</code>

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
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580907824,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1188",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907824,
      "name": "copy_sysctl_value",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580960976,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1207",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960976,
      "name": "copy_sysctl_value",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581124080,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1528",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581124080,
      "name": "copy_sysctl_value",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581157920,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1558",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581157920,
      "name": "copy_sysctl_value",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581172624,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1644",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172624,
      "name": "copy_sysctl_value",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581411696,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1674",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581411696,
      "name": "copy_sysctl_value",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581736864,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1806",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581736864,
      "name": "copy_sysctl_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582149568,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:2045",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582149568,
      "name": "copy_sysctl_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582347024,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:2063",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582347024,
      "name": "copy_sysctl_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582513728,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:2081",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582513728,
      "name": "copy_sysctl_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492305512,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1207",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492305512,
      "name": "copy_sysctl_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226192516,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1207",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226192516,
      "name": "copy_sysctl_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285543536,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1207",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285543536,
      "name": "copy_sysctl_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272436820,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1207",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272436820,
      "name": "copy_sysctl_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580929776,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1207",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929776,
      "name": "copy_sysctl_value",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580875840,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1207",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580875840,
      "name": "copy_sysctl_value",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580921024,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1207",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580921024,
      "name": "copy_sysctl_value",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
```

```json
{
  "name": "copy_sysctl_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580979936,
      "name": "copy_sysctl_value",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1207",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_new_value",
        "kernel/bpf/cgroup.c:bpf_sysctl_get_current_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580979936,
      "name": "copy_sysctl_value",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int copy_sysctl_value(char * dst, size_t dst_len, char * src, size_t src_len)
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

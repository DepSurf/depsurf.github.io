# Function: <code>__bpf_strtoull</code>

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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580836912,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:364",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580836912,
      "name": "__bpf_strtoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580887936,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:364",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580887936,
      "name": "__bpf_strtoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581026848,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:408",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581026848,
      "name": "__bpf_strtoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581033920,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:419",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033920,
      "name": "__bpf_strtoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581045504,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:427",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581045504,
      "name": "__bpf_strtoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581270128,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:441",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581270128,
      "name": "__bpf_strtoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581561680,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:455",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561680,
      "name": "__bpf_strtoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581933984,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:439",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581933984,
      "name": "__bpf_strtoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582117152,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:440",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582117152,
      "name": "__bpf_strtoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 526
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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582257488,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:446",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582257488,
      "name": "__bpf_strtoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 526
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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492213472,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:364",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492213472,
      "name": "__bpf_strtoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226110860,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:364",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226110860,
      "name": "__bpf_strtoull",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285435200,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:364",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285435200,
      "name": "__bpf_strtoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272362192,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:364",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272362192,
      "name": "__bpf_strtoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856736,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:364",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856736,
      "name": "__bpf_strtoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580802896,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:364",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580802896,
      "name": "__bpf_strtoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580847984,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:364",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580847984,
      "name": "__bpf_strtoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
```

```json
{
  "name": "__bpf_strtoull",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906272,
      "name": "__bpf_strtoull",
      "external": false,
      "loc": "kernel/bpf/helpers.c:364",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_strtoul",
        "kernel/bpf/helpers.c:bpf_strtol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906272,
      "name": "__bpf_strtoull",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
int __bpf_strtoull(const char * buf, size_t buf_len, u64 flags, long long unsigned int * res, bool * is_negative)
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

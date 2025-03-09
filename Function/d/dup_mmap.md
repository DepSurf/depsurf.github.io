# Function: <code>dup_mmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579367623,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:402",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process"
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
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579372831,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:412",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579391783,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:560",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579381123,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:595",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579405923,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:603",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579416531,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:425",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_mm"
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
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579456100,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:468",
      "file": "kernel/fork.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579465376,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:474",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579465376,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
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
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491680,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:483",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491680,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
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
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579521920,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:490",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579521920,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1203
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
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503328,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:475",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503328,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1355
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
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506800,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:479",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506800,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1330
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
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:494",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579579408,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1391
    },
    {
      "addr": 18446744071592098101,
      "name": "dup_mmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:585",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670080,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1418
    },
    {
      "addr": 18446744071593865297,
      "name": "dup_mmap.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:586",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579790272,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1526
    },
    {
      "addr": 18446744071595973269,
      "name": "dup_mmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:651",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837824,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1859
    },
    {
      "addr": 18446744071596490874,
      "name": "dup_mmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:631",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873408,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1953
    },
    {
      "addr": 18446744071597387598,
      "name": "dup_mmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490625424,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:483",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490625424,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1124
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
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224703572,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:483",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224703572,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1100
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
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283443040,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:483",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283443040,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1404
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
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271381968,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:483",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271381968,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
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
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579465344,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:483",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579465344,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
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
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579394304,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:483",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394304,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1237
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
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579465264,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:483",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579465264,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
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
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
```

```json
{
  "name": "dup_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497008,
      "name": "dup_mmap",
      "external": false,
      "loc": "kernel/fork.c:483",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497008,
      "name": "dup_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
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
int dup_mmap(struct mm_struct * mm, struct mm_struct * oldmm)
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

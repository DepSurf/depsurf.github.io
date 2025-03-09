# Function: <code>bsg_teardown_job</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583323383,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:35",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_job_put"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void bsg_teardown_job(struct kref * kref)
```

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583506352,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:35",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_softirq_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583506352,
      "name": "bsg_teardown_job",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void bsg_teardown_job(struct kref * kref)
```

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583720448,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:123",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_softirq_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583720448,
      "name": "bsg_teardown_job",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void bsg_teardown_job(struct kref * kref)
```

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583826992,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:128",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583826992,
      "name": "bsg_teardown_job",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void bsg_teardown_job(struct kref * kref)
```

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584017168,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:148",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017168,
      "name": "bsg_teardown_job",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void bsg_teardown_job(struct kref * kref)
```

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584120688,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:148",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584120688,
      "name": "bsg_teardown_job",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584520490,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:148",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584629354,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:148",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584657402,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:148",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585071210,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:149",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585796099,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:156",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586577395,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:156",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586835155,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:156",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587112371,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:156",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_complete"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495967104,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:148",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_job_put"
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
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229309396,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:148",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_job_put"
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
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290187720,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:148",
      "file": "block/bsg-lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg-lib.c:bsg_job_put"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void bsg_teardown_job(struct kref * kref)
```

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275069940,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:148",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275069940,
      "name": "bsg_teardown_job",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void bsg_teardown_job(struct kref * kref)
```

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584089424,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:148",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584089424,
      "name": "bsg_teardown_job",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void bsg_teardown_job(struct kref * kref)
```

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584025184,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:148",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025184,
      "name": "bsg_teardown_job",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void bsg_teardown_job(struct kref * kref)
```

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584073184,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:148",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584073184,
      "name": "bsg_teardown_job",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void bsg_teardown_job(struct kref * kref)
```

```json
{
  "name": "bsg_teardown_job",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584175760,
      "name": "bsg_teardown_job",
      "external": false,
      "loc": "block/bsg-lib.c:148",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584175760,
      "name": "bsg_teardown_job",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void bsg_teardown_job(struct kref * kref)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void bsg_teardown_job(struct kref * kref)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void bsg_teardown_job(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void bsg_teardown_job(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void bsg_teardown_job(struct kref * kref)
```
</details>
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

# Function: <code>__dm_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585800976,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:3223",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585800976,
      "name": "__dm_resume.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586197414,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2227",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586197232,
      "name": "__dm_resume.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586401910,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2288",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586401728,
      "name": "__dm_resume.part.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586505318,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2498",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586505136,
      "name": "__dm_resume.part.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586972319,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2473",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586972176,
      "name": "__dm_resume.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
int __dm_resume(struct mapped_device * md, struct dm_table * map)
```

```json
{
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587266000,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2662",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587266000,
      "name": "__dm_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int __dm_resume(struct mapped_device * md, struct dm_table * map)
```

```json
{
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587445920,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2685",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587445920,
      "name": "__dm_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int __dm_resume(struct mapped_device * md, struct dm_table * map)
```

```json
{
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587715728,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2716",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587715728,
      "name": "__dm_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int __dm_resume(struct mapped_device * md, struct dm_table * map)
```

```json
{
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587920000,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2721",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587920000,
      "name": "__dm_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int __dm_resume(struct mapped_device * md, struct dm_table * map)
```

```json
{
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588772080,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2763",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588772080,
      "name": "__dm_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int __dm_resume(struct mapped_device * md, struct dm_table * map)
```

```json
{
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588791696,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2610",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588791696,
      "name": "__dm_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588677042,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2629",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
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
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589368098,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2518",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
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
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590845540,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2699",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
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
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592538260,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2802",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
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
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592969284,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2842",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
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
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593719412,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2850",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __dm_resume(struct mapped_device * md, struct dm_table * map)
```

```json
{
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501153160,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2721",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501153160,
      "name": "__dm_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int __dm_resume(struct mapped_device * md, struct dm_table * map)
```

```json
{
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233666788,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2721",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233666788,
      "name": "__dm_resume",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __dm_resume(struct mapped_device * md, struct dm_table * map)
```

```json
{
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294665520,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2721",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294665520,
      "name": "__dm_resume",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __dm_resume(struct mapped_device * md, struct dm_table * map)
```

```json
{
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277864592,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2721",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277864592,
      "name": "__dm_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int __dm_resume(struct mapped_device * md, struct dm_table * map)
```

```json
{
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587550976,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2721",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587550976,
      "name": "__dm_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int __dm_resume(struct mapped_device * md, struct dm_table * map)
```

```json
{
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587319072,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2721",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587319072,
      "name": "__dm_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int __dm_resume(struct mapped_device * md, struct dm_table * map)
```

```json
{
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587876144,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2721",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587876144,
      "name": "__dm_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int __dm_resume(struct mapped_device * md, struct dm_table * map)
```

```json
{
  "name": "__dm_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587991696,
      "name": "__dm_resume",
      "external": false,
      "loc": "drivers/md/dm.c:2721",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_internal_resume",
        "drivers/md/dm.c:dm_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587991696,
      "name": "__dm_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
int __dm_resume(struct mapped_device * md, struct dm_table * map)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int __dm_resume(struct mapped_device * md, struct dm_table * map)
```
</details>
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

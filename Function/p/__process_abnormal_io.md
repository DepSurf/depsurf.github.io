# Function: <code>__process_abnormal_io</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __process_abnormal_io(struct clone_info * ci, struct dm_target * ti, int * result)
```

```json
{
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587268000,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1505",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587268000,
      "name": "__process_abnormal_io",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool __process_abnormal_io(struct clone_info * ci, struct dm_target * ti, int * result)
```

```json
{
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587447920,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1536",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587447920,
      "name": "__process_abnormal_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __process_abnormal_io(struct clone_info * ci, struct dm_target * ti, int * result)
```

```json
{
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587717696,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1546",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587717696,
      "name": "__process_abnormal_io",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool __process_abnormal_io(struct clone_info * ci, struct dm_target * ti, int * result)
```

```json
{
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587921984,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1546",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587921984,
      "name": "__process_abnormal_io",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool __process_abnormal_io(struct clone_info * ci, struct dm_target * ti, int * result)
```

```json
{
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588778160,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1554",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588778160,
      "name": "__process_abnormal_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588794596,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1551",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__split_and_process_non_flush"
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
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588679860,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1558",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__split_and_process_non_flush"
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
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589375188,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1454",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__split_and_process_non_flush"
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
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590849623,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1534",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_split_and_process_bio"
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
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592540724,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1599",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_split_and_process_bio"
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
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592971858,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1628",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_split_and_process_bio"
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
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593721809,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1621",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_split_and_process_bio"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool __process_abnormal_io(struct clone_info * ci, struct dm_target * ti, int * result)
```

```json
{
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501161120,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1546",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501161120,
      "name": "__process_abnormal_io",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool __process_abnormal_io(struct clone_info * ci, struct dm_target * ti, int * result)
```

```json
{
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233668080,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1546",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233668080,
      "name": "__process_abnormal_io",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool __process_abnormal_io(struct clone_info * ci, struct dm_target * ti, int * result)
```

```json
{
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294667680,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1546",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294667680,
      "name": "__process_abnormal_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool __process_abnormal_io(struct clone_info * ci, struct dm_target * ti, int * result)
```

```json
{
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277865758,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1546",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277865758,
      "name": "__process_abnormal_io",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool __process_abnormal_io(struct clone_info * ci, struct dm_target * ti, int * result)
```

```json
{
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587552960,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1546",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587552960,
      "name": "__process_abnormal_io",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool __process_abnormal_io(struct clone_info * ci, struct dm_target * ti, int * result)
```

```json
{
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587321056,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1546",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587321056,
      "name": "__process_abnormal_io",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool __process_abnormal_io(struct clone_info * ci, struct dm_target * ti, int * result)
```

```json
{
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587878128,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1546",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587878128,
      "name": "__process_abnormal_io",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool __process_abnormal_io(struct clone_info * ci, struct dm_target * ti, int * result)
```

```json
{
  "name": "__process_abnormal_io",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587993680,
      "name": "__process_abnormal_io",
      "external": false,
      "loc": "drivers/md/dm.c:1546",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:__process_bio",
        "drivers/md/dm.c:__split_and_process_non_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587993680,
      "name": "__process_abnormal_io",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
bool __process_abnormal_io(struct clone_info * ci, struct dm_target * ti, int * result)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
bool __process_abnormal_io(struct clone_info * ci, struct dm_target * ti, int * result)
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

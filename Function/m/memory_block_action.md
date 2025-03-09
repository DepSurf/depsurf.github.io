# Function: <code>memory_block_action</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584485140,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:225",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_online",
        "drivers/base/memory.c:memory_subsys_offline"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int memory_block_action(long unsigned int phys_index, long unsigned int action, int online_type)
```

```json
{
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584830976,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:225",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:memory_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584830976,
      "name": "memory_block_action",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int memory_block_action(long unsigned int phys_index, long unsigned int action, int online_type)
```

```json
{
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585024224,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:225",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:memory_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585024224,
      "name": "memory_block_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 466
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
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585109266,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:229",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_online"
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
int memory_block_action(long unsigned int phys_index, long unsigned int action, int online_type)
```

```json
{
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585537344,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:230",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:memory_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585537344,
      "name": "memory_block_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
int memory_block_action(long unsigned int phys_index, long unsigned int action, int online_type)
```

```json
{
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585780976,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:234",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585780976,
      "name": "memory_block_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
int memory_block_action(long unsigned int phys_index, long unsigned int action, int online_type)
```

```json
{
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585914016,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:233",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585914016,
      "name": "memory_block_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
int memory_block_action(long unsigned int start_section_nr, long unsigned int action, int online_type)
```

```json
{
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586155424,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:244",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586155424,
      "name": "memory_block_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586303907,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:213",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587073616,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:178",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
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
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587158048,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:177",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
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
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587045458,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:250",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
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
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587615063,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:257",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
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
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588955191,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:262",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
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
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590470759,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:274",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
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
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590793687,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:269",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
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
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591137155,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:309",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
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
int memory_block_action(long unsigned int start_section_nr, long unsigned int action, int online_type)
```

```json
{
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499137240,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:213",
      "file": "drivers/base/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499137240,
      "name": "memory_block_action",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292329376,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:213",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586067155,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:213",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
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
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585913107,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:213",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
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
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586251875,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:213",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
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
  "name": "memory_block_action",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586362819,
      "name": "memory_block_action",
      "external": false,
      "loc": "drivers/base/memory.c:213",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_offline",
        "drivers/base/memory.c:memory_subsys_online"
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int memory_block_action(long unsigned int phys_index, long unsigned int action, int online_type)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int memory_block_action(long unsigned int phys_index, long unsigned int action, int online_type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int memory_block_action(long unsigned int phys_index, long unsigned int action, int online_type)
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int start_section_nr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int phys_index</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int memory_block_action(long unsigned int start_section_nr, long unsigned int action, int online_type)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int memory_block_action(long unsigned int start_section_nr, long unsigned int action, int online_type)
```
</details>
</li>
</ul>

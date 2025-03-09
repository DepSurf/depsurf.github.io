# Function: <code>memory_block_change_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584485091,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:254",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int memory_block_change_state(struct memory_block * mem, long unsigned int to_state, long unsigned int from_state_req)
```

```json
{
  "name": "memory_block_change_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584831485,
      "name": "memory_block_change_state",
      "external": true,
      "loc": "drivers/base/memory.c:254",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:online_memory_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584833712,
      "name": "memory_block_change_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int memory_block_change_state(struct memory_block * mem, long unsigned int to_state, long unsigned int from_state_req)
```

```json
{
  "name": "memory_block_change_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585024733,
      "name": "memory_block_change_state",
      "external": true,
      "loc": "drivers/base/memory.c:252",
      "file": "drivers/base/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:online_memory_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585027024,
      "name": "memory_block_change_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585109217,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:256",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585537871,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:257",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585781425,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:261",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585914449,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:260",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586155855,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:272",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586303888,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:241",
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
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587073592,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:203",
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
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587158024,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:202",
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
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587045426,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:270",
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
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587615042,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:277",
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
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588955170,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:282",
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
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590470738,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:294",
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
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590793666,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:289",
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
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591137123,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:329",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499137696,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:241",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292329344,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:241",
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
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586067136,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:241",
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
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585913088,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:241",
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
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586251856,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:241",
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
  "name": "memory_block_change_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586362800,
      "name": "memory_block_change_state",
      "external": false,
      "loc": "drivers/base/memory.c:241",
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
int memory_block_change_state(struct memory_block * mem, long unsigned int to_state, long unsigned int from_state_req)
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
int memory_block_change_state(struct memory_block * mem, long unsigned int to_state, long unsigned int from_state_req)
```
</details>
</li>
</ul>

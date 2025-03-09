# Function: <code>do_register_memory_block_under_node</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_register_memory_block_under_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587069795,
      "name": "do_register_memory_block_under_node",
      "external": false,
      "loc": "drivers/base/node.c:764",
      "file": "drivers/base/node.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_mem_block_under_node_hotplug",
        "drivers/base/node.c:register_mem_block_under_node_early"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void do_register_memory_block_under_node(int nid, struct memory_block * mem_blk)
```

```json
{
  "name": "do_register_memory_block_under_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_register_memory_block_under_node",
      "external": false,
      "loc": "drivers/base/node.c:775",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:register_mem_block_under_node_hotplug",
        "drivers/base/node.c:register_mem_block_under_node_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587151296,
      "name": "do_register_memory_block_under_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071591490250,
      "name": "do_register_memory_block_under_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void do_register_memory_block_under_node(int nid, struct memory_block * mem_blk)
```

```json
{
  "name": "do_register_memory_block_under_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_register_memory_block_under_node",
      "external": false,
      "loc": "drivers/base/node.c:778",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:register_mem_block_under_node_hotplug",
        "drivers/base/node.c:register_mem_block_under_node_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587038688,
      "name": "do_register_memory_block_under_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071591433251,
      "name": "do_register_memory_block_under_node.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void do_register_memory_block_under_node(int nid, struct memory_block * mem_blk)
```

```json
{
  "name": "do_register_memory_block_under_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587606144,
      "name": "do_register_memory_block_under_node",
      "external": false,
      "loc": "drivers/base/node.c:795",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:register_mem_block_under_node_hotplug",
        "drivers/base/node.c:register_mem_block_under_node_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587606144,
      "name": "do_register_memory_block_under_node",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void do_register_memory_block_under_node(int nid, struct memory_block * mem_blk, enum meminit_context context)
```

```json
{
  "name": "do_register_memory_block_under_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588945376,
      "name": "do_register_memory_block_under_node",
      "external": false,
      "loc": "drivers/base/node.c:799",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:register_mem_block_under_node_hotplug",
        "drivers/base/node.c:register_mem_block_under_node_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588945376,
      "name": "do_register_memory_block_under_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
void do_register_memory_block_under_node(int nid, struct memory_block * mem_blk, enum meminit_context context)
```

```json
{
  "name": "do_register_memory_block_under_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590460704,
      "name": "do_register_memory_block_under_node",
      "external": false,
      "loc": "drivers/base/node.c:747",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:register_mem_block_under_node_hotplug",
        "drivers/base/node.c:register_mem_block_under_node_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590460704,
      "name": "do_register_memory_block_under_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
void do_register_memory_block_under_node(int nid, struct memory_block * mem_blk, enum meminit_context context)
```

```json
{
  "name": "do_register_memory_block_under_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590783568,
      "name": "do_register_memory_block_under_node",
      "external": false,
      "loc": "drivers/base/node.c:757",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:register_mem_block_under_node_hotplug",
        "drivers/base/node.c:register_mem_block_under_node_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590783568,
      "name": "do_register_memory_block_under_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
void do_register_memory_block_under_node(int nid, struct memory_block * mem_blk, enum meminit_context context)
```

```json
{
  "name": "do_register_memory_block_under_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591126368,
      "name": "do_register_memory_block_under_node",
      "external": false,
      "loc": "drivers/base/node.c:756",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/node.c:register_mem_block_under_node_hotplug",
        "drivers/base/node.c:register_mem_block_under_node_early"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591126368,
      "name": "do_register_memory_block_under_node",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void do_register_memory_block_under_node(int nid, struct memory_block * mem_blk)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum meminit_context context</code>
</li>
</ul>
</details>
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

# Function: <code>register_memory_blocks_under_node</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void register_memory_blocks_under_node(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context)
```

```json
{
  "name": "register_memory_blocks_under_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617358523,
      "name": "register_memory_blocks_under_node",
      "external": true,
      "loc": "drivers/base/node.c:893",
      "file": "drivers/base/node.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588951344,
      "name": "register_memory_blocks_under_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void register_memory_blocks_under_node(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context)
```

```json
{
  "name": "register_memory_blocks_under_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071628096474,
      "name": "register_memory_blocks_under_node",
      "external": true,
      "loc": "drivers/base/node.c:841",
      "file": "drivers/base/node.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590466752,
      "name": "register_memory_blocks_under_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void register_memory_blocks_under_node(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context)
```

```json
{
  "name": "register_memory_blocks_under_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619862394,
      "name": "register_memory_blocks_under_node",
      "external": true,
      "loc": "drivers/base/node.c:851",
      "file": "drivers/base/node.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:__try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590789680,
      "name": "register_memory_blocks_under_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void register_memory_blocks_under_node(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context)
```

```json
{
  "name": "register_memory_blocks_under_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622170954,
      "name": "register_memory_blocks_under_node",
      "external": true,
      "loc": "drivers/base/node.c:850",
      "file": "drivers/base/node.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:__try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591132624,
      "name": "register_memory_blocks_under_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void register_memory_blocks_under_node(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context)
```
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

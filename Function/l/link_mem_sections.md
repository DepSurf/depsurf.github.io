# Function: <code>link_mem_sections</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584484538,
      "name": "link_mem_sections",
      "external": false,
      "loc": "drivers/base/node.c:460",
      "file": "drivers/base/node.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_one_node"
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
  "name": "link_mem_sections",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584830458,
      "name": "link_mem_sections",
      "external": false,
      "loc": "drivers/base/node.c:471",
      "file": "drivers/base/node.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_one_node"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585023702,
      "name": "link_mem_sections",
      "external": false,
      "loc": "drivers/base/node.c:471",
      "file": "drivers/base/node.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_one_node"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585108432,
      "name": "link_mem_sections",
      "external": true,
      "loc": "drivers/base/node.c:464",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:topology_init",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585108432,
      "name": "link_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585534624,
      "name": "link_mem_sections",
      "external": true,
      "loc": "drivers/base/node.c:481",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:topology_init",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585534624,
      "name": "link_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int nr_pages, bool check_nid)
```

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585778288,
      "name": "link_mem_sections",
      "external": true,
      "loc": "drivers/base/node.c:493",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:topology_init",
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585778288,
      "name": "link_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585911488,
      "name": "link_mem_sections",
      "external": true,
      "loc": "drivers/base/node.c:492",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:topology_init",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585911488,
      "name": "link_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586152560,
      "name": "link_mem_sections",
      "external": true,
      "loc": "drivers/base/node.c:835",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:topology_init",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586152560,
      "name": "link_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586301040,
      "name": "link_mem_sections",
      "external": true,
      "loc": "drivers/base/node.c:832",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:topology_init",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586301040,
      "name": "link_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context)
```

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587071376,
      "name": "link_mem_sections",
      "external": true,
      "loc": "drivers/base/node.c:852",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:topology_init",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587071376,
      "name": "link_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context)
```

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587155920,
      "name": "link_mem_sections",
      "external": true,
      "loc": "drivers/base/node.c:872",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:topology_init",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587155920,
      "name": "link_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context)
```

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587043232,
      "name": "link_mem_sections",
      "external": true,
      "loc": "drivers/base/node.c:875",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:topology_init",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587043232,
      "name": "link_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context)
```

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587611568,
      "name": "link_mem_sections",
      "external": true,
      "loc": "drivers/base/node.c:892",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:topology_init",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587611568,
      "name": "link_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499134680,
      "name": "link_mem_sections",
      "external": true,
      "loc": "drivers/base/node.c:832",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/setup.c:topology_init",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499134680,
      "name": "link_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292325088,
      "name": "link_mem_sections",
      "external": true,
      "loc": "drivers/base/node.c:832",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/sysfs.c:topology_init",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292325088,
      "name": "link_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586064288,
      "name": "link_mem_sections",
      "external": true,
      "loc": "drivers/base/node.c:832",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:topology_init",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586064288,
      "name": "link_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585910240,
      "name": "link_mem_sections",
      "external": true,
      "loc": "drivers/base/node.c:832",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:topology_init",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585910240,
      "name": "link_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586249120,
      "name": "link_mem_sections",
      "external": true,
      "loc": "drivers/base/node.c:832",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:topology_init",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586249120,
      "name": "link_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "link_mem_sections",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586359952,
      "name": "link_mem_sections",
      "external": true,
      "loc": "drivers/base/node.c:832",
      "file": "drivers/base/node.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/topology.c:topology_init",
        "mm/memory_hotplug.c:add_memory_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586359952,
      "name": "link_mem_sections",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int nr_pages)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool check_nid</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int end_pfn</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_pages</code>
</li>
<li>
<b>Param removed. </b>
<code>bool check_nid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum meminit_context context</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
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
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn, enum meminit_context context)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int link_mem_sections(int nid, long unsigned int start_pfn, long unsigned int end_pfn)
```
</details>
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

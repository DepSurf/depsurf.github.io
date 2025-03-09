# Function: <code>register_one_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int register_one_node(int nid)
```

```json
{
  "name": "register_one_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584484304,
      "name": "register_one_node",
      "external": true,
      "loc": "drivers/base/node.c:568",
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
      "addr": 18446744071584484304,
      "name": "register_one_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int register_one_node(int nid)
```

```json
{
  "name": "register_one_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584830224,
      "name": "register_one_node",
      "external": true,
      "loc": "drivers/base/node.c:579",
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
      "addr": 18446744071584830224,
      "name": "register_one_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
int register_one_node(int nid)
```

```json
{
  "name": "register_one_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585023456,
      "name": "register_one_node",
      "external": true,
      "loc": "drivers/base/node.c:579",
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
      "addr": 18446744071585023456,
      "name": "register_one_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596328582,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:48",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581127010,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:48",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_online_node"
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
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602646696,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:49",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581239835,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:49",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_online_node"
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
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602816625,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:51",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581385803,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:51",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_online_node"
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
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604611659,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:51",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581467489,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:51",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604707219,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:118",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583011,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:118",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604719606,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:118",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581647683,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:118",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609066401,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:120",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581863121,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:120",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612129768,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:119",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581907665,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:119",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614269680,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:119",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581754043,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:119",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615191854,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:119",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582036139,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:119",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582464593,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:120",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071617358450,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:120",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init"
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
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582979597,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:114",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071628096407,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:114",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init"
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
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583191375,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:114",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__try_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619862327,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:114",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init"
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
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583376271,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:114",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__try_online_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622170887,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:114",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:node_dev_init"
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
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510815812,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:118",
      "file": "arch/arm64/kernel/setup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/setup.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493095920,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:118",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302383684,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:118",
      "file": "arch/powerpc/kernel/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/sysfs.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286545700,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:118",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
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
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604645896,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:118",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616419,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:118",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604613830,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:118",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557747,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:118",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604723688,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:118",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607731,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:118",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "register_one_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604723718,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:118",
      "file": "arch/x86/kernel/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/topology.c:topology_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581674131,
      "name": "register_one_node",
      "external": false,
      "loc": "include/linux/node.h:118",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int register_one_node(int nid)
```
</details>
</li>
</ul>

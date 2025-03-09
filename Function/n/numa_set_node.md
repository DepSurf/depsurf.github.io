# Function: <code>numa_set_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579323136,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:81",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579323136,
      "name": "numa_set_node.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579323280,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595234834,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:80",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579328768,
      "name": "numa_set_node.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579328912,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595477993,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:80",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu2node",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344112,
      "name": "numa_set_node.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579344256,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596399572,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:80",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338144,
      "name": "numa_set_node.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579338288,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602719243,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:80",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579363552,
      "name": "numa_set_node.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579363728,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602891950,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:80",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579376160,
      "name": "numa_set_node.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579376336,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604689308,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:79",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403824,
      "name": "numa_set_node.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579404000,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604789105,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:80",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579419264,
      "name": "numa_set_node.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579419408,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604814795,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:80",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579422432,
      "name": "numa_set_node.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579422576,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579452768,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:77",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:srat_detect_node",
        "arch/x86/kernel/cpu/hygon.c:srat_detect_node",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452768,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579449696,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:75",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:srat_detect_node",
        "arch/x86/kernel/cpu/hygon.c:srat_detect_node",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579449696,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579452192,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:75",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452192,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579517328,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:75",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517328,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579601168,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:75",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601168,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627728110,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:75",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713936,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619487310,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:75",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579727568,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621783630,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:77",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762512,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604728737,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:80",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418272,
      "name": "numa_set_node.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579418416,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604696467,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:80",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579347408,
      "name": "numa_set_node.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579347552,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604806304,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:80",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418192,
      "name": "numa_set_node.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579418336,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void numa_set_node(int cpu, int node)
```

```json
{
  "name": "numa_set_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604818923,
      "name": "numa_set_node",
      "external": true,
      "loc": "arch/x86/mm/numa.c:80",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:numa_init",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579427248,
      "name": "numa_set_node.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579427392,
      "name": "numa_set_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void numa_set_node(int cpu, int node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void numa_set_node(int cpu, int node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void numa_set_node(int cpu, int node)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void numa_set_node(int cpu, int node)
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

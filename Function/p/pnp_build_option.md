# Function: <code>pnp_build_option</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583794752,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:34",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_register_irq_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_mem_resource"
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
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584121544,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:34",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
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
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584269544,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:34",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584347595,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:34",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
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
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584753387,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:35",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
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
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584981845,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:35",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pnp_option * pnp_build_option(struct pnp_dev * dev, long unsigned int type, unsigned int option_flags)
```

```json
{
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585086016,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:35",
      "file": "drivers/pnp/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585086016,
      "name": "pnp_build_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
struct pnp_option * pnp_build_option(struct pnp_dev * dev, long unsigned int type, unsigned int option_flags)
```

```json
{
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585290368,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:35",
      "file": "drivers/pnp/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585290368,
      "name": "pnp_build_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
struct pnp_option * pnp_build_option(struct pnp_dev * dev, long unsigned int type, unsigned int option_flags)
```

```json
{
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585428336,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:35",
      "file": "drivers/pnp/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585428336,
      "name": "pnp_build_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586145093,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:35",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
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
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586263975,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:35",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
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
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586137943,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:35",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
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
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586638791,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:35",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
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
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587905179,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:35",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
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
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589255515,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:36",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
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
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589552347,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:36",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pnp_option * pnp_build_option(struct pnp_dev * dev, long unsigned int type, unsigned int option_flags)
```

```json
{
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589861280,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:36",
      "file": "drivers/pnp/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource"
      ],
      "caller_func": [
        "drivers/pnp/resource.c:pnp_register_irq_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589860384,
      "name": "pnp_build_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct pnp_option * pnp_build_option(struct pnp_dev * dev, long unsigned int type, unsigned int option_flags)
```

```json
{
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497710880,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:35",
      "file": "drivers/pnp/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497710880,
      "name": "pnp_build_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct pnp_option * pnp_build_option(struct pnp_dev * dev, long unsigned int type, unsigned int option_flags)
```

```json
{
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585190864,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:35",
      "file": "drivers/pnp/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585190864,
      "name": "pnp_build_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
struct pnp_option * pnp_build_option(struct pnp_dev * dev, long unsigned int type, unsigned int option_flags)
```

```json
{
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585143072,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:35",
      "file": "drivers/pnp/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585143072,
      "name": "pnp_build_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
struct pnp_option * pnp_build_option(struct pnp_dev * dev, long unsigned int type, unsigned int option_flags)
```

```json
{
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585378736,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:35",
      "file": "drivers/pnp/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585378736,
      "name": "pnp_build_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
struct pnp_option * pnp_build_option(struct pnp_dev * dev, long unsigned int type, unsigned int option_flags)
```

```json
{
  "name": "pnp_build_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585486080,
      "name": "pnp_build_option",
      "external": false,
      "loc": "drivers/pnp/resource.c:35",
      "file": "drivers/pnp/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pnp/resource.c:pnp_register_mem_resource",
        "drivers/pnp/resource.c:pnp_register_port_resource",
        "drivers/pnp/resource.c:pnp_register_dma_resource",
        "drivers/pnp/resource.c:pnp_register_irq_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585486080,
      "name": "pnp_build_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct pnp_option * pnp_build_option(struct pnp_dev * dev, long unsigned int type, unsigned int option_flags)
```
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct pnp_option * pnp_build_option(struct pnp_dev * dev, long unsigned int type, unsigned int option_flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct pnp_option * pnp_build_option(struct pnp_dev * dev, long unsigned int type, unsigned int option_flags)
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
struct pnp_option * pnp_build_option(struct pnp_dev * dev, long unsigned int type, unsigned int option_flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct pnp_option * pnp_build_option(struct pnp_dev * dev, long unsigned int type, unsigned int option_flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct pnp_option * pnp_build_option(struct pnp_dev * dev, long unsigned int type, unsigned int option_flags)
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

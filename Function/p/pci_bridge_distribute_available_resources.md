# Function: <code>pci_bridge_distribute_available_resources</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584056063,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:2005",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
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
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584255583,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:2000",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
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
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584345343,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:2002",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
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
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584538975,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1968",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
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
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584674111,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1974",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void pci_bridge_distribute_available_resources(struct pci_dev * bridge, struct list_head * add_list)
```

```json
{
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585354272,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:2030",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585354272,
      "name": "pci_bridge_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void pci_bridge_distribute_available_resources(struct pci_dev * bridge, struct list_head * add_list)
```

```json
{
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585506016,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:2031",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585506016,
      "name": "pci_bridge_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void pci_bridge_distribute_available_resources(struct pci_dev * bridge, struct list_head * add_list)
```

```json
{
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585384224,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:2031",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585384224,
      "name": "pci_bridge_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void pci_bridge_distribute_available_resources(struct pci_dev * bridge, struct list_head * add_list)
```

```json
{
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585845632,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:2031",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585845632,
      "name": "pci_bridge_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void pci_bridge_distribute_available_resources(struct pci_dev * bridge, struct list_head * add_list)
```

```json
{
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587038672,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:2031",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587038672,
      "name": "pci_bridge_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void pci_bridge_distribute_available_resources(struct pci_dev * bridge, struct list_head * add_list)
```

```json
{
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588218624,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1970",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_root_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588218624,
      "name": "pci_bridge_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
void pci_bridge_distribute_available_resources(struct pci_dev * bridge, struct list_head * add_list)
```

```json
{
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588494112,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1961",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_root_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588494112,
      "name": "pci_bridge_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
void pci_bridge_distribute_available_resources(struct pci_dev * bridge, struct list_head * add_list)
```

```json
{
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588792480,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1971",
      "file": "drivers/pci/setup-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources",
        "drivers/pci/setup-bus.c:pci_root_bus_distribute_available_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588792480,
      "name": "pci_bridge_distribute_available_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496923776,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1974",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230199556,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1974",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291022228,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1974",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275609026,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1974",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584624575,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1974",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
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
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584554399,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1974",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
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
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584624271,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1974",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
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
  "name": "pci_bridge_distribute_available_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584731967,
      "name": "pci_bridge_distribute_available_resources",
      "external": false,
      "loc": "drivers/pci/setup-bus.c:1974",
      "file": "drivers/pci/setup-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void pci_bridge_distribute_available_resources(struct pci_dev * bridge, struct list_head * add_list)
```
</details>
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

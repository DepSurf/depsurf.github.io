# Function: <code>insert_resource_conflict</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579399744,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:817",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:insert_resource"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399744,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579407378,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:851",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:insert_resource"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411824,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579427682,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:851",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:insert_resource"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432128,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579415426,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:851",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:insert_resource"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579419760,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579443298,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:869",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:insert_resource"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579447728,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579462608,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:838",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:insert_resource",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462608,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579496176,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:832",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:insert_resource",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496176,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579514144,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:846",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:insert_resource",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514144,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540304,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:846",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:insert_resource",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540304,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579569605,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:846",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:insert_resource"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571984,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579551027,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:853",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:insert_resource"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553392,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579555667,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:845",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:insert_resource"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579557968,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579628243,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:845",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:insert_resource"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630544,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579723314,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:832",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:insert_resource"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579725952,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579850610,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:833",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:insert_resource"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855616,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579900850,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:833",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:insert_resource"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905808,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579939586,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:888",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:insert_resource"
      ],
      "caller_func": [
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_reserved"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579945024,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490687136,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:846",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:insert_resource",
        "drivers/acpi/pci_root.c:acpi_pci_root_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490687136,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224756012,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:846",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:insert_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224756012,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283511968,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:846",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:insert_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283511968,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271420338,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:846",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:insert_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271420338,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513968,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:846",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:insert_resource",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513968,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579442768,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:846",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:insert_resource",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579442768,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513888,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:846",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:insert_resource",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513888,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
struct resource * insert_resource_conflict(struct resource * parent, struct resource * new)
```

```json
{
  "name": "insert_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546816,
      "name": "insert_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:846",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:insert_resource",
        "drivers/acpi/pci_root.c:acpi_pci_root_create",
        "arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546816,
      "name": "insert_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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

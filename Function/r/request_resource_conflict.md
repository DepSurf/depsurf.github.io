# Function: <code>request_resource_conflict</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579394018,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:292",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:request_resource",
        "kernel/resource.c:devm_request_resource"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/pci/setup-res.c:pci_assign_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579397424,
      "name": "request_resource_conflict",
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579407660,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:311",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:request_resource"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409760,
      "name": "request_resource_conflict",
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579427964,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:311",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:request_resource"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430064,
      "name": "request_resource_conflict",
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579415708,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:311",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:request_resource"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417712,
      "name": "request_resource_conflict",
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579443580,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:311",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:request_resource"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:add_memory",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579445744,
      "name": "request_resource_conflict",
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579460528,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:278",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "mm/memory_hotplug.c:add_memory",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460528,
      "name": "request_resource_conflict",
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494176,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:278",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "mm/memory_hotplug.c:__add_memory",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494176,
      "name": "request_resource_conflict",
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579512208,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:279",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512208,
      "name": "request_resource_conflict",
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538384,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:279",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538384,
      "name": "request_resource_conflict",
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579568071,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:279",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:devm_request_resource"
      ],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_revert_fw_address",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569952,
      "name": "request_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579549415,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:279",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:devm_request_resource"
      ],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_revert_fw_address",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551360,
      "name": "request_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579553767,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:278",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:devm_request_resource"
      ],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555984,
      "name": "request_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579626334,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:278",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:devm_request_resource"
      ],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628560,
      "name": "request_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579720813,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:265",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:devm_request_resource"
      ],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579723696,
      "name": "request_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627759258,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:265",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853216,
      "name": "request_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619519850,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:265",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579903472,
      "name": "request_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621816858,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:265",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource"
      ],
      "caller_func": [
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942272,
      "name": "request_resource_conflict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490684576,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:279",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/pci/ecam.c:pci_ecam_create",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490684576,
      "name": "request_resource_conflict",
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224754028,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:279",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/pci/ecam.c:pci_ecam_create",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224754028,
      "name": "request_resource_conflict",
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283509232,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:279",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/setup.c:of_pci_parse_iov_addrs",
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/pci/ecam.c:pci_ecam_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283509232,
      "name": "request_resource_conflict",
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271418570,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:279",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/pci/ecam.c:pci_ecam_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271418570,
      "name": "request_resource_conflict",
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579512048,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:279",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512048,
      "name": "request_resource_conflict",
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579440848,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:279",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579440848,
      "name": "request_resource_conflict",
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579511968,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:279",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511968,
      "name": "request_resource_conflict",
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
struct resource * request_resource_conflict(struct resource * root, struct resource * new)
```

```json
{
  "name": "request_resource_conflict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544880,
      "name": "request_resource_conflict",
      "external": true,
      "loc": "kernel/resource.c:279",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "drivers/pci/probe.c:pci_bus_insert_busn_res",
        "drivers/pci/setup-res.c:pci_assign_resource",
        "drivers/pci/setup-res.c:pci_claim_resource",
        "drivers/firmware/efi/efi.c:efi_mem_reserve_iomem",
        "arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544880,
      "name": "request_resource_conflict",
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

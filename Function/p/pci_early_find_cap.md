# Function: <code>pci_early_find_cap</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```

```json
{
  "name": "pci_early_find_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587808768,
      "name": "pci_early_find_cap",
      "external": true,
      "loc": "arch/x86/pci/early.c:54",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808768,
      "name": "pci_early_find_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```

```json
{
  "name": "pci_early_find_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588114240,
      "name": "pci_early_find_cap",
      "external": true,
      "loc": "arch/x86/pci/early.c:54",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588114240,
      "name": "pci_early_find_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```

```json
{
  "name": "pci_early_find_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588319936,
      "name": "pci_early_find_cap",
      "external": true,
      "loc": "arch/x86/pci/early.c:54",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588319936,
      "name": "pci_early_find_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```

```json
{
  "name": "pci_early_find_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591140256,
      "name": "pci_early_find_cap",
      "external": true,
      "loc": "arch/x86/pci/early.c:54",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591140256,
      "name": "pci_early_find_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```

```json
{
  "name": "pci_early_find_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591224480,
      "name": "pci_early_find_cap",
      "external": true,
      "loc": "arch/x86/pci/early.c:54",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591224480,
      "name": "pci_early_find_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```

```json
{
  "name": "pci_early_find_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591173712,
      "name": "pci_early_find_cap",
      "external": true,
      "loc": "arch/x86/pci/early.c:54",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591173712,
      "name": "pci_early_find_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```

```json
{
  "name": "pci_early_find_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592027232,
      "name": "pci_early_find_cap",
      "external": true,
      "loc": "arch/x86/pci/early.c:54",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592027232,
      "name": "pci_early_find_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```

```json
{
  "name": "pci_early_find_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593794384,
      "name": "pci_early_find_cap",
      "external": true,
      "loc": "arch/x86/pci/early.c:54",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593794384,
      "name": "pci_early_find_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```

```json
{
  "name": "pci_early_find_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595737664,
      "name": "pci_early_find_cap",
      "external": true,
      "loc": "arch/x86/pci/early.c:54",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595737664,
      "name": "pci_early_find_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```

```json
{
  "name": "pci_early_find_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596263648,
      "name": "pci_early_find_cap",
      "external": true,
      "loc": "arch/x86/pci/early.c:54",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596263648,
      "name": "pci_early_find_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```

```json
{
  "name": "pci_early_find_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597146304,
      "name": "pci_early_find_cap",
      "external": true,
      "loc": "arch/x86/pci/early.c:54",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597146304,
      "name": "pci_early_find_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```

```json
{
  "name": "pci_early_find_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587923584,
      "name": "pci_early_find_cap",
      "external": true,
      "loc": "arch/x86/pci/early.c:54",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587923584,
      "name": "pci_early_find_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```

```json
{
  "name": "pci_early_find_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587639440,
      "name": "pci_early_find_cap",
      "external": true,
      "loc": "arch/x86/pci/early.c:54",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639440,
      "name": "pci_early_find_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```

```json
{
  "name": "pci_early_find_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588256992,
      "name": "pci_early_find_cap",
      "external": true,
      "loc": "arch/x86/pci/early.c:54",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588256992,
      "name": "pci_early_find_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```

```json
{
  "name": "pci_early_find_cap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588392512,
      "name": "pci_early_find_cap",
      "external": true,
      "loc": "arch/x86/pci/early.c:54",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/early-quirks.c:early_pci_clear_msi",
        "arch/x86/kernel/aperture_64.c:search_agp_bridge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588392512,
      "name": "pci_early_find_cap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
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
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u32 pci_early_find_cap(int bus, int slot, int func, int cap)
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

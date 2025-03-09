# Function: <code>e820__mapped_all</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596323925,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:99",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596323925,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602641914,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:135",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602641914,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602811601,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:135",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602811601,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604606648,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:134",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604606648,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604702256,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:148",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604702256,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604714644,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:148",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604714644,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609061402,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:148",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609061402,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612124762,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:148",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612124762,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614264683,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:148",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614264683,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615186015,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:148",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615186015,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616952557,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:148",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616952557,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627563840,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:148",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627563840,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619314256,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:148",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619314256,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621607376,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:148",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621607376,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604640934,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:148",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604640934,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604608868,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:148",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604608868,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604718726,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:148",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604718726,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```

```json
{
  "name": "e820__mapped_all",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604718756,
      "name": "e820__mapped_all",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:148",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604718756,
      "name": "e820__mapped_all",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```
</details>
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type)
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

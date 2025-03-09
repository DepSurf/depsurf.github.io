# Function: <code>memblock_phys_alloc</code>

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
phys_addr_t memblock_phys_alloc(phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_phys_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604789120,
      "name": "memblock_phys_alloc",
      "external": true,
      "loc": "mm/memblock.c:1334",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604789120,
      "name": "memblock_phys_alloc",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memblock_phys_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604704300,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:354",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605118041,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:354",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "memblock_phys_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604716688,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:354",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605157490,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:354",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memblock_phys_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609063870,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:357",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609426594,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:357",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "memblock_phys_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612127259,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:390",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612500409,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:390",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "memblock_phys_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614267183,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:390",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614642595,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:390",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "memblock_phys_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615189266,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:391",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615600553,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:391",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "memblock_phys_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616956303,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:407",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617410261,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:407",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "memblock_phys_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627570018,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:407",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627740565,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:407",
      "file": "arch/x86/platform/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/memmap.c:efi_memmap_alloc"
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
  "name": "memblock_phys_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619321842,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:406",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619500005,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:406",
      "file": "arch/x86/platform/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/memmap.c:efi_memmap_alloc"
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
  "name": "memblock_phys_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621614962,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:418",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621796837,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:418",
      "file": "arch/x86/platform/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/memmap.c:efi_memmap_alloc"
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
  "name": "memblock_phys_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510831484,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:354",
      "file": "arch/arm64/mm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/mmu.c:early_pgtable_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336511285152,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:354",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "memblock_phys_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243275664,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:354",
      "file": "arch/arm/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/init.c:arm_memblock_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 3243936620,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:354",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "memblock_phys_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270612428,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:354",
      "file": "arch/riscv/mm/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/init.c:create_pgd_mapping",
        "arch/riscv/mm/init.c:create_pgd_mapping"
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
  "name": "memblock_phys_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604642978,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:354",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605047928,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:354",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "memblock_phys_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604610912,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:354",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605013268,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:354",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "memblock_phys_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604720770,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:354",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605134503,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:354",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
  "name": "memblock_phys_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604720800,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:354",
      "file": "arch/x86/kernel/e820.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605161684,
      "name": "memblock_phys_alloc",
      "external": false,
      "loc": "include/linux/memblock.h:354",
      "file": "drivers/firmware/efi/memmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
phys_addr_t memblock_phys_alloc(phys_addr_t size, phys_addr_t align)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
phys_addr_t memblock_phys_alloc(phys_addr_t size, phys_addr_t align)
```
</details>
</li>
</ul>

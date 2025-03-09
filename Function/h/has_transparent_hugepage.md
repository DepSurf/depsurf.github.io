# Function: <code>has_transparent_hugepage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "has_transparent_hugepage",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595152821,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "mm/huge_memory.c",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580674917,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:185",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595324978,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:185",
      "file": "mm/huge_memory.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580742581,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:185",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595573163,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:185",
      "file": "mm/huge_memory.c",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580777087,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596500872,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:225",
      "file": "mm/huge_memory.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580862719,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:240",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602828278,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:240",
      "file": "mm/huge_memory.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580999423,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603001370,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:250",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
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
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581076127,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:252",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604799996,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:252",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
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
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581139519,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:269",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604903295,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:269",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
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
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581197800,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:269",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604937254,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:269",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586580181,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:269",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit",
        "drivers/nvdimm/pfn_devs.c:supported_alignments_show",
        "drivers/nvdimm/pfn_devs.c:align_store"
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
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581383071,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:274",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609251328,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:274",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587365303,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:274",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/pfn_devs.c:supported_alignments_show",
        "drivers/nvdimm/pfn_devs.c:align_store"
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
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581426527,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:273",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612317612,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:273",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587426535,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:273",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/pfn_devs.c:supported_alignments_show",
        "drivers/nvdimm/pfn_devs.c:align_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587442637,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:273",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:align_store"
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
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581447959,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:273",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614457867,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:273",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587308444,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:273",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/pfn_devs.c:supported_alignments_show",
        "drivers/nvdimm/pfn_devs.c:align_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587324241,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:273",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:align_store"
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
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581701632,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:244",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615402785,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:244",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587875234,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:244",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/pfn_devs.c:supported_alignments_show",
        "drivers/nvdimm/pfn_devs.c:align_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587891073,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:244",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:align_store"
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
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582078192,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:247",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617194843,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:247",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589225089,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:247",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/pfn_devs.c:supported_alignments_show",
        "drivers/nvdimm/pfn_devs.c:align_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589240214,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:247",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:align_store"
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
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582553072,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:248",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627893349,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:248",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590781470,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:248",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/pfn_devs.c:supported_alignments_show",
        "drivers/nvdimm/pfn_devs.c:align_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590799270,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:248",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:align_store"
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
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582758560,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:249",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619656277,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:249",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591122977,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:249",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/pfn_devs.c:supported_alignments_show",
        "drivers/nvdimm/pfn_devs.c:align_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591140243,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:249",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:align_store"
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
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582933440,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:285",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621962519,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:285",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591468447,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:285",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/pfn_devs.c:supported_alignments_show",
        "drivers/nvdimm/pfn_devs.c:align_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591485939,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:285",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:align_store"
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
int has_transparent_hugepage()
```

```json
{
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285892784,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1145",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_init"
      ]
    },
    {
      "addr": 13835058055302634168,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1145",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292738416,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1145",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit",
        "drivers/nvdimm/pfn_devs.c:supported_alignments_show",
        "drivers/nvdimm/pfn_devs.c:align_store"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285890416,
      "name": "has_transparent_hugepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581166648,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:269",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604842714,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:269",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586270661,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:269",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit",
        "drivers/nvdimm/pfn_devs.c:supported_alignments_show",
        "drivers/nvdimm/pfn_devs.c:align_store"
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
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581113496,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:269",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604811775,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:269",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586089029,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:269",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit",
        "drivers/nvdimm/pfn_devs.c:supported_alignments_show",
        "drivers/nvdimm/pfn_devs.c:align_store"
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
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581157848,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:269",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604919898,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:269",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586528149,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:269",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit",
        "drivers/nvdimm/pfn_devs.c:supported_alignments_show",
        "drivers/nvdimm/pfn_devs.c:align_store"
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
  "name": "has_transparent_hugepage",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581223736,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:269",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_enabled_store",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_parse_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604941425,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:269",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:hugepage_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586639877,
      "name": "has_transparent_hugepage",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:269",
      "file": "drivers/nvdimm/pfn_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pfn_devs.c:nd_pfn_validate",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit",
        "drivers/nvdimm/pfn_devs.c:supported_alignments_show",
        "drivers/nvdimm/pfn_devs.c:align_store"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int has_transparent_hugepage()
```
</details>
</li>
</ul>

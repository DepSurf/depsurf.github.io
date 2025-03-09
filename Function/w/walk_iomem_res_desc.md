# Function: <code>walk_iomem_res_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(u64, u64, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579409824,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:417",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "kernel/kexec_file.c:kexec_add_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409824,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(u64, u64, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579430128,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:417",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430128,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(u64, u64, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579417776,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:417",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417776,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579445808,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:440",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579445808,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579458976,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:407",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/nvdimm/e820.c:e820_pmem_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458976,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579492560,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:415",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/nvdimm/e820.c:e820_pmem_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579492560,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579510320,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:431",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/nvdimm/e820.c:e820_pmem_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510320,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579536384,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:431",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/nvdimm/e820.c:e820_pmem_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536384,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568992,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:431",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/nvdimm/e820.c:e820_pmem_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568992,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550400,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:438",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "kernel/kexec_file.c:arch_kexec_locate_mem_hole",
        "drivers/nvdimm/e820.c:e820_pmem_probe",
        "drivers/dax/hmem/device.c:hmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550400,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579554096,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:424",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "kernel/kexec_file.c:arch_kexec_locate_mem_hole",
        "drivers/nvdimm/e820.c:e820_pmem_probe",
        "drivers/dax/hmem/device.c:hmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554096,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579626656,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:424",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "kernel/kexec_file.c:arch_kexec_locate_mem_hole",
        "drivers/nvdimm/e820.c:e820_pmem_probe",
        "drivers/dax/hmem/device.c:hmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626656,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579722560,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:411",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "kernel/kexec_file.c:kexec_locate_mem_hole",
        "drivers/nvdimm/e820.c:e820_pmem_probe",
        "drivers/dax/hmem/device.c:hmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579722560,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848352,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:411",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "kernel/kexec_file.c:kexec_locate_mem_hole",
        "drivers/nvdimm/e820.c:e820_pmem_probe",
        "drivers/dax/hmem/device.c:hmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848352,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579898576,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:411",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "kernel/kexec_file.c:kexec_locate_mem_hole",
        "drivers/nvdimm/e820.c:e820_pmem_probe",
        "drivers/dax/hmem/device.c:hmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898576,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579937280,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:411",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_pgtable",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "kernel/kexec_file.c:kexec_locate_mem_hole",
        "drivers/nvdimm/e820.c:e820_pmem_probe",
        "drivers/dax/hmem/device.c:hmem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937280,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490682688,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:431",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490682688,
      "name": "walk_iomem_res_desc",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224753880,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:431",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224753880,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283505808,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:431",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283505808,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271416624,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:431",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271416624,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579510048,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:431",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/nvdimm/e820.c:e820_pmem_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510048,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579438848,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:431",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/nvdimm/e820.c:e820_pmem_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579438848,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509968,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:431",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/nvdimm/e820.c:e820_pmem_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509968,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(struct resource *, void *) func)
```

```json
{
  "name": "walk_iomem_res_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542848,
      "name": "walk_iomem_res_desc",
      "external": true,
      "loc": "kernel/resource.c:431",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/pmem.c:register_e820_pmem",
        "drivers/nvdimm/e820.c:e820_pmem_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542848,
      "name": "walk_iomem_res_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int walk_iomem_res_desc(long unsigned int desc, long unsigned int flags, u64 start, u64 end, void * arg, int (*)(u64, u64, void *) func)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*)(u64, u64, void *) func</code> ➡️ <code>int (*)(struct resource *, void *) func</code>
</li>
</ul>
</details>
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

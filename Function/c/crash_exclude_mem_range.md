# Function: <code>crash_exclude_mem_range</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580130912,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/kexec_file.c:1061",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580130912,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580178224,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/kexec_file.c:1119",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580178224,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580224288,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/kexec_file.c:1164",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580224288,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580272560,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/kexec_file.c:1169",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580272560,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580341488,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/kexec_file.c:1156",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580341488,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580326768,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/kexec_file.c:1174",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580326768,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580330080,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/kexec_file.c:1176",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580330080,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580484752,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/kexec_file.c:1176",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580484752,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580679440,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/kexec_file.c:1135",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580679440,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580950640,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/kexec_file.c:1139",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580950640,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581037648,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/kexec_file.c:1155",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037648,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581116400,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/crash_core.c:576",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:prepare_elf_headers",
        "arch/x86/kernel/crash.c:prepare_elf_headers",
        "arch/x86/kernel/crash.c:prepare_elf_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581116400,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491512616,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/kexec_file.c:1169",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491512616,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284478208,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/kexec_file.c:1169",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284478208,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580241360,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/kexec_file.c:1169",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580241360,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580188912,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/kexec_file.c:1169",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580188912,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580232624,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/kexec_file.c:1169",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580232624,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```

```json
{
  "name": "crash_exclude_mem_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580285600,
      "name": "crash_exclude_mem_range",
      "external": true,
      "loc": "kernel/kexec_file.c:1169",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_load_segments",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries",
        "arch/x86/kernel/crash.c:crash_setup_memmap_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285600,
      "name": "crash_exclude_mem_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int crash_exclude_mem_range(struct crash_mem * mem, long long unsigned int mstart, long long unsigned int mend)
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

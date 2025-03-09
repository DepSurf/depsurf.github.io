# Function: <code>e820__range_update</code>

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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596324799,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:480",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596324799,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602642837,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:500",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602642837,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602812513,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:502",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602812513,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604607560,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:501",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604607560,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604703141,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:515",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604703141,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604715529,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:515",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604715529,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609062169,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:516",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609062169,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612125545,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:530",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612125545,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614265466,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:530",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614265466,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615187553,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:530",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615187553,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616954433,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:530",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616954433,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 49
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627570390,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:530",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627567232,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 49
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619322184,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:530",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619317984,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 49
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621615304,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:530",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621611104,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 49
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604641819,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:515",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604641819,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604609753,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:515",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604609753,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604719611,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:515",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604719611,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```

```json
{
  "name": "e820__range_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604719641,
      "name": "e820__range_update",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:515",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__reserve_setup_data",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:real_trim_memory",
        "arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604719641,
      "name": "e820__range_update",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 34
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
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
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u64 e820__range_update(u64 start, u64 size, enum e820_type old_type, enum e820_type new_type)
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

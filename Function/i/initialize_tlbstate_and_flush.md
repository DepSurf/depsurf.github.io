# Function: <code>initialize_tlbstate_and_flush</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush()
```

```json
{
  "name": "initialize_tlbstate_and_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579347664,
      "name": "initialize_tlbstate_and_flush",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:380",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:restore_processor_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579347664,
      "name": "initialize_tlbstate_and_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
void initialize_tlbstate_and_flush()
```

```json
{
  "name": "initialize_tlbstate_and_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579359360,
      "name": "initialize_tlbstate_and_flush",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:393",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:restore_processor_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359360,
      "name": "initialize_tlbstate_and_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void initialize_tlbstate_and_flush()
```

```json
{
  "name": "initialize_tlbstate_and_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386800,
      "name": "initialize_tlbstate_and_flush",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:481",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:restore_processor_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386800,
      "name": "initialize_tlbstate_and_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void initialize_tlbstate_and_flush()
```

```json
{
  "name": "initialize_tlbstate_and_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "initialize_tlbstate_and_flush",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:482",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403539,
      "name": "initialize_tlbstate_and_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579402288,
      "name": "initialize_tlbstate_and_flush",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush()
```

```json
{
  "name": "initialize_tlbstate_and_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579405552,
      "name": "initialize_tlbstate_and_flush",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:482",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405552,
      "name": "initialize_tlbstate_and_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
void initialize_tlbstate_and_flush()
```

```json
{
  "name": "initialize_tlbstate_and_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579415376,
      "name": "initialize_tlbstate_and_flush",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:658",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579415376,
      "name": "initialize_tlbstate_and_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
void initialize_tlbstate_and_flush()
```

```json
{
  "name": "initialize_tlbstate_and_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579415568,
      "name": "initialize_tlbstate_and_flush",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:617",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579415568,
      "name": "initialize_tlbstate_and_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
void initialize_tlbstate_and_flush()
```

```json
{
  "name": "initialize_tlbstate_and_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579418528,
      "name": "initialize_tlbstate_and_flush",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:624",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418528,
      "name": "initialize_tlbstate_and_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
void initialize_tlbstate_and_flush()
```

```json
{
  "name": "initialize_tlbstate_and_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579481952,
      "name": "initialize_tlbstate_and_flush",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:683",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481952,
      "name": "initialize_tlbstate_and_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
void initialize_tlbstate_and_flush()
```

```json
{
  "name": "initialize_tlbstate_and_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579561040,
      "name": "initialize_tlbstate_and_flush",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:684",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561040,
      "name": "initialize_tlbstate_and_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
void initialize_tlbstate_and_flush()
```

```json
{
  "name": "initialize_tlbstate_and_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668416,
      "name": "initialize_tlbstate_and_flush",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:684",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668416,
      "name": "initialize_tlbstate_and_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
void initialize_tlbstate_and_flush()
```

```json
{
  "name": "initialize_tlbstate_and_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579682304,
      "name": "initialize_tlbstate_and_flush",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:698",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579682304,
      "name": "initialize_tlbstate_and_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void initialize_tlbstate_and_flush()
```

```json
{
  "name": "initialize_tlbstate_and_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716752,
      "name": "initialize_tlbstate_and_flush",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:699",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716752,
      "name": "initialize_tlbstate_and_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void initialize_tlbstate_and_flush()
```

```json
{
  "name": "initialize_tlbstate_and_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579401456,
      "name": "initialize_tlbstate_and_flush",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:482",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579401456,
      "name": "initialize_tlbstate_and_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
void initialize_tlbstate_and_flush()
```

```json
{
  "name": "initialize_tlbstate_and_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579330912,
      "name": "initialize_tlbstate_and_flush",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:482",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:restore_processor_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579330912,
      "name": "initialize_tlbstate_and_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void initialize_tlbstate_and_flush()
```

```json
{
  "name": "initialize_tlbstate_and_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579401376,
      "name": "initialize_tlbstate_and_flush",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:482",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579401376,
      "name": "initialize_tlbstate_and_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
void initialize_tlbstate_and_flush()
```

```json
{
  "name": "initialize_tlbstate_and_flush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579410064,
      "name": "initialize_tlbstate_and_flush",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:482",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410064,
      "name": "initialize_tlbstate_and_flush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void initialize_tlbstate_and_flush()
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void initialize_tlbstate_and_flush()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void initialize_tlbstate_and_flush()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void initialize_tlbstate_and_flush()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void initialize_tlbstate_and_flush()
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

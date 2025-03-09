# Function: <code>__set_phys_to_machine</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578997248,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:658",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578997248,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578994128,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:658",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578994128,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578995968,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:658",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu.c:xen_zap_pfn_range",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578995968,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578967776,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:658",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967776,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578971120,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:645",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578971120,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578973840,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:645",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578973840,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578971984,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:647",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578971984,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578978992,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:654",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578978992,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578981392,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:654",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578981392,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578991584,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:654",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578991584,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578993072,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:650",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578993072,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579001808,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:650",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579001808,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579019488,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:650",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579019488,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579038496,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:650",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038496,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 389
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068048,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:645",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068048,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579067904,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:645",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579067904,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579092992,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:645",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_release_chunk",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/p2m.c:set_foreign_p2m_mapping",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579092992,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490616984,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/arm/xen/p2m.c:169",
      "file": "arch/arm/xen/p2m.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm/xen/p2m.c:clear_foreign_p2m_mapping",
        "arch/arm/xen/p2m.c:set_foreign_p2m_mapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490616768,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578981744,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:654",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578981744,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578981328,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:654",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578981328,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```

```json
{
  "name": "__set_phys_to_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578981920,
      "name": "__set_phys_to_machine",
      "external": true,
      "loc": "arch/x86/xen/p2m.c:654",
      "file": "arch/x86/xen/p2m.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_set_identity_and_remap_chunk",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "arch/x86/xen/mmu_pv.c:xen_zap_pfn_range",
        "drivers/xen/mem-reservation.c:__xenmem_reservation_va_mapping_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578981920,
      "name": "__set_phys_to_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
bool __set_phys_to_machine(long unsigned int pfn, long unsigned int mfn)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

# Function: <code>physid_set_mask_of_physid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578999504,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:142",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579356801,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:142",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071595039890,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:142",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191728,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:142",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578999504,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071579356801,
      "name": "physid_set_mask_of_physid.constprop.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071579191728,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578996432,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:142",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579363677,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:142",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071595205758,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:142",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192112,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:142",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578996432,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071579363677,
      "name": "physid_set_mask_of_physid.constprop.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071579192112,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578998304,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579381748,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071595448645,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203856,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578998304,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071579381748,
      "name": "physid_set_mask_of_physid.constprop.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071579203856,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578960032,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579192284,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071596369547,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201936,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578960032,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071579192284,
      "name": "physid_set_mask_of_physid.constprop.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071579201936,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578963232,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579208104,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071602687674,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217440,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578963232,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071579208104,
      "name": "physid_set_mask_of_physid.constprop.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071579217440,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578965808,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579219497,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071602859121,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579229728,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578965808,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071579219497,
      "name": "physid_set_mask_of_physid.constprop.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071579229728,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578963904,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579243187,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071604656058,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_bsp_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253424,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578963904,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071579243187,
      "name": "physid_set_mask_of_physid.constprop.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071579253424,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578970832,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604743128,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604753246,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267504,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578970832,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071579267504,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578973296,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604756523,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604766873,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269152,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578973296,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071579269152,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578982960,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071609102906,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609112870,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579297072,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578982960,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071579297072,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578984720,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071612167822,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612177631,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302320,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578984720,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071579302320,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578993824,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071614308012,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614318067,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305184,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578993824,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071579305184,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579011200,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071615235632,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615246719,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579353216,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579011200,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071579353216,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579029584,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593838668,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ]
    },
    {
      "addr": 18446744071617023205,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579415424,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579029584,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071593838668,
      "name": "physid_set_mask_of_physid.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071579415424,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579059088,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071627642800,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627658689,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579498192,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579059088,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071579498192,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579058976,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619399280,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619415599,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579510368,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:133",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579058976,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071579510368,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621694368,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:104",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621711127,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:104",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578973648,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604682807,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604693152,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267856,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578973648,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071579267856,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604650361,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604660672,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203280,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203280,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578973232,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604760391,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604770736,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269056,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578973232,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071579269056,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```

```json
{
  "name": "physid_set_mask_of_physid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578973824,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604760622,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:disable_smp",
        "arch/x86/kernel/smpboot.c:disable_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604770993,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:apic_intr_mode_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274656,
      "name": "physid_set_mask_of_physid",
      "external": false,
      "loc": "arch/x86/include/asm/mpspec.h:143",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578973824,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071579274656,
      "name": "physid_set_mask_of_physid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void physid_set_mask_of_physid(int physid, physid_mask_t * map)
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

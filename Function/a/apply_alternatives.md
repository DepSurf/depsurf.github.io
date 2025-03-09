# Function: <code>apply_alternatives</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579066144,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:362",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579066144,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1673
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
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579062544,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:363",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062544,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1677
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
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579062032,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:369",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062032,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1457
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
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579053856,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:369",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579053856,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1374
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
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579062896,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:361",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062896,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1374
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:361",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso_image",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579070052,
      "name": "apply_alternatives.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
    },
    {
      "addr": 18446744071579067312,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 903
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:365",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso_image",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579074676,
      "name": "apply_alternatives.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
    },
    {
      "addr": 18446744071579071920,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 903
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
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:369",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso_image",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579084427,
      "name": "apply_alternatives.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
    },
    {
      "addr": 18446744071579082496,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:369",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso_image",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579086420,
      "name": "apply_alternatives.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
    },
    {
      "addr": 18446744071579084512,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:369",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso_image",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579097818,
      "name": "apply_alternatives.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
    },
    {
      "addr": 18446744071579096336,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 741
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:372",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso_image",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591247865,
      "name": "apply_alternatives.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
    },
    {
      "addr": 18446744071579097600,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:261",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso_image",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591191770,
      "name": "apply_alternatives.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
    },
    {
      "addr": 18446744071579104192,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 839
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:261",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso_image",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592056121,
      "name": "apply_alternatives.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 891
    },
    {
      "addr": 18446744071579128192,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 919
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:265",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso_image",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593823054,
      "name": "apply_alternatives.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1415
    },
    {
      "addr": 18446744071579162496,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579213168,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:266",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213168,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1619
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
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579218704,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:398",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso_image",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579218704,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1387
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
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579248128,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:465",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso_image",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579248128,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1506
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:369",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso_image",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579086772,
      "name": "apply_alternatives.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
    },
    {
      "addr": 18446744071579084864,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:369",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso_image",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579019204,
      "name": "apply_alternatives.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
    },
    {
      "addr": 18446744071579017296,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:369",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso_image",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579086356,
      "name": "apply_alternatives.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
    },
    {
      "addr": 18446744071579084448,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```

```json
{
  "name": "apply_alternatives",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_alternatives",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:369",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso_image",
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090452,
      "name": "apply_alternatives.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
    },
    {
      "addr": 18446744071579088544,
      "name": "apply_alternatives",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void apply_alternatives(struct alt_instr * start, struct alt_instr * end)
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

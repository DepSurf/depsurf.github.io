# Function: <code>apply_paravirt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579067824,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:581",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579067824,
      "name": "apply_paravirt.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071579068160,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595167128,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:582",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064224,
      "name": "apply_paravirt.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    },
    {
      "addr": 18446744071579064560,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595409717,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:588",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579063504,
      "name": "apply_paravirt.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    },
    {
      "addr": 18446744071579063840,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596329119,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:593",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:alternative_instructions"
      ],
      "caller_func": [
        "arch/x86/kernel/alternative.c:alternative_instructions",
        "arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded",
        "arch/x86/kernel/module.c:module_finalize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579055232,
      "name": "apply_paravirt.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071579055584,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064272,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:585",
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
      "addr": 18446744071579064272,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068224,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:585",
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
      "addr": 18446744071579068224,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579072832,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:589",
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
      "addr": 18446744071579072832,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579083264,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:593",
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
      "addr": 18446744071579083264,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579085280,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:593",
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
      "addr": 18446744071579085280,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579097088,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:593",
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
      "addr": 18446744071579097088,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579098352,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:596",
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
      "addr": 18446744071579098352,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579105040,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:492",
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
      "addr": 18446744071579105040,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579129120,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:492",
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
      "addr": 18446744071579129120,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579163840,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:776",
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
      "addr": 18446744071579163840,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579216560,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1230",
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
      "addr": 18446744071579216560,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579222000,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:1421",
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
      "addr": 18446744071579222000,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579085632,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:593",
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
      "addr": 18446744071579085632,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579018064,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:593",
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
      "addr": 18446744071579018064,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579085216,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:593",
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
      "addr": 18446744071579085216,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```

```json
{
  "name": "apply_paravirt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579089312,
      "name": "apply_paravirt",
      "external": true,
      "loc": "arch/x86/kernel/alternative.c:593",
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
      "addr": 18446744071579089312,
      "name": "apply_paravirt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
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
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void apply_paravirt(struct paravirt_patch_site * start, struct paravirt_patch_site * end)
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

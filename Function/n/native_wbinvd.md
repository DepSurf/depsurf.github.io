# Function: <code>native_wbinvd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578958144,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:101",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579256208,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:101",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578958144,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446744071579256208,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578955056,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:139",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579255264,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:139",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578955056,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446744071579255264,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578956896,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:131",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579268816,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:131",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578956896,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446744071579268816,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578969424,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:131",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579265424,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:131",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969424,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446744071579265424,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578972800,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:132",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579075911,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:132",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189177,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:132",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282256,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:132",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578972800,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446744071579282256,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578975552,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:132",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579081319,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:132",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200537,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:132",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293744,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:132",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578975552,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446744071579293744,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578973632,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:132",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579086743,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:132",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189929,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:132",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579224374,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:132",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318736,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:132",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578973632,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    },
    {
      "addr": 18446744071579318736,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578980624,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:141",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579096489,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:141",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579202763,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:141",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579237542,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:141",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333936,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:141",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578980624,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
    },
    {
      "addr": 18446744071579333936,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
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
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578983024,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579098469,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579205018,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239766,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338144,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578983024,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
    },
    {
      "addr": 18446744071579338144,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
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
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578993312,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:128",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579110947,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:128",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225955,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:128",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579263590,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:128",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367872,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:128",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578993312,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
    },
    {
      "addr": 18446744071579367872,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
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
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578995232,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:130",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579110787,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:130",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219907,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:130",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256086,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:130",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366896,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:130",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578995232,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
    },
    {
      "addr": 18446744071579366896,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
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
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579003872,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:130",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579117443,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:130",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222387,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:130",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257526,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:130",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371264,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:130",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579003872,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
    },
    {
      "addr": 18446744071579371264,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
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
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579021568,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579142867,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579261197,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298662,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579432480,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579021568,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
    },
    {
      "addr": 18446744071579432480,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579040128,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579180449,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313067,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579353862,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579501456,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579040128,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    },
    {
      "addr": 18446744071579501456,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
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
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579069776,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579235440,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579378095,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424198,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579598608,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579069776,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    },
    {
      "addr": 18446744071579598608,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 7
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579241346,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387465,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579436150,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596936928,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:pv_native_wbinvd"
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
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579270194,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417959,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579465734,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597862416,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:118",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:pv_native_wbinvd"
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
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578983376,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579098853,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203866,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579238614,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334048,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578983376,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
    },
    {
      "addr": 18446744071579334048,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579031295,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579130081,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138811,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173894,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192659,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/kernel/smpboot.c:hlt_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604679641,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_gart_64.c:gart_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286305,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/tce_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tce_64.c:tce_free",
        "arch/x86/kernel/tce_64.c:tce_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305774,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__cpa_flush_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604700182,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_early_enc_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584373717,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/lib/cache-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/cache-smp.c:__wbinvd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584829781,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_hibernation_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584987880,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "drivers/acpi/acpica/hwesleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584991484,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "drivers/acpi/acpica/hwsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584993582,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "drivers/acpi/acpica/hwxfsleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585070109,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle",
        "drivers/acpi/processor_idle.c:acpi_idle_enter",
        "drivers/acpi/processor_idle.c:acpi_idle_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585572709,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:ipi_handler"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578982960,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579098405,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204938,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239686,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333968,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578982960,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
    },
    {
      "addr": 18446744071579333968,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
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
void native_wbinvd()
```

```json
{
  "name": "native_wbinvd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578983552,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579102853,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210218,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245158,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342320,
      "name": "native_wbinvd",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:127",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578983552,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
    },
    {
      "addr": 18446744071579342320,
      "name": "native_wbinvd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void native_wbinvd()
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
void native_wbinvd()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_wbinvd()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_wbinvd()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_wbinvd()
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
void native_wbinvd()
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

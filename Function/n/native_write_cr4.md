# Function: <code>native_write_cr4</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578958534,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:82",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_write_cr4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161925,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:82",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579256160,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:82",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256160,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578955456,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:82",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_write_cr4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164008,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:82",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256293,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:82",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255216,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578957296,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:74",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_write_cr4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174635,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:74",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269829,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:74",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268768,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578969712,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:74",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174185,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:74",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266392,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:74",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265376,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578973072,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:75",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579283096,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:75",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579282208,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578975845,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:75",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294543,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:75",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293696,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578973925,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:75",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr4"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319199,
      "name": "native_write_cr4",
      "external": false,
      "loc": "arch/x86/include/asm/special_insns.h:75",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318688,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579129968,
      "name": "native_write_cr4",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:391",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr4",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579129968,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579131840,
      "name": "native_write_cr4",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:391",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr4",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579131840,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579148736,
      "name": "native_write_cr4",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:375",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr4",
        "arch/x86/mm/tlb.c:native_flush_tlb_global",
        "arch/x86/mm/tlb.c:native_flush_tlb_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148736,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579145824,
      "name": "native_write_cr4",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:377",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr4",
        "arch/x86/mm/tlb.c:native_flush_tlb_global",
        "arch/x86/mm/tlb.c:native_flush_tlb_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579145824,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579151840,
      "name": "native_write_cr4",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:376",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr4",
        "arch/x86/mm/tlb.c:native_flush_tlb_global",
        "arch/x86/mm/tlb.c:native_flush_tlb_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579151840,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_cr4",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:384",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr4",
        "arch/x86/mm/tlb.c:native_flush_tlb_global",
        "arch/x86/mm/tlb.c:native_flush_tlb_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592061405,
      "name": "native_write_cr4.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579180656,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_cr4",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:440",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel",
        "arch/x86/kernel/head64.c:x86_64_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr4",
        "arch/x86/mm/tlb.c:native_flush_tlb_global",
        "arch/x86/mm/tlb.c:native_flush_tlb_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593827940,
      "name": "native_write_cr4.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579227984,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_cr4",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:441",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head64.c:x86_64_start_kernel",
        "arch/x86/kernel/head64.c:x86_64_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_write_cr4",
        "arch/x86/mm/tlb.c:native_flush_tlb_global",
        "arch/x86/mm/tlb.c:native_flush_tlb_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595960520,
      "name": "native_write_cr4.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579286656,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_cr4",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:429",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr4",
        "arch/x86/kernel/head64.c:x86_64_start_kernel",
        "arch/x86/kernel/head64.c:x86_64_start_kernel",
        "arch/x86/mm/tlb.c:native_flush_tlb_global",
        "arch/x86/mm/tlb.c:native_flush_tlb_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596477827,
      "name": "native_write_cr4.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579293232,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "native_write_cr4",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:410",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr4",
        "arch/x86/kernel/head64.c:x86_64_start_kernel",
        "arch/x86/kernel/head64.c:x86_64_start_kernel",
        "arch/x86/mm/tlb.c:native_flush_tlb_global",
        "arch/x86/mm/tlb.c:native_flush_tlb_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597373607,
      "name": "native_write_cr4.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579322496,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579132224,
      "name": "native_write_cr4",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:391",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr4",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132224,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579063296,
      "name": "native_write_cr4",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:391",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:refresh_pce",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:set_tsc_mode",
        "arch/x86/kernel/process.c:disable_TSC",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:cr4_init",
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global",
        "arch/x86/mm/init.c:cr4_set_bits",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/power/cpu.c:restore_processor_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579063296,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579131776,
      "name": "native_write_cr4",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:391",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr4",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579131776,
      "name": "native_write_cr4",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void native_write_cr4(long unsigned int val)
```

```json
{
  "name": "native_write_cr4",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579136896,
      "name": "native_write_cr4",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:391",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_write_cr4",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579136896,
      "name": "native_write_cr4",
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
void native_write_cr4(long unsigned int val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_write_cr4(long unsigned int val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_write_cr4(long unsigned int val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_write_cr4(long unsigned int val)
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

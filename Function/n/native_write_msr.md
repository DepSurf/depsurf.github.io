# Function: <code>native_write_msr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579161847,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:84",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165581,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:84",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_ucode_in_initrd",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255457,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:84",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_msr(unsigned int msr, unsigned int low, unsigned int high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579163915,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:118",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165801,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:118",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579254593,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:118",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256864,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:118",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256864,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579114010,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:129",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173649,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:129",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579177017,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:129",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579268161,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:129",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270400,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:129",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270400,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579264817,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:145",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267152,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:145",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267152,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579281665,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:146",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579283872,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:146",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579283872,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579293145,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295264,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579295264,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579318457,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320112,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320112,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579333673,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335344,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579335344,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579337913,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579339552,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579339552,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579367401,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368992,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368992,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579366473,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:158",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368000,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:158",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368000,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579371112,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:158",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvmclock_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372384,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:158",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579372384,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579432344,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:158",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvmclock_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579433648,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:158",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433648,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579501352,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:143",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvmclock_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579502528,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:143",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579502528,
      "name": "native_write_msr",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579061162,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:143",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076204,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:143",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_do_write_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579598360,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:143",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvmclock_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579600112,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:143",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600112,
      "name": "native_write_msr",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579061034,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:143",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075705,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:143",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_do_write_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579611048,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:143",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvmclock_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579612816,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:143",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612816,
      "name": "native_write_msr",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579086122,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:143",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579101161,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:143",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_do_write_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579640825,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:143",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvmclock_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579642528,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:143",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642528,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579333817,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335456,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579335456,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578871013,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_pmu_enable_event",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_perf_event_set_period",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_enable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578877181,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_disable_event",
        "arch/x86/events/amd/core.c:amd_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578879727,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_start",
        "arch/x86/events/amd/uncore.c:amd_uncore_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578883057,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/amd/ibs.c:perf_ibs_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578895008,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:core_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_save_and_restart",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:intel_tfa_pmu_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all",
        "arch/x86/events/intel/core.c:__intel_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578914439,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:perf_restore_debug_store",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable_all",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_disable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_pebs_enable",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578915208,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919404,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578922212,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578925346,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578925984,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_buffer",
        "arch/x86/events/intel/pt.c:pt_config_stop",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config",
        "arch/x86/events/intel/pt.c:pt_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578948845,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_rbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_mbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_sbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_bbox_msr_enable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_exit_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_init_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578950485,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:nhm_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:skl_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snb.c:snb_uncore_msr_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578961908,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snr_cha_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:skx_iio_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:hswep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_cbox_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_event",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578964629,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_report_panic_msg",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:set_hv_tscchange_cb",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071578972696,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_eoi_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976287,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:do_arch_prctl_64",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579031953,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:do_arch_prctl_common",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:enable_cpuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053938,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579068733,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment",
        "arch/x86/kernel/cpu/common.c:load_percpu_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579073264,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    },
    {
      "addr": 18446744071579075451,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_syscore_resume",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_offline",
        "arch/x86/kernel/cpu/umwait.c:umwait_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079234,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080880,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579081310,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579085930,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask",
        "arch/x86/kernel/cpu/amd.c:set_dr_addr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088144,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ]
    },
    {
      "addr": 18446744071579088928,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    },
    {
      "addr": 18446744071579099745,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online",
        "arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting",
        "arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks",
        "arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107244,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111632,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118347,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138817,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145187,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:cat_wrmsr",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_intel",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd",
        "arch/x86/kernel/cpu/resctrl/core.c:mba_wrmsr_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579154312,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l2_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:l3_qos_cfg_update",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:__resctrl_sched_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165885,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174125,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:measure_cycles_lat_fn",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194391,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_sync_target",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust"
      ]
    },
    {
      "addr": 18446744071579198074,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline",
        "arch/x86/kernel/apic/apic.c:lapic_next_deadline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579226378,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228129,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239861,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245877,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266085,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_enable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_disable_host_haltpoll",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init"
      ]
    },
    {
      "addr": 18446744071579268345,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock",
        "arch/x86/kernel/kvmclock.c:kvm_get_wallclock"
      ],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock"
      ]
    },
    {
      "addr": 18446744071579287334,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321101,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:pat_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584372926,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584816304,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ]
    },
    {
      "addr": 18446744071587453141,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587462100,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:write_new_vid",
        "drivers/cpufreq/powernow-k8.c:write_new_fid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587472989,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_pstate",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util_hwp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605020077,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_oneshot",
        "drivers/clocksource/hyperv_timer.c:hv_ce_shutdown",
        "drivers/clocksource/hyperv_timer.c:hv_ce_shutdown",
        "drivers/clocksource/hyperv_timer.c:hv_ce_set_next_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587556382,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "drivers/hv/vmbus_drv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/vmbus_drv.c:vmbus_isr",
        "drivers/hv/vmbus_drv.c:vmbus_on_msg_dpc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587560322,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "drivers/hv/hv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/hv.c:hv_synic_disable_regs",
        "drivers/hv/hv.c:hv_synic_disable_regs",
        "drivers/hv/hv.c:hv_synic_disable_regs",
        "drivers/hv/hv.c:hv_synic_disable_regs",
        "drivers/hv/hv.c:hv_synic_enable_regs",
        "drivers/hv/hv.c:hv_synic_enable_regs",
        "drivers/hv/hv.c:hv_synic_enable_regs",
        "drivers/hv/hv.c:hv_synic_enable_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587574903,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "drivers/hv/channel_mgmt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/channel_mgmt.c:vmbus_initiate_unload"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587640383,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587641209,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state",
        "arch/x86/power/cpu.c:restore_processor_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578888160,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071578964080,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579070240,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579088144,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579088928,
      "name": "native_write_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071579193856,
      "name": "native_write_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071579264208,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071579268128,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071584815824,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579333737,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335376,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579335376,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void native_write_msr(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579341993,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown",
        "arch/x86/kernel/kvmclock.c:kvm_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579343728,
      "name": "native_write_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:160",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343728,
      "name": "native_write_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void native_write_msr(unsigned int msr, unsigned int low, unsigned int high)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int low</code> ➡️ <code>u32 low</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int high</code> ➡️ <code>u32 high</code>
</li>
</ul>
</details>
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
void native_write_msr(unsigned int msr, u32 low, u32 high)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_write_msr(unsigned int msr, u32 low, u32 high)
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

# Function: <code>do_trace_read_msr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583448112,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:123",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_read_msr_safe",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:check_current_patch_level",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583448112,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583575760,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:123",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_read_msr_safe",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/amd.c:check_current_patch_level",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583575760,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583614512,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:123",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583614512,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583860512,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:124",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860512,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584061120,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:124",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584061120,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584145248,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:124",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584145248,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584335312,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:124",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584335312,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584469984,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:124",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584469984,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585034432,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:124",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585034432,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585186496,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:124",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585186496,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585068592,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:124",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585068592,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585515328,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:124",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585515328,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586666768,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:124",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666768,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587915216,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:124",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/enlighten_pv.c:xen_do_read_msr",
        "arch/x86/xen/enlighten_pv.c:xen_do_read_msr",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587915216,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588189248,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:130",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/enlighten_pv.c:xen_do_read_msr",
        "arch/x86/xen/enlighten_pv.c:xen_do_read_msr",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588189248,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588481248,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:130",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/enlighten_pv.c:xen_do_read_msr",
        "arch/x86/xen/enlighten_pv.c:xen_do_read_msr",
        "arch/x86/hyperv/ivm.c:hv_snp_boot_ap",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588481248,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584438736,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:124",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584438736,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584375501,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:124",
      "file": "arch/x86/lib/msr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_disable_all",
        "arch/x86/events/core.c:native_read_msr_safe",
        "arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop",
        "arch/x86/events/msr.c:msr_event_start",
        "arch/x86/events/msr.c:msr_event_update",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event",
        "arch/x86/events/intel/core.c:native_read_msr_safe",
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status",
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box",
        "arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read",
        "arch/x86/realmode/init.c:init_real_mode",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/step.c:set_task_blockstep",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/umwait.c:umwait_init",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo",
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz",
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel",
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust",
        "arch/x86/kernel/apic/apic.c:__x2apic_enable",
        "arch/x86/kernel/apic/vector.c:print_local_APIC",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id",
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/kprobes/core.c:resume_execution",
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range",
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:init_cache_modes",
        "kernel/kexec_core.c:crash_save_cpu",
        "kernel/kexec_core.c:crash_save_cpu",
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu",
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt",
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug",
        "drivers/edac/mce_amd.c:amd_decode_mce",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_resume",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show",
        "drivers/hv/vmbus_drv.c:hv_acpi_init",
        "drivers/hv/hv.c:hv_synic_disable_regs",
        "drivers/hv/hv.c:hv_synic_disable_regs",
        "drivers/hv/hv.c:hv_synic_disable_regs",
        "drivers/hv/hv.c:hv_synic_disable_regs",
        "drivers/hv/hv.c:hv_synic_enable_regs",
        "drivers/hv/hv.c:hv_synic_enable_regs",
        "drivers/hv/hv.c:hv_synic_enable_regs",
        "drivers/hv/hv.c:hv_synic_enable_regs",
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h",
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584374512,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584421648,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:124",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584421648,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```

```json
{
  "name": "do_trace_read_msr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584528304,
      "name": "do_trace_read_msr",
      "external": true,
      "loc": "arch/x86/lib/msr.c:124",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr_safe",
        "arch/x86/kernel/paravirt.c:native_read_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584528304,
      "name": "do_trace_read_msr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```
</details>
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
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void do_trace_read_msr(unsigned int msr, u64 val, int failed)
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

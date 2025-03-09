# Function: <code>msr_set_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583152848,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:94",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583152848,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583449120,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:97",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583449120,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583576768,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:97",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583576768,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583615488,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:97",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583615488,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583861488,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:98",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861488,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584062080,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:98",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584062080,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584146208,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:98",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584146208,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584336272,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:98",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584336272,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584470944,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:98",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584470944,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585034784,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:98",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585034784,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585186864,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:98",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585186864,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585068752,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:98",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585068752,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585515488,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:98",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585515488,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586666912,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:98",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666912,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587915376,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:98",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587915376,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588189408,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:102",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588189408,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588481408,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:102",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd_k8",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588481408,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584439696,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:98",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584439696,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584375040,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:98",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584375040,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584422608,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:98",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584422608,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int msr_set_bit(u32 msr, u8 bit)
```

```json
{
  "name": "msr_set_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584528736,
      "name": "msr_set_bit",
      "external": true,
      "loc": "arch/x86/lib/msr.c:98",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688",
        "arch/x86/kernel/amd_nb.c:__fix_erratum_688"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584528736,
      "name": "msr_set_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int msr_set_bit(u32 msr, u8 bit)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int msr_set_bit(u32 msr, u8 bit)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int msr_set_bit(u32 msr, u8 bit)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int msr_set_bit(u32 msr, u8 bit)
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

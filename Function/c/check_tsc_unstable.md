# Function: <code>check_tsc_unstable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579072304,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:332",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579072304,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579068752,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:333",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068752,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579068016,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:334",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/amd.c:early_init_amd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068016,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579059840,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:241",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579059840,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579068896,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:241",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068896,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579073056,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:242",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073056,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077696,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:259",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077696,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579087312,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:259",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579087312,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579089312,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:259",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579089312,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100752,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:266",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100752,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100928,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:266",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100928,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579107536,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:267",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579107536,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579132144,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:267",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132144,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579168000,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:267",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579168000,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579221040,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:267",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221040,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579226464,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:288",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579226464,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579255328,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:288",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255328,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579089664,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:259",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579089664,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579021952,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:259",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579021952,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579089248,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:259",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579089248,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int check_tsc_unstable()
```

```json
{
  "name": "check_tsc_unstable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579093376,
      "name": "check_tsc_unstable",
      "external": true,
      "loc": "arch/x86/kernel/tsc.c:259",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust",
        "arch/x86/kernel/kvmclock.c:kvmclock_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579093376,
      "name": "check_tsc_unstable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int check_tsc_unstable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int check_tsc_unstable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int check_tsc_unstable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int check_tsc_unstable()
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

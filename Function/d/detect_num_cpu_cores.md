# Function: <code>detect_num_cpu_cores</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_num_cpu_cores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579115568,
      "name": "detect_num_cpu_cores",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:590",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579115568,
      "name": "detect_num_cpu_cores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_num_cpu_cores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579121232,
      "name": "detect_num_cpu_cores",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:590",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121232,
      "name": "detect_num_cpu_cores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_num_cpu_cores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579130800,
      "name": "detect_num_cpu_cores",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:654",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579130800,
      "name": "detect_num_cpu_cores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_num_cpu_cores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579132688,
      "name": "detect_num_cpu_cores",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:654",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132688,
      "name": "detect_num_cpu_cores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_num_cpu_cores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579148992,
      "name": "detect_num_cpu_cores",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:659",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148992,
      "name": "detect_num_cpu_cores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_num_cpu_cores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579146080,
      "name": "detect_num_cpu_cores",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:677",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146080,
      "name": "detect_num_cpu_cores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_num_cpu_cores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579152096,
      "name": "detect_num_cpu_cores",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:675",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579152096,
      "name": "detect_num_cpu_cores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_num_cpu_cores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579180976,
      "name": "detect_num_cpu_cores",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:678",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180976,
      "name": "detect_num_cpu_cores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_num_cpu_cores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579228464,
      "name": "detect_num_cpu_cores",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:786",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579228464,
      "name": "detect_num_cpu_cores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_num_cpu_cores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579287024,
      "name": "detect_num_cpu_cores",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:807",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287024,
      "name": "detect_num_cpu_cores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_num_cpu_cores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579293584,
      "name": "detect_num_cpu_cores",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:796",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293584,
      "name": "detect_num_cpu_cores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_num_cpu_cores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579322880,
      "name": "detect_num_cpu_cores",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:793",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322880,
      "name": "detect_num_cpu_cores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_num_cpu_cores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579133072,
      "name": "detect_num_cpu_cores",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:654",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579133072,
      "name": "detect_num_cpu_cores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_num_cpu_cores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064240,
      "name": "detect_num_cpu_cores",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:654",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064240,
      "name": "detect_num_cpu_cores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_num_cpu_cores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579132624,
      "name": "detect_num_cpu_cores",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:654",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132624,
      "name": "detect_num_cpu_cores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```

```json
{
  "name": "detect_num_cpu_cores",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579137744,
      "name": "detect_num_cpu_cores",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:654",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137744,
      "name": "detect_num_cpu_cores",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```
</details>
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
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void detect_num_cpu_cores(struct cpuinfo_x86 * c)
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

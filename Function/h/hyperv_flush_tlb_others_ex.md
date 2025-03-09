# Function: <code>hyperv_flush_tlb_others_ex</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void hyperv_flush_tlb_others_ex(const struct cpumask * cpus, const struct flush_tlb_info * info)
```

```json
{
  "name": "hyperv_flush_tlb_others_ex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579018560,
      "name": "hyperv_flush_tlb_others_ex",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:190",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579018560,
      "name": "hyperv_flush_tlb_others_ex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1161
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
void hyperv_flush_tlb_others_ex(const struct cpumask * cpus, const struct flush_tlb_info * info)
```

```json
{
  "name": "hyperv_flush_tlb_others_ex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579021632,
      "name": "hyperv_flush_tlb_others_ex",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:140",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579021632,
      "name": "hyperv_flush_tlb_others_ex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hyperv_flush_tlb_others_ex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579025413,
      "name": "hyperv_flush_tlb_others_ex",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:162",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hyperv_flush_tlb_others_ex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579033814,
      "name": "hyperv_flush_tlb_others_ex",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:164",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hyperv_flush_tlb_others_ex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579036134,
      "name": "hyperv_flush_tlb_others_ex",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:164",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
u64 hyperv_flush_tlb_others_ex(const struct cpumask * cpus, const struct flush_tlb_info * info)
```

```json
{
  "name": "hyperv_flush_tlb_others_ex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579044960,
      "name": "hyperv_flush_tlb_others_ex",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:164",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044960,
      "name": "hyperv_flush_tlb_others_ex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 899
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
u64 hyperv_flush_tlb_others_ex(const struct cpumask * cpus, const struct flush_tlb_info * info)
```

```json
{
  "name": "hyperv_flush_tlb_others_ex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579048400,
      "name": "hyperv_flush_tlb_others_ex",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:170",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048400,
      "name": "hyperv_flush_tlb_others_ex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 899
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
u64 hyperv_flush_tlb_others_ex(const struct cpumask * cpus, const struct flush_tlb_info * info)
```

```json
{
  "name": "hyperv_flush_tlb_others_ex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579051248,
      "name": "hyperv_flush_tlb_others_ex",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:170",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579051248,
      "name": "hyperv_flush_tlb_others_ex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
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
u64 hyperv_flush_tlb_others_ex(const struct cpumask * cpus, const struct flush_tlb_info * info)
```

```json
{
  "name": "hyperv_flush_tlb_others_ex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hyperv_flush_tlb_others_ex",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:169",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579072112,
      "name": "hyperv_flush_tlb_others_ex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 911
    },
    {
      "addr": 18446744071592050213,
      "name": "hyperv_flush_tlb_others_ex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
u64 hyperv_flush_tlb_others_ex(const struct cpumask * cpus, const struct flush_tlb_info * info)
```

```json
{
  "name": "hyperv_flush_tlb_others_ex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hyperv_flush_tlb_others_ex",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:169",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579097216,
      "name": "hyperv_flush_tlb_others_ex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 925
    },
    {
      "addr": 18446744071593816678,
      "name": "hyperv_flush_tlb_others_ex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
u64 hyperv_flush_tlb_others_ex(const struct cpumask * cpus, const struct flush_tlb_info * info)
```

```json
{
  "name": "hyperv_flush_tlb_others_ex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hyperv_flush_tlb_others_ex",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:169",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579133568,
      "name": "hyperv_flush_tlb_others_ex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
    },
    {
      "addr": 18446744071595958014,
      "name": "hyperv_flush_tlb_others_ex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
u64 hyperv_flush_tlb_others_ex(const struct cpumask * cpus, const struct flush_tlb_info * info)
```

```json
{
  "name": "hyperv_flush_tlb_others_ex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hyperv_flush_tlb_others_ex",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:173",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579134144,
      "name": "hyperv_flush_tlb_others_ex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 991
    },
    {
      "addr": 18446744071596475278,
      "name": "hyperv_flush_tlb_others_ex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
u64 hyperv_flush_tlb_others_ex(const struct cpumask * cpus, const struct flush_tlb_info * info)
```

```json
{
  "name": "hyperv_flush_tlb_others_ex",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hyperv_flush_tlb_others_ex",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:173",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160784,
      "name": "hyperv_flush_tlb_others_ex",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 842
    },
    {
      "addr": 18446744071597370702,
      "name": "hyperv_flush_tlb_others_ex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hyperv_flush_tlb_others_ex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579036486,
      "name": "hyperv_flush_tlb_others_ex",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:164",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hyperv_flush_tlb_others_ex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578969184,
      "name": "hyperv_flush_tlb_others_ex",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:164",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hyperv_flush_tlb_others_ex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579036070,
      "name": "hyperv_flush_tlb_others_ex",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:164",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hyperv_flush_tlb_others_ex",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579039663,
      "name": "hyperv_flush_tlb_others_ex",
      "external": false,
      "loc": "arch/x86/hyperv/mmu.c:164",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void hyperv_flush_tlb_others_ex(const struct cpumask * cpus, const struct flush_tlb_info * info)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void hyperv_flush_tlb_others_ex(const struct cpumask * cpus, const struct flush_tlb_info * info)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
u64 hyperv_flush_tlb_others_ex(const struct cpumask * cpus, const struct flush_tlb_info * info)
```
</details>
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

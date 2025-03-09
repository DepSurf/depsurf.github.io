# Function: <code>__populate_cache_leaves</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579103694,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_cacheinfo.c:923",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579103197,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_cacheinfo.c:923",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579101550,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_cacheinfo.c:942",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579093310,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_cacheinfo.c:943",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579104587,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_cacheinfo.c:947",
      "file": "arch/x86/kernel/cpu/intel_cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_cacheinfo.c:_populate_cache_leaves"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579110224,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:989",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579115888,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1017",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __populate_cache_leaves(unsigned int cpu)
```

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579125168,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1017",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579125168,
      "name": "__populate_cache_leaves",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1071
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
int __populate_cache_leaves(unsigned int cpu)
```

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579127040,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1017",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127040,
      "name": "__populate_cache_leaves",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1071
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
int __populate_cache_leaves(unsigned int cpu)
```

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579143744,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1017",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579143744,
      "name": "__populate_cache_leaves",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
int __populate_cache_leaves(unsigned int cpu)
```

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579140864,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1017",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140864,
      "name": "__populate_cache_leaves",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
int __populate_cache_leaves(unsigned int cpu)
```

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579146944,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1017",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146944,
      "name": "__populate_cache_leaves",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490268920,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/arm64/kernel/cacheinfo.c:81",
      "file": "arch/arm64/kernel/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/cacheinfo.c:_populate_cache_leaves"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271349142,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/riscv/kernel/cacheinfo.c:61",
      "file": "arch/riscv/kernel/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/cacheinfo.c:_populate_cache_leaves"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __populate_cache_leaves(unsigned int cpu)
```

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579127424,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1017",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579127424,
      "name": "__populate_cache_leaves",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1071
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
int __populate_cache_leaves(unsigned int cpu)
```

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579059088,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1017",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579059088,
      "name": "__populate_cache_leaves",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1071
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
int __populate_cache_leaves(unsigned int cpu)
```

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579126976,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1017",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579126976,
      "name": "__populate_cache_leaves",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1071
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
int __populate_cache_leaves(unsigned int cpu)
```

```json
{
  "name": "__populate_cache_leaves",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579132096,
      "name": "__populate_cache_leaves",
      "external": false,
      "loc": "arch/x86/kernel/cpu/cacheinfo.c:1017",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:_populate_cache_leaves"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132096,
      "name": "__populate_cache_leaves",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1071
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int __populate_cache_leaves(unsigned int cpu)
```
</details>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int __populate_cache_leaves(unsigned int cpu)
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
int __populate_cache_leaves(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __populate_cache_leaves(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __populate_cache_leaves(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __populate_cache_leaves(unsigned int cpu)
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

# Function: <code>pat_bp_init</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pat_bp_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579434379,
      "name": "pat_bp_init",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype.c:241",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pat_bp_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579433611,
      "name": "pat_bp_init",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype.c:241",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pat_bp_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579436427,
      "name": "pat_bp_init",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype.c:241",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pat_bp_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579500443,
      "name": "pat_bp_init",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype.c:241",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pat_bp_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579582094,
      "name": "pat_bp_init",
      "external": false,
      "loc": "arch/x86/mm/pat/memtype.c:243",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/memtype.c:pat_init"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void pat_bp_init()
```

```json
{
  "name": "pat_bp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627722240,
      "name": "pat_bp_init",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:254",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_bp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627722240,
      "name": "pat_bp_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 632
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
void pat_bp_init()
```

```json
{
  "name": "pat_bp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619479840,
      "name": "pat_bp_init",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:254",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_bp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619479840,
      "name": "pat_bp_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 589
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
void pat_bp_init()
```

```json
{
  "name": "pat_bp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621776448,
      "name": "pat_bp_init",
      "external": true,
      "loc": "arch/x86/mm/pat/memtype.c:254",
      "file": "arch/x86/mm/pat/memtype.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_bp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621776448,
      "name": "pat_bp_init",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 589
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void pat_bp_init()
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

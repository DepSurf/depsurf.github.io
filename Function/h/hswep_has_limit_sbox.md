# Function: <code>hswep_has_limit_sbox</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hswep_has_limit_sbox",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578981216,
      "name": "hswep_has_limit_sbox",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:2865",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init"
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
  "name": "hswep_has_limit_sbox",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578996688,
      "name": "hswep_has_limit_sbox",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:2885",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init"
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
  "name": "hswep_has_limit_sbox",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579012572,
      "name": "hswep_has_limit_sbox",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:2885",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init"
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
bool hswep_has_limit_sbox(unsigned int device)
```

```json
{
  "name": "hswep_has_limit_sbox",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579026832,
      "name": "hswep_has_limit_sbox",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:2904",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579026832,
      "name": "hswep_has_limit_sbox",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool hswep_has_limit_sbox(unsigned int device)
```

```json
{
  "name": "hswep_has_limit_sbox",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579026912,
      "name": "hswep_has_limit_sbox",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:2894",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579026912,
      "name": "hswep_has_limit_sbox",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool hswep_has_limit_sbox(unsigned int device)
```

```json
{
  "name": "hswep_has_limit_sbox",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579051840,
      "name": "hswep_has_limit_sbox",
      "external": false,
      "loc": "arch/x86/events/intel/uncore_snbep.c:2902",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init",
        "arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579051840,
      "name": "hswep_has_limit_sbox",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool hswep_has_limit_sbox(unsigned int device)
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

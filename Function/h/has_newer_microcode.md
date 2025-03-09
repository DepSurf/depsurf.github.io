# Function: <code>has_newer_microcode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int has_newer_microcode(void * mc, unsigned int csig, int cpf, int new_rev)
```

```json
{
  "name": "has_newer_microcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579164736,
      "name": "has_newer_microcode",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/intel_lib.c:161",
      "file": "arch/x86/kernel/cpu/microcode/intel_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:load_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579164736,
      "name": "has_newer_microcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int has_newer_microcode(void * mc, unsigned int csig, int cpf, int new_rev)
```

```json
{
  "name": "has_newer_microcode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579165136,
      "name": "has_newer_microcode",
      "external": true,
      "loc": "arch/x86/kernel/cpu/microcode/intel_lib.c:176",
      "file": "arch/x86/kernel/cpu/microcode/intel_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:find_microcode_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579165136,
      "name": "has_newer_microcode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579172301,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:92",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579172436,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:92",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579187217,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:96",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579198628,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:96",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579188020,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:96",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579200757,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:93",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579202997,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:93",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579224181,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:93",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579218165,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:93",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579220645,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:93",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579259088,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:93",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579310894,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:79",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579375555,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:51",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579385074,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:51",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579201845,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:93",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579136805,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:93",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579202917,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:93",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
  "name": "has_newer_microcode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579208197,
      "name": "has_newer_microcode",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:93",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:scan_microcode"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int has_newer_microcode(void * mc, unsigned int csig, int cpf, int new_rev)
```
</details>
</li>
</ul>

# Function: <code>__mc_scan_banks</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mc_scan_banks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579149464,
      "name": "__mc_scan_banks",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1107",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
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
  "name": "__mc_scan_banks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579162146,
      "name": "__mc_scan_banks",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1138",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
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
  "name": "__mc_scan_banks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579164614,
      "name": "__mc_scan_banks",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1138",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
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
void __mc_scan_banks(struct mce * m, struct mce * final, long unsigned int * toclear, long unsigned int * valid_banks, int no_way_out, int * worst)
```

```json
{
  "name": "__mc_scan_banks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579182992,
      "name": "__mc_scan_banks",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1105",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579182992,
      "name": "__mc_scan_banks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 742
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
void __mc_scan_banks(struct mce * m, struct pt_regs * regs, struct mce * final, long unsigned int * toclear, long unsigned int * valid_banks, int no_way_out, int * worst)
```

```json
{
  "name": "__mc_scan_banks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579179568,
      "name": "__mc_scan_banks",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1171",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579179568,
      "name": "__mc_scan_banks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 752
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
void __mc_scan_banks(struct mce * m, struct pt_regs * regs, struct mce * final, long unsigned int * toclear, long unsigned int * valid_banks, int no_way_out, int * worst)
```

```json
{
  "name": "__mc_scan_banks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579185664,
      "name": "__mc_scan_banks",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1183",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579185664,
      "name": "__mc_scan_banks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 752
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
void __mc_scan_banks(struct mce * m, struct pt_regs * regs, struct mce * final, long unsigned int * toclear, long unsigned int * valid_banks, int no_way_out, int * worst)
```

```json
{
  "name": "__mc_scan_banks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579219968,
      "name": "__mc_scan_banks",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1203",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219968,
      "name": "__mc_scan_banks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 752
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mc_scan_banks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594664901,
      "name": "__mc_scan_banks",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1223",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
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
  "name": "__mc_scan_banks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596398989,
      "name": "__mc_scan_banks",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1223",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
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
  "name": "__mc_scan_banks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596930106,
      "name": "__mc_scan_banks",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1232",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mc_scan_banks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597855834,
      "name": "__mc_scan_banks",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1263",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
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
  "name": "__mc_scan_banks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579164966,
      "name": "__mc_scan_banks",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1138",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
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
  "name": "__mc_scan_banks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579096566,
      "name": "__mc_scan_banks",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1138",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
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
  "name": "__mc_scan_banks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579164534,
      "name": "__mc_scan_banks",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1138",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
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
  "name": "__mc_scan_banks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579169718,
      "name": "__mc_scan_banks",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:1138",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __mc_scan_banks(struct mce * m, struct mce * final, long unsigned int * toclear, long unsigned int * valid_banks, int no_way_out, int * worst)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pt_regs * regs</code>
</li>
<li>
<b>Param reordered. </b>
<code>m, final, toclear, valid_banks, no_way_out, worst</code> ➡️ <code>m, regs, final, toclear, valid_banks, no_way_out, worst</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void __mc_scan_banks(struct mce * m, struct pt_regs * regs, struct mce * final, long unsigned int * toclear, long unsigned int * valid_banks, int no_way_out, int * worst)
```
</details>
</li>
</ul>

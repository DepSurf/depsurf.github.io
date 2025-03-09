# Function: <code>force_sig_info_umip_fault</code>

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
void force_sig_info_umip_fault(void * addr, struct pt_regs * regs)
```

```json
{
  "name": "force_sig_info_umip_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579292701,
      "name": "force_sig_info_umip_fault",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:272",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579292701,
      "name": "force_sig_info_umip_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void force_sig_info_umip_fault(void * addr, struct pt_regs * regs)
```

```json
{
  "name": "force_sig_info_umip_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579303376,
      "name": "force_sig_info_umip_fault",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:272",
      "file": "arch/x86/kernel/umip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579303376,
      "name": "force_sig_info_umip_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
  "name": "force_sig_info_umip_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579329071,
      "name": "force_sig_info_umip_fault",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:272",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
  "name": "force_sig_info_umip_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579344351,
      "name": "force_sig_info_umip_fault",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:272",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
  "name": "force_sig_info_umip_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579348669,
      "name": "force_sig_info_umip_fault",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:283",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
  "name": "force_sig_info_umip_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579378381,
      "name": "force_sig_info_umip_fault",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:283",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
  "name": "force_sig_info_umip_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579377241,
      "name": "force_sig_info_umip_fault",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:301",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
  "name": "force_sig_info_umip_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579380857,
      "name": "force_sig_info_umip_fault",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:301",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
  "name": "force_sig_info_umip_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579442479,
      "name": "force_sig_info_umip_fault",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:301",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
  "name": "force_sig_info_umip_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579512651,
      "name": "force_sig_info_umip_fault",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:301",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
  "name": "force_sig_info_umip_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579611675,
      "name": "force_sig_info_umip_fault",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:301",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
  "name": "force_sig_info_umip_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579624280,
      "name": "force_sig_info_umip_fault",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:301",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
  "name": "force_sig_info_umip_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579653336,
      "name": "force_sig_info_umip_fault",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:301",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
  "name": "force_sig_info_umip_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579344573,
      "name": "force_sig_info_umip_fault",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:283",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
  "name": "force_sig_info_umip_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579276786,
      "name": "force_sig_info_umip_fault",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:283",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
  "name": "force_sig_info_umip_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579344493,
      "name": "force_sig_info_umip_fault",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:283",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
  "name": "force_sig_info_umip_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579352941,
      "name": "force_sig_info_umip_fault",
      "external": false,
      "loc": "arch/x86/kernel/umip.c:283",
      "file": "arch/x86/kernel/umip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:fixup_umip_exception"
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
void force_sig_info_umip_fault(void * addr, struct pt_regs * regs)
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
void force_sig_info_umip_fault(void * addr, struct pt_regs * regs)
```
</details>
</li>
</ul>

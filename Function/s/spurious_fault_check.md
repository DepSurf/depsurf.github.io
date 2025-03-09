# Function: <code>spurious_fault_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int spurious_fault_check(long unsigned int error_code, pte_t * pte)
```

```json
{
  "name": "spurious_fault_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579279792,
      "name": "spurious_fault_check",
      "external": false,
      "loc": "arch/x86/mm/fault.c:919",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579279792,
      "name": "spurious_fault_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spurious_fault_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579279105,
      "name": "spurious_fault_check",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1011",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault"
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
  "name": "spurious_fault_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579294369,
      "name": "spurious_fault_check",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1042",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault"
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
  "name": "spurious_fault_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579293649,
      "name": "spurious_fault_check",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1083",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int spurious_fault_check(long unsigned int error_code, pte_t * pte)
```

```json
{
  "name": "spurious_fault_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579311136,
      "name": "spurious_fault_check",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1062",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311136,
      "name": "spurious_fault_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
int spurious_fault_check(long unsigned int error_code, pte_t * pte)
```

```json
{
  "name": "spurious_fault_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579322896,
      "name": "spurious_fault_check",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1034",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:spurious_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322896,
      "name": "spurious_fault_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int spurious_fault_check(long unsigned int error_code, pte_t * pte)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int spurious_fault_check(long unsigned int error_code, pte_t * pte)
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
int spurious_fault_check(long unsigned int error_code, pte_t * pte)
```
</details>
</li>
</ul>

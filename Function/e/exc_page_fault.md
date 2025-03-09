# Function: <code>exc_page_fault</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void exc_page_fault(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "exc_page_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591163360,
      "name": "exc_page_fault",
      "external": true,
      "loc": "arch/x86/mm/fault.c:1511",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591163360,
      "name": "exc_page_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
void exc_page_fault(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "exc_page_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591658608,
      "name": "exc_page_fault",
      "external": true,
      "loc": "arch/x86/mm/fault.c:1469",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591658608,
      "name": "exc_page_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void exc_page_fault(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "exc_page_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591602272,
      "name": "exc_page_fault",
      "external": true,
      "loc": "arch/x86/mm/fault.c:1487",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591602272,
      "name": "exc_page_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
void exc_page_fault(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "exc_page_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592775248,
      "name": "exc_page_fault",
      "external": true,
      "loc": "arch/x86/mm/fault.c:1497",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592775248,
      "name": "exc_page_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
void exc_page_fault(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "exc_page_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594672592,
      "name": "exc_page_fault",
      "external": true,
      "loc": "arch/x86/mm/fault.c:1496",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594672592,
      "name": "exc_page_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
void exc_page_fault(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "exc_page_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596407232,
      "name": "exc_page_fault",
      "external": true,
      "loc": "arch/x86/mm/fault.c:1531",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596407232,
      "name": "exc_page_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
void exc_page_fault(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "exc_page_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596938944,
      "name": "exc_page_fault",
      "external": true,
      "loc": "arch/x86/mm/fault.c:1498",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596938944,
      "name": "exc_page_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
void exc_page_fault(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "exc_page_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597864512,
      "name": "exc_page_fault",
      "external": true,
      "loc": "arch/x86/mm/fault.c:1510",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597864512,
      "name": "exc_page_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void exc_page_fault(struct pt_regs * regs, long unsigned int error_code)
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

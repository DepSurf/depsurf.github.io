# Function: <code>kfence_handle_page_fault</code>

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
  "name": "kfence_handle_page_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "kfence_handle_page_fault",
      "external": false,
      "loc": "include/linux/kfence.h:215",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool kfence_handle_page_fault(long unsigned int addr, bool is_write, struct pt_regs * regs)
```

```json
{
  "name": "kfence_handle_page_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kfence_handle_page_fault",
      "external": true,
      "loc": "mm/kfence/core.c:819",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:page_fault_oops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592222378,
      "name": "kfence_handle_page_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582238960,
      "name": "kfence_handle_page_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 715
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
bool kfence_handle_page_fault(long unsigned int addr, bool is_write, struct pt_regs * regs)
```

```json
{
  "name": "kfence_handle_page_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kfence_handle_page_fault",
      "external": true,
      "loc": "mm/kfence/core.c:1087",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:page_fault_oops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594001444,
      "name": "kfence_handle_page_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582711024,
      "name": "kfence_handle_page_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
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
bool kfence_handle_page_fault(long unsigned int addr, bool is_write, struct pt_regs * regs)
```

```json
{
  "name": "kfence_handle_page_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kfence_handle_page_fault",
      "external": true,
      "loc": "mm/kfence/core.c:1073",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:page_fault_oops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596046679,
      "name": "kfence_handle_page_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583236848,
      "name": "kfence_handle_page_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 842
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
bool kfence_handle_page_fault(long unsigned int addr, bool is_write, struct pt_regs * regs)
```

```json
{
  "name": "kfence_handle_page_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kfence_handle_page_fault",
      "external": true,
      "loc": "mm/kfence/core.c:1111",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:page_fault_oops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596569227,
      "name": "kfence_handle_page_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583456384,
      "name": "kfence_handle_page_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 795
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
bool kfence_handle_page_fault(long unsigned int addr, bool is_write, struct pt_regs * regs)
```

```json
{
  "name": "kfence_handle_page_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kfence_handle_page_fault",
      "external": true,
      "loc": "mm/kfence/core.c:1157",
      "file": "mm/kfence/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:page_fault_oops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597473347,
      "name": "kfence_handle_page_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071583649504,
      "name": "kfence_handle_page_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool kfence_handle_page_fault(long unsigned int addr, bool is_write, struct pt_regs * regs)
```
</details>
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

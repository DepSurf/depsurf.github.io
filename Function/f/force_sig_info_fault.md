# Function: <code>force_sig_info_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void force_sig_info_fault(int si_signo, int si_code, long unsigned int address, struct task_struct * tsk, int fault)
```

```json
{
  "name": "force_sig_info_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579279648,
      "name": "force_sig_info_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:171",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:mm_fault_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579279648,
      "name": "force_sig_info_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void force_sig_info_fault(int si_signo, int si_code, long unsigned int address, struct task_struct * tsk, struct vm_area_struct * vma, int fault)
```

```json
{
  "name": "force_sig_info_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579279456,
      "name": "force_sig_info_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:225",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579279456,
      "name": "force_sig_info_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void force_sig_info_fault(int si_signo, int si_code, long unsigned int address, struct task_struct * tsk, struct vm_area_struct * vma, int fault)
```

```json
{
  "name": "force_sig_info_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579294720,
      "name": "force_sig_info_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:225",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294720,
      "name": "force_sig_info_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void force_sig_info_fault(int si_signo, int si_code, long unsigned int address, struct task_struct * tsk, struct vm_area_struct * vma, int fault)
```

```json
{
  "name": "force_sig_info_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291952,
      "name": "force_sig_info_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:226",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291952,
      "name": "force_sig_info_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void force_sig_info_fault(int si_signo, int si_code, long unsigned int address, struct task_struct * tsk, u32 * pkey, int fault)
```

```json
{
  "name": "force_sig_info_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579311760,
      "name": "force_sig_info_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:206",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311760,
      "name": "force_sig_info_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
void force_sig_info_fault(int si_signo, int si_code, long unsigned int address, struct task_struct * tsk, u32 * pkey, int fault)
```

```json
{
  "name": "force_sig_info_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579323536,
      "name": "force_sig_info_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:206",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579323536,
      "name": "force_sig_info_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>si_signo, si_code, address, tsk, fault</code> ➡️ <code>si_signo, si_code, address, tsk, vma, fault</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 * pkey</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * vma</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void force_sig_info_fault(int si_signo, int si_code, long unsigned int address, struct task_struct * tsk, u32 * pkey, int fault)
```
</details>
</li>
</ul>

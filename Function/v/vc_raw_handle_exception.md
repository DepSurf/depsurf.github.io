# Function: <code>vc_raw_handle_exception</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
bool vc_raw_handle_exception(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "vc_raw_handle_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vc_raw_handle_exception",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1322",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:user_exc_vmm_communication",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579389296,
      "name": "vc_raw_handle_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
    },
    {
      "addr": 18446744071591207634,
      "name": "vc_raw_handle_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool vc_raw_handle_exception(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "vc_raw_handle_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vc_raw_handle_exception",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1318",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:user_exc_vmm_communication",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579451184,
      "name": "vc_raw_handle_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
    },
    {
      "addr": 18446744071592081173,
      "name": "vc_raw_handle_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
bool vc_raw_handle_exception(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "vc_raw_handle_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vc_raw_handle_exception",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1864",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:user_exc_vmm_communication",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525008,
      "name": "vc_raw_handle_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
    },
    {
      "addr": 18446744071593848633,
      "name": "vc_raw_handle_exception.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
bool vc_raw_handle_exception(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "vc_raw_handle_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579625168,
      "name": "vc_raw_handle_exception",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1864",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:user_exc_vmm_communication",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625168,
      "name": "vc_raw_handle_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
bool vc_raw_handle_exception(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "vc_raw_handle_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579639104,
      "name": "vc_raw_handle_exception",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1821",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:user_exc_vmm_communication",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579639104,
      "name": "vc_raw_handle_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
bool vc_raw_handle_exception(struct pt_regs * regs, long unsigned int error_code)
```

```json
{
  "name": "vc_raw_handle_exception",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579668992,
      "name": "vc_raw_handle_exception",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1859",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:user_exc_vmm_communication",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579668992,
      "name": "vc_raw_handle_exception",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
bool vc_raw_handle_exception(struct pt_regs * regs, long unsigned int error_code)
```
</details>
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

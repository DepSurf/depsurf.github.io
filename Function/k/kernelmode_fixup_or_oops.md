# Function: <code>kernelmode_fixup_or_oops</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void kernelmode_fixup_or_oops(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, int signal, int si_code)
```

```json
{
  "name": "kernelmode_fixup_or_oops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579403792,
      "name": "kernelmode_fixup_or_oops",
      "external": false,
      "loc": "arch/x86/mm/fault.c:712",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403792,
      "name": "kernelmode_fixup_or_oops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
void kernelmode_fixup_or_oops(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, int signal, int si_code, u32 pkey)
```

```json
{
  "name": "kernelmode_fixup_or_oops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579466272,
      "name": "kernelmode_fixup_or_oops",
      "external": false,
      "loc": "arch/x86/mm/fault.c:712",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579466272,
      "name": "kernelmode_fixup_or_oops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void kernelmode_fixup_or_oops(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, int signal, int si_code, u32 pkey)
```

```json
{
  "name": "kernelmode_fixup_or_oops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542928,
      "name": "kernelmode_fixup_or_oops",
      "external": false,
      "loc": "arch/x86/mm/fault.c:712",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542928,
      "name": "kernelmode_fixup_or_oops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
void kernelmode_fixup_or_oops(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, int signal, int si_code, u32 pkey)
```

```json
{
  "name": "kernelmode_fixup_or_oops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579648112,
      "name": "kernelmode_fixup_or_oops",
      "external": false,
      "loc": "arch/x86/mm/fault.c:733",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579648112,
      "name": "kernelmode_fixup_or_oops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
void kernelmode_fixup_or_oops(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, int signal, int si_code, u32 pkey)
```

```json
{
  "name": "kernelmode_fixup_or_oops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579662512,
      "name": "kernelmode_fixup_or_oops",
      "external": false,
      "loc": "arch/x86/mm/fault.c:713",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662512,
      "name": "kernelmode_fixup_or_oops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
void kernelmode_fixup_or_oops(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, int signal, int si_code, u32 pkey)
```

```json
{
  "name": "kernelmode_fixup_or_oops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579696512,
      "name": "kernelmode_fixup_or_oops",
      "external": false,
      "loc": "arch/x86/mm/fault.c:713",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579696512,
      "name": "kernelmode_fixup_or_oops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
void kernelmode_fixup_or_oops(struct pt_regs * regs, long unsigned int error_code, long unsigned int address, int signal, int si_code)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 pkey</code>
</li>
</ul>
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

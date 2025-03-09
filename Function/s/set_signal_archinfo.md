# Function: <code>set_signal_archinfo</code>

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
  "name": "set_signal_archinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579352336,
      "name": "set_signal_archinfo",
      "external": false,
      "loc": "arch/x86/mm/fault.c:722",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
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
  "name": "set_signal_archinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579367237,
      "name": "set_signal_archinfo",
      "external": false,
      "loc": "arch/x86/mm/fault.c:684",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
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
  "name": "set_signal_archinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579371477,
      "name": "set_signal_archinfo",
      "external": false,
      "loc": "arch/x86/mm/fault.c:706",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
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
void set_signal_archinfo(long unsigned int address, long unsigned int error_code)
```

```json
{
  "name": "set_signal_archinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579395728,
      "name": "set_signal_archinfo",
      "external": false,
      "loc": "arch/x86/mm/fault.c:670",
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
      "addr": 18446744071579395728,
      "name": "set_signal_archinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_signal_archinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579402090,
      "name": "set_signal_archinfo",
      "external": false,
      "loc": "arch/x86/mm/fault.c:629",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
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
  "name": "set_signal_archinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579406418,
      "name": "set_signal_archinfo",
      "external": false,
      "loc": "arch/x86/mm/fault.c:620",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops"
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
  "name": "set_signal_archinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579468954,
      "name": "set_signal_archinfo",
      "external": false,
      "loc": "arch/x86/mm/fault.c:621",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops"
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
  "name": "set_signal_archinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579545843,
      "name": "set_signal_archinfo",
      "external": false,
      "loc": "arch/x86/mm/fault.c:621",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops"
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
  "name": "set_signal_archinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579651573,
      "name": "set_signal_archinfo",
      "external": false,
      "loc": "arch/x86/mm/fault.c:642",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops"
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
  "name": "set_signal_archinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579665715,
      "name": "set_signal_archinfo",
      "external": false,
      "loc": "arch/x86/mm/fault.c:622",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops"
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
  "name": "set_signal_archinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579699684,
      "name": "set_signal_archinfo",
      "external": false,
      "loc": "arch/x86/mm/fault.c:622",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops"
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
  "name": "set_signal_archinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579367381,
      "name": "set_signal_archinfo",
      "external": false,
      "loc": "arch/x86/mm/fault.c:706",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
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
  "name": "set_signal_archinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579297861,
      "name": "set_signal_archinfo",
      "external": false,
      "loc": "arch/x86/mm/fault.c:706",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
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
  "name": "set_signal_archinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579367301,
      "name": "set_signal_archinfo",
      "external": false,
      "loc": "arch/x86/mm/fault.c:706",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
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
  "name": "set_signal_archinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579375733,
      "name": "set_signal_archinfo",
      "external": false,
      "loc": "arch/x86/mm/fault.c:706",
      "file": "arch/x86/mm/fault.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
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
void set_signal_archinfo(long unsigned int address, long unsigned int error_code)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void set_signal_archinfo(long unsigned int address, long unsigned int error_code)
```
</details>
</li>
</ul>

# Function: <code>get_kernel_gp_address</code>

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
enum kernel_gp_hint get_kernel_gp_address(struct pt_regs * regs, long unsigned int * addr)
```

```json
{
  "name": "get_kernel_gp_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579058432,
      "name": "get_kernel_gp_address",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:491",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579058432,
      "name": "get_kernel_gp_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
enum kernel_gp_hint get_kernel_gp_address(struct pt_regs * regs, long unsigned int * addr)
```

```json
{
  "name": "get_kernel_gp_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579060992,
      "name": "get_kernel_gp_address",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:496",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579060992,
      "name": "get_kernel_gp_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
enum kernel_gp_hint get_kernel_gp_address(struct pt_regs * regs, long unsigned int * addr)
```

```json
{
  "name": "get_kernel_gp_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579067776,
      "name": "get_kernel_gp_address",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:496",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579067776,
      "name": "get_kernel_gp_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
enum kernel_gp_hint get_kernel_gp_address(struct pt_regs * regs, long unsigned int * addr)
```

```json
{
  "name": "get_kernel_gp_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579088928,
      "name": "get_kernel_gp_address",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:497",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088928,
      "name": "get_kernel_gp_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
enum kernel_gp_hint get_kernel_gp_address(struct pt_regs * regs, long unsigned int * addr)
```

```json
{
  "name": "get_kernel_gp_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579117216,
      "name": "get_kernel_gp_address",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:574",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579117216,
      "name": "get_kernel_gp_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
enum kernel_gp_hint get_kernel_gp_address(struct pt_regs * regs, long unsigned int * addr)
```

```json
{
  "name": "get_kernel_gp_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579156528,
      "name": "get_kernel_gp_address",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:583",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156528,
      "name": "get_kernel_gp_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
enum kernel_gp_hint get_kernel_gp_address(struct pt_regs * regs, long unsigned int * addr)
```

```json
{
  "name": "get_kernel_gp_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579158688,
      "name": "get_kernel_gp_address",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:583",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579158688,
      "name": "get_kernel_gp_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
enum kernel_gp_hint get_kernel_gp_address(struct pt_regs * regs, long unsigned int * addr)
```

```json
{
  "name": "get_kernel_gp_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579188000,
      "name": "get_kernel_gp_address",
      "external": false,
      "loc": "arch/x86/kernel/traps.c:497",
      "file": "arch/x86/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:exc_general_protection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188000,
      "name": "get_kernel_gp_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
enum kernel_gp_hint get_kernel_gp_address(struct pt_regs * regs, long unsigned int * addr)
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

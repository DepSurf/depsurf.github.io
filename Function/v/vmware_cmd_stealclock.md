# Function: <code>vmware_cmd_stealclock</code>

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
int vmware_cmd_stealclock(uint32_t arg1, uint32_t arg2)
```

```json
{
  "name": "vmware_cmd_stealclock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579268736,
      "name": "vmware_cmd_stealclock",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:167",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup",
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_down_prepare",
        "arch/x86/kernel/cpu/vmware.c:vmware_pv_guest_cpu_reboot",
        "arch/x86/kernel/cpu/vmware.c:vmware_register_steal_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268736,
      "name": "vmware_cmd_stealclock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
int vmware_cmd_stealclock(uint32_t arg1, uint32_t arg2)
```

```json
{
  "name": "vmware_cmd_stealclock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579275968,
      "name": "vmware_cmd_stealclock",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:168",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_paravirt_ops_setup",
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_down_prepare",
        "arch/x86/kernel/cpu/vmware.c:vmware_pv_guest_cpu_reboot",
        "arch/x86/kernel/cpu/vmware.c:vmware_register_steal_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275968,
      "name": "vmware_cmd_stealclock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
int vmware_cmd_stealclock(uint32_t arg1, uint32_t arg2)
```

```json
{
  "name": "vmware_cmd_stealclock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579278672,
      "name": "vmware_cmd_stealclock",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:169",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_down_prepare",
        "arch/x86/kernel/cpu/vmware.c:vmware_pv_guest_cpu_reboot",
        "arch/x86/kernel/cpu/vmware.c:vmware_register_steal_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579278672,
      "name": "vmware_cmd_stealclock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
int vmware_cmd_stealclock(uint32_t arg1, uint32_t arg2)
```

```json
{
  "name": "vmware_cmd_stealclock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579321392,
      "name": "vmware_cmd_stealclock",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:169",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_down_prepare",
        "arch/x86/kernel/cpu/vmware.c:vmware_pv_guest_cpu_reboot",
        "arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579321392,
      "name": "vmware_cmd_stealclock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
int vmware_cmd_stealclock(uint32_t arg1, uint32_t arg2)
```

```json
{
  "name": "vmware_cmd_stealclock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579380864,
      "name": "vmware_cmd_stealclock",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:169",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_down_prepare",
        "arch/x86/kernel/cpu/vmware.c:vmware_pv_guest_cpu_reboot",
        "arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579380864,
      "name": "vmware_cmd_stealclock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int vmware_cmd_stealclock(uint32_t arg1, uint32_t arg2)
```

```json
{
  "name": "vmware_cmd_stealclock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579457392,
      "name": "vmware_cmd_stealclock",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:169",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_down_prepare",
        "arch/x86/kernel/cpu/vmware.c:vmware_pv_guest_cpu_reboot",
        "arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579457392,
      "name": "vmware_cmd_stealclock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int vmware_cmd_stealclock(uint32_t arg1, uint32_t arg2)
```

```json
{
  "name": "vmware_cmd_stealclock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579469536,
      "name": "vmware_cmd_stealclock",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:169",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_down_prepare",
        "arch/x86/kernel/cpu/vmware.c:vmware_pv_guest_cpu_reboot",
        "arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579469536,
      "name": "vmware_cmd_stealclock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int vmware_cmd_stealclock(uint32_t arg1, uint32_t arg2)
```

```json
{
  "name": "vmware_cmd_stealclock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579499648,
      "name": "vmware_cmd_stealclock",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:169",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_down_prepare",
        "arch/x86/kernel/cpu/vmware.c:vmware_pv_guest_cpu_reboot",
        "arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579499648,
      "name": "vmware_cmd_stealclock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int vmware_cmd_stealclock(uint32_t arg1, uint32_t arg2)
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

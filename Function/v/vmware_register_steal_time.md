# Function: <code>vmware_register_steal_time</code>

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
void vmware_register_steal_time()
```

```json
{
  "name": "vmware_register_steal_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579268864,
      "name": "vmware_register_steal_time",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:243",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_online",
        "arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268864,
      "name": "vmware_register_steal_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void vmware_register_steal_time()
```

```json
{
  "name": "vmware_register_steal_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276480,
      "name": "vmware_register_steal_time",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:244",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_online",
        "arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276480,
      "name": "vmware_register_steal_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void vmware_register_steal_time()
```

```json
{
  "name": "vmware_register_steal_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579279168,
      "name": "vmware_register_steal_time",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:245",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_online",
        "arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579279168,
      "name": "vmware_register_steal_time",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vmware_register_steal_time",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579321857,
      "name": "vmware_register_steal_time",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:245",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init"
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
  "name": "vmware_register_steal_time",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579381385,
      "name": "vmware_register_steal_time",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:245",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init"
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
  "name": "vmware_register_steal_time",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579457961,
      "name": "vmware_register_steal_time",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:245",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init"
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
  "name": "vmware_register_steal_time",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579470320,
      "name": "vmware_register_steal_time",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:245",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init"
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
  "name": "vmware_register_steal_time",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579500432,
      "name": "vmware_register_steal_time",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:245",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_guest_cpu_init"
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
void vmware_register_steal_time()
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void vmware_register_steal_time()
```
</details>
</li>
</ul>

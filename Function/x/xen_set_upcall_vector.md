# Function: <code>xen_set_upcall_vector</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xen_set_upcall_vector(unsigned int cpu)
```

```json
{
  "name": "xen_set_upcall_vector",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071628040529,
      "name": "xen_set_upcall_vector",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:2224",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_setup_upcall_vector",
        "drivers/xen/events/events_base.c:xen_init_setup_upcall_vector"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589471712,
      "name": "xen_set_upcall_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xen_set_upcall_vector(unsigned int cpu)
```

```json
{
  "name": "xen_set_upcall_vector",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619806017,
      "name": "xen_set_upcall_vector",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:2221",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_setup_upcall_vector",
        "drivers/xen/events/events_base.c:xen_init_setup_upcall_vector"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589771632,
      "name": "xen_set_upcall_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int xen_set_upcall_vector(unsigned int cpu)
```

```json
{
  "name": "xen_set_upcall_vector",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622114497,
      "name": "xen_set_upcall_vector",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:2198",
      "file": "drivers/xen/events/events_base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:xen_init_setup_upcall_vector",
        "drivers/xen/events/events_base.c:xen_init_setup_upcall_vector"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm",
        "arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590107664,
      "name": "xen_set_upcall_vector",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int xen_set_upcall_vector(unsigned int cpu)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

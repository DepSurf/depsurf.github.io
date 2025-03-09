# Function: <code>register_vmcore_cb</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void register_vmcore_cb(struct vmcore_cb * cb)
```

```json
{
  "name": "register_vmcore_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_vmcore_cb",
      "external": true,
      "loc": "fs/proc/vmcore.c:73",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops",
        "arch/x86/kernel/aperture_64.c:exclude_from_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594029531,
      "name": "register_vmcore_cb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071583759344,
      "name": "register_vmcore_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void register_vmcore_cb(struct vmcore_cb * cb)
```

```json
{
  "name": "register_vmcore_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_vmcore_cb",
      "external": true,
      "loc": "fs/proc/vmcore.c:72",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops",
        "arch/x86/kernel/aperture_64.c:exclude_from_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596063598,
      "name": "register_vmcore_cb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584375744,
      "name": "register_vmcore_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void register_vmcore_cb(struct vmcore_cb * cb)
```

```json
{
  "name": "register_vmcore_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_vmcore_cb",
      "external": true,
      "loc": "fs/proc/vmcore.c:72",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops",
        "arch/x86/kernel/aperture_64.c:exclude_from_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596587516,
      "name": "register_vmcore_cb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584604032,
      "name": "register_vmcore_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void register_vmcore_cb(struct vmcore_cb * cb)
```

```json
{
  "name": "register_vmcore_cb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_vmcore_cb",
      "external": true,
      "loc": "fs/proc/vmcore.c:72",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops",
        "arch/x86/kernel/aperture_64.c:exclude_from_core",
        "drivers/firmware/efi/unaccepted_memory.c:unaccepted_memory_init_kdump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597493344,
      "name": "register_vmcore_cb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584836032,
      "name": "register_vmcore_cb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void register_vmcore_cb(struct vmcore_cb * cb)
```
</details>
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

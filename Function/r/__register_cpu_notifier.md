# Function: <code>__register_cpu_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __register_cpu_notifier(struct notifier_block * nb)
```

```json
{
  "name": "__register_cpu_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579374192,
      "name": "__register_cpu_notifier",
      "external": true,
      "loc": "kernel/cpu.c:205",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:init_vdso",
        "arch/x86/events/amd/uncore.c:amd_uncore_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/intel/rapl.c:rapl_pmu_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "kernel/profile.c:create_proc_profile",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "kernel/events/core.c:perf_event_init",
        "mm/vmstat.c:setup_vmstat",
        "mm/zswap.c:zswap_pool_create",
        "mm/zswap.c:init_zswap",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "net/core/flow.c:flow_cache_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374192,
      "name": "__register_cpu_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int __register_cpu_notifier(struct notifier_block * nb)
```

```json
{
  "name": "__register_cpu_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579383792,
      "name": "__register_cpu_notifier",
      "external": true,
      "loc": "kernel/cpu.c:282",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "kernel/trace/ring_buffer.c:__ring_buffer_alloc",
        "mm/vmstat.c:setup_vmstat",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:zswap_pool_create",
        "drivers/base/topology.c:topology_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "net/core/flow.c:flow_cache_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383792,
      "name": "__register_cpu_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int __register_cpu_notifier(struct notifier_block * nb)
```
</details>
</li>
</ul>

# Function: <code>__static_call_update</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __static_call_update(struct static_call_key * key, void * tramp, void * func)
```

```json
{
  "name": "__static_call_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581177888,
      "name": "__static_call_update",
      "external": true,
      "loc": "kernel/static_call.c:123",
      "file": "kernel/static_call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "kernel/tracepoint.c:tracepoint_remove_func",
        "kernel/tracepoint.c:tracepoint_add_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581177888,
      "name": "__static_call_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
void __static_call_update(struct static_call_key * key, void * tramp, void * func)
```

```json
{
  "name": "__static_call_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581196304,
      "name": "__static_call_update",
      "external": true,
      "loc": "kernel/static_call.c:123",
      "file": "kernel/static_call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/xen/time.c:xen_init_time_common",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/paravirt.c:paravirt_set_sched_clock",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/tracepoint.c:tracepoint_add_func",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "drivers/xen/time.c:xen_time_setup_guest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581196304,
      "name": "__static_call_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
void __static_call_update(struct static_call_key * key, void * tramp, void * func)
```

```json
{
  "name": "__static_call_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__static_call_update",
      "external": true,
      "loc": "kernel/static_call.c:123",
      "file": "kernel/static_call.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/xen/time.c:xen_init_time_common",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/paravirt.c:paravirt_set_sched_clock",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/tracepoint.c:tracepoint_add_func",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "drivers/xen/time.c:xen_time_setup_guest"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592188026,
      "name": "__static_call_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071581436624,
      "name": "__static_call_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
void __static_call_update(struct static_call_key * key, void * tramp, void * func)
```

```json
{
  "name": "__static_call_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__static_call_update",
      "external": true,
      "loc": "kernel/static_call_inline.c:123",
      "file": "kernel/static_call_inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/brs.c:amd_brs_lopwr_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/xen/time.c:xen_init_time_common",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/paravirt.c:paravirt_set_sched_clock",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/events/core.c:perf_unregister_guest_info_callbacks",
        "kernel/events/core.c:perf_unregister_guest_info_callbacks",
        "kernel/events/core.c:perf_unregister_guest_info_callbacks",
        "kernel/events/core.c:perf_register_guest_info_callbacks",
        "kernel/events/core.c:perf_register_guest_info_callbacks",
        "kernel/events/core.c:perf_register_guest_info_callbacks",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593963091,
      "name": "__static_call_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071581776160,
      "name": "__static_call_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
void __static_call_update(struct static_call_key * key, void * tramp, void * func)
```

```json
{
  "name": "__static_call_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__static_call_update",
      "external": true,
      "loc": "kernel/static_call_inline.c:134",
      "file": "kernel/static_call_inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/brs.c:amd_brs_lopwr_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/xen/time.c:xen_hvm_init_time_ops",
        "arch/x86/xen/time.c:xen_init_time_ops",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/paravirt.c:paravirt_set_sched_clock",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/sched/core.c:sched_dynamic_update",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/events/core.c:perf_unregister_guest_info_callbacks",
        "kernel/events/core.c:perf_unregister_guest_info_callbacks",
        "kernel/events/core.c:perf_unregister_guest_info_callbacks",
        "kernel/events/core.c:perf_register_guest_info_callbacks",
        "kernel/events/core.c:perf_register_guest_info_callbacks",
        "kernel/events/core.c:perf_register_guest_info_callbacks",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596023237,
      "name": "__static_call_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582200496,
      "name": "__static_call_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
void __static_call_update(struct static_call_key * key, void * tramp, void * func)
```

```json
{
  "name": "__static_call_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__static_call_update",
      "external": true,
      "loc": "kernel/static_call_inline.c:134",
      "file": "kernel/static_call_inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/brs.c:amd_brs_lopwr_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/xen/time.c:xen_hvm_init_time_ops",
        "arch/x86/xen/time.c:xen_init_time_ops",
        "arch/x86/kernel/process.c:idle_setup",
        "arch/x86/kernel/process.c:select_idle_routine",
        "arch/x86/kernel/process.c:select_idle_routine",
        "arch/x86/kernel/process.c:select_idle_routine",
        "arch/x86/kernel/process.c:select_idle_routine",
        "arch/x86/kernel/process.c:xen_set_default_idle",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/paravirt.c:paravirt_set_sched_clock",
        "kernel/sched/core.c:sched_dynamic_klp_enable",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/events/core.c:perf_unregister_guest_info_callbacks",
        "kernel/events/core.c:perf_unregister_guest_info_callbacks",
        "kernel/events/core.c:perf_unregister_guest_info_callbacks",
        "kernel/events/core.c:perf_register_guest_info_callbacks",
        "kernel/events/core.c:perf_register_guest_info_callbacks",
        "kernel/events/core.c:perf_register_guest_info_callbacks",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596545345,
      "name": "__static_call_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582400384,
      "name": "__static_call_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
void __static_call_update(struct static_call_key * key, void * tramp, void * func)
```

```json
{
  "name": "__static_call_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__static_call_update",
      "external": true,
      "loc": "kernel/static_call_inline.c:134",
      "file": "kernel/static_call_inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/core.c:x86_pmu_static_call_update",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/core.c:amd_core_pmu_init",
        "arch/x86/events/amd/brs.c:amd_brs_lopwr_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/xen/time.c:xen_hvm_init_time_ops",
        "arch/x86/xen/time.c:xen_init_time_ops",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/hyperv/hv_apic.c:hv_apic_init",
        "arch/x86/kernel/process.c:idle_setup",
        "arch/x86/kernel/process.c:select_idle_routine",
        "arch/x86/kernel/process.c:select_idle_routine",
        "arch/x86/kernel/process.c:select_idle_routine",
        "arch/x86/kernel/process.c:select_idle_routine",
        "arch/x86/kernel/process.c:xen_set_default_idle",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform_setup",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_mp_wake",
        "arch/x86/kernel/apic/init.c:update_static_calls",
        "arch/x86/kernel/apic/init.c:update_static_calls",
        "arch/x86/kernel/apic/init.c:update_static_calls",
        "arch/x86/kernel/apic/init.c:update_static_calls",
        "arch/x86/kernel/apic/init.c:update_static_calls",
        "arch/x86/kernel/apic/init.c:update_static_calls",
        "arch/x86/kernel/apic/init.c:update_static_calls",
        "arch/x86/kernel/apic/init.c:update_static_calls",
        "arch/x86/kernel/apic/init.c:update_static_calls",
        "arch/x86/kernel/apic/init.c:update_static_calls",
        "arch/x86/kernel/apic/init.c:update_static_calls",
        "arch/x86/kernel/apic/init.c:update_static_calls",
        "arch/x86/kernel/apic/init.c:update_static_calls",
        "arch/x86/kernel/apic/init.c:update_static_calls",
        "arch/x86/kernel/apic/init.c:update_static_calls",
        "arch/x86/kernel/kvm.c:kvm_apic_init",
        "arch/x86/kernel/kvm.c:kvm_apic_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/paravirt.c:paravirt_set_sched_clock",
        "arch/x86/kernel/sev.c:snp_set_wakeup_secondary_cpu",
        "kernel/sched/core.c:sched_dynamic_klp_enable",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/sched/core.c:__sched_dynamic_update",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog",
        "kernel/events/core.c:perf_unregister_guest_info_callbacks",
        "kernel/events/core.c:perf_unregister_guest_info_callbacks",
        "kernel/events/core.c:perf_unregister_guest_info_callbacks",
        "kernel/events/core.c:perf_register_guest_info_callbacks",
        "kernel/events/core.c:perf_register_guest_info_callbacks",
        "kernel/events/core.c:perf_register_guest_info_callbacks",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "security/keys/trusted-keys/trusted_core.c:init_trusted",
        "drivers/xen/time.c:xen_time_setup_guest",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init",
        "drivers/cpufreq/amd-pstate.c:amd_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597449040,
      "name": "__static_call_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071582568016,
      "name": "__static_call_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void __static_call_update(struct static_call_key * key, void * tramp, void * func)
```
</details>
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

# Function: <code>idr_get_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * idr_get_next(struct idr * idp, int * nextidp)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582948560,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:736",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_cpu_up_callback",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/cgroup.c:task_cgroup_path",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582948560,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void * idr_get_next(struct idr * idp, int * nextidp)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583236272,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:736",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/cgroup.c:task_cgroup_path",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_find_get",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236272,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * idr_get_next(struct idr * idp, int * nextidp)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583351520,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:736",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/cgroup.c:task_cgroup_path",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_find_get",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "net/netlink/genetlink.c:genl_unbind",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumpfamily",
        "net/netlink/genetlink.c:genl_family_find_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583351520,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588203072,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:123",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_find_get",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "net/netlink/genetlink.c:genl_unbind",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumpfamily",
        "net/netlink/genetlink.c:genl_family_find_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588203072,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588751824,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:110",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_find_get",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "net/netlink/genetlink.c:genl_unbind",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumpfamily",
        "net/netlink/genetlink.c:genl_family_find_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588751824,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589130112,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:230",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_find_get",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_unbind",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumpfamily",
        "net/netlink/genetlink.c:genl_family_find_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130112,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589364976,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:226",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_unbind",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumpfamily",
        "net/netlink/genetlink.c:genl_family_find_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589364976,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589822000,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:227",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_unbind",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumpfamily",
        "net/netlink/genetlink.c:genl_family_find_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589822000,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590048544,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:264",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_unbind",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumpfamily",
        "net/netlink/genetlink.c:genl_family_find_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590048544,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585042496,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:264",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_map_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:ctrl_dumppolicy",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:ctrl_dumpfamily"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585042496,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585194224,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:264",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_prog_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_map_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:ctrl_dumppolicy_start",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:ctrl_dumpfamily"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585194224,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585077312,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:264",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_prog_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_map_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumppolicy_start",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:ctrl_dumpfamily"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585077312,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585524144,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:264",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_prog_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_map_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/btf.c:bpf_btf_find_by_name_kind",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_rmid",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumppolicy_start",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:ctrl_dumpfamily"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585524144,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586677312,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:264",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_link_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_prog_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_map_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_rmid",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumppolicy_start",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:ctrl_dumpfamily"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586677312,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595757488,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:264",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_link_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_prog_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_map_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_rmid",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumppolicy_start",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:ctrl_dumpfamily"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595757488,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596281808,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:264",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/pid.c:find_ge_pid",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_link_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_prog_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_map_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_rmid",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumppolicy_start",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:ctrl_dumpfamily"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596281808,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597166512,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:264",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/pid.c:find_ge_pid",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_link_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_prog_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_map_get_curr_or_next",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/btf.c:bpf_find_btf_id",
        "ipc/util.c:sysvipc_proc_start",
        "ipc/util.c:sysvipc_proc_next",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_rmid",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/gpu/drm/drm_connector.c:drm_mode_get_tile_group",
        "drivers/gpu/drm/drm_file.c:drm_show_memory_stats",
        "drivers/gpu/drm/drm_lease.c:drm_mode_get_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:_drm_lease_revoke",
        "drivers/gpu/drm/drm_lease.c:drm_lease_create",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumppolicy_start",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:ctrl_dumpfamily",
        "net/netlink/genetlink.c:genl_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597166512,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503823240,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:264",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_unbind",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumpfamily",
        "net/netlink/genetlink.c:ctrl_dumpfamily",
        "net/netlink/genetlink.c:genl_family_find_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503823240,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236444784,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:264",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/mtd/mtdcore.c:mtd_proc_show",
        "drivers/mtd/mtdcore.c:mtd_proc_show",
        "drivers/mtd/mtdcore.c:get_mtd_device_nm",
        "drivers/mtd/mtdcore.c:get_mtd_device_nm",
        "drivers/mtd/mtdcore.c:get_mtd_device",
        "drivers/mtd/mtdcore.c:get_mtd_device",
        "drivers/mtd/mtdcore.c:unregister_mtd_user",
        "drivers/mtd/mtdcore.c:unregister_mtd_user",
        "drivers/mtd/mtdcore.c:register_mtd_user",
        "drivers/mtd/mtdcore.c:register_mtd_user",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_unbind",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumpfamily",
        "net/netlink/genetlink.c:genl_family_find_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236444784,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297668352,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:264",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_unbind",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumpfamily",
        "net/netlink/genetlink.c:genl_family_find_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297668352,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279718480,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:264",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_unbind",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumpfamily",
        "net/netlink/genetlink.c:genl_family_find_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279718480,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589650800,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:264",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_unbind",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumpfamily",
        "net/netlink/genetlink.c:genl_family_find_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589650800,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589376608,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:264",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_unbind",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumpfamily",
        "net/netlink/genetlink.c:genl_family_find_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589376608,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590094176,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:264",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_unbind",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumpfamily",
        "net/netlink/genetlink.c:genl_family_find_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590094176,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void * idr_get_next(struct idr * idr, int * nextid)
```

```json
{
  "name": "idr_get_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590144432,
      "name": "idr_get_next",
      "external": true,
      "loc": "lib/idr.c:264",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_online_cpu",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/pid.c:find_ge_pid",
        "kernel/cgroup/cgroup.c:task_cgroup_path",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "drivers/char/tpm/tpm-chip.c:tpm_default_chip",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/devices.c:usb_device_read",
        "drivers/pps/pps.c:pps_lookup_dev",
        "net/netlink/genetlink.c:genl_unbind",
        "net/netlink/genetlink.c:genl_bind",
        "net/netlink/genetlink.c:ctrl_dumpfamily",
        "net/netlink/genetlink.c:genl_family_find_byname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590144432,
      "name": "idr_get_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct idr * idr</code>
</li>
<li>
<b>Param added. </b>
<code>int * nextid</code>
</li>
<li>
<b>Param removed. </b>
<code>struct idr * idp</code>
</li>
<li>
<b>Param removed. </b>
<code>int * nextidp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

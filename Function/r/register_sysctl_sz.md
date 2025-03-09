# Function: <code>register_sysctl_sz</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ctl_table_header * register_sysctl_sz(const char * path, struct ctl_table * table, size_t table_size)
```

```json
{
  "name": "register_sysctl_sz",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621982997,
      "name": "register_sysctl_sz",
      "external": true,
      "loc": "fs/proc/proc_sysctl.c:1414",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:__register_sysctl_init",
        "fs/proc/proc_sysctl.c:register_sysctl_mount_point"
      ],
      "caller_func": [
        "arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init",
        "arch/x86/kernel/itmt.c:sched_set_itmt_support",
        "kernel/ucount.c:user_namespace_sysctl_init",
        "kernel/time/timer.c:timer_sysctl_init",
        "kernel/pid_namespace.c:pid_namespaces_init",
        "kernel/utsname_sysctl.c:utsname_sysctl_init",
        "fs/notify/inotify/inotify_user.c:inotify_user_setup",
        "fs/notify/fanotify/fanotify_user.c:fanotify_user_setup",
        "fs/eventpoll.c:eventpoll_init",
        "fs/verity/init.c:fsverity_init",
        "fs/devpts/inode.c:init_devpts_fs",
        "security/apparmor/lsm.c:apparmor_init",
        "security/yama/yama_lsm.c:yama_init",
        "drivers/char/hpet.c:hpet_init",
        "drivers/base/firmware_loader/fallback_table.c:register_firmware_config_sysctl",
        "drivers/scsi/scsi_sysctl.c:scsi_init_sysctl",
        "drivers/scsi/sg.c:init_sg",
        "drivers/md/md.c:md_init",
        "drivers/hv/hv_common.c:hv_common_init",
        "net/sysctl_net.c:net_sysctl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584826832,
      "name": "register_sysctl_sz",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct ctl_table_header * register_sysctl_sz(const char * path, struct ctl_table * table, size_t table_size)
```
</details>
</li>
</ul>

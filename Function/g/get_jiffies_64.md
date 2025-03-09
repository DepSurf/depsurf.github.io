# Function: <code>get_jiffies_64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579145205,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:therm_throt_process",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454308,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:SyS_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582063477,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584964696,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585851709,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585868502,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_update",
        "drivers/cpufreq/cpufreq_stats.c:__cpufreq_stats_create_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586885471,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv4/syncookies.c:__cookie_v4_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587229855,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_check"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579146300,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:therm_throt_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579467124,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:SyS_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582288583,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585331896,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586251245,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586271128,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587334990,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587687206,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579155516,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:therm_throt_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579487524,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:SyS_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582376730,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585532936,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586456013,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586475416,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587537838,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587895926,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579153529,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:82",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:therm_throt_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474628,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:82",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:SyS_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582461450,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:82",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585618936,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:82",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586580533,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:82",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586599919,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:82",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587683675,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:82",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588053043,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:82",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579168390,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:therm_throt_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579502500,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:SyS_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582612077,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586050702,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_ering_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587063813,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587083263,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588210347,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588591075,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:83",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579179844,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "arch/x86/kernel/cpu/mcheck/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mcheck/therm_throt.c:therm_throt_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579515236,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582805282,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586298503,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_ering_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587362033,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587381366,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588565093,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588956338,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579169257,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579551092,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582908202,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584629525,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_get_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586440023,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_ering_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587541905,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587561270,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588762453,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589180354,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579181741,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579573046,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583087395,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584829205,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_get_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586684615,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_ering_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587816469,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587837261,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589195504,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589634093,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579184029,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579599366,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581759792,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583192531,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_dentry_delete",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584964933,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_get_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586831688,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588021669,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588042093,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589420944,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589858285,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579204627,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:84",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:notify_package_thresholds",
        "arch/x86/kernel/cpu/mce/therm_throt.c:notify_package_thresholds",
        "arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579630550,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:84",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581026341,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:84",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_jiffies64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581979584,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:84",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583512744,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:84",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_delete",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585660485,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:84",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_get_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587637389,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:84",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_speed_down",
        "drivers/ata/libata-eh.c:ata_eh_speed_down_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588881717,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:84",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588902653,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:84",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589135643,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:84",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_update_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590408192,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:84",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590885226,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:84",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579199891,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:notify_package_thresholds",
        "arch/x86/kernel/cpu/mce/therm_throt.c:notify_package_thresholds",
        "arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579610518,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033221,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_jiffies64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582029890,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583626962,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_delete",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585786101,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_get_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586405408,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker",
        "drivers/xen/events/events_base.c:lateeoi_list_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587698333,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_speed_down",
        "drivers/ata/libata-eh.c:ata_eh_speed_down_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588894533,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589134218,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_update_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590466032,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590946730,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579616966,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044757,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_jiffies64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582056070,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583650034,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_delete",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585666469,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_get_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586288655,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587577258,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_speed_down",
        "drivers/ata/libata-eh.c:ata_eh_speed_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588573659,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588783541,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589023970,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_update_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590391799,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590876678,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579693222,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581267845,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_jiffies64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582363948,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584009090,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_delete",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586145941,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_get_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586804403,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588159427,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_speed_down",
        "drivers/ata/libata-eh.c:ata_eh_speed_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248653,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589475761,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589739602,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_update_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591186983,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591707270,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579794436,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581559061,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_jiffies64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582861276,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584594204,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_delete",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587378373,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_get_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588086413,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589539912,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_speed_down",
        "drivers/ata/libata-eh.c:ata_eh_speed_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590715654,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590955081,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591243691,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:trans_stat_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_update_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592846253,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593406960,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579928820,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581931733,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_jiffies64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583408652,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585272540,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_delete",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588628213,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_get_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589468717,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591131048,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_speed_down",
        "drivers/ata/libata-eh.c:ata_eh_speed_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592387230,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592657545,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592996379,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:trans_stat_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_update_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594723261,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595317312,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579978756,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582114997,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_jiffies64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583628908,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585503020,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_delete",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588915973,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_get_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589768637,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591488967,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_speed_down",
        "drivers/ata/libata-eh.c:ata_eh_speed_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592816094,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593088281,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593447851,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:trans_stat_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_update_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595115346,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595712352,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:85",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580018164,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:99",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582255317,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:99",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_jiffies64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583823484,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:99",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585742845,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:99",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_get_attr",
        "fs/fuse/dir.c:fuse_do_getattr",
        "fs/fuse/dir.c:fuse_do_statx",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_lookup",
        "fs/fuse/dir.c:fuse_lookup_name",
        "fs/fuse/dir.c:fuse_dentry_delete",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589212037,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:99",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_get_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590105079,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:99",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591837703,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:99",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_speed_down",
        "drivers/ata/libata-eh.c:ata_eh_speed_down"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593564990,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:99",
      "file": "drivers/thermal/intel/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593840707,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:99",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594194251,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:99",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:trans_stat_store",
        "drivers/devfreq/devfreq.c:devfreq_add_device",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_update_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595928073,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:99",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596560558,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:99",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490773576,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__arm64_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493213540,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494910852,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_dentry_delete",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497379936,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_get_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499761932,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501284868,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501310224,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503073752,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503575628,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
u64 get_jiffies_64()
```

```json
{
  "name": "get_jiffies_64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225364468,
      "name": "get_jiffies_64",
      "external": true,
      "loc": "kernel/time/jiffies.c:64",
      "file": "kernel/time/jiffies.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/smp_twd.c:twd_timer_setup",
        "arch/arm/kernel/smp_twd.c:twd_timer_setup",
        "arch/arm/kernel/smp_twd.c:twd_timer_setup",
        "kernel/sys.c:__se_sys_times",
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_dentry_delete",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "fs/fuse/dir.c:fuse_dentry_revalidate",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_update",
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence",
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225364468,
      "name": "get_jiffies_64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283590468,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286725048,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288776864,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_dentry_delete",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293107304,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294810836,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294843032,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294862476,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/powernv-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_target_index"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296777888,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297378980,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271465704,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272990120,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274221290,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_dentry_delete",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276919042,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279130098,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279531922,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579184285,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579575670,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581728528,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583161267,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_dentry_delete",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584915109,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_get_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586590264,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587646661,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587667085,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589025312,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589462653,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579117371,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579504278,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581667296,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098419,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_dentry_delete",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584821029,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_get_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586458776,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587420533,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587440957,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588750352,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589187645,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579183949,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579572950,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581719840,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583145299,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_dentry_delete",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584916517,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_get_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586786248,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587977813,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587998237,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589461696,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589899517,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
  "name": "get_jiffies_64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579189197,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579606982,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_times",
        "kernel/sys.c:__x64_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581787769,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583238851,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_getattr",
        "fs/fuse/dir.c:fuse_permission",
        "fs/fuse/dir.c:fuse_update_attributes",
        "fs/fuse/dir.c:fuse_dentry_delete",
        "fs/fuse/dir.c:fuse_dentry_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585022597,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_get_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586892296,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588093189,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:get_cpu_idle_time"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588113661,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "drivers/cpufreq/cpufreq_stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition",
        "drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table",
        "drivers/cpufreq/cpufreq_stats.c:store_reset",
        "drivers/cpufreq/cpufreq_stats.c:show_time_in_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589508032,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:__cookie_v4_check",
        "net/ipv4/syncookies.c:__cookie_v4_init_sequence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589951837,
      "name": "get_jiffies_64",
      "external": false,
      "loc": "include/linux/jiffies.h:86",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:__cookie_v6_check",
        "net/ipv6/syncookies.c:__cookie_v6_init_sequence"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
u64 get_jiffies_64()
```
</details>
</li>
</ul>

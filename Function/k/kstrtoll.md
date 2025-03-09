# Function: <code>kstrtoll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583048128,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:146",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/cgroup.c:cgroup_file_write",
        "kernel/cgroup_pids.c:pids_max_write",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/trace_events_filter.c:replace_preds",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "security/keys/trusted.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "lib/kstrtox.c:_kstrtol",
        "lib/kstrtox.c:kstrtoint_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtol_from_user",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/rapidio/rio-sysfs.c:bus_scan_store",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/power/power_supply_sysfs.c:power_supply_store_property",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store",
        "drivers/md/bitmap.c:location_store",
        "drivers/md/bitmap.c:location_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048128,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583341936,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:146",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/cgroup.c:cgroup_file_write",
        "kernel/cgroup_pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:replace_preds",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "security/keys/trusted.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "lib/kstrtox.c:kstrtol_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:bus_scan_store",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/rtc/rtc-sysfs.c:offset_store",
        "drivers/power/power_supply_sysfs.c:power_supply_store_property",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583341936,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583467312,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:142",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/cgroup.c:cgroup_file_write",
        "kernel/cgroup_pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:replace_preds",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "security/keys/trusted.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "lib/kstrtox.c:kstrtol_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:bus_scan_store",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/rtc/rtc-sysfs.c:offset_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583467312,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583489584,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:144",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:replace_preds",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "security/keys/trusted.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "lib/kstrtox.c:kstrtol_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:bus_scan_store",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/rtc/rtc-sysfs.c:offset_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583489584,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583670624,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:145",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:replace_preds",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_split_symbol_offset",
        "security/keys/trusted.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "lib/kstrtox.c:kstrtol_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:bus_scan_store",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/rtc/rtc-sysfs.c:offset_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583670624,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583888400,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:145",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_split_symbol_offset",
        "security/keys/trusted.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "lib/kstrtox.c:kstrtol_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:bus_scan_store",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/rtc/rtc-sysfs.c:offset_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583888400,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583972640,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:145",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_probe.c:traceprobe_split_symbol_offset",
        "security/keys/trusted.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "lib/kstrtox.c:kstrtol_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:bus_scan_store",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972640,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584153856,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:145",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_probe.c:traceprobe_split_symbol_offset",
        "security/keys/trusted.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "lib/kstrtox.c:kstrtol_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:scan_store",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153856,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584276480,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:145",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/tlb_uv.c:ptc_proc_write",
        "kernel/params.c:param_set_long",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_probe.c:traceprobe_split_symbol_offset",
        "security/keys/trusted.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "lib/kstrtox.c:kstrtol_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:scan_store",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584276480,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584686447,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:145",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "lib/kstrtox.c:_kstrtol"
      ],
      "caller_func": [
        "arch/x86/platform/uv/tlb_uv.c:ptc_proc_write",
        "kernel/params.c:param_set_long",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_inject.c:parse_field",
        "kernel/trace/trace_probe.c:traceprobe_update_arg",
        "security/keys/trusted-keys/trusted_tpm1.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:scan_store",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584685648,
      "name": "kstrtoll",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584804015,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:143",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "lib/kstrtox.c:_kstrtol"
      ],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_inject.c:parse_field",
        "kernel/trace/trace_probe.c:traceprobe_update_arg",
        "security/keys/trusted-keys/trusted_tpm1.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:scan_store",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584803216,
      "name": "kstrtoll",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584848079,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:150",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "lib/kstrtox.c:_kstrtol"
      ],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/sched/core.c:setup_resched_latency_warn_ms",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_inject.c:parse_field",
        "kernel/trace/trace_probe.c:traceprobe_update_arg",
        "security/keys/trusted-keys/trusted_core.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:scan_store",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584846992,
      "name": "kstrtoll",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585268237,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:151",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "lib/kstrtox.c:_kstrtol"
      ],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/sched/core.c:setup_resched_latency_warn_ms",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_inject.c:parse_field",
        "kernel/trace/trace_probe.c:traceprobe_update_arg",
        "security/keys/trusted-keys/trusted_core.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:scan_store",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585267056,
      "name": "kstrtoll",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586111952,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:156",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/sched/core.c:setup_resched_latency_warn_ms",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_inject.c:parse_field",
        "kernel/trace/trace_probe.c:traceprobe_update_arg",
        "security/keys/trusted-keys/trusted_core.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:kstrtos8",
        "lib/kstrtox.c:kstrtos16",
        "lib/kstrtox.c:kstrtoint",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:scan_store",
        "drivers/acpi/acpi_lpss.c:byt_i2c_setup",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586111952,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587097824,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:156",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/sched/core.c:setup_resched_latency_warn_ms",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_inject.c:parse_field",
        "kernel/trace/trace_probe.c:traceprobe_update_arg",
        "security/keys/trusted-keys/trusted_core.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:kstrtos8",
        "lib/kstrtox.c:kstrtos16",
        "lib/kstrtox.c:kstrtoint",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:scan_store",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587097824,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587357888,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:156",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/sched/core.c:setup_resched_latency_warn_ms",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_inject.c:parse_field",
        "kernel/trace/trace_probe.c:traceprobe_update_arg",
        "security/keys/trusted-keys/trusted_core.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:kstrtos8",
        "lib/kstrtox.c:kstrtos16",
        "lib/kstrtox.c:kstrtoint",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:scan_store",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587357888,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587644208,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:156",
      "file": "lib/kstrtox.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/sched/core.c:setup_resched_latency_warn_ms",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_inject.c:parse_field",
        "kernel/trace/trace_probe.c:traceprobe_update_arg",
        "security/keys/trusted-keys/trusted_core.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:kstrtos8",
        "lib/kstrtox.c:kstrtos16",
        "lib/kstrtox.c:kstrtoint",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:scan_store",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587644208,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496161944,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:145",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_probe.c:traceprobe_split_symbol_offset",
        "security/keys/trusted.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "lib/kstrtox.c:kstrtol_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:scan_store",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/reset/vexpress-poweroff.c:vexpress_reset_active_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496161944,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229482936,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:145",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "lib/kstrtox.c:kstrtol_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229482936,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290425984,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:145",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_probe.c:traceprobe_split_symbol_offset",
        "security/keys/trusted.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "lib/kstrtox.c:kstrtol_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:scan_store",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290425984,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275213184,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:145",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "security/keys/trusted.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "lib/kstrtox.c:kstrtol_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:scan_store",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275213184,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584245216,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:145",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_probe.c:traceprobe_split_symbol_offset",
        "security/keys/trusted.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "lib/kstrtox.c:kstrtol_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:scan_store",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584245216,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584180416,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:145",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_probe.c:traceprobe_split_symbol_offset",
        "security/keys/trusted.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "lib/kstrtox.c:kstrtol_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:scan_store",
        "drivers/acpi/nfit/core.c:hw_error_scrub_store",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584180416,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584228976,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:145",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:param_set_long",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_probe.c:traceprobe_split_symbol_offset",
        "security/keys/trusted.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "lib/kstrtox.c:kstrtol_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:scan_store",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584228976,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int kstrtoll(const char * s, unsigned int base, long long int * res)
```

```json
{
  "name": "kstrtoll",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584333808,
      "name": "kstrtoll",
      "external": true,
      "loc": "lib/kstrtox.c:145",
      "file": "lib/kstrtox.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/tlb_uv.c:ptc_proc_write",
        "kernel/params.c:param_set_long",
        "kernel/time/ntp.c:ntp_tick_adj_setup",
        "kernel/cgroup/cgroup.c:cgroup_file_write",
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_probe.c:traceprobe_split_symbol_offset",
        "security/keys/trusted.c:datablob_parse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc",
        "block/blk-sysfs.c:queue_wb_lat_store",
        "lib/kstrtox.c:kstrtos8_from_user",
        "lib/kstrtox.c:kstrtos16_from_user",
        "lib/kstrtox.c:kstrtoint_from_user",
        "lib/kstrtox.c:kstrtol_from_user",
        "lib/kstrtox.c:kstrtoll_from_user",
        "lib/kstrtox.c:_kstrtol",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:active_low_store",
        "drivers/gpio/gpiolib-sysfs.c:value_store",
        "drivers/rapidio/rio-sysfs.c:scan_store",
        "drivers/base/core.c:device_store_int",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/rtc/sysfs.c:offset_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_store_property",
        "drivers/hwmon/hwmon.c:hwmon_attr_store",
        "drivers/md/md.c:sync_force_parallel_store",
        "drivers/md/md.c:level_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333808,
      "name": "kstrtoll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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

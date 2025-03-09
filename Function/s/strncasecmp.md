# Function: <code>strncasecmp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582982192,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:41",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/thermal/thermal_core.c:thermal_zone_get_zone_by_name",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/thermal/thermal_core.c:thermal_unregister_governor",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/cpufreq/cpufreq.c:find_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982192,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583271376,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:41",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/thermal/thermal_core.c:thermal_zone_get_zone_by_name",
        "drivers/thermal/thermal_core.c:thermal_unregister_governor",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/cpufreq/cpufreq.c:find_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271376,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583390144,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:41",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/thermal/thermal_core.c:thermal_zone_get_zone_by_name",
        "drivers/thermal/thermal_core.c:thermal_unregister_governor",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/cpufreq/cpufreq.c:find_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583390144,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588246256,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:41",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/thermal/thermal_core.c:thermal_unregister_governor",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/cpufreq/cpufreq.c:find_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588246256,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588797680,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:42",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/thermal/thermal_core.c:thermal_unregister_governor",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/cpufreq/cpufreq.c:find_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588797680,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589175760,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:42",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_unregister_governor",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/cpufreq/cpufreq.c:find_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589175760,
      "name": "strncasecmp",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589405680,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:43",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_unregister_governor",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:dm_stats_message",
        "drivers/cpufreq/cpufreq.c:find_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589405680,
      "name": "strncasecmp",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589861568,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:43",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:message_stats_create",
        "drivers/cpufreq/cpufreq.c:find_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589861568,
      "name": "strncasecmp",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590087360,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:43",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:message_stats_create",
        "drivers/cpufreq/cpufreq.c:cpufreq_parse_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_parse_policy",
        "drivers/cpufreq/cpufreq.c:find_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_find_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590087360,
      "name": "strncasecmp",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585085312,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:43",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_parsebp",
        "kernel/debug/kdb/kdb_bp.c:kdb_parsebp",
        "kernel/debug/kdb/kdb_bp.c:kdb_parsebp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/acpi/battery.c:acpi_battery_quirks",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:message_stats_create",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_governor",
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:get_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585085312,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585234448,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:43",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_parsebp",
        "kernel/debug/kdb/kdb_bp.c:kdb_parsebp",
        "kernel/debug/kdb/kdb_bp.c:kdb_parsebp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/acpi/battery.c:acpi_battery_quirks",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:message_stats_create",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_governor",
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_init_policy",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:get_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585234448,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585117280,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:43",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/acpi/battery.c:acpi_battery_quirks",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:message_stats_create",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_governor",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:get_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585117280,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585566000,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:44",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "lib/bitmap.c:bitmap_parse_region",
        "drivers/acpi/battery.c:acpi_battery_quirks",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:message_stats_create",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_governor",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:get_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585566000,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586719488,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:39",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "lib/bitmap.c:bitmap_parselist",
        "drivers/acpi/battery.c:acpi_battery_quirks",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:message_stats_create",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_governor",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:get_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586719488,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595881904,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:39",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "lib/bitmap.c:bitmap_parselist",
        "drivers/acpi/battery.c:acpi_battery_quirks",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:message_stats_create",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_governor",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:get_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595881904,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596399152,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:39",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "block/early-lookup.c:match_dev_by_uuid",
        "lib/bitmap.c:bitmap_parselist",
        "drivers/acpi/battery.c:acpi_battery_quirks",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:message_stats_create",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_governor",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:get_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596399152,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597294256,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:39",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:parse_affn_scope",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "block/early-lookup.c:match_dev_by_uuid",
        "lib/bitmap-str.c:bitmap_parselist",
        "drivers/acpi/battery.c:acpi_battery_quirks",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:message_stats_create",
        "drivers/cpufreq/cpufreq.c:cpufreq_register_governor",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:store_scaling_governor",
        "drivers/cpufreq/cpufreq.c:get_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597294256,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503865720,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:43",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:message_stats_create",
        "drivers/cpufreq/cpufreq.c:cpufreq_parse_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_parse_policy",
        "drivers/cpufreq/cpufreq.c:find_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_find_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503865720,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236493256,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:43",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:message_stats_create",
        "drivers/cpufreq/cpufreq.c:cpufreq_parse_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_parse_policy",
        "drivers/cpufreq/cpufreq.c:find_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_find_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236493256,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297725040,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:43",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "block/partitions/mac.c:mac_partition",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:message_stats_create",
        "drivers/cpufreq/cpufreq.c:cpufreq_parse_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_parse_policy",
        "drivers/cpufreq/cpufreq.c:find_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_find_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297725040,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279761366,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:43",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "block/partitions/mac.c:mac_partition",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:dm_stats_message",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279761366,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589689616,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:43",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:message_stats_create",
        "drivers/cpufreq/cpufreq.c:cpufreq_parse_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_parse_policy",
        "drivers/cpufreq/cpufreq.c:find_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_find_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589689616,
      "name": "strncasecmp",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589415408,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:43",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:message_stats_create",
        "drivers/cpufreq/cpufreq.c:cpufreq_parse_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_parse_policy",
        "drivers/cpufreq/cpufreq.c:find_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_find_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589415408,
      "name": "strncasecmp",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590132992,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:43",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:message_stats_create",
        "drivers/cpufreq/cpufreq.c:cpufreq_parse_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_parse_policy",
        "drivers/cpufreq/cpufreq.c:find_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_find_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590132992,
      "name": "strncasecmp",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int strncasecmp(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strncasecmp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590183376,
      "name": "strncasecmp",
      "external": true,
      "loc": "lib/string.c:43",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:match_dev_by_uuid",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "kernel/debug/kdb/kdb_bp.c:kdb_bp",
        "fs/efivarfs/super.c:efivarfs_d_compare",
        "block/partitions/mac.c:mac_partition",
        "drivers/acpi/battery.c:acpi_battery_get_property",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/ata/libata-core.c:ata_parse_force_param",
        "drivers/thermal/thermal_core.c:thermal_register_governor",
        "drivers/md/dm-stats.c:message_stats_create",
        "drivers/cpufreq/cpufreq.c:cpufreq_parse_policy",
        "drivers/cpufreq/cpufreq.c:cpufreq_parse_policy",
        "drivers/cpufreq/cpufreq.c:find_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_register_governor",
        "drivers/cpuidle/governor.c:cpuidle_find_governor",
        "net/netfilter/nf_log.c:__find_logger",
        "net/netfilter/nf_log.c:__find_logger",
        "net/dns_resolver/dns_key.c:dns_resolver_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590183376,
      "name": "strncasecmp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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

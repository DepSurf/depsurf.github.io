# Function: <code>blkcg_print_blkgs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582877248,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:495",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-throttle.c:tg_print_max",
        "block/cfq-iosched.c:cfqg_print_rwstat_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_sectors_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_recursive",
        "block/cfq-iosched.c:cfqg_print_rwstat",
        "block/cfq-iosched.c:cfqg_print_stat_sectors",
        "block/cfq-iosched.c:cfqg_print_stat",
        "block/cfq-iosched.c:cfqg_print_weight_device",
        "block/cfq-iosched.c:cfqg_print_leaf_weight_device",
        "block/cfq-iosched.c:cfq_print_weight_on_dfl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582877248,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583163264,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:495",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_print_max",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/cfq-iosched.c:cfq_print_weight_on_dfl",
        "block/cfq-iosched.c:cfqg_print_stat_sectors_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_sectors",
        "block/cfq-iosched.c:cfqg_print_rwstat_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_recursive",
        "block/cfq-iosched.c:cfqg_print_rwstat",
        "block/cfq-iosched.c:cfqg_print_stat",
        "block/cfq-iosched.c:cfqg_print_leaf_weight_device",
        "block/cfq-iosched.c:cfqg_print_weight_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583163264,
      "name": "blkcg_print_blkgs",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583275328,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:496",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_print_max",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/cfq-iosched.c:cfq_print_weight_on_dfl",
        "block/cfq-iosched.c:cfqg_print_stat_sectors_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_sectors",
        "block/cfq-iosched.c:cfqg_print_rwstat_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_recursive",
        "block/cfq-iosched.c:cfqg_print_rwstat",
        "block/cfq-iosched.c:cfqg_print_stat",
        "block/cfq-iosched.c:cfqg_print_leaf_weight_device",
        "block/cfq-iosched.c:cfqg_print_weight_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583275328,
      "name": "blkcg_print_blkgs",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583330512,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:497",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/cfq-iosched.c:cfq_print_weight_on_dfl",
        "block/cfq-iosched.c:cfqg_print_stat_sectors_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_sectors",
        "block/cfq-iosched.c:cfqg_print_rwstat_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_recursive",
        "block/cfq-iosched.c:cfqg_print_rwstat",
        "block/cfq-iosched.c:cfqg_print_stat",
        "block/cfq-iosched.c:cfqg_print_leaf_weight_device",
        "block/cfq-iosched.c:cfqg_print_weight_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583330512,
      "name": "blkcg_print_blkgs",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583513776,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:497",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/cfq-iosched.c:cfq_print_weight_on_dfl",
        "block/cfq-iosched.c:cfqg_print_stat_sectors_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_sectors",
        "block/cfq-iosched.c:cfqg_print_rwstat_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_recursive",
        "block/cfq-iosched.c:cfqg_print_rwstat",
        "block/cfq-iosched.c:cfqg_print_stat",
        "block/cfq-iosched.c:cfqg_print_leaf_weight_device",
        "block/cfq-iosched.c:cfqg_print_weight_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583513776,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583728016,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:508",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/cfq-iosched.c:cfq_print_weight_on_dfl",
        "block/cfq-iosched.c:cfqg_print_stat_sectors_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_sectors",
        "block/cfq-iosched.c:cfqg_print_rwstat_recursive",
        "block/cfq-iosched.c:cfqg_print_stat_recursive",
        "block/cfq-iosched.c:cfqg_print_rwstat",
        "block/cfq-iosched.c:cfqg_print_stat",
        "block/cfq-iosched.c:cfqg_print_leaf_weight_device",
        "block/cfq-iosched.c:cfqg_print_weight_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728016,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583833392,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:499",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583833392,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584023632,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:520",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584023632,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584127216,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:520",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584127216,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584524592,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:521",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_rwstat_recursive",
        "block/blk-throttle.c:tg_print_rwstat",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584524592,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584633728,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:502",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_rwstat_recursive",
        "block/blk-throttle.c:tg_print_rwstat",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584633728,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584661296,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:500",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_rwstat_recursive",
        "block/blk-throttle.c:tg_print_rwstat",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584661296,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585077024,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:515",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_rwstat_recursive",
        "block/blk-throttle.c:tg_print_rwstat",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585077024,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585802096,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:576",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_rwstat_recursive",
        "block/blk-throttle.c:tg_print_rwstat",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585802096,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586578048,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:585",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_rwstat_recursive",
        "block/blk-throttle.c:tg_print_rwstat",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586578048,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586836048,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:675",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_rwstat_recursive",
        "block/blk-throttle.c:tg_print_rwstat",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586836048,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587113264,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:688",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_rwstat_recursive",
        "block/blk-throttle.c:tg_print_rwstat",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587113264,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495974008,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:520",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495974008,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229311732,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:520",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229311732,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290197408,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:520",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290197408,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275075978,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:520",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275075978,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584095952,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:520",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584095952,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584031712,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:520",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584031712,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584079712,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:520",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584079712,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void blkcg_print_blkgs(struct seq_file * sf, struct blkcg * blkcg, u64 (*)(struct seq_file *, struct blkg_policy_data *, int) prfill, const struct blkcg_policy * pol, int data, bool show_total)
```

```json
{
  "name": "blkcg_print_blkgs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584178336,
      "name": "blkcg_print_blkgs",
      "external": true,
      "loc": "block/blk-cgroup.c:520",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_print_stat_ios_recursive",
        "block/blk-cgroup.c:blkg_print_stat_bytes_recursive",
        "block/blk-cgroup.c:blkg_print_stat_ios",
        "block/blk-cgroup.c:blkg_print_stat_bytes",
        "block/blk-throttle.c:tg_print_limit",
        "block/blk-throttle.c:tg_print_conf_uint",
        "block/blk-throttle.c:tg_print_conf_u64",
        "block/blk-iocost.c:ioc_cost_model_show",
        "block/blk-iocost.c:ioc_qos_show",
        "block/blk-iocost.c:ioc_weight_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584178336,
      "name": "blkcg_print_blkgs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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

# Function: <code>blkg_lookup_slowpath</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582871328,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:142",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum"
      ],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:get_request",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/cfq-iosched.c:cfq_get_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582871328,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583162049,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:142",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:get_request",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:tg_conf_updated",
        "block/cfq-iosched.c:cfq_get_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583157264,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583274113,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:142",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:get_request",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:tg_conf_updated",
        "block/cfq-iosched.c:cfq_get_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269344,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583332895,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:143",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:get_request",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated",
        "block/cfq-iosched.c:cfq_get_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583324688,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583516191,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:143",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:get_request",
        "block/blk-mq.c:blk_mq_bio_to_request",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated",
        "block/cfq-iosched.c:cfq_get_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583507792,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583722208,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:143",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:get_request",
        "block/blk-mq.c:blk_mq_bio_to_request",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated",
        "block/cfq-iosched.c:cfq_get_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583722208,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583828752,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:166",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_stat_recursive_sum",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583828752,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584019040,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:194",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584019040,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584122624,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:194",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584122624,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584530316,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:197",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": [
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:blk_throtl_update_limit_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584520720,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584640154,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:203",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": [
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584629440,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584668097,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:201",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": [
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584657600,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585084465,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:204",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": [
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585071296,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585810936,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:266",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": [
        "block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:throtl_can_upgrade",
        "block/blk-throttle.c:blk_throtl_cancel_bios",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585796400,
      "name": "blkg_lookup_slowpath",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495969344,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:194",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495969344,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229311192,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:194",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:blk_throtl_update_limit_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229311192,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290190480,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:194",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290190480,
      "name": "blkg_lookup_slowpath",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275071818,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:194",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275071818,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584091360,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:194",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584091360,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584027120,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:194",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584027120,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584075120,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:194",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075120,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```

```json
{
  "name": "blkg_lookup_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584177696,
      "name": "blkg_lookup_slowpath",
      "external": true,
      "loc": "block/blk-cgroup.c:194",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_rwstat_recursive_sum",
        "block/blk-cgroup.c:blkg_lookup_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:throtl_upgrade_state",
        "block/blk-throttle.c:tg_conf_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584177696,
      "name": "blkg_lookup_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct blkcg_gq * blkg_lookup_slowpath(struct blkcg * blkcg, struct request_queue * q, bool update_hint)
```
</details>
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

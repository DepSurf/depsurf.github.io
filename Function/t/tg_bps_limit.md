# Function: <code>tg_bps_limit</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583334048,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:294",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583334048,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583517344,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:295",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583517344,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583731792,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:293",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731792,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583839440,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:292",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583839440,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584030592,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:292",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584030592,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584134384,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:292",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584134384,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584537184,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:296",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584537184,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584645008,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:296",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584645008,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584673248,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:296",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584673248,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585091136,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:299",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585091136,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585821728,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:147",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:__blk_throtl_bio",
        "block/blk-throttle.c:__blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585821728,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586603824,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:147",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:__blk_throtl_bio",
        "block/blk-throttle.c:__blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:__tg_update_carryover",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586603824,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586862080,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:147",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:__blk_throtl_bio",
        "block/blk-throttle.c:__blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:__tg_update_carryover",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586862080,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587139536,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:147",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:__blk_throtl_bio",
        "block/blk-throttle.c:__blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:__tg_update_carryover",
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587139536,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495985120,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:292",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495985120,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229324868,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:292",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229324868,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290209440,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:292",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290209440,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275083518,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:292",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275083518,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584103120,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:292",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584103120,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584038800,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:292",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584038800,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584086880,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:292",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584086880,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_bps_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584189744,
      "name": "tg_bps_limit",
      "external": false,
      "loc": "block/blk-throttle.c:292",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_conf_updated",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584189744,
      "name": "tg_bps_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
uint64_t tg_bps_limit(struct throtl_grp * tg, int rw)
```
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

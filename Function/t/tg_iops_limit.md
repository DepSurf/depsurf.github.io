# Function: <code>tg_iops_limit</code>

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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583334336,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:324",
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
      "addr": 18446744071583334336,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583517632,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:325",
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
      "addr": 18446744071583517632,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583732080,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:323",
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
      "addr": 18446744071583732080,
      "name": "tg_iops_limit",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583839728,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:322",
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
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583839728,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584030288,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:322",
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
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584030288,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584134080,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:322",
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
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584134080,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584531744,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:326",
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
        "block/blk-throttle.c:throtl_trim_slice",
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584531744,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584641776,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:326",
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
      "addr": 18446744071584641776,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584670016,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:326",
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
      "addr": 18446744071584670016,
      "name": "tg_iops_limit",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585086624,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:329",
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
      "addr": 18446744071585086624,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585814048,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:177",
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
      "addr": 18446744071585814048,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586596032,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:177",
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
      "addr": 18446744071586596032,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586854320,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:177",
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
      "addr": 18446744071586854320,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587131648,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:177",
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
      "addr": 18446744071587131648,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495985408,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:322",
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
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495985408,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229325200,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:322",
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
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229325200,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290209776,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:322",
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
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290209776,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275083772,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:322",
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
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275083772,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584102816,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:322",
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
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584102816,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584038496,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:322",
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
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584038496,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584086576,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:322",
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
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584086576,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
```

```json
{
  "name": "tg_iops_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584189440,
      "name": "tg_iops_limit",
      "external": false,
      "loc": "block/blk-throttle.c:322",
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
        "block/blk-throttle.c:tg_update_has_rules"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584189440,
      "name": "tg_iops_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
unsigned int tg_iops_limit(struct throtl_grp * tg, int rw)
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

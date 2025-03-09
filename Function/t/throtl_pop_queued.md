# Function: <code>throtl_pop_queued</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582881344,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:291",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582881344,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583167584,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:285",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583167584,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583279648,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:285",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583279648,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583336144,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:451",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583336144,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583519360,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:450",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583519360,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583733504,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:448",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583733504,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583843632,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:447",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583843632,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584034048,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:447",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584034048,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584137888,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:447",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137888,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584536320,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:451",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536320,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584644432,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:452",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644432,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584672672,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:452",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584672672,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585090560,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:455",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585090560,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585818192,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:303",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585818192,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586600544,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:303",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586600544,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586858784,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:303",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586858784,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587136240,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:303",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587136240,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495989464,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:447",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495989464,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229328720,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:447",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229328720,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290213568,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:447",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290213568,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275086562,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:447",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275086562,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584106624,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:447",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584106624,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584042304,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:447",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584042304,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584090384,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:447",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584090384,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
struct bio * throtl_pop_queued(struct list_head * queued, struct throtl_grp * * tg_to_put)
```

```json
{
  "name": "throtl_pop_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584192336,
      "name": "throtl_pop_queued",
      "external": false,
      "loc": "block/blk-throttle.c:447",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_drain",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:blk_throtl_dispatch_work_fn",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584192336,
      "name": "throtl_pop_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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

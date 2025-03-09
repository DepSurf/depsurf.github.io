# Function: <code>throtl_peek_queued</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bio * throtl_peek_queued(struct list_head * queued)
```

```json
{
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582880640,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:264",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_may_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:tg_drain_bios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880640,
      "name": "throtl_peek_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
struct bio * throtl_peek_queued(struct list_head * queued)
```

```json
{
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583166864,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:258",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166864,
      "name": "throtl_peek_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
struct bio * throtl_peek_queued(struct list_head * queued)
```

```json
{
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583278928,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:258",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583278928,
      "name": "throtl_peek_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583347794,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:424",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bio * throtl_peek_queued(struct list_head * queued)
```

```json
{
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583518656,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:423",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583518656,
      "name": "throtl_peek_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
struct bio * throtl_peek_queued(struct list_head * queued)
```

```json
{
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583732496,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:421",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583732496,
      "name": "throtl_peek_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
struct bio * throtl_peek_queued(struct list_head * queued)
```

```json
{
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583840032,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:420",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583840032,
      "name": "throtl_peek_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
struct bio * throtl_peek_queued(struct list_head * queued)
```

```json
{
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584030144,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:420",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584030144,
      "name": "throtl_peek_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584147405,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:420",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584539660,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:424",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_dispatch_tg",
        "block/blk-throttle.c:throtl_dispatch_tg",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584651584,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:424",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_dispatch_tg",
        "block/blk-throttle.c:throtl_dispatch_tg",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584678802,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:424",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585100565,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:427",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585833130,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:275",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586611039,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:275",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586869490,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:275",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587147375,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:275",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:throtl_pending_timer_fn",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495998052,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:420",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
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
struct bio * throtl_peek_queued(struct list_head * queued)
```

```json
{
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229325844,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:420",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229325844,
      "name": "throtl_peek_queued",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290226756,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:420",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275094352,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:420",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584116141,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:420",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584051821,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:420",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584099901,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:420",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
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
  "name": "throtl_peek_queued",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584203469,
      "name": "throtl_peek_queued",
      "external": false,
      "loc": "block/blk-throttle.c:420",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:tg_drain_bios",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:throtl_select_dispatch",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_update_disptime",
        "block/blk-throttle.c:tg_may_dispatch"
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
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct bio * throtl_peek_queued(struct list_head * queued)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct bio * throtl_peek_queued(struct list_head * queued)
```
</details>
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
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
struct bio * throtl_peek_queued(struct list_head * queued)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct bio * throtl_peek_queued(struct list_head * queued)
```
</details>
</li>
</ul>

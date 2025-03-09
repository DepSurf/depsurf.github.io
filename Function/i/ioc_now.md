# Function: <code>ioc_now</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_now",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584153296,
      "name": "ioc_now",
      "external": false,
      "loc": "block/blk-iocost.c:853",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153296,
      "name": "ioc_now",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_now",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584550784,
      "name": "ioc_now",
      "external": false,
      "loc": "block/blk-iocost.c:851",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584550784,
      "name": "ioc_now",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_now",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584662240,
      "name": "ioc_now",
      "external": false,
      "loc": "block/blk-iocost.c:1027",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584662240,
      "name": "ioc_now",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_now",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584690592,
      "name": "ioc_now",
      "external": false,
      "loc": "block/blk-iocost.c:1023",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584690592,
      "name": "ioc_now",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_now",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585113168,
      "name": "ioc_now",
      "external": false,
      "loc": "block/blk-iocost.c:1023",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585113168,
      "name": "ioc_now",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_now",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585843168,
      "name": "ioc_now",
      "external": false,
      "loc": "block/blk-iocost.c:1022",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585843168,
      "name": "ioc_now",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_now",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586623616,
      "name": "ioc_now",
      "external": false,
      "loc": "block/blk-iocost.c:1026",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586623616,
      "name": "ioc_now",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_now",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586881888,
      "name": "ioc_now",
      "external": false,
      "loc": "block/blk-iocost.c:1042",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586881888,
      "name": "ioc_now",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_now",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587159840,
      "name": "ioc_now",
      "external": false,
      "loc": "block/blk-iocost.c:1042",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_weight_write",
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587159840,
      "name": "ioc_now",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_now",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496003296,
      "name": "ioc_now",
      "external": false,
      "loc": "block/blk-iocost.c:853",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496003296,
      "name": "ioc_now",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_now",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229356632,
      "name": "ioc_now",
      "external": false,
      "loc": "block/blk-iocost.c:853",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229356632,
      "name": "ioc_now",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_now",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290234592,
      "name": "ioc_now",
      "external": false,
      "loc": "block/blk-iocost.c:853",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290234592,
      "name": "ioc_now",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_now",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275099640,
      "name": "ioc_now",
      "external": false,
      "loc": "block/blk-iocost.c:853",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275099640,
      "name": "ioc_now",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_now",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584122032,
      "name": "ioc_now",
      "external": false,
      "loc": "block/blk-iocost.c:853",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584122032,
      "name": "ioc_now",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_now",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584057696,
      "name": "ioc_now",
      "external": false,
      "loc": "block/blk-iocost.c:853",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584057696,
      "name": "ioc_now",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_now",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584105792,
      "name": "ioc_now",
      "external": false,
      "loc": "block/blk-iocost.c:853",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584105792,
      "name": "ioc_now",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_now",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584209648,
      "name": "ioc_now",
      "external": false,
      "loc": "block/blk-iocost.c:853",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584209648,
      "name": "ioc_now",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void ioc_now(struct ioc * ioc, struct ioc_now * now)
```
</details>
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

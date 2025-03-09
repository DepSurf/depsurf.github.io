# Function: <code>qdisc_tree_reduce_backlog</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc * sch, unsigned int n, unsigned int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586912112,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:744",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586912112,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, unsigned int n, unsigned int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587106464,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:750",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587106464,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, unsigned int n, unsigned int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587234784,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:746",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587234784,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, unsigned int n, unsigned int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587750288,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:727",
      "file": "net/sched/sch_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587750288,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, unsigned int n, unsigned int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588088864,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:739",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588088864,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, unsigned int n, unsigned int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588265840,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:761",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588265840,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588657440,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:753",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588657440,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588879824,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:753",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588879824,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589764208,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:762",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589764208,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589798832,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:764",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589798832,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589702704,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:764",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589702704,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590460896,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:770",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590460896,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592063504,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:771",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592063504,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593883376,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:773",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593883376,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594252848,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:781",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594252848,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595050208,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:781",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595050208,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502469528,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:753",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502469528,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235184028,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:753",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235184028,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296025680,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:753",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296025680,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278651988,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:753",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278651988,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588486208,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:753",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588486208,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588198208,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:753",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588198208,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588818384,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:753",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588818384,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
void qdisc_tree_reduce_backlog(struct Qdisc * sch, int n, int len)
```

```json
{
  "name": "qdisc_tree_reduce_backlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588958992,
      "name": "qdisc_tree_reduce_backlog",
      "external": true,
      "loc": "net/sched/sch_api.c:753",
      "file": "net/sched/sch_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_fifo.c:pfifo_tail_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588958992,
      "name": "qdisc_tree_reduce_backlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void qdisc_tree_reduce_backlog(struct Qdisc * sch, unsigned int n, unsigned int len)
```
</details>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int n</code> ➡️ <code>int n</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int len</code> ➡️ <code>int len</code>
</li>
</ul>
</details>
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

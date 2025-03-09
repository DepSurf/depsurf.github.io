# Function: <code>pfifo_tail_enqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586484592,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:38",
      "file": "net/sched/sch_fifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586484592,
      "name": "pfifo_tail_enqueue",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586930992,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:40",
      "file": "net/sched/sch_fifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586930992,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587126000,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:40",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587126000,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587255840,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:40",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587255840,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587775280,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:40",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587775280,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588118224,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:40",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588118224,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588300480,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:40",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588300480,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588698416,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:36",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588698416,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588922304,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:36",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588922304,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589811520,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:37",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589811520,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589847824,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:37",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589847824,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589753184,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:37",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589753184,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590512192,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:37",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590512192,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592118608,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:37",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592118608,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593940928,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:37",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593940928,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594317568,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:37",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594317568,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595117120,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:37",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595117120,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502515272,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:36",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502515272,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235226552,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:36",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235226552,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296085648,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:36",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296085648,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278686994,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:36",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278686994,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588528688,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:36",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588528688,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588240688,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:36",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588240688,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588860864,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:36",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588860864,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int pfifo_tail_enqueue(struct sk_buff * skb, struct Qdisc * sch, struct sk_buff * * to_free)
```

```json
{
  "name": "pfifo_tail_enqueue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589002320,
      "name": "pfifo_tail_enqueue",
      "external": false,
      "loc": "net/sched/sch_fifo.c:36",
      "file": "net/sched/sch_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589002320,
      "name": "pfifo_tail_enqueue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_buff * * to_free</code>
</li>
</ul>
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

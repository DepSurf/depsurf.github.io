# Function: <code>sch_fragment</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int sch_fragment(struct net * net, struct sk_buff * skb, u16 mru, int (*)(struct sk_buff *) xmit)
```

```json
{
  "name": "sch_fragment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_fragment",
      "external": false,
      "loc": "net/sched/sch_frag.c:82",
      "file": "net/sched/sch_frag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_frag.c:sch_frag_xmit_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589787136,
      "name": "sch_fragment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1100
    },
    {
      "addr": 18446744071591633135,
      "name": "sch_fragment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int sch_fragment(struct net * net, struct sk_buff * skb, u16 mru, int (*)(struct sk_buff *) xmit)
```

```json
{
  "name": "sch_fragment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_fragment",
      "external": false,
      "loc": "net/sched/sch_frag.c:82",
      "file": "net/sched/sch_frag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_frag.c:sch_frag_xmit_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589691088,
      "name": "sch_fragment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1130
    },
    {
      "addr": 18446744071591576528,
      "name": "sch_fragment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int sch_fragment(struct net * net, struct sk_buff * skb, u16 mru, int (*)(struct sk_buff *) xmit)
```

```json
{
  "name": "sch_fragment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_fragment",
      "external": false,
      "loc": "net/sched/sch_frag.c:83",
      "file": "net/sched/sch_frag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_frag.c:sch_frag_xmit_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590448800,
      "name": "sch_fragment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1148
    },
    {
      "addr": 18446744071592709609,
      "name": "sch_fragment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int sch_fragment(struct net * net, struct sk_buff * skb, u16 mru, int (*)(struct sk_buff *) xmit)
```

```json
{
  "name": "sch_fragment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sch_fragment",
      "external": false,
      "loc": "net/sched/sch_frag.c:84",
      "file": "net/sched/sch_frag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_frag.c:sch_frag_xmit_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592050528,
      "name": "sch_fragment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1182
    },
    {
      "addr": 18446744071594595928,
      "name": "sch_fragment.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
int sch_fragment(struct net * net, struct sk_buff * skb, u16 mru, int (*)(struct sk_buff *) xmit)
```

```json
{
  "name": "sch_fragment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593869072,
      "name": "sch_fragment",
      "external": false,
      "loc": "net/sched/sch_frag.c:84",
      "file": "net/sched/sch_frag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_frag.c:sch_frag_xmit_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593869072,
      "name": "sch_fragment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1255
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
int sch_fragment(struct net * net, struct sk_buff * skb, u16 mru, int (*)(struct sk_buff *) xmit)
```

```json
{
  "name": "sch_fragment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594243984,
      "name": "sch_fragment",
      "external": false,
      "loc": "net/sched/sch_frag.c:84",
      "file": "net/sched/sch_frag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_frag.c:sch_frag_xmit_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594243984,
      "name": "sch_fragment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1289
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
int sch_fragment(struct net * net, struct sk_buff * skb, u16 mru, int (*)(struct sk_buff *) xmit)
```

```json
{
  "name": "sch_fragment",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595041296,
      "name": "sch_fragment",
      "external": false,
      "loc": "net/sched/sch_frag.c:84",
      "file": "net/sched/sch_frag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_frag.c:sch_frag_xmit_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595041296,
      "name": "sch_fragment",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1274
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int sch_fragment(struct net * net, struct sk_buff * skb, u16 mru, int (*)(struct sk_buff *) xmit)
```
</details>
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

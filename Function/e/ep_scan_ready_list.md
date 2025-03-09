# Function: <code>ep_scan_ready_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ep_scan_ready_list(struct eventpoll * ep, int (*)(struct eventpoll *, struct list_head *, void *) sproc, void * priv, int depth, bool ep_locked)
```

```json
{
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581290896,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:592",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll_readyevents_proc",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581290896,
      "name": "ep_scan_ready_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581455648,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:597",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll_readyevents_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455648,
      "name": "ep_scan_ready_list.constprop.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 523
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581536432,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:597",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll_readyevents_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581536432,
      "name": "ep_scan_ready_list.constprop.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581589408,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:679",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll_readyevents_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581589408,
      "name": "ep_scan_ready_list.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581734032,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:663",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_eventpoll_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581734032,
      "name": "ep_scan_ready_list.constprop.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581901456,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:664",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_eventpoll_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901456,
      "name": "ep_scan_ready_list.constprop.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581987936,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:672",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_eventpoll_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581987936,
      "name": "ep_scan_ready_list.constprop.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582123536,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:668",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_eventpoll_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123536,
      "name": "ep_scan_ready_list.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
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
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582200768,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:668",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_eventpoll_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582200768,
      "name": "ep_scan_ready_list.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582439104,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:677",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_eventpoll_poll",
        "fs/eventpoll.c:ep_item_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582439104,
      "name": "ep_scan_ready_list.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493762240,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:668",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_eventpoll_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493762240,
      "name": "ep_scan_ready_list.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227279824,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:668",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:ep_eventpoll_poll",
        "fs/eventpoll.c:ep_item_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227279824,
      "name": "ep_scan_ready_list.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287373344,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:668",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_eventpoll_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287373344,
      "name": "ep_scan_ready_list.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273362990,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:668",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:ep_eventpoll_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273362990,
      "name": "ep_scan_ready_list.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582169504,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:668",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_eventpoll_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582169504,
      "name": "ep_scan_ready_list.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582104384,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:668",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_eventpoll_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582104384,
      "name": "ep_scan_ready_list.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582159984,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:668",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_eventpoll_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582159984,
      "name": "ep_scan_ready_list.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ep_scan_ready_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582230528,
      "name": "ep_scan_ready_list",
      "external": false,
      "loc": "fs/eventpoll.c:668",
      "file": "fs/eventpoll.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_eventpoll_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582230528,
      "name": "ep_scan_ready_list.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int ep_scan_ready_list(struct eventpoll * ep, int (*)(struct eventpoll *, struct list_head *, void *) sproc, void * priv, int depth, bool ep_locked)
```
</details>
</li>
</ul>

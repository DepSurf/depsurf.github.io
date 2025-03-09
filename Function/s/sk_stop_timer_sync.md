# Function: <code>sk_stop_timer_sync</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void sk_stop_timer_sync(struct sock * sk, struct timer_list * timer)
```

```json
{
  "name": "sk_stop_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589218208,
      "name": "sk_stop_timer_sync",
      "external": true,
      "loc": "net/core/sock.c:2958",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589218208,
      "name": "sk_stop_timer_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void sk_stop_timer_sync(struct sock * sk, struct timer_list * timer)
```

```json
{
  "name": "sk_stop_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589111840,
      "name": "sk_stop_timer_sync",
      "external": true,
      "loc": "net/core/sock.c:2981",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589111840,
      "name": "sk_stop_timer_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void sk_stop_timer_sync(struct sock * sk, struct timer_list * timer)
```

```json
{
  "name": "sk_stop_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589828688,
      "name": "sk_stop_timer_sync",
      "external": true,
      "loc": "net/core/sock.c:3112",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589828688,
      "name": "sk_stop_timer_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void sk_stop_timer_sync(struct sock * sk, struct timer_list * timer)
```

```json
{
  "name": "sk_stop_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591353120,
      "name": "sk_stop_timer_sync",
      "external": true,
      "loc": "net/core/sock.c:3297",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591353120,
      "name": "sk_stop_timer_sync",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sk_stop_timer_sync(struct sock * sk, struct timer_list * timer)
```

```json
{
  "name": "sk_stop_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593104912,
      "name": "sk_stop_timer_sync",
      "external": true,
      "loc": "net/core/sock.c:3377",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593104912,
      "name": "sk_stop_timer_sync",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sk_stop_timer_sync(struct sock * sk, struct timer_list * timer)
```

```json
{
  "name": "sk_stop_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593560256,
      "name": "sk_stop_timer_sync",
      "external": true,
      "loc": "net/core/sock.c:3410",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593560256,
      "name": "sk_stop_timer_sync",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sk_stop_timer_sync(struct sock * sk, struct timer_list * timer)
```

```json
{
  "name": "sk_stop_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594328944,
      "name": "sk_stop_timer_sync",
      "external": true,
      "loc": "net/core/sock.c:3420",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594328944,
      "name": "sk_stop_timer_sync",
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
void sk_stop_timer_sync(struct sock * sk, struct timer_list * timer)
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

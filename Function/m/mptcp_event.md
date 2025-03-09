# Function: <code>mptcp_event</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void mptcp_event(enum mptcp_event_type type, const struct mptcp_sock * msk, const struct sock * ssk, gfp_t gfp)
```

```json
{
  "name": "mptcp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591147760,
      "name": "mptcp_event",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:1793",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_join",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/pm.c:mptcp_pm_mp_prio_received",
        "net/mptcp/pm.c:mptcp_pm_fully_established",
        "net/mptcp/pm.c:mptcp_pm_new_connection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591147760,
      "name": "mptcp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
void mptcp_event(enum mptcp_event_type type, const struct mptcp_sock * msk, const struct sock * ssk, gfp_t gfp)
```

```json
{
  "name": "mptcp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591998768,
      "name": "mptcp_event",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:1983",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_join",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/pm.c:mptcp_pm_mp_prio_received",
        "net/mptcp/pm.c:mptcp_pm_fully_established",
        "net/mptcp/pm.c:mptcp_pm_new_connection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591998768,
      "name": "mptcp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 702
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
void mptcp_event(enum mptcp_event_type type, const struct mptcp_sock * msk, const struct sock * ssk, gfp_t gfp)
```

```json
{
  "name": "mptcp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_event",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:2145",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_join",
        "net/mptcp/protocol.c:mptcp_disconnect",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/pm.c:mptcp_pm_mp_prio_received",
        "net/mptcp/pm.c:mptcp_pm_fully_established",
        "net/mptcp/pm.c:mptcp_pm_new_connection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594642329,
      "name": "mptcp_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071593732816,
      "name": "mptcp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 743
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_event(enum mptcp_event_type type, const struct mptcp_sock * msk, const struct sock * ssk, gfp_t gfp)
```

```json
{
  "name": "mptcp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_event",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:2211",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_join",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/pm.c:mptcp_pm_mp_prio_received",
        "net/mptcp/pm.c:mptcp_pm_fully_established",
        "net/mptcp/pm.c:mptcp_pm_new_connection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596371607,
      "name": "mptcp_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071595668784,
      "name": "mptcp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 743
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_event(enum mptcp_event_type type, const struct mptcp_sock * msk, const struct sock * ssk, gfp_t gfp)
```

```json
{
  "name": "mptcp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_event",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:2227",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_join",
        "net/mptcp/protocol.c:mptcp_disconnect",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/pm.c:mptcp_pm_mp_prio_received",
        "net/mptcp/pm.c:mptcp_pm_fully_established",
        "net/mptcp/pm.c:mptcp_pm_new_connection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596900841,
      "name": "mptcp_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071596177856,
      "name": "mptcp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 745
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_event(enum mptcp_event_type type, const struct mptcp_sock * msk, const struct sock * ssk, gfp_t gfp)
```

```json
{
  "name": "mptcp_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_event",
      "external": true,
      "loc": "net/mptcp/pm_netlink.c:2226",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/protocol.c:mptcp_finish_join",
        "net/mptcp/protocol.c:mptcp_disconnect",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/pm.c:mptcp_pm_mp_prio_received",
        "net/mptcp/pm.c:mptcp_pm_fully_established",
        "net/mptcp/pm.c:mptcp_pm_new_connection"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597826057,
      "name": "mptcp_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071597052448,
      "name": "mptcp_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 698
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void mptcp_event(enum mptcp_event_type type, const struct mptcp_sock * msk, const struct sock * ssk, gfp_t gfp)
```
</details>
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

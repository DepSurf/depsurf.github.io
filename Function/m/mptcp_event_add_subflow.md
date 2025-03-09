# Function: <code>mptcp_event_add_subflow</code>

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
int mptcp_event_add_subflow(struct sk_buff * skb, const struct sock * ssk)
```

```json
{
  "name": "mptcp_event_add_subflow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591133440,
      "name": "mptcp_event_add_subflow",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:1587",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591133440,
      "name": "mptcp_event_add_subflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
int mptcp_event_add_subflow(struct sk_buff * skb, const struct sock * ssk)
```

```json
{
  "name": "mptcp_event_add_subflow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_event_add_subflow",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:1777",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591982976,
      "name": "mptcp_event_add_subflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    },
    {
      "addr": 18446744071592755181,
      "name": "mptcp_event_add_subflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int mptcp_event_add_subflow(struct sk_buff * skb, const struct sock * ssk)
```

```json
{
  "name": "mptcp_event_add_subflow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_event_add_subflow",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:1931",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593713552,
      "name": "mptcp_event_add_subflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
    },
    {
      "addr": 18446744071594642179,
      "name": "mptcp_event_add_subflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int mptcp_event_add_subflow(struct sk_buff * skb, const struct sock * ssk)
```

```json
{
  "name": "mptcp_event_add_subflow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_event_add_subflow",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:1945",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595651072,
      "name": "mptcp_event_add_subflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
    },
    {
      "addr": 18446744071596371502,
      "name": "mptcp_event_add_subflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int mptcp_event_add_subflow(struct sk_buff * skb, const struct sock * ssk)
```

```json
{
  "name": "mptcp_event_add_subflow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_event_add_subflow",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:1961",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596159904,
      "name": "mptcp_event_add_subflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071596900749,
      "name": "mptcp_event_add_subflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int mptcp_event_add_subflow(struct sk_buff * skb, const struct sock * ssk)
```

```json
{
  "name": "mptcp_event_add_subflow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_event_add_subflow",
      "external": false,
      "loc": "net/mptcp/pm_netlink.c:1960",
      "file": "net/mptcp/pm_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_put_token_and_ssk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597034272,
      "name": "mptcp_event_add_subflow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
    },
    {
      "addr": 18446744071597825955,
      "name": "mptcp_event_add_subflow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int mptcp_event_add_subflow(struct sk_buff * skb, const struct sock * ssk)
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

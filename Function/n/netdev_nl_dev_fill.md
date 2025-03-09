# Function: <code>netdev_nl_dev_fill</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netdev_nl_dev_fill",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594036720,
      "name": "netdev_nl_dev_fill",
      "external": false,
      "loc": "net/core/netdev-genl.c:12",
      "file": "net/core/netdev-genl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/netdev-genl.c:netdev_nl_dev_get_dumpit",
        "net/core/netdev-genl.c:netdev_nl_dev_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594036720,
      "name": "netdev_nl_dev_fill.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
int netdev_nl_dev_fill(struct net_device * netdev, struct sk_buff * rsp, const struct genl_info * info)
```

```json
{
  "name": "netdev_nl_dev_fill",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594824736,
      "name": "netdev_nl_dev_fill",
      "external": false,
      "loc": "net/core/netdev-genl.c:31",
      "file": "net/core/netdev-genl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/netdev-genl.c:netdev_nl_dev_get_dumpit",
        "net/core/netdev-genl.c:netdev_nl_dev_get_doit",
        "net/core/netdev-genl.c:netdev_genl_dev_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594824736,
      "name": "netdev_nl_dev_fill",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int netdev_nl_dev_fill(struct net_device * netdev, struct sk_buff * rsp, const struct genl_info * info)
```
</details>
</li>
</ul>

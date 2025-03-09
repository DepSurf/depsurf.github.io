# Function: <code>devlink_get_from_attrs_lock</code>

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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct devlink * devlink_get_from_attrs_lock(struct net * net, struct nlattr * * attrs)
```

```json
{
  "name": "devlink_get_from_attrs_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595894560,
      "name": "devlink_get_from_attrs_lock",
      "external": true,
      "loc": "net/devlink/netlink.c:86",
      "file": "net/devlink/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit",
        "net/devlink/netlink.c:devlink_nl_pre_doit",
        "net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595894560,
      "name": "devlink_get_from_attrs_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
struct devlink * devlink_get_from_attrs_lock(struct net * net, struct nlattr * * attrs, bool dev_lock)
```

```json
{
  "name": "devlink_get_from_attrs_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596677200,
      "name": "devlink_get_from_attrs_lock",
      "external": true,
      "loc": "net/devlink/netlink.c:181",
      "file": "net/devlink/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/netlink.c:devlink_nl_dumpit",
        "net/devlink/netlink.c:devlink_nl_pre_doit_port_optional",
        "net/devlink/netlink.c:devlink_nl_pre_doit_dev_lock",
        "net/devlink/netlink.c:devlink_nl_pre_doit_port",
        "net/devlink/netlink.c:devlink_nl_pre_doit",
        "net/devlink/region.c:devlink_nl_region_read_dumpit",
        "net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596677200,
      "name": "devlink_get_from_attrs_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 457
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct devlink * devlink_get_from_attrs_lock(struct net * net, struct nlattr * * attrs)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool dev_lock</code>
</li>
</ul>
</details>
</li>
</ul>

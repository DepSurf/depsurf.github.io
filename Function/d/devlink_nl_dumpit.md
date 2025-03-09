# Function: <code>devlink_nl_dumpit</code>

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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int devlink_nl_dumpit(struct sk_buff * msg, struct netlink_callback * cb, devlink_nl_dump_one_func_t * dump_one)
```

```json
{
  "name": "devlink_nl_dumpit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596678256,
      "name": "devlink_nl_dumpit",
      "external": true,
      "loc": "net/devlink/netlink.c:346",
      "file": "net/devlink/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/dev.c:devlink_nl_selftests_get_dumpit",
        "net/devlink/dev.c:devlink_nl_info_get_dumpit",
        "net/devlink/dev.c:devlink_nl_get_dumpit",
        "net/devlink/port.c:devlink_nl_port_get_dumpit",
        "net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_get_dumpit",
        "net/devlink/sb.c:devlink_nl_sb_port_pool_get_dumpit",
        "net/devlink/sb.c:devlink_nl_sb_pool_get_dumpit",
        "net/devlink/sb.c:devlink_nl_sb_get_dumpit",
        "net/devlink/param.c:devlink_nl_param_get_dumpit",
        "net/devlink/region.c:devlink_nl_region_get_dumpit",
        "net/devlink/health.c:devlink_nl_health_reporter_get_dumpit",
        "net/devlink/trap.c:devlink_nl_trap_policer_get_dumpit",
        "net/devlink/trap.c:devlink_nl_trap_group_get_dumpit",
        "net/devlink/trap.c:devlink_nl_trap_get_dumpit",
        "net/devlink/rate.c:devlink_nl_rate_get_dumpit",
        "net/devlink/linecard.c:devlink_nl_linecard_get_dumpit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596678256,
      "name": "devlink_nl_dumpit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
int devlink_nl_dumpit(struct sk_buff * msg, struct netlink_callback * cb, devlink_nl_dump_one_func_t * dump_one)
```
</details>
</li>
</ul>

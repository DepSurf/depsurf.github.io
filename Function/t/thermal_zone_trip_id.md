# Function: <code>thermal_zone_trip_id</code>

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
int thermal_zone_trip_id(const struct thermal_zone_device * tz, const struct thermal_trip * trip)
```

```json
{
  "name": "thermal_zone_trip_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593536272,
      "name": "thermal_zone_trip_id",
      "external": true,
      "loc": "drivers/thermal/thermal_trip.c:146",
      "file": "drivers/thermal/thermal_trip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_sysfs.c:trip_point_show",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip",
        "drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_change",
        "drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_up",
        "drivers/thermal/thermal_netlink.c:thermal_notify_tz_trip_down",
        "drivers/thermal/gov_fair_share.c:fair_share_throttle",
        "drivers/thermal/gov_bang_bang.c:thermal_zone_trip_update",
        "drivers/thermal/gov_step_wise.c:thermal_zone_trip_update",
        "drivers/thermal/gov_user_space.c:notify_user_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593536272,
      "name": "thermal_zone_trip_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int thermal_zone_trip_id(const struct thermal_zone_device * tz, const struct thermal_trip * trip)
```
</details>
</li>
</ul>

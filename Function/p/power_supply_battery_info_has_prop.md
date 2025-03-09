# Function: <code>power_supply_battery_info_has_prop</code>

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
bool power_supply_battery_info_has_prop(struct power_supply_battery_info * info, enum power_supply_property psp)
```

```json
{
  "name": "power_supply_battery_info_has_prop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592727952,
      "name": "power_supply_battery_info_has_prop",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:864",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:power_supply_battery_info_get_prop",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_attr_is_visible"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592727952,
      "name": "power_supply_battery_info_has_prop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
bool power_supply_battery_info_has_prop(struct power_supply_battery_info * info, enum power_supply_property psp)
```

```json
{
  "name": "power_supply_battery_info_has_prop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593475808,
      "name": "power_supply_battery_info_has_prop",
      "external": true,
      "loc": "drivers/power/supply/power_supply_core.c:863",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/power_supply_core.c:power_supply_battery_info_get_prop",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_uevent",
        "drivers/power/supply/power_supply_sysfs.c:power_supply_attr_is_visible"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593475808,
      "name": "power_supply_battery_info_has_prop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
bool power_supply_battery_info_has_prop(struct power_supply_battery_info * info, enum power_supply_property psp)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

# Function: <code>power_supply_charge_behaviour_show</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t power_supply_charge_behaviour_show(struct device * dev, unsigned int available_behaviours, enum power_supply_charge_behaviour current_behaviour, char * buf)
```

```json
{
  "name": "power_supply_charge_behaviour_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "power_supply_charge_behaviour_show",
      "external": true,
      "loc": "drivers/power/supply/power_supply_sysfs.c:497",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594517088,
      "name": "power_supply_charge_behaviour_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071590647744,
      "name": "power_supply_charge_behaviour_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
ssize_t power_supply_charge_behaviour_show(struct device * dev, unsigned int available_behaviours, enum power_supply_charge_behaviour current_behaviour, char * buf)
```

```json
{
  "name": "power_supply_charge_behaviour_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592312240,
      "name": "power_supply_charge_behaviour_show",
      "external": true,
      "loc": "drivers/power/supply/power_supply_sysfs.c:497",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592312240,
      "name": "power_supply_charge_behaviour_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
ssize_t power_supply_charge_behaviour_show(struct device * dev, unsigned int available_behaviours, enum power_supply_charge_behaviour current_behaviour, char * buf)
```

```json
{
  "name": "power_supply_charge_behaviour_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592738208,
      "name": "power_supply_charge_behaviour_show",
      "external": true,
      "loc": "drivers/power/supply/power_supply_sysfs.c:519",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592738208,
      "name": "power_supply_charge_behaviour_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
ssize_t power_supply_charge_behaviour_show(struct device * dev, unsigned int available_behaviours, enum power_supply_charge_behaviour current_behaviour, char * buf)
```

```json
{
  "name": "power_supply_charge_behaviour_show",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593486160,
      "name": "power_supply_charge_behaviour_show",
      "external": true,
      "loc": "drivers/power/supply/power_supply_sysfs.c:520",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593486160,
      "name": "power_supply_charge_behaviour_show",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
ssize_t power_supply_charge_behaviour_show(struct device * dev, unsigned int available_behaviours, enum power_supply_charge_behaviour current_behaviour, char * buf)
```
</details>
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

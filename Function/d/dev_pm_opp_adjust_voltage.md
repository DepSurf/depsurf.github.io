# Function: <code>dev_pm_opp_adjust_voltage</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int dev_pm_opp_adjust_voltage(struct device * dev, long unsigned int freq, long unsigned int u_volt)
```

```json
{
  "name": "dev_pm_opp_adjust_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587060336,
      "name": "dev_pm_opp_adjust_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:1772",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587060336,
      "name": "dev_pm_opp_adjust_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int dev_pm_opp_adjust_voltage(struct device * dev, long unsigned int freq, long unsigned int u_volt)
```

```json
{
  "name": "dev_pm_opp_adjust_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587358496,
      "name": "dev_pm_opp_adjust_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:1663",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587358496,
      "name": "dev_pm_opp_adjust_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_pm_opp_adjust_voltage(struct device * dev, long unsigned int freq, long unsigned int u_volt, long unsigned int u_volt_min, long unsigned int u_volt_max)
```

```json
{
  "name": "dev_pm_opp_adjust_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_adjust_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:2231",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588878435,
      "name": "dev_pm_opp_adjust_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071588875920,
      "name": "dev_pm_opp_adjust_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 499
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_pm_opp_adjust_voltage(struct device * dev, long unsigned int freq, long unsigned int u_volt, long unsigned int u_volt_min, long unsigned int u_volt_max)
```

```json
{
  "name": "dev_pm_opp_adjust_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_adjust_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:2328",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591596889,
      "name": "dev_pm_opp_adjust_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071588884608,
      "name": "dev_pm_opp_adjust_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 499
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_pm_opp_adjust_voltage(struct device * dev, long unsigned int freq, long unsigned int u_volt, long unsigned int u_volt_min, long unsigned int u_volt_max)
```

```json
{
  "name": "dev_pm_opp_adjust_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_adjust_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:2702",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591539870,
      "name": "dev_pm_opp_adjust_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071588772208,
      "name": "dev_pm_opp_adjust_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 495
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
int dev_pm_opp_adjust_voltage(struct device * dev, long unsigned int freq, long unsigned int u_volt, long unsigned int u_volt_min, long unsigned int u_volt_max)
```

```json
{
  "name": "dev_pm_opp_adjust_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_adjust_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:2712",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592654333,
      "name": "dev_pm_opp_adjust_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071589464176,
      "name": "dev_pm_opp_adjust_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 495
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
int dev_pm_opp_adjust_voltage(struct device * dev, long unsigned int freq, long unsigned int u_volt, long unsigned int u_volt_min, long unsigned int u_volt_max)
```

```json
{
  "name": "dev_pm_opp_adjust_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_adjust_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:2852",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594538961,
      "name": "dev_pm_opp_adjust_voltage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071590941856,
      "name": "dev_pm_opp_adjust_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
int dev_pm_opp_adjust_voltage(struct device * dev, long unsigned int freq, long unsigned int u_volt, long unsigned int u_volt_min, long unsigned int u_volt_max)
```

```json
{
  "name": "dev_pm_opp_adjust_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592643744,
      "name": "dev_pm_opp_adjust_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:2854",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592643744,
      "name": "dev_pm_opp_adjust_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
int dev_pm_opp_adjust_voltage(struct device * dev, long unsigned int freq, long unsigned int u_volt, long unsigned int u_volt_min, long unsigned int u_volt_max)
```

```json
{
  "name": "dev_pm_opp_adjust_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593074240,
      "name": "dev_pm_opp_adjust_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:2868",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593074240,
      "name": "dev_pm_opp_adjust_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
int dev_pm_opp_adjust_voltage(struct device * dev, long unsigned int freq, long unsigned int u_volt, long unsigned int u_volt_min, long unsigned int u_volt_max)
```

```json
{
  "name": "dev_pm_opp_adjust_voltage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593826160,
      "name": "dev_pm_opp_adjust_voltage",
      "external": true,
      "loc": "drivers/opp/core.c:2952",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593826160,
      "name": "dev_pm_opp_adjust_voltage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int dev_pm_opp_adjust_voltage(struct device * dev, long unsigned int freq, long unsigned int u_volt)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int dev_pm_opp_adjust_voltage(struct device * dev, long unsigned int freq, long unsigned int u_volt)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int dev_pm_opp_adjust_voltage(struct device * dev, long unsigned int freq, long unsigned int u_volt, long unsigned int u_volt_min, long unsigned int u_volt_max)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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

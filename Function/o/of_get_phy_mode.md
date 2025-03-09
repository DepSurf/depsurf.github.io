# Function: <code>of_get_phy_mode</code>

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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int of_get_phy_mode(struct device_node * np)
```

```json
{
  "name": "of_get_phy_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501646736,
      "name": "of_get_phy_mode",
      "external": true,
      "loc": "drivers/of/of_net.c:23",
      "file": "drivers/of/of_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fman/mac.c:mac_probe",
        "drivers/of/of_mdio.c:of_phy_get_and_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501646736,
      "name": "of_get_phy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int of_get_phy_mode(struct device_node * np)
```

```json
{
  "name": "of_get_phy_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234167240,
      "name": "of_get_phy_mode",
      "external": true,
      "loc": "drivers/of/of_net.c:23",
      "file": "drivers/of/of_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe_dt",
        "drivers/of/of_mdio.c:of_phy_get_and_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234167240,
      "name": "of_get_phy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int of_get_phy_mode(struct device_node * np)
```

```json
{
  "name": "of_get_phy_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295085296,
      "name": "of_get_phy_mode",
      "external": true,
      "loc": "drivers/of/of_net.c:23",
      "file": "drivers/of/of_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/of_mdio.c:of_phy_get_and_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295085296,
      "name": "of_get_phy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int of_get_phy_mode(struct device_node * np)
```

```json
{
  "name": "of_get_phy_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278105318,
      "name": "of_get_phy_mode",
      "external": true,
      "loc": "drivers/of/of_net.c:23",
      "file": "drivers/of/of_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/of_mdio.c:of_phy_get_and_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278105318,
      "name": "of_get_phy_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int of_get_phy_mode(struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_get_phy_mode(struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_get_phy_mode(struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_get_phy_mode(struct device_node * np)
```
</details>
</li>
</ul>

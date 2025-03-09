# Function: <code>of_phy_find_device</code>

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
struct phy_device * of_phy_find_device(struct device_node * phy_np)
```

```json
{
  "name": "of_phy_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501648064,
      "name": "of_phy_find_device",
      "external": true,
      "loc": "drivers/of/of_mdio.c:291",
      "file": "drivers/of/of_mdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fman/mac.c:mac_probe",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_config",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_config",
        "drivers/of/of_mdio.c:of_phy_deregister_fixed_link",
        "drivers/of/of_mdio.c:of_phy_attach",
        "drivers/of/of_mdio.c:of_phy_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501648064,
      "name": "of_phy_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct phy_device * of_phy_find_device(struct device_node * phy_np)
```

```json
{
  "name": "of_phy_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234168488,
      "name": "of_phy_find_device",
      "external": true,
      "loc": "drivers/of/of_mdio.c:291",
      "file": "drivers/of/of_mdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/of_mdio.c:of_phy_deregister_fixed_link",
        "drivers/of/of_mdio.c:of_phy_attach",
        "drivers/of/of_mdio.c:of_phy_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234168488,
      "name": "of_phy_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct phy_device * of_phy_find_device(struct device_node * phy_np)
```

```json
{
  "name": "of_phy_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295087008,
      "name": "of_phy_find_device",
      "external": true,
      "loc": "drivers/of/of_mdio.c:291",
      "file": "drivers/of/of_mdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/of_mdio.c:of_phy_deregister_fixed_link",
        "drivers/of/of_mdio.c:of_phy_attach",
        "drivers/of/of_mdio.c:of_phy_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295087008,
      "name": "of_phy_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct phy_device * of_phy_find_device(struct device_node * phy_np)
```

```json
{
  "name": "of_phy_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278106356,
      "name": "of_phy_find_device",
      "external": true,
      "loc": "drivers/of/of_mdio.c:291",
      "file": "drivers/of/of_mdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/of_mdio.c:of_phy_deregister_fixed_link",
        "drivers/of/of_mdio.c:of_phy_attach",
        "drivers/of/of_mdio.c:of_phy_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278106356,
      "name": "of_phy_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct phy_device * of_phy_find_device(struct device_node * phy_np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct phy_device * of_phy_find_device(struct device_node * phy_np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct phy_device * of_phy_find_device(struct device_node * phy_np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct phy_device * of_phy_find_device(struct device_node * phy_np)
```
</details>
</li>
</ul>

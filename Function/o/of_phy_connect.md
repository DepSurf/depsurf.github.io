# Function: <code>of_phy_connect</code>

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
struct phy_device * of_phy_connect(struct net_device * dev, struct device_node * phy_np, void (*)(struct net_device *) hndlr, u32 flags, phy_interface_t iface)
```

```json
{
  "name": "of_phy_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501648176,
      "name": "of_phy_connect",
      "external": true,
      "loc": "drivers/of/of_mdio.c:323",
      "file": "drivers/of/of_mdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe",
        "drivers/of/of_mdio.c:of_phy_get_and_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501648176,
      "name": "of_phy_connect",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct phy_device * of_phy_connect(struct net_device * dev, struct device_node * phy_np, void (*)(struct net_device *) hndlr, u32 flags, phy_interface_t iface)
```

```json
{
  "name": "of_phy_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234168596,
      "name": "of_phy_connect",
      "external": true,
      "loc": "drivers/of/of_mdio.c:323",
      "file": "drivers/of/of_mdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_mii_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_slave_open",
        "drivers/of/of_mdio.c:of_phy_get_and_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234168596,
      "name": "of_phy_connect",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct phy_device * of_phy_connect(struct net_device * dev, struct device_node * phy_np, void (*)(struct net_device *) hndlr, u32 flags, phy_interface_t iface)
```

```json
{
  "name": "of_phy_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295087168,
      "name": "of_phy_connect",
      "external": true,
      "loc": "drivers/of/of_mdio.c:323",
      "file": "drivers/of/of_mdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/of_mdio.c:of_phy_get_and_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295087168,
      "name": "of_phy_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct phy_device * of_phy_connect(struct net_device * dev, struct device_node * phy_np, void (*)(struct net_device *) hndlr, u32 flags, phy_interface_t iface)
```

```json
{
  "name": "of_phy_connect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278106454,
      "name": "of_phy_connect",
      "external": true,
      "loc": "drivers/of/of_mdio.c:323",
      "file": "drivers/of/of_mdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/of_mdio.c:of_phy_get_and_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278106454,
      "name": "of_phy_connect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct phy_device * of_phy_connect(struct net_device * dev, struct device_node * phy_np, void (*)(struct net_device *) hndlr, u32 flags, phy_interface_t iface)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct phy_device * of_phy_connect(struct net_device * dev, struct device_node * phy_np, void (*)(struct net_device *) hndlr, u32 flags, phy_interface_t iface)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct phy_device * of_phy_connect(struct net_device * dev, struct device_node * phy_np, void (*)(struct net_device *) hndlr, u32 flags, phy_interface_t iface)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct phy_device * of_phy_connect(struct net_device * dev, struct device_node * phy_np, void (*)(struct net_device *) hndlr, u32 flags, phy_interface_t iface)
```
</details>
</li>
</ul>

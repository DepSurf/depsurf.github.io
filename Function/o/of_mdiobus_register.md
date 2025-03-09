# Function: <code>of_mdiobus_register</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int of_mdiobus_register(struct mii_bus * mdio, struct device_node * np)
```

```json
{
  "name": "of_mdiobus_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501649184,
      "name": "of_mdiobus_register",
      "external": true,
      "loc": "drivers/of/of_mdio.c:199",
      "file": "drivers/of/of_mdio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio-mux.c:mdio_mux_init",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501649184,
      "name": "of_mdiobus_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    },
    {
      "addr": 18446603336501649920,
      "name": "of_mdiobus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int of_mdiobus_register(struct mii_bus * mdio, struct device_node * np)
```

```json
{
  "name": "of_mdiobus_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234169556,
      "name": "of_mdiobus_register",
      "external": true,
      "loc": "drivers/of/of_mdio.c:199",
      "file": "drivers/of/of_mdio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_probe",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234169556,
      "name": "of_mdiobus_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 756
    },
    {
      "addr": 3234170312,
      "name": "of_mdiobus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int of_mdiobus_register(struct mii_bus * mdio, struct device_node * np)
```

```json
{
  "name": "of_mdiobus_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295088848,
      "name": "of_mdiobus_register",
      "external": true,
      "loc": "drivers/of/of_mdio.c:199",
      "file": "drivers/of/of_mdio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295088848,
      "name": "of_mdiobus_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1052
    },
    {
      "addr": 13835058055295089904,
      "name": "of_mdiobus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int of_mdiobus_register(struct mii_bus * mdio, struct device_node * np)
```

```json
{
  "name": "of_mdiobus_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278107266,
      "name": "of_mdiobus_register",
      "external": true,
      "loc": "drivers/of/of_mdio.c:199",
      "file": "drivers/of/of_mdio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278107266,
      "name": "of_mdiobus_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 602
    },
    {
      "addr": 18446743936278107868,
      "name": "of_mdiobus_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int of_mdiobus_register(struct mii_bus * mdio, struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_mdiobus_register(struct mii_bus * mdio, struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_mdiobus_register(struct mii_bus * mdio, struct device_node * np)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_mdiobus_register(struct mii_bus * mdio, struct device_node * np)
```
</details>
</li>
</ul>

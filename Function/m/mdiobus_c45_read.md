# Function: <code>mdiobus_c45_read</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mdiobus_c45_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587769525,
      "name": "mdiobus_c45_read",
      "external": false,
      "loc": "include/linux/mdio.h:354",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mdiobus_c45_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587837011,
      "name": "mdiobus_c45_read",
      "external": false,
      "loc": "include/linux/mdio.h:355",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:phy_c45_probe_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mdiobus_c45_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587717172,
      "name": "mdiobus_c45_read",
      "external": false,
      "loc": "include/linux/mdio.h:368",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:phy_c45_probe_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mdiobus_c45_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588309940,
      "name": "mdiobus_c45_read",
      "external": false,
      "loc": "include/linux/mdio.h:371",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:phy_c45_probe_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mdiobus_c45_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589669958,
      "name": "mdiobus_c45_read",
      "external": false,
      "loc": "include/linux/mdio.h:479",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589698212,
      "name": "mdiobus_c45_read",
      "external": false,
      "loc": "include/linux/mdio.h:479",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:phy_c45_probe_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mdiobus_c45_read",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591284118,
      "name": "mdiobus_c45_read",
      "external": false,
      "loc": "include/linux/mdio.h:479",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591311556,
      "name": "mdiobus_c45_read",
      "external": false,
      "loc": "include/linux/mdio.h:479",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:phy_c45_probe_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mdiobus_c45_read(struct mii_bus * bus, int addr, int devad, u32 regnum)
```

```json
{
  "name": "mdiobus_c45_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591682720,
      "name": "mdiobus_c45_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:1072",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:phy_c45_probe_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591682720,
      "name": "mdiobus_c45_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mdiobus_c45_read(struct mii_bus * bus, int addr, int devad, u32 regnum)
```

```json
{
  "name": "mdiobus_c45_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592428192,
      "name": "mdiobus_c45_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:1090",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:phy_c45_probe_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592428192,
      "name": "mdiobus_c45_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int mdiobus_c45_read(struct mii_bus * bus, int addr, int devad, u32 regnum)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

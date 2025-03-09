# Function: <code>__mdiobus_write</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586420832,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:566",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_modify",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586420832,
      "name": "__mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586567056,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:565",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_modify",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586567056,
      "name": "__mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586818336,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:582",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586818336,
      "name": "__mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586964448,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:574",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586964448,
      "name": "__mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587785440,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:821",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify",
        "drivers/net/phy/mdio_bus.c:mdiobus_write",
        "drivers/net/phy/mdio_bus.c:mdiobus_write_nested"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587785440,
      "name": "__mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587843840,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:765",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587843840,
      "name": "__mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587723216,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:764",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587723216,
      "name": "__mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588316432,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:775",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588316432,
      "name": "__mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589707120,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:782",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify_changed",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589707120,
      "name": "__mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591322016,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:787",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify_changed",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591322016,
      "name": "__mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591682976,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:871",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify_changed",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591682976,
      "name": "__mdiobus_write",
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
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592425712,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:889",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_package_read_mmd",
        "drivers/net/phy/phy-core.c:__phy_package_read_mmd",
        "drivers/net/phy/phy-core.c:__phy_package_read_mmd",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify_changed",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592425712,
      "name": "__mdiobus_write",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499952160,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:574",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499952160,
      "name": "__mdiobus_write",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232493056,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:574",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232493056,
      "name": "__mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293276560,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:574",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/mdio_bus.c:mdiobus_write",
        "drivers/net/phy/mdio_bus.c:mdiobus_write_nested"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293276560,
      "name": "__mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277033880,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:574",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277033880,
      "name": "__mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586721456,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:574",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721456,
      "name": "__mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586589760,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:574",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586589760,
      "name": "__mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586919008,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:574",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586919008,
      "name": "__mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "__mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587025424,
      "name": "__mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:574",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_write_mmd",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect",
        "drivers/net/phy/phy-core.c:mmd_phy_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025424,
      "name": "__mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int __mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

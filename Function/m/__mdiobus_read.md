# Function: <code>__mdiobus_read</code>

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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586421904,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:541",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:__phy_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586421904,
      "name": "__mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586566016,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:540",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:__phy_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586566016,
      "name": "__mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586817024,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:557",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_read_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586817024,
      "name": "__mdiobus_read",
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586963200,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:549",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_read_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586963200,
      "name": "__mdiobus_read",
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587785952,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:795",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify",
        "drivers/net/phy/mdio_bus.c:mdiobus_read",
        "drivers/net/phy/mdio_bus.c:mdiobus_read_nested"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587785952,
      "name": "__mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587844240,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:739",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587844240,
      "name": "__mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587724400,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:738",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587724400,
      "name": "__mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588317728,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:749",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588317728,
      "name": "__mdiobus_read",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589704848,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:756",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify_changed",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589704848,
      "name": "__mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591323664,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:761",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify_changed",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591323664,
      "name": "__mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591683680,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:842",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify_changed",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591683680,
      "name": "__mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592426416,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:860",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:__phy_package_read_mmd",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify_changed",
        "drivers/net/phy/mdio_bus.c:mdiobus_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592426416,
      "name": "__mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499951648,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:549",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_read_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499951648,
      "name": "__mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232494224,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:549",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_read_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232494224,
      "name": "__mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293278096,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:549",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_read_mmd",
        "drivers/net/phy/mdio_bus.c:mdiobus_read",
        "drivers/net/phy/mdio_bus.c:mdiobus_read_nested"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293278096,
      "name": "__mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277035074,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:549",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_read_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277035074,
      "name": "__mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586720208,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:549",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_read_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586720208,
      "name": "__mdiobus_read",
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586588512,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:549",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_read_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586588512,
      "name": "__mdiobus_read",
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586917760,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:549",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_read_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586917760,
      "name": "__mdiobus_read",
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "__mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587024144,
      "name": "__mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:549",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:__phy_modify_changed",
        "drivers/net/phy/phy-core.c:__phy_read_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587024144,
      "name": "__mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
int __mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
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

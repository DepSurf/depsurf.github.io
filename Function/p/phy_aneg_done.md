# Function: <code>phy_aneg_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585049689,
      "name": "phy_aneg_done",
      "external": false,
      "loc": "drivers/net/phy/phy.c:146",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585437112,
      "name": "phy_aneg_done",
      "external": false,
      "loc": "drivers/net/phy/phy.c:146",
      "file": "drivers/net/phy/phy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585632928,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:147",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585632928,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585718400,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:182",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start_aneg_priv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585718400,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586151200,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:145",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start_aneg_priv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586151200,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586401584,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:145",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start_aneg_priv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586401584,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586545584,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:153",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586545584,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586793408,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:169",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586793408,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586939744,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:169",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586939744,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587753600,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:177",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587753600,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587813152,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:160",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587813152,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587692640,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:160",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587692640,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588283968,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:160",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588283968,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589674201,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:161",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_down",
        "drivers/net/phy/phy.c:phy_speed_down"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589667616,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591285897,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:189",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_down",
        "drivers/net/phy/phy.c:phy_speed_down"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591278288,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591635925,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:202",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_down",
        "drivers/net/phy/phy.c:phy_speed_down"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591634096,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592376517,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:202",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_speed_down",
        "drivers/net/phy/phy.c:phy_speed_down"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592374688,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499923800,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:169",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499923800,
      "name": "phy_aneg_done",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232468280,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:169",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232468280,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293239584,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:169",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293239584,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277010400,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:169",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277010400,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586696752,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:169",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586696752,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586565088,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:169",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586565088,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586894304,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:169",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586894304,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```

```json
{
  "name": "phy_aneg_done",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587000688,
      "name": "phy_aneg_done",
      "external": true,
      "loc": "drivers/net/phy/phy.c:169",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587000688,
      "name": "phy_aneg_done",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int phy_aneg_done(struct phy_device * phydev)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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

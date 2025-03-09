# Function: <code>phy_restore_page</code>

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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586408784,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:444",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586408784,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586552560,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:615",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586552560,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586802608,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:721",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586802608,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586948672,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:760",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586948672,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587766942,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:778",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587765296,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587826126,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:825",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587824480,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587705554,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:825",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587703904,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588297378,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:826",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588295568,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589684413,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:821",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589682832,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591297613,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:904",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591295632,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591656253,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:907",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591654272,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592398333,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:1045",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592395104,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499932568,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:760",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499932568,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232476648,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:760",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232476648,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293251744,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:760",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293251744,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277018152,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:760",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277018152,
      "name": "phy_restore_page",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586705680,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:760",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586705680,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586574000,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:760",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586574000,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586903232,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:760",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586903232,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
```

```json
{
  "name": "phy_restore_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587009616,
      "name": "phy_restore_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:760",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009616,
      "name": "phy_restore_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
int phy_restore_page(struct phy_device * phydev, int oldpage, int ret)
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

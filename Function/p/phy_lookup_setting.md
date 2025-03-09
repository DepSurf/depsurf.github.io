# Function: <code>phy_lookup_setting</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
const struct phy_setting * phy_lookup_setting(int speed, int duplex, u32 features, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585717168,
      "name": "phy_lookup_setting",
      "external": false,
      "loc": "drivers/net/phy/phy.c:285",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_start_aneg_priv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717168,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, size_t maxbit, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586157952,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:146",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_start_aneg_priv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586157952,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, size_t maxbit, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586408464,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:146",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_start_aneg_priv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586408464,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586552192,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:299",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_start_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586552192,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586801744,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:164",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_start_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586801744,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586947792,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:164",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_start_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586947792,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587765712,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:172",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_start_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587765712,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587824688,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:199",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_start_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587824688,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587704048,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:199",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_start_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587704048,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588295712,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:200",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:_phy_start_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588295712,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589681168,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:201",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:_phy_start_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589681168,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591293472,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:284",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:_phy_start_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591293472,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591652112,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:287",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:_phy_start_aneg",
        "drivers/net/phy/phy.c:phy_check_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591652112,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592393360,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:289",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:_phy_start_aneg",
        "drivers/net/phy/phy.c:phy_check_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592393360,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499931440,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:164",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_start_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499931440,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232475716,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:164",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_start_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232475716,
      "name": "phy_lookup_setting",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293250272,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:164",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_start_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293250272,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277017118,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:164",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_start_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277017118,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586704800,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:164",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_start_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586704800,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586573120,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:164",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_start_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586573120,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586902352,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:164",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_start_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586902352,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
const struct phy_setting * phy_lookup_setting(int speed, int duplex, const long unsigned int * mask, bool exact)
```

```json
{
  "name": "phy_lookup_setting",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587008736,
      "name": "phy_lookup_setting",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:164",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_start_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587008736,
      "name": "phy_lookup_setting",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
const struct phy_setting * phy_lookup_setting(int speed, int duplex, u32 features, bool exact)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const long unsigned int * mask</code>
</li>
<li>
<b>Param added. </b>
<code>size_t maxbit</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 features</code>
</li>
<li>
<b>Param reordered. </b>
<code>speed, duplex, features, exact</code> ➡️ <code>speed, duplex, mask, maxbit, exact</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>size_t maxbit</code>
</li>
<li>
<b>Param reordered. </b>
<code>speed, duplex, mask, maxbit, exact</code> ➡️ <code>speed, duplex, mask, exact</code>
</li>
</ul>
</details>
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

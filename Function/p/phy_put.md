# Function: <code>phy_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void phy_put(struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583154112,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:429",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583154112,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void phy_put(struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583450656,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:444",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583450656,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void phy_put(struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583578400,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:459",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583578400,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void phy_put(struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583618365,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:459",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583620576,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void phy_put(struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583864461,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:478",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583866688,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void phy_put(struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584067245,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:498",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584065152,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void phy_put(struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584150269,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:562",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:devm_phy_release",
        "drivers/phy/phy-core.c:devm_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584151808,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void phy_put(struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584338240,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:564",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584338240,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void phy_put(struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584472912,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:574",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584472912,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void phy_put(struct device * dev, struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585136830,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:596",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585136768,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void phy_put(struct device * dev, struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585288110,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:596",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585288048,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void phy_put(struct device * dev, struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585171806,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:626",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585171744,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void phy_put(struct device * dev, struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585625502,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:626",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585625440,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void phy_put(struct device * dev, struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586784957,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:664",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586784896,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void phy_put(struct device * dev, struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587918173,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:664",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587918096,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void phy_put(struct device * dev, struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588192205,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:666",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588192128,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void phy_put(struct device * dev, struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588484205,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:666",
      "file": "drivers/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588484128,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void phy_put(struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496473960,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:574",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496473960,
      "name": "phy_put",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void phy_put(struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229787408,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:574",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229787408,
      "name": "phy_put",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void phy_put(struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290688464,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:574",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290688464,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void phy_put(struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275407874,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:574",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275407874,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void phy_put(struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584441664,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:574",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584441664,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void phy_put(struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584377344,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:574",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584377344,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void phy_put(struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584424576,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:574",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584424576,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void phy_put(struct phy * phy)
```

```json
{
  "name": "phy_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584530704,
      "name": "phy_put",
      "external": true,
      "loc": "drivers/phy/phy-core.c:574",
      "file": "drivers/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:devm_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584530704,
      "name": "phy_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>phy</code> ➡️ <code>dev, phy</code>
</li>
</ul>
</details>
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

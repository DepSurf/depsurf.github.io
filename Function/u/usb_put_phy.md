# Function: <code>usb_put_phy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585270672,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:360",
      "file": "drivers/usb/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/phy/phy.c:devm_usb_phy_release",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585270672,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585666384,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:360",
      "file": "drivers/usb/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585666384,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585854080,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:360",
      "file": "drivers/usb/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585854080,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585941365,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:408",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585941216,
      "name": "usb_put_phy.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071585941264,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586383912,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:676",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586383760,
      "name": "usb_put_phy.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586383808,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586642616,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:595",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586642464,
      "name": "usb_put_phy.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586642512,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586791736,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:595",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586791584,
      "name": "usb_put_phy.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071586791632,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587047896,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:595",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587047744,
      "name": "usb_put_phy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071587047792,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587248296,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:595",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587248144,
      "name": "usb_put_phy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071587248192,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588101370,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:606",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588102512,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588143258,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:606",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588144400,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588025338,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:606",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588026416,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588641802,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:644",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588642896,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590058440,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:644",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590059664,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591665448,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:644",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591666864,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592088264,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:644",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592089696,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592828696,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:644",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592830128,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500347044,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:595",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500346840,
      "name": "usb_put_phy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336500346904,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232805484,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:595",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232805312,
      "name": "usb_put_phy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3232805360,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293659980,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:595",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293659744,
      "name": "usb_put_phy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 13835058055293659840,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277237156,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:595",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277236970,
      "name": "usb_put_phy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446743936277237026,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586954376,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:595",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586954224,
      "name": "usb_put_phy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071586954272,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587202856,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:595",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587202704,
      "name": "usb_put_phy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071587202752,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void usb_put_phy(struct usb_phy * x)
```

```json
{
  "name": "usb_put_phy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587309928,
      "name": "usb_put_phy",
      "external": true,
      "loc": "drivers/usb/phy/phy.c:595",
      "file": "drivers/usb/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ],
      "caller_func": [
        "drivers/usb/phy/phy.c:devm_usb_phy_release2",
        "drivers/usb/phy/phy.c:devm_usb_phy_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587309776,
      "name": "usb_put_phy.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071587309824,
      "name": "usb_put_phy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void usb_put_phy(struct usb_phy * x)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

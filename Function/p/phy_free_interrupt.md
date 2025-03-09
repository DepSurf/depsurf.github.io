# Function: <code>phy_free_interrupt</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586792640,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:843",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586792640,
      "name": "phy_free_interrupt",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586938976,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:824",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586938976,
      "name": "phy_free_interrupt",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587759728,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:936",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_request_interrupt",
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587759728,
      "name": "phy_free_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587813648,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:995",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_request_interrupt",
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587813648,
      "name": "phy_free_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587693136,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:996",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_request_interrupt",
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587693136,
      "name": "phy_free_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588284464,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:1022",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_request_interrupt",
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588284464,
      "name": "phy_free_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589668080,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:1054",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_request_interrupt",
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589668080,
      "name": "phy_free_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591280131,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:1083",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_request_interrupt"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591279568,
      "name": "phy_free_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591636755,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:1317",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_request_interrupt"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591636032,
      "name": "phy_free_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592377347,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:1370",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_request_interrupt"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592376624,
      "name": "phy_free_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499922952,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:824",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499922952,
      "name": "phy_free_interrupt",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232467488,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:824",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232467488,
      "name": "phy_free_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293238400,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:824",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293238400,
      "name": "phy_free_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277009646,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:824",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277009646,
      "name": "phy_free_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586695984,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:824",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586695984,
      "name": "phy_free_interrupt",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586564320,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:824",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586564320,
      "name": "phy_free_interrupt",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586893536,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:824",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586893536,
      "name": "phy_free_interrupt",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void phy_free_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_free_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586999920,
      "name": "phy_free_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:824",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_disconnect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586999920,
      "name": "phy_free_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void phy_free_interrupt(struct phy_device * phydev)
```
</details>
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

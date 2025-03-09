# Function: <code>phy_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585046216,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:555",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_disable_interrupts",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/net/phy/phy.c:phy_change",
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
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585437463,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:637",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/net/phy/phy.c:phy_disable_interrupts"
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
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585635216,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:695",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/net/phy/phy.c:phy_disable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585635216,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585721536,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:763",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/net/phy/phy.c:phy_disable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585721536,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586154416,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:608",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_disable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586154416,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586404768,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:611",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/net/phy/phy.c:phy_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586404768,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586544608,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:726",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_stop_interrupts",
        "drivers/net/phy/phy.c:phy_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586544608,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586798325,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:734",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586798325,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586938688,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:714",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586938688,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587754192,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:828",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587754192,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587813936,
      "name": "phy_error",
      "external": true,
      "loc": "drivers/net/phy/phy.c:913",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587813936,
      "name": "phy_error",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587693424,
      "name": "phy_error",
      "external": true,
      "loc": "drivers/net/phy/phy.c:914",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587693424,
      "name": "phy_error",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588290484,
      "name": "phy_error",
      "external": true,
      "loc": "drivers/net/phy/phy.c:940",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588284752,
      "name": "phy_error",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589674663,
      "name": "phy_error",
      "external": true,
      "loc": "drivers/net/phy/phy.c:945",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589668544,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591286423,
      "name": "phy_error",
      "external": true,
      "loc": "drivers/net/phy/phy.c:974",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591279824,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591636432,
      "name": "phy_error",
      "external": true,
      "loc": "drivers/net/phy/phy.c:1213",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591636432,
      "name": "phy_error",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592377024,
      "name": "phy_error",
      "external": true,
      "loc": "drivers/net/phy/phy.c:1266",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592377024,
      "name": "phy_error",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499922664,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:714",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499922664,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232467180,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:714",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232467180,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293237952,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:714",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293237952,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277009250,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:714",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277009250,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586695696,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:714",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586695696,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586564032,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:714",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586564032,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586893248,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:714",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586893248,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void phy_error(struct phy_device * phydev)
```

```json
{
  "name": "phy_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586999632,
      "name": "phy_error",
      "external": false,
      "loc": "drivers/net/phy/phy.c:714",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586999632,
      "name": "phy_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void phy_error(struct phy_device * phydev)
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

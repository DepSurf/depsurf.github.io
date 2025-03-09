# Function: <code>phy_led_trigger_no_link</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586171952,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:30",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586423757,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:30",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586568974,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:30",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586820432,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:20",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586966528,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:20",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_led_trigger_no_link(struct phy_device * phy)
```

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587789280,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:20",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
      ],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587788960,
      "name": "phy_led_trigger_no_link",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_led_trigger_no_link(struct phy_device * phy)
```

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587847328,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:20",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
      ],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587847008,
      "name": "phy_led_trigger_no_link",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_led_trigger_no_link(struct phy_device * phy)
```

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587726608,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:20",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
      ],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587726288,
      "name": "phy_led_trigger_no_link",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_led_trigger_no_link(struct phy_device * phy)
```

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588320288,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:20",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
      ],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588319968,
      "name": "phy_led_trigger_no_link",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_led_trigger_no_link(struct phy_device * phy)
```

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589710424,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:20",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
      ],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589710080,
      "name": "phy_led_trigger_no_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591327252,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:20",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591688676,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:20",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592431588,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:20",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499954656,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:20",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void phy_led_trigger_no_link(struct phy_device * phy)
```

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232496224,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:20",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232496224,
      "name": "phy_led_trigger_no_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void phy_led_trigger_no_link(struct phy_device * phy)
```

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293281424,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:20",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293281424,
      "name": "phy_led_trigger_no_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void phy_led_trigger_no_link(struct phy_device * phy)
```

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277036992,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:20",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277036992,
      "name": "phy_led_trigger_no_link",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586723536,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:20",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586921088,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:20",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_led_trigger_no_link",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587027536,
      "name": "phy_led_trigger_no_link",
      "external": false,
      "loc": "drivers/net/phy/phy_led_triggers.c:20",
      "file": "drivers/net/phy/phy_led_triggers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed",
        "drivers/net/phy/phy_led_triggers.c:phy_led_trigger_change_speed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void phy_led_trigger_no_link(struct phy_device * phy)
```
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void phy_led_trigger_no_link(struct phy_device * phy)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void phy_led_trigger_no_link(struct phy_device * phy)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void phy_led_trigger_no_link(struct phy_device * phy)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void phy_led_trigger_no_link(struct phy_device * phy)
```
</details>
</li>
</ul>

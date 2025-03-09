# Function: <code>__set_linkmode_max_speed</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_linkmode_max_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586947949,
      "name": "__set_linkmode_max_speed",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:210",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_set_max_speed"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_linkmode_max_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587764237,
      "name": "__set_linkmode_max_speed",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:218",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_set_max_speed"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_linkmode_max_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587823421,
      "name": "__set_linkmode_max_speed",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:245",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_set_max_speed"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_linkmode_max_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587706536,
      "name": "__set_linkmode_max_speed",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:245",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_set_max_speed"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_linkmode_max_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588298604,
      "name": "__set_linkmode_max_speed",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:246",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_set_max_speed"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_linkmode_max_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589685751,
      "name": "__set_linkmode_max_speed",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:247",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_set_max_speed"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __set_linkmode_max_speed(u32 max_speed, long unsigned int * addr)
```

```json
{
  "name": "__set_linkmode_max_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591293696,
      "name": "__set_linkmode_max_speed",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:330",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_set_max_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591293696,
      "name": "__set_linkmode_max_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void __set_linkmode_max_speed(u32 max_speed, long unsigned int * addr)
```

```json
{
  "name": "__set_linkmode_max_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591652336,
      "name": "__set_linkmode_max_speed",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:333",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_set_max_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591652336,
      "name": "__set_linkmode_max_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void __set_linkmode_max_speed(u32 max_speed, long unsigned int * addr)
```

```json
{
  "name": "__set_linkmode_max_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592393584,
      "name": "__set_linkmode_max_speed",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:335",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_set_max_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592393584,
      "name": "__set_linkmode_max_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__set_linkmode_max_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499935004,
      "name": "__set_linkmode_max_speed",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:210",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:of_set_phy_supported",
        "drivers/net/phy/phy-core.c:phy_set_max_speed"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__set_linkmode_max_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232478624,
      "name": "__set_linkmode_max_speed",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:210",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:of_set_phy_supported",
        "drivers/net/phy/phy-core.c:phy_set_max_speed"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__set_linkmode_max_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293254548,
      "name": "__set_linkmode_max_speed",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:210",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:of_set_phy_supported",
        "drivers/net/phy/phy-core.c:phy_set_max_speed"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__set_linkmode_max_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277020626,
      "name": "__set_linkmode_max_speed",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:210",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:of_set_phy_supported",
        "drivers/net/phy/phy-core.c:phy_set_max_speed"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_linkmode_max_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586704957,
      "name": "__set_linkmode_max_speed",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:210",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_set_max_speed"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_linkmode_max_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586573277,
      "name": "__set_linkmode_max_speed",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:210",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_set_max_speed"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_linkmode_max_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586902509,
      "name": "__set_linkmode_max_speed",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:210",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_set_max_speed"
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
  "name": "__set_linkmode_max_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587008893,
      "name": "__set_linkmode_max_speed",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:210",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_speed_down_core",
        "drivers/net/phy/phy-core.c:phy_set_max_speed"
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void __set_linkmode_max_speed(u32 max_speed, long unsigned int * addr)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

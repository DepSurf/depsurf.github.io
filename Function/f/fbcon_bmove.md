# Function: <code>fbcon_bmove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void fbcon_bmove(struct vc_data * vc, int sy, int sx, int dy, int dx, int height, int width)
```

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583431952,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:2003",
      "file": "drivers/video/console/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583431952,
      "name": "fbcon_bmove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583768928,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:2002",
      "file": "drivers/video/console/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583768928,
      "name": "fbcon_bmove.constprop.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583908160,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:2005",
      "file": "drivers/video/console/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583908160,
      "name": "fbcon_bmove.constprop.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583950608,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/console/fbcon.c:2003",
      "file": "drivers/video/console/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll",
        "drivers/video/console/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583950608,
      "name": "fbcon_bmove.constprop.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584246336,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2019",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584246336,
      "name": "fbcon_bmove.constprop.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584466688,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2026",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584466688,
      "name": "fbcon_bmove.constprop.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584565376,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2045",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584565376,
      "name": "fbcon_bmove.constprop.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584763040,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2073",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584763040,
      "name": "fbcon_bmove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584897904,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2073",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584897904,
      "name": "fbcon_bmove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585592112,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1897",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585592112,
      "name": "fbcon_bmove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585724496,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1893",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585724496,
      "name": "fbcon_bmove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585604960,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1885",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585604960,
      "name": "fbcon_bmove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1885",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1718",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1713",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1711",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:1713",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497296656,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2073",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497296656,
      "name": "fbcon_bmove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230471756,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2073",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230471756,
      "name": "fbcon_bmove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291288688,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2073",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291288688,
      "name": "fbcon_bmove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275832100,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2073",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275832100,
      "name": "fbcon_bmove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584849008,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2073",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584849008,
      "name": "fbcon_bmove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584778832,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2073",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584778832,
      "name": "fbcon_bmove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584850432,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2073",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584850432,
      "name": "fbcon_bmove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fbcon_bmove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584955568,
      "name": "fbcon_bmove",
      "external": false,
      "loc": "drivers/video/fbdev/core/fbcon.c:2073",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584955568,
      "name": "fbcon_bmove.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void fbcon_bmove(struct vc_data * vc, int sy, int sx, int dy, int dx, int height, int width)
```
</details>
</li>
</ul>

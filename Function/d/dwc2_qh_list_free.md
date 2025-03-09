# Function: <code>dwc2_qh_list_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dwc2_qh_list_free(struct dwc2_hsotg * hsotg, struct list_head * qh_list)
```

```json
{
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585308512,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:143",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585308512,
      "name": "dwc2_qh_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
void dwc2_qh_list_free(struct dwc2_hsotg * hsotg, struct list_head * qh_list)
```

```json
{
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585701456,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1722",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585701456,
      "name": "dwc2_qh_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
void dwc2_qh_list_free(struct dwc2_hsotg * hsotg, struct list_head * qh_list)
```

```json
{
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585890240,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1752",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585890240,
      "name": "dwc2_qh_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585973224,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1769",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585972864,
      "name": "dwc2_qh_list_free.part.48",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586417000,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1775",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586416640,
      "name": "dwc2_qh_list_free.part.49",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586679192,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1819",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586678816,
      "name": "dwc2_qh_list_free.part.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586834760,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1809",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586834352,
      "name": "dwc2_qh_list_free.part.48",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587091782,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1619",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587091376,
      "name": "dwc2_qh_list_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587292278,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1619",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587291872,
      "name": "dwc2_qh_list_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588147446,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1619",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588147072,
      "name": "dwc2_qh_list_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588187990,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1620",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588187616,
      "name": "dwc2_qh_list_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588063798,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1618",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588063424,
      "name": "dwc2_qh_list_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588690904,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1618",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588690528,
      "name": "dwc2_qh_list_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590109420,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1614",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590109024,
      "name": "dwc2_qh_list_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591721052,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1585",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591720640,
      "name": "dwc2_qh_list_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592144444,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1585",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592144032,
      "name": "dwc2_qh_list_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592884972,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1585",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592884560,
      "name": "dwc2_qh_list_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500408284,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1619",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500407752,
      "name": "dwc2_qh_list_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232863872,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1619",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232863516,
      "name": "dwc2_qh_list_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293745300,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1619",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293744752,
      "name": "dwc2_qh_list_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277297582,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1619",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277297238,
      "name": "dwc2_qh_list_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586998358,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1619",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586997952,
      "name": "dwc2_qh_list_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587246838,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1619",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587246432,
      "name": "dwc2_qh_list_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
  "name": "dwc2_qh_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587353606,
      "name": "dwc2_qh_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:1619",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release"
      ],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587353200,
      "name": "dwc2_qh_list_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void dwc2_qh_list_free(struct dwc2_hsotg * hsotg, struct list_head * qh_list)
```
</details>
</li>
</ul>

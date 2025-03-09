# Function: <code>dwc2_hcd_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585310185,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:2976",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove"
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
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585704459,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4956",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585893166,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4956",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585975918,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:5038",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586419809,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:5053",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
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
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586682141,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:5119",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void dwc2_hcd_release(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586834704,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:5138",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586834704,
      "name": "dwc2_hcd_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 646
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
void dwc2_hcd_release(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587091728,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4995",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587091728,
      "name": "dwc2_hcd_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
void dwc2_hcd_release(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587292224,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4995",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587292224,
      "name": "dwc2_hcd_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588149892,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4995",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
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
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588190436,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4997",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
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
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588066228,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:5114",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
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
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588693673,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:5115",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
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
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590112181,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:5111",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591724069,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:5082",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
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
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592147445,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:5082",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
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
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592888069,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:5082",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
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
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500410460,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4995",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
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
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232866336,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4995",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
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
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293748392,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4995",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
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
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277299986,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4995",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void dwc2_hcd_release(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586998304,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4995",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586998304,
      "name": "dwc2_hcd_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void dwc2_hcd_release(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587246784,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4995",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587246784,
      "name": "dwc2_hcd_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
void dwc2_hcd_release(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_hcd_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587353552,
      "name": "dwc2_hcd_release",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4995",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587353552,
      "name": "dwc2_hcd_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void dwc2_hcd_release(struct dwc2_hsotg * hsotg)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void dwc2_hcd_release(struct dwc2_hsotg * hsotg)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void dwc2_hcd_release(struct dwc2_hsotg * hsotg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void dwc2_hcd_release(struct dwc2_hsotg * hsotg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void dwc2_hcd_release(struct dwc2_hsotg * hsotg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void dwc2_hcd_release(struct dwc2_hsotg * hsotg)
```
</details>
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
void dwc2_hcd_release(struct dwc2_hsotg * hsotg)
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

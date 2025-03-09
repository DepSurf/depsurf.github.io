# Function: <code>dwc2_ovr_avalid</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int dwc2_ovr_avalid(struct dwc2_hsotg * hsotg, bool valid)
```

```json
{
  "name": "dwc2_ovr_avalid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588159248,
      "name": "dwc2_ovr_avalid",
      "external": false,
      "loc": "drivers/usb/dwc2/drd.c:33",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588159248,
      "name": "dwc2_ovr_avalid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
int dwc2_ovr_avalid(struct dwc2_hsotg * hsotg, bool valid)
```

```json
{
  "name": "dwc2_ovr_avalid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588041248,
      "name": "dwc2_ovr_avalid",
      "external": false,
      "loc": "drivers/usb/dwc2/drd.c:33",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588041248,
      "name": "dwc2_ovr_avalid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
  "name": "dwc2_ovr_avalid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588663541,
      "name": "dwc2_ovr_avalid",
      "external": false,
      "loc": "drivers/usb/dwc2/drd.c:34",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int dwc2_ovr_avalid(struct dwc2_hsotg * hsotg, bool valid)
```

```json
{
  "name": "dwc2_ovr_avalid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_ovr_avalid",
      "external": false,
      "loc": "drivers/usb/dwc2/drd.c:41",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_resume",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590079744,
      "name": "dwc2_ovr_avalid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071594461609,
      "name": "dwc2_ovr_avalid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int dwc2_ovr_avalid(struct dwc2_hsotg * hsotg, bool valid)
```

```json
{
  "name": "dwc2_ovr_avalid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_ovr_avalid",
      "external": false,
      "loc": "drivers/usb/dwc2/drd.c:41",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_resume",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591688080,
      "name": "dwc2_ovr_avalid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071596280246,
      "name": "dwc2_ovr_avalid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int dwc2_ovr_avalid(struct dwc2_hsotg * hsotg, bool valid)
```

```json
{
  "name": "dwc2_ovr_avalid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_ovr_avalid",
      "external": false,
      "loc": "drivers/usb/dwc2/drd.c:42",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_resume",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592111376,
      "name": "dwc2_ovr_avalid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071596810110,
      "name": "dwc2_ovr_avalid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int dwc2_ovr_avalid(struct dwc2_hsotg * hsotg, bool valid)
```

```json
{
  "name": "dwc2_ovr_avalid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_ovr_avalid",
      "external": false,
      "loc": "drivers/usb/dwc2/drd.c:42",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_resume",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592851808,
      "name": "dwc2_ovr_avalid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071597733717,
      "name": "dwc2_ovr_avalid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int dwc2_ovr_avalid(struct dwc2_hsotg * hsotg, bool valid)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int dwc2_ovr_avalid(struct dwc2_hsotg * hsotg, bool valid)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int dwc2_ovr_avalid(struct dwc2_hsotg * hsotg, bool valid)
```
</details>
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

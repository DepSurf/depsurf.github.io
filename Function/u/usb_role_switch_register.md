# Function: <code>usb_role_switch_register</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct usb_role_switch * usb_role_switch_register(struct device * parent, const struct usb_role_switch_desc * desc)
```

```json
{
  "name": "usb_role_switch_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588460912,
      "name": "usb_role_switch_register",
      "external": true,
      "loc": "drivers/usb/roles/class.c:304",
      "file": "drivers/usb/roles/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588460912,
      "name": "usb_role_switch_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071588461216,
      "name": "usb_role_switch_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
struct usb_role_switch * usb_role_switch_register(struct device * parent, const struct usb_role_switch_desc * desc)
```

```json
{
  "name": "usb_role_switch_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588343520,
      "name": "usb_role_switch_register",
      "external": true,
      "loc": "drivers/usb/roles/class.c:306",
      "file": "drivers/usb/roles/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588343520,
      "name": "usb_role_switch_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct usb_role_switch * usb_role_switch_register(struct device * parent, const struct usb_role_switch_desc * desc)
```

```json
{
  "name": "usb_role_switch_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589002609,
      "name": "usb_role_switch_register",
      "external": true,
      "loc": "drivers/usb/roles/class.c:315",
      "file": "drivers/usb/roles/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592616271,
      "name": "usb_role_switch_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589002560,
      "name": "usb_role_switch_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct usb_role_switch * usb_role_switch_register(struct device * parent, const struct usb_role_switch_desc * desc)
```

```json
{
  "name": "usb_role_switch_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590438353,
      "name": "usb_role_switch_register",
      "external": true,
      "loc": "drivers/usb/roles/class.c:315",
      "file": "drivers/usb/roles/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594499359,
      "name": "usb_role_switch_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590438304,
      "name": "usb_role_switch_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct usb_role_switch * usb_role_switch_register(struct device * parent, const struct usb_role_switch_desc * desc)
```

```json
{
  "name": "usb_role_switch_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592077313,
      "name": "usb_role_switch_register",
      "external": true,
      "loc": "drivers/usb/roles/class.c:318",
      "file": "drivers/usb/roles/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596302011,
      "name": "usb_role_switch_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592077264,
      "name": "usb_role_switch_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct usb_role_switch * usb_role_switch_register(struct device * parent, const struct usb_role_switch_desc * desc)
```

```json
{
  "name": "usb_role_switch_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592500033,
      "name": "usb_role_switch_register",
      "external": true,
      "loc": "drivers/usb/roles/class.c:319",
      "file": "drivers/usb/roles/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596831429,
      "name": "usb_role_switch_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592499984,
      "name": "usb_role_switch_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct usb_role_switch * usb_role_switch_register(struct device * parent, const struct usb_role_switch_desc * desc)
```

```json
{
  "name": "usb_role_switch_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593244764,
      "name": "usb_role_switch_register",
      "external": true,
      "loc": "drivers/usb/roles/class.c:327",
      "file": "drivers/usb/roles/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/drd.c:dwc2_drd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597755462,
      "name": "usb_role_switch_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593244704,
      "name": "usb_role_switch_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
struct usb_role_switch * usb_role_switch_register(struct device * parent, const struct usb_role_switch_desc * desc)
```

```json
{
  "name": "usb_role_switch_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500714088,
      "name": "usb_role_switch_register",
      "external": true,
      "loc": "drivers/usb/roles/class.c:285",
      "file": "drivers/usb/roles/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500714088,
      "name": "usb_role_switch_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
struct usb_role_switch * usb_role_switch_register(struct device * parent, const struct usb_role_switch_desc * desc)
```

```json
{
  "name": "usb_role_switch_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233239536,
      "name": "usb_role_switch_register",
      "external": true,
      "loc": "drivers/usb/roles/class.c:285",
      "file": "drivers/usb/roles/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233239536,
      "name": "usb_role_switch_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
    }
  ]
}
```
</details>
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
struct usb_role_switch * usb_role_switch_register(struct device * parent, const struct usb_role_switch_desc * desc)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct usb_role_switch * usb_role_switch_register(struct device * parent, const struct usb_role_switch_desc * desc)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct usb_role_switch * usb_role_switch_register(struct device * parent, const struct usb_role_switch_desc * desc)
```
</details>
</li>
</ul>

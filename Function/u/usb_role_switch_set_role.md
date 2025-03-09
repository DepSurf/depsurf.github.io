# Function: <code>usb_role_switch_set_role</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int usb_role_switch_set_role(struct usb_role_switch * sw, enum usb_role role)
```

```json
{
  "name": "usb_role_switch_set_role",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588460368,
      "name": "usb_role_switch_set_role",
      "external": true,
      "loc": "drivers/usb/roles/class.c:42",
      "file": "drivers/usb/roles/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/roles/class.c:role_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588460368,
      "name": "usb_role_switch_set_role",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int usb_role_switch_set_role(struct usb_role_switch * sw, enum usb_role role)
```

```json
{
  "name": "usb_role_switch_set_role",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588342976,
      "name": "usb_role_switch_set_role",
      "external": true,
      "loc": "drivers/usb/roles/class.c:42",
      "file": "drivers/usb/roles/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/roles/class.c:role_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588342976,
      "name": "usb_role_switch_set_role",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int usb_role_switch_set_role(struct usb_role_switch * sw, enum usb_role role)
```

```json
{
  "name": "usb_role_switch_set_role",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589001984,
      "name": "usb_role_switch_set_role",
      "external": true,
      "loc": "drivers/usb/roles/class.c:42",
      "file": "drivers/usb/roles/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/roles/class.c:role_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589001984,
      "name": "usb_role_switch_set_role",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int usb_role_switch_set_role(struct usb_role_switch * sw, enum usb_role role)
```

```json
{
  "name": "usb_role_switch_set_role",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590437040,
      "name": "usb_role_switch_set_role",
      "external": true,
      "loc": "drivers/usb/roles/class.c:42",
      "file": "drivers/usb/roles/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/roles/class.c:role_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590437040,
      "name": "usb_role_switch_set_role",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int usb_role_switch_set_role(struct usb_role_switch * sw, enum usb_role role)
```

```json
{
  "name": "usb_role_switch_set_role",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592075760,
      "name": "usb_role_switch_set_role",
      "external": true,
      "loc": "drivers/usb/roles/class.c:42",
      "file": "drivers/usb/roles/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/roles/class.c:role_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592075760,
      "name": "usb_role_switch_set_role",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int usb_role_switch_set_role(struct usb_role_switch * sw, enum usb_role role)
```

```json
{
  "name": "usb_role_switch_set_role",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592498512,
      "name": "usb_role_switch_set_role",
      "external": true,
      "loc": "drivers/usb/roles/class.c:44",
      "file": "drivers/usb/roles/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/roles/class.c:role_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592498512,
      "name": "usb_role_switch_set_role",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int usb_role_switch_set_role(struct usb_role_switch * sw, enum usb_role role)
```

```json
{
  "name": "usb_role_switch_set_role",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_role_switch_set_role",
      "external": true,
      "loc": "drivers/usb/roles/class.c:46",
      "file": "drivers/usb/roles/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/roles/class.c:role_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597755399,
      "name": "usb_role_switch_set_role.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593243696,
      "name": "usb_role_switch_set_role",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int usb_role_switch_set_role(struct usb_role_switch * sw, enum usb_role role)
```

```json
{
  "name": "usb_role_switch_set_role",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500713280,
      "name": "usb_role_switch_set_role",
      "external": true,
      "loc": "drivers/usb/roles/class.c:42",
      "file": "drivers/usb/roles/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/roles/class.c:role_store"
      ],
      "caller_func": [
        "drivers/usb/roles/class.c:role_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500713016,
      "name": "usb_role_switch_set_role.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446603336500713120,
      "name": "usb_role_switch_set_role",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int usb_role_switch_set_role(struct usb_role_switch * sw, enum usb_role role)
```

```json
{
  "name": "usb_role_switch_set_role",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233238844,
      "name": "usb_role_switch_set_role",
      "external": true,
      "loc": "drivers/usb/roles/class.c:42",
      "file": "drivers/usb/roles/class.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/roles/class.c:role_store"
      ],
      "caller_func": [
        "drivers/usb/roles/class.c:role_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233238632,
      "name": "usb_role_switch_set_role.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 3233238712,
      "name": "usb_role_switch_set_role",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int usb_role_switch_set_role(struct usb_role_switch * sw, enum usb_role role)
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
int usb_role_switch_set_role(struct usb_role_switch * sw, enum usb_role role)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int usb_role_switch_set_role(struct usb_role_switch * sw, enum usb_role role)
```
</details>
</li>
</ul>

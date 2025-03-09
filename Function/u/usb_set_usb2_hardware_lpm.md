# Function: <code>usb_set_usb2_hardware_lpm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int usb_set_usb2_hardware_lpm(struct usb_device * udev, int enable)
```

```json
{
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585224464,
      "name": "usb_set_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1860",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585224464,
      "name": "usb_set_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int usb_set_usb2_hardware_lpm(struct usb_device * udev, int enable)
```

```json
{
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585617568,
      "name": "usb_set_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1870",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585617568,
      "name": "usb_set_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int usb_set_usb2_hardware_lpm(struct usb_device * udev, int enable)
```

```json
{
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585805104,
      "name": "usb_set_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1873",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805104,
      "name": "usb_set_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int usb_set_usb2_hardware_lpm(struct usb_device * udev, int enable)
```

```json
{
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585891552,
      "name": "usb_set_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1894",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585891552,
      "name": "usb_set_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int usb_set_usb2_hardware_lpm(struct usb_device * udev, int enable)
```

```json
{
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586332144,
      "name": "usb_set_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1902",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586332144,
      "name": "usb_set_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int usb_set_usb2_hardware_lpm(struct usb_device * udev, int enable)
```

```json
{
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586589296,
      "name": "usb_set_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1902",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586589296,
      "name": "usb_set_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586738408,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1899",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586993512,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1886",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587192584,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1888",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588044313,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1986",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588093161,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1996",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587975913,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1992",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588587625,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1992",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590000019,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1994",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591596355,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1994",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592018195,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1994",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592758467,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:2000",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500277072,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1888",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232747488,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1888",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293577832,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1888",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277187966,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1888",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586898664,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1888",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586839784,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1888",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587147144,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1888",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
  "name": "usb_set_usb2_hardware_lpm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587254216,
      "name": "usb_set_usb2_hardware_lpm",
      "external": false,
      "loc": "drivers/usb/core/driver.c:1888",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_disable_usb2_hardware_lpm",
        "drivers/usb/core/driver.c:usb_enable_usb2_hardware_lpm"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int usb_set_usb2_hardware_lpm(struct usb_device * udev, int enable)
```
</details>
</li>
</ul>

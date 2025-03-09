# Function: <code>usb_enable_usb2_hardware_lpm</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586738288,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1913",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586738288,
      "name": "usb_enable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586993392,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1900",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586993392,
      "name": "usb_enable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587192464,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1902",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587192464,
      "name": "usb_enable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588044176,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:2000",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588044176,
      "name": "usb_enable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588093024,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:2010",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588093024,
      "name": "usb_enable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587975792,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:2006",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587975792,
      "name": "usb_enable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588587504,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:2006",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588587504,
      "name": "usb_enable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589999856,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:2008",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589999856,
      "name": "usb_enable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591596192,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:2008",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591596192,
      "name": "usb_enable_usb2_hardware_lpm",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592018032,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:2008",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592018032,
      "name": "usb_enable_usb2_hardware_lpm",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592758304,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:2014",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592758304,
      "name": "usb_enable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500276928,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1902",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500276928,
      "name": "usb_enable_usb2_hardware_lpm",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232747344,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1902",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232747344,
      "name": "usb_enable_usb2_hardware_lpm",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293577584,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1902",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293577584,
      "name": "usb_enable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277187846,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1902",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277187846,
      "name": "usb_enable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586898544,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1902",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586898544,
      "name": "usb_enable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586839664,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1902",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586839664,
      "name": "usb_enable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587147024,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1902",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587147024,
      "name": "usb_enable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_enable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587254096,
      "name": "usb_enable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1902",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:hub_port_init",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587254096,
      "name": "usb_enable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int usb_enable_usb2_hardware_lpm(struct usb_device * udev)
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

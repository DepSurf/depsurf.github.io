# Function: <code>usb_disable_usb2_hardware_lpm</code>

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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586738384,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1923",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586738384,
      "name": "usb_disable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586993488,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1910",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586993488,
      "name": "usb_disable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587192560,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1912",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587192560,
      "name": "usb_disable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588044288,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:2010",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588044288,
      "name": "usb_disable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588093136,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:2020",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588093136,
      "name": "usb_disable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587975888,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:2016",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587975888,
      "name": "usb_disable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588587600,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:2016",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588587600,
      "name": "usb_disable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589999984,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:2018",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589999984,
      "name": "usb_disable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591596320,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:2018",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591596320,
      "name": "usb_disable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592018160,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:2018",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592018160,
      "name": "usb_disable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592758432,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:2024",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592758432,
      "name": "usb_disable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500277040,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1912",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500277040,
      "name": "usb_disable_usb2_hardware_lpm",
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232747452,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1912",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232747452,
      "name": "usb_disable_usb2_hardware_lpm",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293577792,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1912",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293577792,
      "name": "usb_disable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277187934,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1912",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277187934,
      "name": "usb_disable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586898640,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1912",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586898640,
      "name": "usb_disable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586839760,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1912",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586839760,
      "name": "usb_disable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587147120,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1912",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587147120,
      "name": "usb_disable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
```

```json
{
  "name": "usb_disable_usb2_hardware_lpm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587254192,
      "name": "usb_disable_usb2_hardware_lpm",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1912",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_reset_and_verify_device",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/hub.c:usb_port_suspend",
        "drivers/usb/core/message.c:usb_disable_device",
        "drivers/usb/core/sysfs.c:usb2_hardware_lpm_store",
        "drivers/usb/core/port.c:usb_port_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587254192,
      "name": "usb_disable_usb2_hardware_lpm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int usb_disable_usb2_hardware_lpm(struct usb_device * udev)
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

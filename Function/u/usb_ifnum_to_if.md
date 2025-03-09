# Function: <code>usb_ifnum_to_if</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585148704,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:139",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf",
        "drivers/usb/core/devio.c:proc_ioctl",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585148704,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585541088,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:135",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:proc_ioctl",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585541088,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585728976,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:138",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:proc_ioctl",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585728976,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585816352,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:272",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:proc_ioctl",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585816352,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586255600,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:272",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:proc_ioctl",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586255600,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586513008,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:274",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:proc_ioctl",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586513008,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586661536,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:274",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:proc_ioctl",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586661536,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586915792,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:273",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586915792,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587114240,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:273",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587114240,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587960912,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:273",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:proc_getdriver",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587960912,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588020736,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:271",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:proc_getdriver",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588020736,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587902448,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:271",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:proc_getdriver",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587902448,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588511600,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:271",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:proc_getdriver",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588511600,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589918464,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:271",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:proc_ioctl",
        "drivers/usb/core/devio.c:proc_getdriver",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589918464,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591498688,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:271",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:proc_ioctl",
        "drivers/usb/core/devio.c:proc_getdriver",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591498688,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591920000,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:347",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:proc_ioctl",
        "drivers/usb/core/devio.c:proc_getdriver",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591920000,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592659840,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:348",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:proc_ioctl",
        "drivers/usb/core/devio.c:proc_getdriver",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592659840,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500187208,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:273",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500187208,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232667452,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:273",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:proc_getdriver",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232667452,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293468656,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:273",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:proc_getdriver",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293468656,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277113964,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:273",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:usbdev_do_ioctl",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:proc_getdriver",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277113964,
      "name": "usb_ifnum_to_if",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586820320,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:273",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586820320,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586762096,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:273",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586762096,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587068800,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:273",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587068800,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct usb_interface * usb_ifnum_to_if(const struct usb_device * dev, unsigned int ifnum)
```

```json
{
  "name": "usb_ifnum_to_if",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587175968,
      "name": "usb_ifnum_to_if",
      "external": true,
      "loc": "drivers/usb/core/usb.c:273",
      "file": "drivers/usb/core/usb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth",
        "drivers/usb/core/message.c:usb_set_interface",
        "drivers/usb/core/devio.c:proc_disconnect_claim",
        "drivers/usb/core/devio.c:parse_usbdevfs_streams",
        "drivers/usb/core/devio.c:releaseintf",
        "drivers/usb/core/devio.c:claimintf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587175968,
      "name": "usb_ifnum_to_if",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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

# Function: <code>usb_get_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int usb_get_status(struct usb_device * dev, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585206720,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:942",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585206720,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int usb_get_status(struct usb_device * dev, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585598912,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:939",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585598912,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int usb_get_status(struct usb_device * dev, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585786480,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:942",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585786480,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int usb_get_status(struct usb_device * dev, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585873024,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:940",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585873024,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586313296,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:945",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586313296,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586570752,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:970",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586570752,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586719696,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:971",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586719696,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586974832,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:973",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586974832,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587173872,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:973",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587173872,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588024112,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:981",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588024112,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588073504,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:1121",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588073504,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587956288,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:1127",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587956288,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588567200,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:1127",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588567200,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589978048,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:1127",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589978048,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591571648,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:1128",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591571648,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591993408,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:1123",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591993408,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592733280,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:1124",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:finish_port_resume",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592733280,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500255408,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:973",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500255408,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232728156,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:973",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232728156,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293549872,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:973",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293549872,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277169528,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:973",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277169528,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586879952,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:973",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586879952,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586821072,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:973",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586821072,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587128432,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:973",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587128432,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int usb_get_status(struct usb_device * dev, int recip, int type, int target, void * data)
```

```json
{
  "name": "usb_get_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587235536,
      "name": "usb_get_status",
      "external": true,
      "loc": "drivers/usb/core/message.c:973",
      "file": "drivers/usb/core/message.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/hub.c:usb_port_resume",
        "drivers/usb/core/driver.c:usb_suspend_both"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587235536,
      "name": "usb_get_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int recip</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, type, target, data</code> ➡️ <code>dev, recip, type, target, data</code>
</li>
</ul>
</details>
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

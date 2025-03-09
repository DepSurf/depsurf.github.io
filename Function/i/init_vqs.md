# Function: <code>init_vqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583841168,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:387",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/virtio/virtio_balloon.c:virtballoon_restore"
      ]
    },
    {
      "addr": 18446744071584178352,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1873",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    },
    {
      "addr": 18446744071585087440,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/net/virtio_net.c:1634",
      "file": "drivers/net/virtio_net.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_restore",
        "drivers/net/virtio_net.c:virtnet_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583841168,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
    },
    {
      "addr": 18446744071584178352,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
    },
    {
      "addr": 18446744071585087440,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584170032,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:404",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071584517392,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1880",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    },
    {
      "addr": 18446744071585479664,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/net/virtio_net.c:1636",
      "file": "drivers/net/virtio_net.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_restore",
        "drivers/net/virtio_net.c:virtnet_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584170032,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071584517392,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
    },
    {
      "addr": 18446744071585479664,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584353024,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:404",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071584699504,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1889",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584353024,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071584699504,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584433152,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:405",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071584781600,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1897",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584433152,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071584781600,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 726
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584841344,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:418",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071585201728,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1894",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584841344,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071585201728,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 732
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585072192,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:428",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071585449248,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1883",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072192,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446744071585449248,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585180192,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:470",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071585571520,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1856",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585180192,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
    },
    {
      "addr": 18446744071585571520,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:461",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071585792176,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1844",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585392672,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    },
    {
      "addr": 18446744071585397250,
      "name": "init_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585792176,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:463",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071585934944,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1845",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585533328,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071585537986,
      "name": "init_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585934944,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:503",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071586670672,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1843",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586253008,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
    },
    {
      "addr": 18446744071586256082,
      "name": "init_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586670672,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 662
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:497",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071586780544,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1843",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586370736,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
    },
    {
      "addr": 18446744071591447028,
      "name": "init_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586780544,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 662
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:497",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071586657664,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1840",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586253248,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
    },
    {
      "addr": 18446744071591388593,
      "name": "init_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071586657664,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:497",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071587206080,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1840",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586763696,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
    },
    {
      "addr": 18446744071592432107,
      "name": "init_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071587206080,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:497",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071588516848,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1841",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588041952,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
    },
    {
      "addr": 18446744071594300290,
      "name": "init_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071588516848,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589420512,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:490",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071589959040,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1837",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589420512,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
    },
    {
      "addr": 18446744071589959040,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589719696,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:490",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071590268400,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1837",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    },
    {
      "addr": 18446744071591773180,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/net/virtio_net.c:3866",
      "file": "drivers/net/virtio_net.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_restore",
        "drivers/net/virtio_net.c:virtnet_restore",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589719696,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
    },
    {
      "addr": 18446744071590268400,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590057456,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:529",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071590609344,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1805",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    },
    {
      "addr": 18446744071592500694,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/net/virtio_net.c:4427",
      "file": "drivers/net/virtio_net.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_restore",
        "drivers/net/virtio_net.c:virtnet_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590057456,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
    },
    {
      "addr": 18446744071590609344,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
    },
    {
      "addr": 18446744071592500624,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071597719360,
      "name": "init_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498190856,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:463",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446603336498752576,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1845",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498190856,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
    },
    {
      "addr": 18446603336498752576,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230956688,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:463",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 3231383092,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1845",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230956688,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
    },
    {
      "addr": 3231383092,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291435872,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:463",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 13835058055291926448,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1845",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291435872,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    },
    {
      "addr": 13835058055291926448,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275973992,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:463",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446743936276261990,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1845",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:virtcons_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275973992,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Transformation ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:463",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071585695920,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1845",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585295360,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071585300018,
      "name": "init_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585695920,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Transformation ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:463",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071585555296,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1845",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585247872,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071585252514,
      "name": "init_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585555296,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Transformation ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:463",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071585884976,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1845",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585483728,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071585488386,
      "name": "init_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585884976,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Transformation ❓</summary>

```c
int init_vqs(struct virtio_balloon * vb)
```

```json
{
  "name": "init_vqs",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/virtio/virtio_balloon.c:463",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_balloon.c:virtballoon_restore",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe"
      ]
    },
    {
      "addr": 18446744071585993024,
      "name": "init_vqs",
      "external": false,
      "loc": "drivers/char/virtio_console.c:1845",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585592736,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071585596427,
      "name": "init_vqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585993024,
      "name": "init_vqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
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

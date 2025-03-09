# Function: <code>urb_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void urb_destroy(struct kref * kref)
```

```json
{
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585201952,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:14",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585201952,
      "name": "urb_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void urb_destroy(struct kref * kref)
```

```json
{
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585594096,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:14",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585594096,
      "name": "urb_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void urb_destroy(struct kref * kref)
```

```json
{
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585781696,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585781696,
      "name": "urb_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585868742,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_free_urb"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void urb_destroy(struct kref * kref)
```

```json
{
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586308736,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586308736,
      "name": "urb_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void urb_destroy(struct kref * kref)
```

```json
{
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586566016,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586566016,
      "name": "urb_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void urb_destroy(struct kref * kref)
```

```json
{
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586715056,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586715056,
      "name": "urb_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void urb_destroy(struct kref * kref)
```

```json
{
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586970320,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586970320,
      "name": "urb_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void urb_destroy(struct kref * kref)
```

```json
{
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587169360,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587169360,
      "name": "urb_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588021618,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_scuttle_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
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
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588069192,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_scuttle_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
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
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587951976,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_scuttle_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
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
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588562616,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_scuttle_anchored_urbs",
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
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
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589974382,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
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
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591567870,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:20",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
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
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591989614,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:20",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
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
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592729534,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:20",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
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
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500250524,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232725320,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293542848,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_free_urb"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void urb_destroy(struct kref * kref)
```

```json
{
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277164760,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277164760,
      "name": "urb_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void urb_destroy(struct kref * kref)
```

```json
{
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586875440,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586875440,
      "name": "urb_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void urb_destroy(struct kref * kref)
```

```json
{
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586816576,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586816576,
      "name": "urb_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void urb_destroy(struct kref * kref)
```

```json
{
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587123920,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587123920,
      "name": "urb_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void urb_destroy(struct kref * kref)
```

```json
{
  "name": "urb_destroy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587231024,
      "name": "urb_destroy",
      "external": false,
      "loc": "drivers/usb/core/urb.c:19",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/urb.c:usb_unlink_anchored_urbs",
        "drivers/usb/core/urb.c:usb_poison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_kill_anchored_urbs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587231024,
      "name": "urb_destroy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void urb_destroy(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void urb_destroy(struct kref * kref)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void urb_destroy(struct kref * kref)
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
void urb_destroy(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void urb_destroy(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void urb_destroy(struct kref * kref)
```
</details>
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

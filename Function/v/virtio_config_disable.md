# Function: <code>virtio_config_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583820301,
      "name": "virtio_config_disable",
      "external": false,
      "loc": "drivers/virtio/virtio.c:148",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_dev_remove",
        "drivers/virtio/virtio.c:virtio_device_freeze"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584149277,
      "name": "virtio_config_disable",
      "external": false,
      "loc": "drivers/virtio/virtio.c:148",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584329853,
      "name": "virtio_config_disable",
      "external": false,
      "loc": "drivers/virtio/virtio.c:148",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void virtio_config_disable(struct virtio_device * dev)
```

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584409885,
      "name": "virtio_config_disable",
      "external": true,
      "loc": "drivers/virtio/virtio.c:143",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584408944,
      "name": "virtio_config_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void virtio_config_disable(struct virtio_device * dev)
```

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584817325,
      "name": "virtio_config_disable",
      "external": true,
      "loc": "drivers/virtio/virtio.c:143",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584816272,
      "name": "virtio_config_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void virtio_config_disable(struct virtio_device * dev)
```

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585047820,
      "name": "virtio_config_disable",
      "external": true,
      "loc": "drivers/virtio/virtio.c:143",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585046736,
      "name": "virtio_config_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void virtio_config_disable(struct virtio_device * dev)
```

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585155612,
      "name": "virtio_config_disable",
      "external": true,
      "loc": "drivers/virtio/virtio.c:143",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585154528,
      "name": "virtio_config_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void virtio_config_disable(struct virtio_device * dev)
```

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585362697,
      "name": "virtio_config_disable",
      "external": true,
      "loc": "drivers/virtio/virtio.c:144",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585361824,
      "name": "virtio_config_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void virtio_config_disable(struct virtio_device * dev)
```

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585501289,
      "name": "virtio_config_disable",
      "external": true,
      "loc": "drivers/virtio/virtio.c:144",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585500416,
      "name": "virtio_config_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void virtio_config_disable(struct virtio_device * dev)
```

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586223040,
      "name": "virtio_config_disable",
      "external": true,
      "loc": "drivers/virtio/virtio.c:144",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586223040,
      "name": "virtio_config_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void virtio_config_disable(struct virtio_device * dev)
```

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586341744,
      "name": "virtio_config_disable",
      "external": true,
      "loc": "drivers/virtio/virtio.c:144",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586341744,
      "name": "virtio_config_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586226169,
      "name": "virtio_config_disable",
      "external": false,
      "loc": "drivers/virtio/virtio.c:144",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
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
  "name": "virtio_config_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586732409,
      "name": "virtio_config_disable",
      "external": false,
      "loc": "drivers/virtio/virtio.c:145",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
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
  "name": "virtio_config_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588004537,
      "name": "virtio_config_disable",
      "external": false,
      "loc": "drivers/virtio/virtio.c:146",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
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
  "name": "virtio_config_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589375641,
      "name": "virtio_config_disable",
      "external": false,
      "loc": "drivers/virtio/virtio.c:146",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
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
  "name": "virtio_config_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589674281,
      "name": "virtio_config_disable",
      "external": false,
      "loc": "drivers/virtio/virtio.c:146",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
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
  "name": "virtio_config_disable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590005129,
      "name": "virtio_config_disable",
      "external": false,
      "loc": "drivers/virtio/virtio.c:146",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void virtio_config_disable(struct virtio_device * dev)
```

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498157288,
      "name": "virtio_config_disable",
      "external": true,
      "loc": "drivers/virtio/virtio.c:144",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498156200,
      "name": "virtio_config_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void virtio_config_disable(struct virtio_device * dev)
```

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230919056,
      "name": "virtio_config_disable",
      "external": true,
      "loc": "drivers/virtio/virtio.c:144",
      "file": "drivers/virtio/virtio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230919056,
      "name": "virtio_config_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void virtio_config_disable(struct virtio_device * dev)
```

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291384564,
      "name": "virtio_config_disable",
      "external": true,
      "loc": "drivers/virtio/virtio.c:144",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291383024,
      "name": "virtio_config_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void virtio_config_disable(struct virtio_device * dev)
```

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275938502,
      "name": "virtio_config_disable",
      "external": true,
      "loc": "drivers/virtio/virtio.c:144",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_dev_remove"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275939826,
      "name": "virtio_config_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void virtio_config_disable(struct virtio_device * dev)
```

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585263369,
      "name": "virtio_config_disable",
      "external": true,
      "loc": "drivers/virtio/virtio.c:144",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585262496,
      "name": "virtio_config_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void virtio_config_disable(struct virtio_device * dev)
```

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585215977,
      "name": "virtio_config_disable",
      "external": true,
      "loc": "drivers/virtio/virtio.c:144",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585215120,
      "name": "virtio_config_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void virtio_config_disable(struct virtio_device * dev)
```

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585451689,
      "name": "virtio_config_disable",
      "external": true,
      "loc": "drivers/virtio/virtio.c:144",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585450816,
      "name": "virtio_config_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void virtio_config_disable(struct virtio_device * dev)
```

```json
{
  "name": "virtio_config_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585557769,
      "name": "virtio_config_disable",
      "external": true,
      "loc": "drivers/virtio/virtio.c:144",
      "file": "drivers/virtio/virtio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio.c:virtio_device_freeze",
        "drivers/virtio/virtio.c:virtio_dev_remove"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585557536,
      "name": "virtio_config_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void virtio_config_disable(struct virtio_device * dev)
```
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void virtio_config_disable(struct virtio_device * dev)
```
</details>
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

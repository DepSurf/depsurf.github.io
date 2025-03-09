# Function: <code>cdev_set_parent</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581293120,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:483",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293120,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581432784,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:508",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432784,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581590576,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:508",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581590576,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581676560,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:508",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581676560,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:505",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581797578,
      "name": "cdev_set_parent.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071581794768,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581868689,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:505",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581867392,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582095425,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:508",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582093392,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582142241,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:508",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_add"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139648,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582166769,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:508",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_add"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582164432,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582483969,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:508",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_add"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582481536,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583005216,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:508",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_add"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002512,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583567920,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:515",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_add"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583564336,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583784032,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:515",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_add"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583780752,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583989616,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:515",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_add"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_cdev.c:rproc_char_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986256,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493341208,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:505",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493340632,
      "name": "cdev_set_parent",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226934672,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:505",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226934432,
      "name": "cdev_set_parent",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286882800,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:505",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:cdev_device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286882800,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273071046,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:505",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273070522,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581837425,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:505",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836128,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581775089,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:505",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_add"
      ],
      "caller_func": [
        "drivers/dax/device.c:dev_dax_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581773792,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581828737,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:505",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827440,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
```

```json
{
  "name": "cdev_set_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581898097,
      "name": "cdev_set_parent",
      "external": true,
      "loc": "fs/char_dev.c:505",
      "file": "fs/char_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/char_dev.c:cdev_device_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896720,
      "name": "cdev_set_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void cdev_set_parent(struct cdev * p, struct kobject * kobj)
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

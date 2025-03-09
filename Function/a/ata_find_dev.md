# Function: <code>ata_find_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584946352,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:2832",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584946352,
      "name": "ata_find_dev.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585325354,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:2972",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585312096,
      "name": "ata_find_dev.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585526394,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3053",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585513440,
      "name": "ata_find_dev.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585601072,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3030",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585601072,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586032656,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3031",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586032656,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586279680,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3034",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586279680,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586420544,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3029",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586420544,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586666320,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3033",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666320,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586813632,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3033",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586813632,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587607333,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:2745",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587606800,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587669029,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:2745",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587668496,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587548385,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:2741",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587547840,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588127446,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:2701",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588126992,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589508860,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:2705",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589507392,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591094204,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:2718",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591092208,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
struct ata_device * ata_find_dev(struct ata_port * ap, unsigned int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591452022,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:2848",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591444784,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
struct ata_device * ata_find_dev(struct ata_port * ap, unsigned int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591801318,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:2720",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591794592,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499728664,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3033",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499728664,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232186336,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3033",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232186336,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293078544,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3033",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293078544,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276898722,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3033",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276898722,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586572208,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3033",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586572208,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586440784,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3033",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586440784,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586768192,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3033",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586768192,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
```

```json
{
  "name": "ata_find_dev",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586874256,
      "name": "ata_find_dev",
      "external": false,
      "loc": "drivers/ata/libata-scsi.c:3033",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev",
        "drivers/ata/libata-scsi.c:__ata_scsi_find_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586874256,
      "name": "ata_find_dev",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
struct ata_device * ata_find_dev(struct ata_port * ap, int devno)
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int devno</code> ➡️ <code>unsigned int devno</code>
</li>
</ul>
</details>
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

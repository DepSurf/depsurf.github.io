# Function: <code>hibernation_restore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579695104,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:494",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579695104,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579714224,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:501",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579714224,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579741792,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:503",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741792,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579737968,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:501",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737968,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579771344,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:501",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771344,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:506",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807012,
      "name": "hibernation_restore.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579805120,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:507",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853655,
      "name": "hibernation_restore.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579851760,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:514",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887860,
      "name": "hibernation_restore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579885936,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:515",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938112,
      "name": "hibernation_restore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579936160,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980528,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:527",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980528,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579966592,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:527",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579966592,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:527",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591236386,
      "name": "hibernation_restore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579968976,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:530",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592124043,
      "name": "hibernation_restore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071580100096,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580239136,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:531",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580239136,
      "name": "hibernation_restore",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580433728,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:535",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580433728,
      "name": "hibernation_restore",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580502960,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:536",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580502960,
      "name": "hibernation_restore",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580562848,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:536",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580562848,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225144484,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:515",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225144484,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:515",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905952,
      "name": "hibernation_restore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579904000,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:515",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579845120,
      "name": "hibernation_restore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579843200,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:515",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898384,
      "name": "hibernation_restore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579896432,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hibernation_restore(int platform_mode)
```

```json
{
  "name": "hibernation_restore",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernation_restore",
      "external": true,
      "loc": "kernel/power/hibernate.c:515",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:load_image_and_restore",
        "kernel/power/user.c:snapshot_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944416,
      "name": "hibernation_restore.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579942464,
      "name": "hibernation_restore",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int hibernation_restore(int platform_mode)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int hibernation_restore(int platform_mode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int hibernation_restore(int platform_mode)
```
</details>
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

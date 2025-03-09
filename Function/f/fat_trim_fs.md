# Function: <code>fat_trim_fs</code>

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
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582797696,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:701",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582797696,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1142
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
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582972112,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:701",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582972112,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1202
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
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583078720,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:704",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583078720,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1202
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
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583397184,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:760",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_ioctl_fitrim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583397184,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1344
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
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583512832,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:760",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_ioctl_fitrim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583512832,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1344
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
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583535952,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:760",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583535952,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1340
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
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:761",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592279181,
      "name": "fat_trim_fs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071583893600,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1541
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:762",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594061518,
      "name": "fat_trim_fs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
    },
    {
      "addr": 18446744071584469920,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1658
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:762",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596089403,
      "name": "fat_trim_fs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
    },
    {
      "addr": 18446744071585133552,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1658
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:762",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596612766,
      "name": "fat_trim_fs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    },
    {
      "addr": 18446744071585362896,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1658
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:762",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597518720,
      "name": "fat_trim_fs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
    },
    {
      "addr": 18446744071585597632,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1658
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
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494784048,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:704",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494784048,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 992
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
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228204052,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:704",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228204052,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1412
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
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288618144,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:704",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288618144,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1368
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
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274116098,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:704",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274116098,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 850
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
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583047456,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:704",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583047456,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1202
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
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582984608,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:704",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582984608,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1202
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
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583036064,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:704",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583036064,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1202
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
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
```

```json
{
  "name": "fat_trim_fs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583125200,
      "name": "fat_trim_fs",
      "external": true,
      "loc": "fs/fat/fatent.c:704",
      "file": "fs/fat/fatent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_generic_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583125200,
      "name": "fat_trim_fs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1197
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
int fat_trim_fs(struct inode * inode, struct fstrim_range * range)
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

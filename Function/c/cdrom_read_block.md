# Function: <code>cdrom_read_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585141260,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2082",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
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
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585533852,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2092",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
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
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585721740,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2092",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585796720,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2090",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585796720,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586235568,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2090",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235568,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586494512,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2087",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586494512,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586642512,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2087",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586642512,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586896096,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2088",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586896096,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587093440,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2095",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587093440,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587940288,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2098",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587940288,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588000768,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2081",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000768,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587882112,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2081",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587882112,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588484976,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2081",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588484976,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589905188,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2085",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589890256,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591482050,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2085",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591466752,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591888432,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2068",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591888432,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592627936,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2068",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592627936,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500163040,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2095",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500163040,
      "name": "cdrom_read_block",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232640508,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2095",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232640508,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293439760,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2095",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293439760,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277104836,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2095",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586799520,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2095",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586799520,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586741360,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2095",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586741360,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587048000,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2095",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587048000,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
```

```json
{
  "name": "cdrom_read_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587155168,
      "name": "cdrom_read_block",
      "external": false,
      "loc": "drivers/cdrom/cdrom.c:2095",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587155168,
      "name": "cdrom_read_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int cdrom_read_block(struct cdrom_device_info * cdi, struct packet_command * cgc, int lba, int nblocks, int format, int blksize)
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

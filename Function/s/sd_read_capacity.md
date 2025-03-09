# Function: <code>sd_read_capacity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584865766,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2229",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585230165,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2240",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585425451,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2296",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585510315,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2446",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585942053,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2484",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586189152,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2455",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586332126,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2442",
      "file": "drivers/scsi/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586568784,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2429",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586568784,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 919
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
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586715936,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2439",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586715936,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 907
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
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587525920,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2459",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587525920,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587589936,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2503",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587589936,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587470496,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2518",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587470496,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588045600,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2481",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588045600,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589408336,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2421",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589408336,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 866
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
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590982128,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2462",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590982128,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 835
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
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591335696,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2576",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591335696,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 863
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
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591685232,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2626",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591685232,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 863
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
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499627656,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2439",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499627656,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 800
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
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232081604,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2439",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232081604,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
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
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292945088,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2439",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292945088,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
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
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276809510,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2439",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276809510,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 734
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
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586406416,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2439",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586406416,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 907
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
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586282672,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2439",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586282672,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 907
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
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586670496,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2439",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586670496,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 907
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
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```

```json
{
  "name": "sd_read_capacity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586776448,
      "name": "sd_read_capacity",
      "external": false,
      "loc": "drivers/scsi/sd.c:2439",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586776448,
      "name": "sd_read_capacity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 907
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void sd_read_capacity(struct scsi_disk * sdkp, unsigned char * buffer)
```
</details>
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

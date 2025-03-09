# Function: <code>md_add_new_disk</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int md_add_new_disk(struct mddev * mddev, struct mdu_disk_info_s * info)
```

```json
{
  "name": "md_add_new_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_add_new_disk",
      "external": true,
      "loc": "drivers/md/md.c:6724",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591589067,
      "name": "md_add_new_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    },
    {
      "addr": 18446744071588762896,
      "name": "md_add_new_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1513
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
int md_add_new_disk(struct mddev * mddev, struct mdu_disk_info_s * info)
```

```json
{
  "name": "md_add_new_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_add_new_disk",
      "external": true,
      "loc": "drivers/md/md.c:6679",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591532155,
      "name": "md_add_new_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071588648272,
      "name": "md_add_new_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1507
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
int md_add_new_disk(struct mddev * mddev, struct mdu_disk_info_s * info)
```

```json
{
  "name": "md_add_new_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_add_new_disk",
      "external": true,
      "loc": "drivers/md/md.c:6692",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592643771,
      "name": "md_add_new_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071589326064,
      "name": "md_add_new_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1564
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
int md_add_new_disk(struct mddev * mddev, struct mdu_disk_info_s * info)
```

```json
{
  "name": "md_add_new_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_add_new_disk",
      "external": true,
      "loc": "drivers/md/md.c:6683",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594528025,
      "name": "md_add_new_disk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071590797952,
      "name": "md_add_new_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1431
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
int md_add_new_disk(struct mddev * mddev, struct mdu_disk_info_s * info)
```

```json
{
  "name": "md_add_new_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592483504,
      "name": "md_add_new_disk",
      "external": true,
      "loc": "drivers/md/md.c:6669",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592483504,
      "name": "md_add_new_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1584
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
int md_add_new_disk(struct mddev * mddev, struct mdu_disk_info_s * info)
```

```json
{
  "name": "md_add_new_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592913872,
      "name": "md_add_new_disk",
      "external": true,
      "loc": "drivers/md/md.c:6673",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592913872,
      "name": "md_add_new_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1586
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
int md_add_new_disk(struct mddev * mddev, struct mdu_disk_info_s * info)
```

```json
{
  "name": "md_add_new_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593643616,
      "name": "md_add_new_disk",
      "external": true,
      "loc": "drivers/md/md.c:6783",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593643616,
      "name": "md_add_new_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1574
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int md_add_new_disk(struct mddev * mddev, struct mdu_disk_info_s * info)
```
</details>
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

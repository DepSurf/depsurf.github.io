# Function: <code>md_set_array_info</code>

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
int md_set_array_info(struct mddev * mddev, struct mdu_array_info_s * info)
```

```json
{
  "name": "md_set_array_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_set_array_info",
      "external": true,
      "loc": "drivers/md/md.c:7142",
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
      "addr": 18446744071591587860,
      "name": "md_set_array_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588751792,
      "name": "md_set_array_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 469
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
int md_set_array_info(struct mddev * mddev, struct mdu_array_info_s * info)
```

```json
{
  "name": "md_set_array_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_set_array_info",
      "external": true,
      "loc": "drivers/md/md.c:7097",
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
      "addr": 18446744071591530949,
      "name": "md_set_array_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588637360,
      "name": "md_set_array_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
int md_set_array_info(struct mddev * mddev, struct mdu_array_info_s * info)
```

```json
{
  "name": "md_set_array_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_set_array_info",
      "external": true,
      "loc": "drivers/md/md.c:7110",
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
      "addr": 18446744071592642539,
      "name": "md_set_array_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589314896,
      "name": "md_set_array_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 499
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
int md_set_array_info(struct mddev * mddev, struct mdu_array_info_s * info)
```

```json
{
  "name": "md_set_array_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "md_set_array_info",
      "external": true,
      "loc": "drivers/md/md.c:7107",
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
      "addr": 18446744071594526800,
      "name": "md_set_array_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590787024,
      "name": "md_set_array_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int md_set_array_info(struct mddev * mddev, struct mdu_array_info_s * info)
```

```json
{
  "name": "md_set_array_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592469648,
      "name": "md_set_array_info",
      "external": true,
      "loc": "drivers/md/md.c:7093",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:__md_set_array_info",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592469648,
      "name": "md_set_array_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
int md_set_array_info(struct mddev * mddev, struct mdu_array_info_s * info)
```

```json
{
  "name": "md_set_array_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592892208,
      "name": "md_set_array_info",
      "external": true,
      "loc": "drivers/md/md.c:7096",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:__md_set_array_info",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592892208,
      "name": "md_set_array_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
int md_set_array_info(struct mddev * mddev, struct mdu_array_info_s * info)
```

```json
{
  "name": "md_set_array_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593641136,
      "name": "md_set_array_info",
      "external": true,
      "loc": "drivers/md/md.c:7211",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:__md_set_array_info",
        "drivers/md/md-autodetect.c:md_setup_drive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593641136,
      "name": "md_set_array_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
int md_set_array_info(struct mddev * mddev, struct mdu_array_info_s * info)
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

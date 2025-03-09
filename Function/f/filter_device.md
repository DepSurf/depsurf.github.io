# Function: <code>filter_device</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
bool filter_device(struct hash_cell * hc, const char * pfx_name, const char * pfx_uuid)
```

```json
{
  "name": "filter_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filter_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:543",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:list_devices",
        "drivers/md/dm-ioctl.c:list_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588711616,
      "name": "filter_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071591535686,
      "name": "filter_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
bool filter_device(struct hash_cell * hc, const char * pfx_name, const char * pfx_uuid)
```

```json
{
  "name": "filter_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filter_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:548",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:list_devices",
        "drivers/md/dm-ioctl.c:list_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589400288,
      "name": "filter_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071592649203,
      "name": "filter_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
bool filter_device(struct hash_cell * hc, const char * pfx_name, const char * pfx_uuid)
```

```json
{
  "name": "filter_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "filter_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:549",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:list_devices",
        "drivers/md/dm-ioctl.c:list_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590876576,
      "name": "filter_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071594533933,
      "name": "filter_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
bool filter_device(struct hash_cell * hc, const char * pfx_name, const char * pfx_uuid)
```

```json
{
  "name": "filter_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592570848,
      "name": "filter_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:549",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:list_devices",
        "drivers/md/dm-ioctl.c:list_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592570848,
      "name": "filter_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
bool filter_device(struct hash_cell * hc, const char * pfx_name, const char * pfx_uuid)
```

```json
{
  "name": "filter_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593001584,
      "name": "filter_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:567",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:list_devices",
        "drivers/md/dm-ioctl.c:list_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593001584,
      "name": "filter_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
bool filter_device(struct hash_cell * hc, const char * pfx_name, const char * pfx_uuid)
```

```json
{
  "name": "filter_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593752784,
      "name": "filter_device",
      "external": false,
      "loc": "drivers/md/dm-ioctl.c:567",
      "file": "drivers/md/dm-ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:list_devices",
        "drivers/md/dm-ioctl.c:list_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593752784,
      "name": "filter_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
bool filter_device(struct hash_cell * hc, const char * pfx_name, const char * pfx_uuid)
```
</details>
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

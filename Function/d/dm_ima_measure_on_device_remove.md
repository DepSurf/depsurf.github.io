# Function: <code>dm_ima_measure_on_device_remove</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void dm_ima_measure_on_device_remove(struct mapped_device * md, bool remove_all)
```

```json
{
  "name": "dm_ima_measure_on_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_ima_measure_on_device_remove",
      "external": true,
      "loc": "drivers/md/dm-ima.c:477",
      "file": "drivers/md/dm-ima.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592648349,
      "name": "dm_ima_measure_on_device_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071589359680,
      "name": "dm_ima_measure_on_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1259
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
void dm_ima_measure_on_device_remove(struct mapped_device * md, bool remove_all)
```

```json
{
  "name": "dm_ima_measure_on_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dm_ima_measure_on_device_remove",
      "external": true,
      "loc": "drivers/md/dm-ima.c:478",
      "file": "drivers/md/dm-ima.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594533285,
      "name": "dm_ima_measure_on_device_remove.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071590833520,
      "name": "dm_ima_measure_on_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1248
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
void dm_ima_measure_on_device_remove(struct mapped_device * md, bool remove_all)
```

```json
{
  "name": "dm_ima_measure_on_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592522528,
      "name": "dm_ima_measure_on_device_remove",
      "external": true,
      "loc": "drivers/md/dm-ima.c:475",
      "file": "drivers/md/dm-ima.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592522528,
      "name": "dm_ima_measure_on_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1260
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
void dm_ima_measure_on_device_remove(struct mapped_device * md, bool remove_all)
```

```json
{
  "name": "dm_ima_measure_on_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592952912,
      "name": "dm_ima_measure_on_device_remove",
      "external": true,
      "loc": "drivers/md/dm-ima.c:474",
      "file": "drivers/md/dm-ima.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592952912,
      "name": "dm_ima_measure_on_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1260
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
void dm_ima_measure_on_device_remove(struct mapped_device * md, bool remove_all)
```

```json
{
  "name": "dm_ima_measure_on_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593702752,
      "name": "dm_ima_measure_on_device_remove",
      "external": true,
      "loc": "drivers/md/dm-ima.c:474",
      "file": "drivers/md/dm-ima.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-ioctl.c:dev_remove",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all",
        "drivers/md/dm-ioctl.c:dm_hash_remove_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593702752,
      "name": "dm_ima_measure_on_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1260
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void dm_ima_measure_on_device_remove(struct mapped_device * md, bool remove_all)
```
</details>
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

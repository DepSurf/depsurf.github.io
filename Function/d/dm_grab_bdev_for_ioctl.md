# Function: <code>dm_grab_bdev_for_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int dm_grab_bdev_for_ioctl(struct mapped_device * md, struct block_device * * bdev, fmode_t * mode)
```

```json
{
  "name": "dm_grab_bdev_for_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586190896,
      "name": "dm_grab_bdev_for_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:413",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586190896,
      "name": "dm_grab_bdev_for_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int dm_grab_bdev_for_ioctl(struct mapped_device * md, struct block_device * * bdev, fmode_t * mode)
```

```json
{
  "name": "dm_grab_bdev_for_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586395024,
      "name": "dm_grab_bdev_for_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:413",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586395024,
      "name": "dm_grab_bdev_for_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int dm_grab_bdev_for_ioctl(struct mapped_device * md, struct block_device * * bdev, fmode_t * mode)
```

```json
{
  "name": "dm_grab_bdev_for_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586498224,
      "name": "dm_grab_bdev_for_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:408",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586498224,
      "name": "dm_grab_bdev_for_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int dm_grab_bdev_for_ioctl(struct mapped_device * md, struct block_device * * bdev, fmode_t * mode)
```

```json
{
  "name": "dm_grab_bdev_for_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586965632,
      "name": "dm_grab_bdev_for_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:415",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586965632,
      "name": "dm_grab_bdev_for_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    }
  ]
}
```
</details>
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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int dm_grab_bdev_for_ioctl(struct mapped_device * md, struct block_device * * bdev, fmode_t * mode)
```
</details>
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int dm_grab_bdev_for_ioctl(struct mapped_device * md, struct block_device * * bdev, fmode_t * mode)
```
</details>
</li>
</ul>

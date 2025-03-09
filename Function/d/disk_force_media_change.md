# Function: <code>disk_force_media_change</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool disk_force_media_change(struct gendisk * disk, unsigned int events)
```

```json
{
  "name": "disk_force_media_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585065844,
      "name": "disk_force_media_change",
      "external": true,
      "loc": "block/disk-events.c:303",
      "file": "block/disk-events.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592319901,
      "name": "disk_force_media_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585065808,
      "name": "disk_force_media_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool disk_force_media_change(struct gendisk * disk, unsigned int events)
```

```json
{
  "name": "disk_force_media_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585788780,
      "name": "disk_force_media_change",
      "external": true,
      "loc": "block/disk-events.c:303",
      "file": "block/disk-events.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594104365,
      "name": "disk_force_media_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585788736,
      "name": "disk_force_media_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
bool disk_force_media_change(struct gendisk * disk, unsigned int events)
```

```json
{
  "name": "disk_force_media_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586569296,
      "name": "disk_force_media_change",
      "external": true,
      "loc": "block/disk-events.c:303",
      "file": "block/disk-events.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586569296,
      "name": "disk_force_media_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
bool disk_force_media_change(struct gendisk * disk, unsigned int events)
```

```json
{
  "name": "disk_force_media_change",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586827088,
      "name": "disk_force_media_change",
      "external": true,
      "loc": "block/disk-events.c:303",
      "file": "block/disk-events.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586827088,
      "name": "disk_force_media_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void disk_force_media_change(struct gendisk * disk)
```

```json
{
  "name": "disk_force_media_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587103984,
      "name": "disk_force_media_change",
      "external": true,
      "loc": "block/disk-events.c:294",
      "file": "block/disk-events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587103984,
      "name": "disk_force_media_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool disk_force_media_change(struct gendisk * disk, unsigned int events)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int events</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>

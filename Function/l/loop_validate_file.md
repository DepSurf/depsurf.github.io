# Function: <code>loop_validate_file</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585831424,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:667",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585831424,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585965632,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:655",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585965632,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586208768,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:655",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586208768,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586356816,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:665",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586356816,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587134928,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:680",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:loop_change_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587134928,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587220720,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:678",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd",
        "drivers/block/loop.c:loop_change_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587220720,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587110288,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:711",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587110288,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587682208,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:704",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587682208,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589030624,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:532",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589030624,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590559040,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:532",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590559040,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590887488,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:532",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590887488,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591231600,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:528",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591231600,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499202648,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:665",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499202648,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231733480,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:665",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231733480,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292405968,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:665",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292405968,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276493124,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:665",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276493124,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586118704,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:665",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118704,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585963328,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:665",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585963328,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586304784,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:665",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586304784,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
int loop_validate_file(struct file * file, struct block_device * bdev)
```

```json
{
  "name": "loop_validate_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586416240,
      "name": "loop_validate_file",
      "external": false,
      "loc": "drivers/block/loop.c:665",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586416240,
      "name": "loop_validate_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int loop_validate_file(struct file * file, struct block_device * bdev)
```
</details>
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

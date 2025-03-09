# Function: <code>remove_and_add_spares</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585747552,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:8138",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:md_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585747552,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586144528,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:8187",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586144528,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 999
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586347344,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:8238",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586347344,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586447824,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:8489",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586447824,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 944
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586941104,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:8549",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586913744,
      "name": "remove_and_add_spares.part.55",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 956
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587192352,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:8635",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587192352,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 991
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587372448,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:8648",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587372448,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 979
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587642880,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:8717",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587642880,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 986
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587846976,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:8821",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587846976,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 986
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588704640,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:9018",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588704640,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1001
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588732176,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:9049",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588732176,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1000
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588618976,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:9027",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588618976,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1000
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589296208,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:9092",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589296208,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1000
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590772960,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:9095",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590772960,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1073
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592447792,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:9106",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592447792,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1090
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592873024,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:9122",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592873024,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1090
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593621840,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:9279",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_choose_sync_action",
        "drivers/md/md.c:hot_remove_disk",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593621840,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 811
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501063784,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:8821",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501063784,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233599432,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:8821",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233599432,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1016
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294580048,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:8821",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294580048,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1312
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277800002,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:8821",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277800002,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587477952,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:8821",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587477952,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 986
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587246112,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:8821",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587246112,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 986
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587803120,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:8821",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587803120,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 986
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
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```

```json
{
  "name": "remove_and_add_spares",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587930720,
      "name": "remove_and_add_spares",
      "external": false,
      "loc": "drivers/md/md.c:8821",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:slot_store",
        "drivers/md/md.c:state_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587930720,
      "name": "remove_and_add_spares",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 986
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int remove_and_add_spares(struct mddev * mddev, struct md_rdev * this)
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

# Function: <code>mddev_create_serial_pool</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void mddev_create_serial_pool(struct mddev * mddev, struct md_rdev * rdev, bool is_suspend)
```

```json
{
  "name": "mddev_create_serial_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mddev_create_serial_pool",
      "external": true,
      "loc": "drivers/md/md.c:211",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588744471,
      "name": "mddev_create_serial_pool.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588713264,
      "name": "mddev_create_serial_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 457
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void mddev_create_serial_pool(struct mddev * mddev, struct md_rdev * rdev, bool is_suspend)
```

```json
{
  "name": "mddev_create_serial_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mddev_create_serial_pool",
      "external": true,
      "loc": "drivers/md/md.c:209",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591587330,
      "name": "mddev_create_serial_pool.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588740672,
      "name": "mddev_create_serial_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
void mddev_create_serial_pool(struct mddev * mddev, struct md_rdev * rdev, bool is_suspend)
```

```json
{
  "name": "mddev_create_serial_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mddev_create_serial_pool",
      "external": true,
      "loc": "drivers/md/md.c:209",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591530419,
      "name": "mddev_create_serial_pool.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071588625792,
      "name": "mddev_create_serial_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
void mddev_create_serial_pool(struct mddev * mddev, struct md_rdev * rdev, bool is_suspend)
```

```json
{
  "name": "mddev_create_serial_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mddev_create_serial_pool",
      "external": true,
      "loc": "drivers/md/md.c:210",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592641936,
      "name": "mddev_create_serial_pool.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071589303120,
      "name": "mddev_create_serial_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
void mddev_create_serial_pool(struct mddev * mddev, struct md_rdev * rdev, bool is_suspend)
```

```json
{
  "name": "mddev_create_serial_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mddev_create_serial_pool",
      "external": true,
      "loc": "drivers/md/md.c:211",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594526239,
      "name": "mddev_create_serial_pool.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071590774768,
      "name": "mddev_create_serial_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void mddev_create_serial_pool(struct mddev * mddev, struct md_rdev * rdev, bool is_suspend)
```

```json
{
  "name": "mddev_create_serial_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592454688,
      "name": "mddev_create_serial_pool",
      "external": true,
      "loc": "drivers/md/md.c:223",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592454688,
      "name": "mddev_create_serial_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
void mddev_create_serial_pool(struct mddev * mddev, struct md_rdev * rdev, bool is_suspend)
```

```json
{
  "name": "mddev_create_serial_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592874912,
      "name": "mddev_create_serial_pool",
      "external": true,
      "loc": "drivers/md/md.c:209",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592874912,
      "name": "mddev_create_serial_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
void mddev_create_serial_pool(struct mddev * mddev, struct md_rdev * rdev)
```

```json
{
  "name": "mddev_create_serial_pool",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593625216,
      "name": "mddev_create_serial_pool",
      "external": true,
      "loc": "drivers/md/md.c:229",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:state_store",
        "drivers/md/md.c:bind_rdev_to_array",
        "drivers/md/md-bitmap.c:backlog_store",
        "drivers/md/md-bitmap.c:md_bitmap_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593625216,
      "name": "mddev_create_serial_pool",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void mddev_create_serial_pool(struct mddev * mddev, struct md_rdev * rdev, bool is_suspend)
```
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool is_suspend</code>
</li>
</ul>
</details>
</li>
</ul>

# Function: <code>ioc_check_iocgs</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int ioc_check_iocgs(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_check_iocgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584672448,
      "name": "ioc_check_iocgs",
      "external": false,
      "loc": "block/blk-iocost.c:2134",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584672448,
      "name": "ioc_check_iocgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 879
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
int ioc_check_iocgs(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_check_iocgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584701728,
      "name": "ioc_check_iocgs",
      "external": false,
      "loc": "block/blk-iocost.c:2141",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584701728,
      "name": "ioc_check_iocgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 877
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
int ioc_check_iocgs(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_check_iocgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_check_iocgs",
      "external": false,
      "loc": "block/blk-iocost.c:2141",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585125008,
      "name": "ioc_check_iocgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
    },
    {
      "addr": 18446744071592320637,
      "name": "ioc_check_iocgs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int ioc_check_iocgs(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_check_iocgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_check_iocgs",
      "external": false,
      "loc": "block/blk-iocost.c:2134",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585860416,
      "name": "ioc_check_iocgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 919
    },
    {
      "addr": 18446744071594105270,
      "name": "ioc_check_iocgs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int ioc_check_iocgs(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_check_iocgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_check_iocgs",
      "external": false,
      "loc": "block/blk-iocost.c:2139",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586640672,
      "name": "ioc_check_iocgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 919
    },
    {
      "addr": 18446744071596109516,
      "name": "ioc_check_iocgs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int ioc_check_iocgs(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_check_iocgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_check_iocgs",
      "external": false,
      "loc": "block/blk-iocost.c:2155",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586901712,
      "name": "ioc_check_iocgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 919
    },
    {
      "addr": 18446744071596633424,
      "name": "ioc_check_iocgs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int ioc_check_iocgs(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_check_iocgs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_check_iocgs",
      "external": false,
      "loc": "block/blk-iocost.c:2162",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587179744,
      "name": "ioc_check_iocgs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 919
    },
    {
      "addr": 18446744071597539742,
      "name": "ioc_check_iocgs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int ioc_check_iocgs(struct ioc * ioc, struct ioc_now * now)
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

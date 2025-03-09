# Function: <code>loop_set_status_from_info</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int loop_set_status_from_info(struct loop_device * lo, const struct loop_info64 * info)
```

```json
{
  "name": "loop_set_status_from_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587140784,
      "name": "loop_set_status_from_info",
      "external": false,
      "loc": "drivers/block/loop.c:1054",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587140784,
      "name": "loop_set_status_from_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 895
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
int loop_set_status_from_info(struct loop_device * lo, const struct loop_info64 * info)
```

```json
{
  "name": "loop_set_status_from_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587225392,
      "name": "loop_set_status_from_info",
      "external": false,
      "loc": "drivers/block/loop.c:1050",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587225392,
      "name": "loop_set_status_from_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 895
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
int loop_set_status_from_info(struct loop_device * lo, const struct loop_info64 * info)
```

```json
{
  "name": "loop_set_status_from_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587113696,
      "name": "loop_set_status_from_info",
      "external": false,
      "loc": "drivers/block/loop.c:1063",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587113696,
      "name": "loop_set_status_from_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 884
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
int loop_set_status_from_info(struct loop_device * lo, const struct loop_info64 * info)
```

```json
{
  "name": "loop_set_status_from_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587683328,
      "name": "loop_set_status_from_info",
      "external": false,
      "loc": "drivers/block/loop.c:1167",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587683328,
      "name": "loop_set_status_from_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 913
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
int loop_set_status_from_info(struct loop_device * lo, const struct loop_info64 * info)
```

```json
{
  "name": "loop_set_status_from_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "loop_set_status_from_info",
      "external": false,
      "loc": "drivers/block/loop.c:961",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589023424,
      "name": "loop_set_status_from_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    },
    {
      "addr": 18446744071594369271,
      "name": "loop_set_status_from_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int loop_set_status_from_info(struct loop_device * lo, const struct loop_info64 * info)
```

```json
{
  "name": "loop_set_status_from_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590551904,
      "name": "loop_set_status_from_info",
      "external": false,
      "loc": "drivers/block/loop.c:961",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590551904,
      "name": "loop_set_status_from_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int loop_set_status_from_info(struct loop_device * lo, const struct loop_info64 * info)
```

```json
{
  "name": "loop_set_status_from_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590880144,
      "name": "loop_set_status_from_info",
      "external": false,
      "loc": "drivers/block/loop.c:961",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590880144,
      "name": "loop_set_status_from_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int loop_set_status_from_info(struct loop_device * lo, const struct loop_info64 * info)
```

```json
{
  "name": "loop_set_status_from_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591224048,
      "name": "loop_set_status_from_info",
      "external": false,
      "loc": "drivers/block/loop.c:957",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591224048,
      "name": "loop_set_status_from_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int loop_set_status_from_info(struct loop_device * lo, const struct loop_info64 * info)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

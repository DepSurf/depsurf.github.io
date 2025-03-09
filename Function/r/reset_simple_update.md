# Function: <code>reset_simple_update</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int reset_simple_update(struct reset_controller_dev * rcdev, long unsigned int id, bool assert)
```

```json
{
  "name": "reset_simple_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reset_simple_update",
      "external": false,
      "loc": "drivers/reset/reset-simple.c:31",
      "file": "drivers/reset/reset-simple.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589624016,
      "name": "reset_simple_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071596232552,
      "name": "reset_simple_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int reset_simple_update(struct reset_controller_dev * rcdev, long unsigned int id, bool assert)
```

```json
{
  "name": "reset_simple_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reset_simple_update",
      "external": false,
      "loc": "drivers/reset/reset-simple.c:31",
      "file": "drivers/reset/reset-simple.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589927536,
      "name": "reset_simple_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071596760454,
      "name": "reset_simple_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int reset_simple_update(struct reset_controller_dev * rcdev, long unsigned int id, bool assert)
```

```json
{
  "name": "reset_simple_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reset_simple_update",
      "external": false,
      "loc": "drivers/reset/reset-simple.c:30",
      "file": "drivers/reset/reset-simple.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590265856,
      "name": "reset_simple_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071597669005,
      "name": "reset_simple_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int reset_simple_update(struct reset_controller_dev * rcdev, long unsigned int id, bool assert)
```

```json
{
  "name": "reset_simple_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498339320,
      "name": "reset_simple_update",
      "external": false,
      "loc": "drivers/reset/reset-simple.c:31",
      "file": "drivers/reset/reset-simple.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/reset-simple.c:reset_simple_deassert",
        "drivers/reset/reset-simple.c:reset_simple_assert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498339320,
      "name": "reset_simple_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int reset_simple_update(struct reset_controller_dev * rcdev, long unsigned int id, bool assert)
```

```json
{
  "name": "reset_simple_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231031264,
      "name": "reset_simple_update",
      "external": false,
      "loc": "drivers/reset/reset-simple.c:31",
      "file": "drivers/reset/reset-simple.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/reset-simple.c:reset_simple_deassert",
        "drivers/reset/reset-simple.c:reset_simple_assert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231031264,
      "name": "reset_simple_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int reset_simple_update(struct reset_controller_dev * rcdev, long unsigned int id, bool assert)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int reset_simple_update(struct reset_controller_dev * rcdev, long unsigned int id, bool assert)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int reset_simple_update(struct reset_controller_dev * rcdev, long unsigned int id, bool assert)
```
</details>
</li>
</ul>

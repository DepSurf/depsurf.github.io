# Function: <code>rdev_read_only</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdev_read_only",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588600085,
      "name": "rdev_read_only",
      "external": false,
      "loc": "drivers/md/md.c:2379",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:bind_rdev_to_array"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdev_read_only",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589276965,
      "name": "rdev_read_only",
      "external": false,
      "loc": "drivers/md/md.c:2389",
      "file": "drivers/md/md.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:bind_rdev_to_array"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool rdev_read_only(struct md_rdev * rdev)
```

```json
{
  "name": "rdev_read_only",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdev_read_only",
      "external": false,
      "loc": "drivers/md/md.c:2383",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:bind_rdev_to_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590757328,
      "name": "rdev_read_only",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071594522391,
      "name": "rdev_read_only.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
bool rdev_read_only(struct md_rdev * rdev)
```

```json
{
  "name": "rdev_read_only",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdev_read_only",
      "external": false,
      "loc": "drivers/md/md.c:2374",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:bind_rdev_to_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592437856,
      "name": "rdev_read_only",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071596310073,
      "name": "rdev_read_only.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
bool rdev_read_only(struct md_rdev * rdev)
```

```json
{
  "name": "rdev_read_only",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdev_read_only",
      "external": false,
      "loc": "drivers/md/md.c:2350",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:bind_rdev_to_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592862464,
      "name": "rdev_read_only",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071596839447,
      "name": "rdev_read_only.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
bool rdev_read_only(struct md_rdev * rdev)
```

```json
{
  "name": "rdev_read_only",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rdev_read_only",
      "external": false,
      "loc": "drivers/md/md.c:2480",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:bind_rdev_to_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593611616,
      "name": "rdev_read_only",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071597763584,
      "name": "rdev_read_only.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool rdev_read_only(struct md_rdev * rdev)
```
</details>
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

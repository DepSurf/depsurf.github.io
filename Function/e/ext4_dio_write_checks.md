# Function: <code>ext4_dio_write_checks</code>

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
ssize_t ext4_dio_write_checks(struct kiocb * iocb, struct iov_iter * from, bool * ilock_shared, bool * extend)
```

```json
{
  "name": "ext4_dio_write_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582946112,
      "name": "ext4_dio_write_checks",
      "external": false,
      "loc": "fs/ext4/file.c:405",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dio_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582946112,
      "name": "ext4_dio_write_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
ssize_t ext4_dio_write_checks(struct kiocb * iocb, struct iov_iter * from, bool * ilock_shared, bool * extend)
```

```json
{
  "name": "ext4_dio_write_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583020800,
      "name": "ext4_dio_write_checks",
      "external": false,
      "loc": "fs/ext4/file.c:406",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dio_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583020800,
      "name": "ext4_dio_write_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dio_write_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583047836,
      "name": "ext4_dio_write_checks",
      "external": false,
      "loc": "fs/ext4/file.c:422",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/file.c:ext4_dio_write_iter"
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
  "name": "ext4_dio_write_checks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_dio_write_checks",
      "external": false,
      "loc": "fs/ext4/file.c:422",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dio_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583383888,
      "name": "ext4_dio_write_checks.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
    },
    {
      "addr": 18446744071592254694,
      "name": "ext4_dio_write_checks.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dio_write_checks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_dio_write_checks",
      "external": false,
      "loc": "fs/ext4/file.c:422",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dio_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583897696,
      "name": "ext4_dio_write_checks.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
    },
    {
      "addr": 18446744071594035666,
      "name": "ext4_dio_write_checks.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dio_write_checks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_dio_write_checks",
      "external": false,
      "loc": "fs/ext4/file.c:437",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dio_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584522416,
      "name": "ext4_dio_write_checks.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
    },
    {
      "addr": 18446744071596068862,
      "name": "ext4_dio_write_checks.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_dio_write_checks",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_dio_write_checks",
      "external": false,
      "loc": "fs/ext4/file.c:451",
      "file": "fs/ext4/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dio_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584751280,
      "name": "ext4_dio_write_checks.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 849
    },
    {
      "addr": 18446744071596592510,
      "name": "ext4_dio_write_checks.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
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
ssize_t ext4_dio_write_checks(struct kiocb * iocb, struct iov_iter * from, bool * ilock_shared, bool * extend, bool * unwritten, int * dio_flags)
```

```json
{
  "name": "ext4_dio_write_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_dio_write_checks",
      "external": false,
      "loc": "fs/ext4/file.c:421",
      "file": "fs/ext4/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dio_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584984064,
      "name": "ext4_dio_write_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 822
    },
    {
      "addr": 18446744071597498188,
      "name": "ext4_dio_write_checks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
ssize_t ext4_dio_write_checks(struct kiocb * iocb, struct iov_iter * from, bool * ilock_shared, bool * extend)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
ssize_t ext4_dio_write_checks(struct kiocb * iocb, struct iov_iter * from, bool * ilock_shared, bool * extend)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
ssize_t ext4_dio_write_checks(struct kiocb * iocb, struct iov_iter * from, bool * ilock_shared, bool * extend, bool * unwritten, int * dio_flags)
```
</details>
</li>
</ul>

# Function: <code>__iomap_dio_rw</code>

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
struct iomap_dio * __iomap_dio_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops, const struct iomap_dio_ops * dops, bool wait_for_completion)
```

```json
{
  "name": "__iomap_dio_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582771648,
      "name": "__iomap_dio_rw",
      "external": true,
      "loc": "fs/iomap/direct-io.c:421",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582771648,
      "name": "__iomap_dio_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1262
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
struct iomap_dio * __iomap_dio_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops, const struct iomap_dio_ops * dops, unsigned int dio_flags)
```

```json
{
  "name": "__iomap_dio_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582799392,
      "name": "__iomap_dio_rw",
      "external": true,
      "loc": "fs/iomap/direct-io.c:451",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582799392,
      "name": "__iomap_dio_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1413
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
struct iomap_dio * __iomap_dio_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops, const struct iomap_dio_ops * dops, unsigned int dio_flags)
```

```json
{
  "name": "__iomap_dio_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iomap_dio_rw",
      "external": true,
      "loc": "fs/iomap/direct-io.c:453",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592245909,
      "name": "__iomap_dio_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071583128048,
      "name": "__iomap_dio_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1611
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
struct iomap_dio * __iomap_dio_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops, const struct iomap_dio_ops * dops, unsigned int dio_flags, void * private, size_t done_before)
```

```json
{
  "name": "__iomap_dio_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iomap_dio_rw",
      "external": true,
      "loc": "fs/iomap/direct-io.c:484",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594026623,
      "name": "__iomap_dio_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071583617424,
      "name": "__iomap_dio_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1760
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
struct iomap_dio * __iomap_dio_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops, const struct iomap_dio_ops * dops, unsigned int dio_flags, void * private, size_t done_before)
```

```json
{
  "name": "__iomap_dio_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iomap_dio_rw",
      "external": true,
      "loc": "fs/iomap/direct-io.c:483",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596062248,
      "name": "__iomap_dio_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071584220912,
      "name": "__iomap_dio_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1848
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
struct iomap_dio * __iomap_dio_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops, const struct iomap_dio_ops * dops, unsigned int dio_flags, void * private, size_t done_before)
```

```json
{
  "name": "__iomap_dio_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iomap_dio_rw",
      "external": true,
      "loc": "fs/iomap/direct-io.c:470",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596586388,
      "name": "__iomap_dio_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071584450320,
      "name": "__iomap_dio_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1836
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
struct iomap_dio * __iomap_dio_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops, const struct iomap_dio_ops * dops, unsigned int dio_flags, void * private, size_t done_before)
```

```json
{
  "name": "__iomap_dio_rw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iomap_dio_rw",
      "external": true,
      "loc": "fs/iomap/direct-io.c:540",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597492187,
      "name": "__iomap_dio_rw.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071584673296,
      "name": "__iomap_dio_rw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1898
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
struct iomap_dio * __iomap_dio_rw(struct kiocb * iocb, struct iov_iter * iter, const struct iomap_ops * ops, const struct iomap_dio_ops * dops, bool wait_for_completion)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int dio_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool wait_for_completion</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * private</code>
</li>
<li>
<b>Param added. </b>
<code>size_t done_before</code>
</li>
</ul>
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

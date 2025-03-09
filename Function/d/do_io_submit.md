# Function: <code>do_io_submit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int do_io_submit(aio_context_t ctx_id, long int nr, struct iocb * * iocbpp, bool compat)
```

```json
{
  "name": "do_io_submit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581324320,
      "name": "do_io_submit",
      "external": true,
      "loc": "fs/aio.c:1572",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:SyS_io_submit",
        "fs/compat.c:compat_SyS_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581324320,
      "name": "do_io_submit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1279
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
long int do_io_submit(aio_context_t ctx_id, long int nr, struct iocb * * iocbpp, bool compat)
```

```json
{
  "name": "do_io_submit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581491472,
      "name": "do_io_submit",
      "external": true,
      "loc": "fs/aio.c:1580",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:SyS_io_submit",
        "fs/compat.c:compat_SyS_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581491472,
      "name": "do_io_submit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1344
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
long int do_io_submit(aio_context_t ctx_id, long int nr, struct iocb * * iocbpp, bool compat)
```

```json
{
  "name": "do_io_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570352,
      "name": "do_io_submit",
      "external": false,
      "loc": "fs/aio.c:1629",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:compat_SyS_io_submit",
        "fs/aio.c:SyS_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570352,
      "name": "do_io_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1555
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
long int do_io_submit(aio_context_t ctx_id, long int nr, struct iocb * * iocbpp, bool compat)
```

```json
{
  "name": "do_io_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581626848,
      "name": "do_io_submit",
      "external": false,
      "loc": "fs/aio.c:1647",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:compat_SyS_io_submit",
        "fs/aio.c:SyS_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581626848,
      "name": "do_io_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1740
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long int do_io_submit(aio_context_t ctx_id, long int nr, struct iocb * * iocbpp, bool compat)
```

```json
{
  "name": "do_io_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581771120,
      "name": "do_io_submit",
      "external": false,
      "loc": "fs/aio.c:1655",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:compat_SyS_io_submit",
        "fs/aio.c:SyS_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581771120,
      "name": "do_io_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1646
    }
  ]
}
```
</details>
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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
long int do_io_submit(aio_context_t ctx_id, long int nr, struct iocb * * iocbpp, bool compat)
```
</details>
</li>
</ul>

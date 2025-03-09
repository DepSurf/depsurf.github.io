# Function: <code>SyS_io_getevents</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int SyS_io_getevents(long int ctx_id, long int min_nr, long int nr, long int events, long int timeout)
```

```json
{
  "name": "SyS_io_getevents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581325920,
      "name": "SyS_io_getevents",
      "external": true,
      "loc": "fs/aio.c:1726",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581325920,
      "name": "SyS_io_getevents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
long int SyS_io_getevents(long int ctx_id, long int min_nr, long int nr, long int events, long int timeout)
```

```json
{
  "name": "SyS_io_getevents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581493136,
      "name": "SyS_io_getevents",
      "external": true,
      "loc": "fs/aio.c:1734",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493136,
      "name": "SyS_io_getevents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_io_getevents(long int ctx_id, long int min_nr, long int nr, long int events, long int timeout)
```

```json
{
  "name": "SyS_io_getevents",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581574942,
      "name": "SyS_io_getevents",
      "external": true,
      "loc": "fs/aio.c:1821",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:compat_SyS_io_getevents"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581574672,
      "name": "SyS_io_getevents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_io_getevents(long int ctx_id, long int min_nr, long int nr, long int events, long int timeout)
```

```json
{
  "name": "SyS_io_getevents",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581631598,
      "name": "SyS_io_getevents",
      "external": true,
      "loc": "fs/aio.c:1839",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:compat_SyS_io_getevents"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581631328,
      "name": "SyS_io_getevents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
long int SyS_io_getevents(long int ctx_id, long int min_nr, long int nr, long int events, long int timeout)
```

```json
{
  "name": "SyS_io_getevents",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581776144,
      "name": "SyS_io_getevents",
      "external": true,
      "loc": "fs/aio.c:1866",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581776144,
      "name": "SyS_io_getevents",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
long int SyS_io_getevents(long int ctx_id, long int min_nr, long int nr, long int events, long int timeout)
```
</details>
</li>
</ul>

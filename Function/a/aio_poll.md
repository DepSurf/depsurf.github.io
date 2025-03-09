# Function: <code>aio_poll</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582029768,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1722",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582167508,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1717",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582244900,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1733",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int aio_poll(struct aio_kiocb * aiocb, const struct iocb * iocb)
```

```json
{
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582481648,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1740",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582481648,
      "name": "aio_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
int aio_poll(struct aio_kiocb * aiocb, const struct iocb * iocb)
```

```json
{
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582538208,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1738",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582538208,
      "name": "aio_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 731
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
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582567184,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1735",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582567184,
      "name": "aio_poll.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 758
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1839",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582884336,
      "name": "aio_poll.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 907
    },
    {
      "addr": 18446744071592236939,
      "name": "aio_poll.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1863",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452064,
      "name": "aio_poll.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 946
    },
    {
      "addr": 18446744071594017208,
      "name": "aio_poll.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1864",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584041920,
      "name": "aio_poll.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 946
    },
    {
      "addr": 18446744071596056814,
      "name": "aio_poll.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1856",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584266640,
      "name": "aio_poll.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 944
    },
    {
      "addr": 18446744071596581063,
      "name": "aio_poll.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1899",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584483440,
      "name": "aio_poll.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 944
    },
    {
      "addr": 18446744071597484908,
      "name": "aio_poll.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493816832,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1733",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227316772,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1733",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287435408,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1733",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273396890,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1733",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582213636,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1733",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582150532,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1733",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582204116,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1733",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aio_poll",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582272852,
      "name": "aio_poll",
      "external": false,
      "loc": "fs/aio.c:1733",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int aio_poll(struct aio_kiocb * aiocb, const struct iocb * iocb)
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
int aio_poll(struct aio_kiocb * aiocb, const struct iocb * iocb)
```
</details>
</li>
</ul>

# Function: <code>nvm_submit_io_wait</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int nvm_submit_io_wait(struct nvm_dev * dev, struct nvm_rq * rqd, void * buf)
```

```json
{
  "name": "nvm_submit_io_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586141408,
      "name": "nvm_submit_io_wait",
      "external": false,
      "loc": "drivers/lightnvm/core.c:767",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/lightnvm/core.c:nvm_submit_io_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586141408,
      "name": "nvm_submit_io_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvm_submit_io_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586897958,
      "name": "nvm_submit_io_wait",
      "external": false,
      "loc": "drivers/lightnvm/core.c:766",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/lightnvm/core.c:nvm_submit_io_sync"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvm_submit_io_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586982822,
      "name": "nvm_submit_io_wait",
      "external": false,
      "loc": "drivers/lightnvm/core.c:762",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/lightnvm/core.c:nvm_submit_io_sync"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvm_submit_io_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586865254,
      "name": "nvm_submit_io_wait",
      "external": false,
      "loc": "drivers/lightnvm/core.c:762",
      "file": "drivers/lightnvm/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/lightnvm/core.c:nvm_submit_io_sync"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int nvm_submit_io_wait(struct nvm_dev * dev, struct nvm_rq * rqd, void * buf)
```

```json
{
  "name": "nvm_submit_io_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498932608,
      "name": "nvm_submit_io_wait",
      "external": false,
      "loc": "drivers/lightnvm/core.c:767",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/lightnvm/core.c:nvm_submit_io_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498932608,
      "name": "nvm_submit_io_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int nvm_submit_io_wait(struct nvm_dev * dev, struct nvm_rq * rqd, void * buf)
```

```json
{
  "name": "nvm_submit_io_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231505376,
      "name": "nvm_submit_io_wait",
      "external": false,
      "loc": "drivers/lightnvm/core.c:767",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/lightnvm/core.c:nvm_submit_io_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231505376,
      "name": "nvm_submit_io_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int nvm_submit_io_wait(struct nvm_dev * dev, struct nvm_rq * rqd, void * buf)
```

```json
{
  "name": "nvm_submit_io_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292069632,
      "name": "nvm_submit_io_wait",
      "external": false,
      "loc": "drivers/lightnvm/core.c:767",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/lightnvm/core.c:nvm_submit_io_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292069632,
      "name": "nvm_submit_io_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int nvm_submit_io_wait(struct nvm_dev * dev, struct nvm_rq * rqd, void * buf)
```

```json
{
  "name": "nvm_submit_io_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276319676,
      "name": "nvm_submit_io_wait",
      "external": false,
      "loc": "drivers/lightnvm/core.c:767",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/lightnvm/core.c:nvm_submit_io_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276319676,
      "name": "nvm_submit_io_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int nvm_submit_io_wait(struct nvm_dev * dev, struct nvm_rq * rqd, void * buf)
```

```json
{
  "name": "nvm_submit_io_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585901776,
      "name": "nvm_submit_io_wait",
      "external": false,
      "loc": "drivers/lightnvm/core.c:767",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/lightnvm/core.c:nvm_submit_io_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585901776,
      "name": "nvm_submit_io_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int nvm_submit_io_wait(struct nvm_dev * dev, struct nvm_rq * rqd, void * buf)
```

```json
{
  "name": "nvm_submit_io_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586091424,
      "name": "nvm_submit_io_wait",
      "external": false,
      "loc": "drivers/lightnvm/core.c:767",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/lightnvm/core.c:nvm_submit_io_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586091424,
      "name": "nvm_submit_io_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int nvm_submit_io_wait(struct nvm_dev * dev, struct nvm_rq * rqd, void * buf)
```

```json
{
  "name": "nvm_submit_io_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586200032,
      "name": "nvm_submit_io_wait",
      "external": false,
      "loc": "drivers/lightnvm/core.c:767",
      "file": "drivers/lightnvm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/lightnvm/core.c:nvm_submit_io_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586200032,
      "name": "nvm_submit_io_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int nvm_submit_io_wait(struct nvm_dev * dev, struct nvm_rq * rqd, void * buf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int nvm_submit_io_wait(struct nvm_dev * dev, struct nvm_rq * rqd, void * buf)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int nvm_submit_io_wait(struct nvm_dev * dev, struct nvm_rq * rqd, void * buf)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

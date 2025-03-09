# Function: <code>io_wq_worker_cancel</code>

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
bool io_wq_worker_cancel(struct io_worker * worker, void * data)
```

```json
{
  "name": "io_wq_worker_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582555488,
      "name": "io_wq_worker_cancel",
      "external": false,
      "loc": "fs/io-wq.c:911",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582555488,
      "name": "io_wq_worker_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
bool io_wq_worker_cancel(struct io_worker * worker, void * data)
```

```json
{
  "name": "io_wq_worker_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582624848,
      "name": "io_wq_worker_cancel",
      "external": false,
      "loc": "fs/io-wq.c:932",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624848,
      "name": "io_wq_worker_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
bool io_wq_worker_cancel(struct io_worker * worker, void * data)
```

```json
{
  "name": "io_wq_worker_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582654304,
      "name": "io_wq_worker_cancel",
      "external": false,
      "loc": "fs/io-wq.c:810",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582654304,
      "name": "io_wq_worker_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
bool io_wq_worker_cancel(struct io_worker * worker, void * data)
```

```json
{
  "name": "io_wq_worker_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_wq_worker_cancel",
      "external": false,
      "loc": "fs/io-wq.c:973",
      "file": "fs/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582978816,
      "name": "io_wq_worker_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071592238974,
      "name": "io_wq_worker_cancel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
bool io_wq_worker_cancel(struct io_worker * worker, void * data)
```

```json
{
  "name": "io_wq_worker_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_wq_worker_cancel",
      "external": false,
      "loc": "io_uring/io-wq.c:1001",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586029824,
      "name": "io_wq_worker_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071594126635,
      "name": "io_wq_worker_cancel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
bool io_wq_worker_cancel(struct io_worker * worker, void * data)
```

```json
{
  "name": "io_wq_worker_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_wq_worker_cancel",
      "external": false,
      "loc": "io_uring/io-wq.c:988",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586865552,
      "name": "io_wq_worker_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071596112624,
      "name": "io_wq_worker_cancel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
bool io_wq_worker_cancel(struct io_worker * worker, void * data)
```

```json
{
  "name": "io_wq_worker_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_wq_worker_cancel",
      "external": false,
      "loc": "io_uring/io-wq.c:978",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587131632,
      "name": "io_wq_worker_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071596637130,
      "name": "io_wq_worker_cancel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
bool io_wq_worker_cancel(struct io_worker * worker, void * data)
```

```json
{
  "name": "io_wq_worker_cancel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "io_wq_worker_cancel",
      "external": false,
      "loc": "io_uring/io-wq.c:999",
      "file": "io_uring/io-wq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587417776,
      "name": "io_wq_worker_cancel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071597544866,
      "name": "io_wq_worker_cancel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
bool io_wq_worker_cancel(struct io_worker * worker, void * data)
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

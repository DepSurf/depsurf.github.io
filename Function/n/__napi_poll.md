# Function: <code>__napi_poll</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int __napi_poll(struct napi_struct * n, bool * repoll)
```

```json
{
  "name": "__napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__napi_poll",
      "external": false,
      "loc": "net/core/dev.c:6994",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_threaded_poll",
        "net/core/dev.c:napi_threaded_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589276880,
      "name": "__napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
    },
    {
      "addr": 18446744071591573020,
      "name": "__napi_poll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
int __napi_poll(struct napi_struct * n, bool * repoll)
```

```json
{
  "name": "__napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__napi_poll",
      "external": false,
      "loc": "net/core/dev.c:6984",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_threaded_poll",
        "net/core/dev.c:napi_threaded_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590001456,
      "name": "__napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    },
    {
      "addr": 18446744071592698892,
      "name": "__napi_poll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int __napi_poll(struct napi_struct * n, bool * repoll)
```

```json
{
  "name": "__napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__napi_poll",
      "external": false,
      "loc": "net/core/dev.c:6479",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_threaded_poll",
        "net/core/dev.c:napi_threaded_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591544064,
      "name": "__napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071594585065,
      "name": "__napi_poll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int __napi_poll(struct napi_struct * n, bool * repoll)
```

```json
{
  "name": "__napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__napi_poll",
      "external": false,
      "loc": "net/core/dev.c:6465",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_threaded_poll",
        "net/core/dev.c:napi_threaded_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593317664,
      "name": "__napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
    },
    {
      "addr": 18446744071596324468,
      "name": "__napi_poll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
int __napi_poll(struct napi_struct * n, bool * repoll)
```

```json
{
  "name": "__napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__napi_poll",
      "external": false,
      "loc": "net/core/dev.c:6446",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_threaded_poll",
        "net/core/dev.c:napi_threaded_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593779328,
      "name": "__napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
    },
    {
      "addr": 18446744071596854771,
      "name": "__napi_poll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
int __napi_poll(struct napi_struct * n, bool * repoll)
```

```json
{
  "name": "__napi_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__napi_poll",
      "external": false,
      "loc": "net/core/dev.c:6562",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_threaded_poll",
        "net/core/dev.c:napi_threaded_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594559776,
      "name": "__napi_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
    },
    {
      "addr": 18446744071597779779,
      "name": "__napi_poll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int __napi_poll(struct napi_struct * n, bool * repoll)
```
</details>
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

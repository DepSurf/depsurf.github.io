# Function: <code>fanotify_get_fsid</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:346",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:346",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
__kernel_fsid_t fanotify_get_fsid(struct fsnotify_iter_info * iter_info)
```

```json
{
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582425360,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:466",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582425360,
      "name": "fanotify_get_fsid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
__kernel_fsid_t fanotify_get_fsid(struct fsnotify_iter_info * iter_info)
```

```json
{
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582479312,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:620",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582479312,
      "name": "fanotify_get_fsid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:665",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:665",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:838",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:841",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:845",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:838",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:346",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:346",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287362092,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:346",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273355726,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:346",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ],
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
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:346",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:346",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:346",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_get_fsid",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_get_fsid",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:346",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ],
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
__kernel_fsid_t fanotify_get_fsid(struct fsnotify_iter_info * iter_info)
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
__kernel_fsid_t fanotify_get_fsid(struct fsnotify_iter_info * iter_info)
```
</details>
</li>
</ul>

# Function: <code>fanotify_event_info_len</code>

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
  "name": "fanotify_event_info_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582118223,
      "name": "fanotify_event_info_len",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:54",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user"
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
  "name": "fanotify_event_info_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582195455,
      "name": "fanotify_event_info_len",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:54",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user"
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
int fanotify_event_info_len(struct fanotify_event * event)
```

```json
{
  "name": "fanotify_event_info_len",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582428848,
      "name": "fanotify_event_info_len",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:67",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:get_one_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582428848,
      "name": "fanotify_event_info_len",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int fanotify_event_info_len(unsigned int fid_mode, struct fanotify_event * event)
```

```json
{
  "name": "fanotify_event_info_len",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582485776,
      "name": "fanotify_event_info_len",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:67",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:get_one_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582485776,
      "name": "fanotify_event_info_len",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
int fanotify_event_info_len(unsigned int fid_mode, struct fanotify_event * event)
```

```json
{
  "name": "fanotify_event_info_len",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582513392,
      "name": "fanotify_event_info_len",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:120",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582513392,
      "name": "fanotify_event_info_len",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int fanotify_event_info_len(unsigned int info_mode, struct fanotify_event * event)
```

```json
{
  "name": "fanotify_event_info_len",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582829376,
      "name": "fanotify_event_info_len",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:129",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582829376,
      "name": "fanotify_event_info_len",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_event_info_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493758736,
      "name": "fanotify_event_info_len",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:54",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user"
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
  "name": "fanotify_event_info_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227275016,
      "name": "fanotify_event_info_len",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:54",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read"
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
  "name": "fanotify_event_info_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287367260,
      "name": "fanotify_event_info_len",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:54",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user"
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
  "name": "fanotify_event_info_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273359268,
      "name": "fanotify_event_info_len",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:54",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user"
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
  "name": "fanotify_event_info_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582164191,
      "name": "fanotify_event_info_len",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:54",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user"
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
  "name": "fanotify_event_info_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582101631,
      "name": "fanotify_event_info_len",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:54",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user"
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
  "name": "fanotify_event_info_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582154671,
      "name": "fanotify_event_info_len",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:54",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user"
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
  "name": "fanotify_event_info_len",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582225838,
      "name": "fanotify_event_info_len",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:54",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:copy_fid_to_user"
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
int fanotify_event_info_len(struct fanotify_event * event)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int fid_mode</code>
</li>
<li>
<b>Param reordered. </b>
<code>event</code> ➡️ <code>fid_mode, event</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int info_mode</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int fid_mode</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int fanotify_event_info_len(unsigned int info_mode, struct fanotify_event * event)
```
</details>
</li>
</ul>

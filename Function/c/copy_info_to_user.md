# Function: <code>copy_info_to_user</code>

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
int copy_info_to_user(__kernel_fsid_t * fsid, struct fanotify_fh * fh, const char * name, size_t name_len, char * buf, size_t count)
```

```json
{
  "name": "copy_info_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582430224,
      "name": "copy_info_to_user",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:220",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582430224,
      "name": "copy_info_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 734
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
int copy_info_to_user(__kernel_fsid_t * fsid, struct fanotify_fh * fh, int info_type, const char * name, size_t name_len, char * buf, size_t count)
```

```json
{
  "name": "copy_info_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582483584,
      "name": "copy_info_to_user",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:228",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582483584,
      "name": "copy_info_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
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
int copy_info_to_user(__kernel_fsid_t * fsid, struct fanotify_fh * fh, int info_type, const char * name, size_t name_len, char * buf, size_t count)
```

```json
{
  "name": "copy_info_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582511264,
      "name": "copy_info_to_user",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:306",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582511264,
      "name": "copy_info_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 800
    }
  ]
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
int copy_info_to_user(__kernel_fsid_t * fsid, struct fanotify_fh * fh, const char * name, size_t name_len, char * buf, size_t count)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int info_type</code>
</li>
<li>
<b>Param reordered. </b>
<code>fsid, fh, name, name_len, buf, count</code> ➡️ <code>fsid, fh, info_type, name, name_len, buf, count</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int copy_info_to_user(__kernel_fsid_t * fsid, struct fanotify_fh * fh, int info_type, const char * name, size_t name_len, char * buf, size_t count)
```
</details>
</li>
</ul>

# Function: <code>remove_watch_from_object</code>

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
int remove_watch_from_object(struct watch_list * wlist, struct watch_queue * wq, u64 id, bool all)
```

```json
{
  "name": "remove_watch_from_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581256896,
      "name": "remove_watch_from_object",
      "external": true,
      "loc": "kernel/watch_queue.c:484",
      "file": "kernel/watch_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_watch_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581256896,
      "name": "remove_watch_from_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
int remove_watch_from_object(struct watch_list * wlist, struct watch_queue * wq, u64 id, bool all)
```

```json
{
  "name": "remove_watch_from_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581298960,
      "name": "remove_watch_from_object",
      "external": true,
      "loc": "kernel/watch_queue.c:484",
      "file": "kernel/watch_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_watch_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581298960,
      "name": "remove_watch_from_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
int remove_watch_from_object(struct watch_list * wlist, struct watch_queue * wq, u64 id, bool all)
```

```json
{
  "name": "remove_watch_from_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581316208,
      "name": "remove_watch_from_object",
      "external": true,
      "loc": "kernel/watch_queue.c:484",
      "file": "kernel/watch_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_watch_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581316208,
      "name": "remove_watch_from_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 627
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
int remove_watch_from_object(struct watch_list * wlist, struct watch_queue * wq, u64 id, bool all)
```

```json
{
  "name": "remove_watch_from_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581561472,
      "name": "remove_watch_from_object",
      "external": true,
      "loc": "kernel/watch_queue.c:487",
      "file": "kernel/watch_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_watch_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581561472,
      "name": "remove_watch_from_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 627
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
int remove_watch_from_object(struct watch_list * wlist, struct watch_queue * wq, u64 id, bool all)
```

```json
{
  "name": "remove_watch_from_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_watch_from_object",
      "external": true,
      "loc": "kernel/watch_queue.c:526",
      "file": "kernel/watch_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_watch_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593964216,
      "name": "remove_watch_from_object.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071581914784,
      "name": "remove_watch_from_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
int remove_watch_from_object(struct watch_list * wlist, struct watch_queue * wq, u64 id, bool all)
```

```json
{
  "name": "remove_watch_from_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "remove_watch_from_object",
      "external": true,
      "loc": "kernel/watch_queue.c:526",
      "file": "kernel/watch_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_watch_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596023849,
      "name": "remove_watch_from_object.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071582349952,
      "name": "remove_watch_from_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int remove_watch_from_object(struct watch_list * wlist, struct watch_queue * wq, u64 id, bool all)
```

```json
{
  "name": "remove_watch_from_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582552800,
      "name": "remove_watch_from_object",
      "external": true,
      "loc": "kernel/watch_queue.c:523",
      "file": "kernel/watch_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_watch_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582552800,
      "name": "remove_watch_from_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 675
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int remove_watch_from_object(struct watch_list * wlist, struct watch_queue * wq, u64 id, bool all)
```

```json
{
  "name": "remove_watch_from_object",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582723376,
      "name": "remove_watch_from_object",
      "external": true,
      "loc": "kernel/watch_queue.c:523",
      "file": "kernel/watch_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:keyctl_watch_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582723376,
      "name": "remove_watch_from_object",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 675
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
int remove_watch_from_object(struct watch_list * wlist, struct watch_queue * wq, u64 id, bool all)
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

# Function: <code>fanotify_should_merge</code>

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
bool fanotify_should_merge(struct fsnotify_event * old_fsn, struct fsnotify_event * new_fsn)
```

```json
{
  "name": "fanotify_should_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582426512,
      "name": "fanotify_should_merge",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:73",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582426512,
      "name": "fanotify_should_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
bool fanotify_should_merge(struct fsnotify_event * old_fsn, struct fsnotify_event * new_fsn)
```

```json
{
  "name": "fanotify_should_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582480320,
      "name": "fanotify_should_merge",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:91",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480320,
      "name": "fanotify_should_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
bool fanotify_should_merge(struct fanotify_event * old, struct fanotify_event * new)
```

```json
{
  "name": "fanotify_should_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582507120,
      "name": "fanotify_should_merge",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:114",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582507120,
      "name": "fanotify_should_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 554
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
  "name": "fanotify_should_merge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582822412,
      "name": "fanotify_should_merge",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:114",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_merge"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool fanotify_should_merge(struct fanotify_event * old, struct fanotify_event * new)
```

```json
{
  "name": "fanotify_should_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583380496,
      "name": "fanotify_should_merge",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:136",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583380496,
      "name": "fanotify_should_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool fanotify_should_merge(struct fanotify_event * old, struct fanotify_event * new)
```

```json
{
  "name": "fanotify_should_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583965920,
      "name": "fanotify_should_merge",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:136",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583965920,
      "name": "fanotify_should_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
bool fanotify_should_merge(struct fanotify_event * old, struct fanotify_event * new)
```

```json
{
  "name": "fanotify_should_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584189360,
      "name": "fanotify_should_merge",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:136",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584189360,
      "name": "fanotify_should_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
bool fanotify_should_merge(struct fanotify_event * old, struct fanotify_event * new)
```

```json
{
  "name": "fanotify_should_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584403344,
      "name": "fanotify_should_merge",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:130",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584403344,
      "name": "fanotify_should_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
bool fanotify_should_merge(struct fsnotify_event * old_fsn, struct fsnotify_event * new_fsn)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fanotify_event * old</code>
</li>
<li>
<b>Param added. </b>
<code>struct fanotify_event * new</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fsnotify_event * old_fsn</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fsnotify_event * new_fsn</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
bool fanotify_should_merge(struct fanotify_event * old, struct fanotify_event * new)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool fanotify_should_merge(struct fanotify_event * old, struct fanotify_event * new)
```
</details>
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

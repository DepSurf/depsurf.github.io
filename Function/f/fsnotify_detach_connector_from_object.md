# Function: <code>fsnotify_detach_connector_from_object</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581570464,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:175",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570464,
      "name": "fsnotify_detach_connector_from_object.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581714704,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:165",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714704,
      "name": "fsnotify_detach_connector_from_object.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581884528,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:164",
      "file": "fs/notify/mark.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581965776,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:184",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581965776,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582098592,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:172",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582098592,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582175936,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:172",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582175936,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582412912,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:172",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582412912,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582467008,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:172",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582467008,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582494064,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:172",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582494064,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582808800,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:203",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582808800,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583363312,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:241",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583363312,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583947024,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:241",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583947024,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584170352,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:241",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584170352,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584384576,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:241",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584384576,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493732872,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:172",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493732872,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227256840,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:172",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227256840,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287340592,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:172",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287340592,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273341508,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:172",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273341508,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582144672,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:172",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582144672,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582082112,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:172",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582082112,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582135152,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:172",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582135152,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```

```json
{
  "name": "fsnotify_detach_connector_from_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582208192,
      "name": "fsnotify_detach_connector_from_object",
      "external": false,
      "loc": "fs/notify/mark.c:172",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_destroy_marks",
        "fs/notify/mark.c:fsnotify_put_mark"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208192,
      "name": "fsnotify_detach_connector_from_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void * fsnotify_detach_connector_from_object(struct fsnotify_mark_connector * conn, unsigned int * type)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

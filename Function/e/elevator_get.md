# Function: <code>elevator_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct elevator_type * elevator_get(const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582724368,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:99",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init",
        "block/elevator.c:__elevator_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582724368,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct elevator_type * elevator_get(const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002112,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:99",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002112,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct elevator_type * elevator_get(const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583107088,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:99",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583107088,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct elevator_type * elevator_get(const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583162832,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:103",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583162832,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583338528,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:116",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583338528,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583548448,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:116",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elevator_init_mq",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init",
        "block/elevator.c:elevator_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583548448,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583671568,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:115",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elevator_init_mq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583671568,
      "name": "elevator_get.constprop.22",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583860192,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:116",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elevator_init_mq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860192,
      "name": "elevator_get.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583962864,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:140",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elevator_init_mq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583962864,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584350736,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:140",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init_mq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584350736,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584467376,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:140",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init_mq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584467376,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584502336,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:140",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init_mq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584502336,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584912864,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:140",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init_mq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584912864,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585613760,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:140",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elevator_change",
        "block/elevator.c:elevator_init_mq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585613760,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
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
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495785688,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:140",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elevator_init_mq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495785688,
      "name": "elevator_get.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229136484,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:140",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elevator_init_mq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229136484,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289962928,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:140",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elevator_init_mq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289962928,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274928442,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:140",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elevator_init_mq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274928442,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583931600,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:140",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elevator_init_mq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583931600,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583868544,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:140",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elevator_init_mq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583868544,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583915360,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:140",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elevator_init_mq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583915360,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```

```json
{
  "name": "elevator_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584016400,
      "name": "elevator_get",
      "external": false,
      "loc": "block/elevator.c:140",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:elv_iosched_store",
        "block/elevator.c:elevator_init_mq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584016400,
      "name": "elevator_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue * q</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, try_loading</code> ➡️ <code>q, name, try_loading</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct elevator_type * elevator_get(struct request_queue * q, const char * name, bool try_loading)
```
</details>
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

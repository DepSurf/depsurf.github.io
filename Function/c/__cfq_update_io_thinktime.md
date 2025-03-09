# Function: <code>__cfq_update_io_thinktime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__cfq_update_io_thinktime",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582924153,
      "name": "__cfq_update_io_thinktime",
      "external": false,
      "loc": "block/cfq-iosched.c:3830",
      "file": "block/cfq-iosched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __cfq_update_io_thinktime(struct cfq_ttime * ttime, u64 slice_idle)
```

```json
{
  "name": "__cfq_update_io_thinktime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583184688,
      "name": "__cfq_update_io_thinktime",
      "external": false,
      "loc": "block/cfq-iosched.c:3874",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184688,
      "name": "__cfq_update_io_thinktime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void __cfq_update_io_thinktime(struct cfq_ttime * ttime, u64 slice_idle)
```

```json
{
  "name": "__cfq_update_io_thinktime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583295536,
      "name": "__cfq_update_io_thinktime",
      "external": false,
      "loc": "block/cfq-iosched.c:3880",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583295536,
      "name": "__cfq_update_io_thinktime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void __cfq_update_io_thinktime(struct cfq_ttime * ttime, u64 slice_idle)
```

```json
{
  "name": "__cfq_update_io_thinktime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583357984,
      "name": "__cfq_update_io_thinktime",
      "external": false,
      "loc": "block/cfq-iosched.c:3885",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583357984,
      "name": "__cfq_update_io_thinktime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void __cfq_update_io_thinktime(struct cfq_ttime * ttime, u64 slice_idle)
```

```json
{
  "name": "__cfq_update_io_thinktime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583540352,
      "name": "__cfq_update_io_thinktime",
      "external": false,
      "loc": "block/cfq-iosched.c:3862",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583540352,
      "name": "__cfq_update_io_thinktime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void __cfq_update_io_thinktime(struct cfq_ttime * ttime, u64 slice_idle)
```

```json
{
  "name": "__cfq_update_io_thinktime",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583755824,
      "name": "__cfq_update_io_thinktime",
      "external": false,
      "loc": "block/cfq-iosched.c:3865",
      "file": "block/cfq-iosched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583755824,
      "name": "__cfq_update_io_thinktime",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void __cfq_update_io_thinktime(struct cfq_ttime * ttime, u64 slice_idle)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void __cfq_update_io_thinktime(struct cfq_ttime * ttime, u64 slice_idle)
```
</details>
</li>
</ul>

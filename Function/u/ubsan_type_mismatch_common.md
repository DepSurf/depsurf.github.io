# Function: <code>ubsan_type_mismatch_common</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void ubsan_type_mismatch_common(struct type_mismatch_data_common * data, long unsigned int ptr)
```

```json
{
  "name": "ubsan_type_mismatch_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ubsan_type_mismatch_common",
      "external": false,
      "loc": "lib/ubsan.c:235",
      "file": "lib/ubsan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ubsan.c:__ubsan_handle_type_mismatch_v1",
        "lib/ubsan.c:__ubsan_handle_type_mismatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585503888,
      "name": "ubsan_type_mismatch_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071592340555,
      "name": "ubsan_type_mismatch_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void ubsan_type_mismatch_common(struct type_mismatch_data_common * data, long unsigned int ptr)
```

```json
{
  "name": "ubsan_type_mismatch_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ubsan_type_mismatch_common",
      "external": false,
      "loc": "lib/ubsan.c:227",
      "file": "lib/ubsan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ubsan.c:__ubsan_handle_type_mismatch_v1",
        "lib/ubsan.c:__ubsan_handle_type_mismatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586652544,
      "name": "ubsan_type_mismatch_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 18446744071594201346,
      "name": "ubsan_type_mismatch_common.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void ubsan_type_mismatch_common(struct type_mismatch_data_common * data, long unsigned int ptr)
```

```json
{
  "name": "ubsan_type_mismatch_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587899328,
      "name": "ubsan_type_mismatch_common",
      "external": false,
      "loc": "lib/ubsan.c:226",
      "file": "lib/ubsan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ubsan.c:__ubsan_handle_type_mismatch_v1",
        "lib/ubsan.c:__ubsan_handle_type_mismatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587899328,
      "name": "ubsan_type_mismatch_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
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
void ubsan_type_mismatch_common(struct type_mismatch_data_common * data, long unsigned int ptr)
```

```json
{
  "name": "ubsan_type_mismatch_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588171040,
      "name": "ubsan_type_mismatch_common",
      "external": false,
      "loc": "lib/ubsan.c:292",
      "file": "lib/ubsan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ubsan.c:__ubsan_handle_type_mismatch_v1",
        "lib/ubsan.c:__ubsan_handle_type_mismatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588171040,
      "name": "ubsan_type_mismatch_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
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
void ubsan_type_mismatch_common(struct type_mismatch_data_common * data, long unsigned int ptr)
```

```json
{
  "name": "ubsan_type_mismatch_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588461856,
      "name": "ubsan_type_mismatch_common",
      "external": false,
      "loc": "lib/ubsan.c:291",
      "file": "lib/ubsan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/ubsan.c:__ubsan_handle_type_mismatch_v1",
        "lib/ubsan.c:__ubsan_handle_type_mismatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588461856,
      "name": "ubsan_type_mismatch_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void ubsan_type_mismatch_common(struct type_mismatch_data_common * data, long unsigned int ptr)
```
</details>
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

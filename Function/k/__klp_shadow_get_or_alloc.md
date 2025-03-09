# Function: <code>__klp_shadow_get_or_alloc</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, void * data, size_t size, gfp_t gfp_flags, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579905664,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:116",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905664,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579939936,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:116",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939936,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579987024,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:116",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987024,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
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
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580028736,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:104",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028736,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580079456,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:104",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079456,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580138720,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:104",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138720,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580115952,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:104",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580115952,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580119536,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:104",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580119536,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580262048,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:104",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580262048,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
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
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580432016,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:104",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580432016,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
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
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580674112,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:104",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674112,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
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
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580750448,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:104",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580750448,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
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
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580835568,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:104",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580835568,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284203632,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:104",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284203632,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580048192,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:104",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048192,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993504,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:104",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993504,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580039728,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:104",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039728,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```

```json
{
  "name": "__klp_shadow_get_or_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580090480,
      "name": "__klp_shadow_get_or_alloc",
      "external": false,
      "loc": "kernel/livepatch/shadow.c:104",
      "file": "kernel/livepatch/shadow.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/shadow.c:klp_shadow_get_or_alloc",
        "kernel/livepatch/shadow.c:klp_shadow_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090480,
      "name": "__klp_shadow_get_or_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, void * data, size_t size, gfp_t gfp_flags, bool warn_on_exist)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>klp_shadow_ctor_t ctor</code>
</li>
<li>
<b>Param added. </b>
<code>void * ctor_data</code>
</li>
<li>
<b>Param removed. </b>
<code>void * data</code>
</li>
<li>
<b>Param reordered. </b>
<code>obj, id, data, size, gfp_flags, warn_on_exist</code> ➡️ <code>obj, id, size, gfp_flags, ctor, ctor_data, warn_on_exist</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * __klp_shadow_get_or_alloc(void * obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void * ctor_data, bool warn_on_exist)
```
</details>
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

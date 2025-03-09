# Function: <code>copyin</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int copyin(void * to, const void * from, size_t n)
```

```json
{
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583452816,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:142",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452816,
      "name": "copyin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int copyin(void * to, const void * from, size_t n)
```

```json
{
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583632912,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:142",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583632912,
      "name": "copyin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
int copyin(void * to, const void * from, size_t n)
```

```json
{
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583850992,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:142",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583850992,
      "name": "copyin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int copyin(void * to, const void * from, size_t n)
```

```json
{
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583934800,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:146",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583934800,
      "name": "copyin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int copyin(void * to, const void * from, size_t n)
```

```json
{
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584112976,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:147",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584112976,
      "name": "copyin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int copyin(void * to, const void * from, size_t n)
```

```json
{
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584235904,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:147",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584235904,
      "name": "copyin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584651073,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:148",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:copy_page_from_iter_iovec",
        "lib/iov_iter.c:copy_page_from_iter_iovec"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int copyin(void * to, const void * from, size_t n)
```

```json
{
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584760640,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:153",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:copy_page_from_iter_iovec",
        "lib/iov_iter.c:copy_page_from_iter_iovec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584760640,
      "name": "copyin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584799035,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:195",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
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
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585222272,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:162",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
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
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586065856,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:160",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
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
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587059028,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:175",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int copyin(void * to, const void * from, size_t n)
```

```json
{
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587299856,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:185",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587299856,
      "name": "copyin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int copyin(void * to, const void * from, size_t n)
```

```json
{
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496112608,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:147",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496112608,
      "name": "copyin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int copyin(void * to, const void * from, size_t n)
```

```json
{
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229435044,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:147",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229435044,
      "name": "copyin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int copyin(void * to, const void * from, size_t n)
```

```json
{
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290381760,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:147",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290381760,
      "name": "copyin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int copyin(void * to, const void * from, size_t n)
```

```json
{
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275175078,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:147",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275175078,
      "name": "copyin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int copyin(void * to, const void * from, size_t n)
```

```json
{
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584204640,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:147",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584204640,
      "name": "copyin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int copyin(void * to, const void * from, size_t n)
```

```json
{
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584139856,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:147",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584139856,
      "name": "copyin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int copyin(void * to, const void * from, size_t n)
```

```json
{
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584188400,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:147",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188400,
      "name": "copyin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int copyin(void * to, const void * from, size_t n)
```

```json
{
  "name": "copyin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584292784,
      "name": "copyin",
      "external": false,
      "loc": "lib/iov_iter.c:147",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter_full",
        "lib/iov_iter.c:_copy_from_iter",
        "lib/iov_iter.c:_copy_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292784,
      "name": "copyin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int copyin(void * to, const void * from, size_t n)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int copyin(void * to, const void * from, size_t n)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int copyin(void * to, const void * from, size_t n)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int copyin(void * to, const void * from, size_t n)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int copyin(void * to, const void * from, size_t n)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int copyin(void * to, const void * from, size_t n)
```
</details>
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

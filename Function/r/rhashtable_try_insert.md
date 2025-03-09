# Function: <code>rhashtable_try_insert</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583459409,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:521",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_insert_slow"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583482017,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:615",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_insert_slow"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583663009,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:617",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_insert_slow"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583880611,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:587",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_insert_slow"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583963043,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:579",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_insert_slow"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584142818,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:580",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_insert_slow"
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
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584265266,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:580",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_insert_slow"
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
void * rhashtable_try_insert(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584672144,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:587",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_insert_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584672144,
      "name": "rhashtable_try_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 964
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
void * rhashtable_try_insert(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584789744,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:587",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_insert_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584789744,
      "name": "rhashtable_try_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 964
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
void * rhashtable_try_insert(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584834384,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:587",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_insert_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584834384,
      "name": "rhashtable_try_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void * rhashtable_try_insert(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:587",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_insert_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585253504,
      "name": "rhashtable_try_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1196
    },
    {
      "addr": 18446744071592324227,
      "name": "rhashtable_try_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void * rhashtable_try_insert(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:587",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_insert_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586095264,
      "name": "rhashtable_try_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1259
    },
    {
      "addr": 18446744071594128724,
      "name": "rhashtable_try_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void * rhashtable_try_insert(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:590",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_insert_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587078848,
      "name": "rhashtable_try_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1254
    },
    {
      "addr": 18446744071596115648,
      "name": "rhashtable_try_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void * rhashtable_try_insert(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:590",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_insert_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587337808,
      "name": "rhashtable_try_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 939
    },
    {
      "addr": 18446744071596641345,
      "name": "rhashtable_try_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void * rhashtable_try_insert(struct rhashtable * ht, const void * key, struct rhash_head * obj)
```

```json
{
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:590",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/rhashtable.c:rhashtable_insert_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587621280,
      "name": "rhashtable_try_insert",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 939
    },
    {
      "addr": 18446744071597549410,
      "name": "rhashtable_try_insert.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496147192,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:580",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_insert_slow"
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
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229468736,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:580",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_insert_slow"
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
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290407364,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:580",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_insert_slow"
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
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275202160,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:580",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_insert_slow"
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
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584234002,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:580",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_insert_slow"
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
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584169202,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:580",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_insert_slow"
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
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584217762,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:580",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_insert_slow"
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
  "name": "rhashtable_try_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584322439,
      "name": "rhashtable_try_insert",
      "external": false,
      "loc": "lib/rhashtable.c:580",
      "file": "lib/rhashtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_insert_slow"
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
void * rhashtable_try_insert(struct rhashtable * ht, const void * key, struct rhash_head * obj)
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

# Function: <code>zswap_pool_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580779598,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:682",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_free_entry",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580904466,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:692",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_free_entry"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580972483,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:619",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_free_entry"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void zswap_pool_put(struct zswap_pool * pool)
```

```json
{
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581016512,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:650",
      "file": "mm/zswap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_free_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581016512,
      "name": "zswap_pool_put",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581128592,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:650",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_free_entry"
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
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581272234,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:665",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_free_entry"
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
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581355391,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:665",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_free_entry"
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
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581464904,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:656",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_free_entry"
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
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581529913,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:656",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_free_entry"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581737932,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:687",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:shrink_worker",
        "mm/zswap.c:zswap_free_entry"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581786466,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:743",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:shrink_worker",
        "mm/zswap.c:zswap_free_entry"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581812777,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:743",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:shrink_worker",
        "mm/zswap.c:zswap_free_entry"
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
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582100209,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:743",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:shrink_worker",
        "mm/zswap.c:zswap_free_entry"
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
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582540327,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:758",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:shrink_worker",
        "mm/zswap.c:zswap_free_entry"
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
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583055959,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:758",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:shrink_worker",
        "mm/zswap.c:zswap_free_entry"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583264292,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:856",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:shrink_worker",
        "mm/zswap.c:zswap_free_entry"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583500669,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:1198",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:shrink_worker",
        "mm/zswap.c:shrink_memcg",
        "mm/zswap.c:zswap_free_entry"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void zswap_pool_put(struct zswap_pool * pool)
```

```json
{
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492954560,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:656",
      "file": "mm/zswap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_free_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492954560,
      "name": "zswap_pool_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void zswap_pool_put(struct zswap_pool * pool)
```

```json
{
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226736900,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:656",
      "file": "mm/zswap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_free_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226736900,
      "name": "zswap_pool_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void zswap_pool_put(struct zswap_pool * pool)
```

```json
{
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286366800,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:656",
      "file": "mm/zswap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_free_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286366800,
      "name": "zswap_pool_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272870628,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:656",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_free_entry"
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
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581498649,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:656",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_free_entry"
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
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581440889,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:656",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_free_entry"
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
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581489961,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:656",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_free_entry"
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
  "name": "zswap_pool_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581554851,
      "name": "zswap_pool_put",
      "external": false,
      "loc": "mm/zswap.c:656",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:__zswap_param_set",
        "mm/zswap.c:zswap_free_entry"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void zswap_pool_put(struct zswap_pool * pool)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void zswap_pool_put(struct zswap_pool * pool)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void zswap_pool_put(struct zswap_pool * pool)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void zswap_pool_put(struct zswap_pool * pool)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void zswap_pool_put(struct zswap_pool * pool)
```
</details>
</li>
</ul>

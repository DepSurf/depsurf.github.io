# Function: <code>prefetch_freepointer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580855742,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:250",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node_track_caller"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581000007,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:248",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581073799,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:244",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581122215,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:246",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void prefetch_freepointer(const struct kmem_cache * s, void * object)
```

```json
{
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581234668,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:272",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc"
      ],
      "caller_func": [
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581203776,
      "name": "prefetch_freepointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void prefetch_freepointer(const struct kmem_cache * s, void * object)
```

```json
{
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581377718,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:272",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc"
      ],
      "caller_func": [
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581348608,
      "name": "prefetch_freepointer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581462031,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:282",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581576288,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:283",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581641504,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:283",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581846999,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:281",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581898369,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:282",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581926192,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:292",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582223780,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:355",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582689490,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:357",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583215004,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:399",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:__kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583433425,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:404",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:__kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583413839,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:517",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_node_trace",
        "mm/slub.c:kmalloc_trace",
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493091284,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:283",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226796728,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:283",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286540428,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:283",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272947120,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:283",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581610240,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:283",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581551573,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:283",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581601552,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:283",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
  "name": "prefetch_freepointer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581667513,
      "name": "prefetch_freepointer",
      "external": false,
      "loc": "mm/slub.c:283",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc"
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void prefetch_freepointer(const struct kmem_cache * s, void * object)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void prefetch_freepointer(const struct kmem_cache * s, void * object)
```
</details>
</li>
</ul>

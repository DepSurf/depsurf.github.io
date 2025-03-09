# Function: <code>inet_frag_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586848765,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:386",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_find"
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
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587298504,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:378",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_find"
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
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587500568,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:378",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_find"
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
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587637902,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:376",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_find"
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
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588162478,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:379",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_find"
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
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588516835,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:175",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588712398,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:180",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct inet_frag_queue * inet_frag_create(struct fqdir * fqdir, void * arg, struct inet_frag_queue * * prev)
```

```json
{
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589132640,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:296",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589132640,
      "name": "inet_frag_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
struct inet_frag_queue * inet_frag_create(struct fqdir * fqdir, void * arg, struct inet_frag_queue * * prev)
```

```json
{
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589356784,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:296",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589356784,
      "name": "inet_frag_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
struct inet_frag_queue * inet_frag_create(struct fqdir * fqdir, void * arg, struct inet_frag_queue * * prev)
```

```json
{
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590339008,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:296",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590339008,
      "name": "inet_frag_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
struct inet_frag_queue * inet_frag_create(struct fqdir * fqdir, void * arg, struct inet_frag_queue * * prev)
```

```json
{
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590391856,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:327",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590391856,
      "name": "inet_frag_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590308539,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:327",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591095947,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:327",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592747466,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:327",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_find"
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
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594618890,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:333",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_find"
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
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595011026,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:333",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_find"
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
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595823746,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:333",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_find"
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
struct inet_frag_queue * inet_frag_create(struct fqdir * fqdir, void * arg, struct inet_frag_queue * * prev)
```

```json
{
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502997816,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:296",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502997816,
      "name": "inet_frag_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1044
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
struct inet_frag_queue * inet_frag_create(struct fqdir * fqdir, void * arg, struct inet_frag_queue * * prev)
```

```json
{
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235687524,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:296",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235687524,
      "name": "inet_frag_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1196
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
struct inet_frag_queue * inet_frag_create(struct fqdir * fqdir, void * arg, struct inet_frag_queue * * prev)
```

```json
{
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296687952,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:296",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296687952,
      "name": "inet_frag_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1392
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
struct inet_frag_queue * inet_frag_create(struct fqdir * fqdir, void * arg, struct inet_frag_queue * * prev)
```

```json
{
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279073104,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:296",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279073104,
      "name": "inet_frag_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 770
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
struct inet_frag_queue * inet_frag_create(struct fqdir * fqdir, void * arg, struct inet_frag_queue * * prev)
```

```json
{
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588962960,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:296",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588962960,
      "name": "inet_frag_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
struct inet_frag_queue * inet_frag_create(struct fqdir * fqdir, void * arg, struct inet_frag_queue * * prev)
```

```json
{
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588674896,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:296",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588674896,
      "name": "inet_frag_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
struct inet_frag_queue * inet_frag_create(struct fqdir * fqdir, void * arg, struct inet_frag_queue * * prev)
```

```json
{
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589399344,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:296",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589399344,
      "name": "inet_frag_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
struct inet_frag_queue * inet_frag_create(struct fqdir * fqdir, void * arg, struct inet_frag_queue * * prev)
```

```json
{
  "name": "inet_frag_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589442544,
      "name": "inet_frag_create",
      "external": false,
      "loc": "net/ipv4/inet_fragment.c:296",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589442544,
      "name": "inet_frag_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1136
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct inet_frag_queue * inet_frag_create(struct fqdir * fqdir, void * arg, struct inet_frag_queue * * prev)
```
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct inet_frag_queue * inet_frag_create(struct fqdir * fqdir, void * arg, struct inet_frag_queue * * prev)
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

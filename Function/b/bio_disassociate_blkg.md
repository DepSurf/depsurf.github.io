# Function: <code>bio_disassociate_blkg</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_disassociate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_disassociate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583663619,
      "name": "bio_disassociate_blkg",
      "external": true,
      "loc": "block/bio.c:1983",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_endio",
        "block/bio.c:bio_reset",
        "block/bio.c:bio_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583662320,
      "name": "bio_disassociate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_disassociate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_disassociate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583851676,
      "name": "bio_disassociate_blkg",
      "external": true,
      "loc": "block/bio.c:2017",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_endio",
        "block/bio.c:bio_reset",
        "block/bio.c:bio_free"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583850240,
      "name": "bio_disassociate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_disassociate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_disassociate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583949733,
      "name": "bio_disassociate_blkg",
      "external": true,
      "loc": "block/bio.c:2059",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583951152,
      "name": "bio_disassociate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bio_disassociate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_disassociate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584342533,
      "name": "bio_disassociate_blkg",
      "external": true,
      "loc": "block/bio.c:1638",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_uninit"
      ],
      "caller_func": [
        "block/bio.c:__bio_associate_blkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584340288,
      "name": "bio_disassociate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void bio_disassociate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_disassociate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495773056,
      "name": "bio_disassociate_blkg",
      "external": true,
      "loc": "block/bio.c:2059",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495773056,
      "name": "bio_disassociate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void bio_disassociate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_disassociate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229123340,
      "name": "bio_disassociate_blkg",
      "external": true,
      "loc": "block/bio.c:2059",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_associate_blkg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229126212,
      "name": "bio_disassociate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void bio_disassociate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_disassociate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289943604,
      "name": "bio_disassociate_blkg",
      "external": true,
      "loc": "block/bio.c:2059",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289946848,
      "name": "bio_disassociate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void bio_disassociate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_disassociate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274916330,
      "name": "bio_disassociate_blkg",
      "external": true,
      "loc": "block/bio.c:2059",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274917148,
      "name": "bio_disassociate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void bio_disassociate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_disassociate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583918469,
      "name": "bio_disassociate_blkg",
      "external": true,
      "loc": "block/bio.c:2059",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919888,
      "name": "bio_disassociate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void bio_disassociate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_disassociate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583855429,
      "name": "bio_disassociate_blkg",
      "external": true,
      "loc": "block/bio.c:2059",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583856848,
      "name": "bio_disassociate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void bio_disassociate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_disassociate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583902229,
      "name": "bio_disassociate_blkg",
      "external": true,
      "loc": "block/bio.c:2059",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583903648,
      "name": "bio_disassociate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void bio_disassociate_blkg(struct bio * bio)
```

```json
{
  "name": "bio_disassociate_blkg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584003381,
      "name": "bio_disassociate_blkg",
      "external": true,
      "loc": "block/bio.c:2059",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584006288,
      "name": "bio_disassociate_blkg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void bio_disassociate_blkg(struct bio * bio)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void bio_disassociate_blkg(struct bio * bio)
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

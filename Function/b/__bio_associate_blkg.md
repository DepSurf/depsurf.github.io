# Function: <code>__bio_associate_blkg</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_associate_blkg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583662336,
      "name": "__bio_associate_blkg",
      "external": false,
      "loc": "block/bio.c:2006",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:__bio_clone_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583662336,
      "name": "__bio_associate_blkg.isra.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
  "name": "__bio_associate_blkg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583850400,
      "name": "__bio_associate_blkg",
      "external": false,
      "loc": "block/bio.c:2040",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:__bio_clone_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583850400,
      "name": "__bio_associate_blkg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_associate_blkg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583949728,
      "name": "__bio_associate_blkg",
      "external": false,
      "loc": "block/bio.c:2082",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:__bio_clone_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583949728,
      "name": "__bio_associate_blkg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void __bio_associate_blkg(struct bio * bio, struct blkcg_gq * blkg)
```

```json
{
  "name": "__bio_associate_blkg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584340368,
      "name": "__bio_associate_blkg",
      "external": false,
      "loc": "block/bio.c:1661",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg",
        "block/bio.c:bio_associate_blkg",
        "block/bio.c:bio_associate_blkg_from_page",
        "block/bio.c:bio_associate_blkg_from_page",
        "block/bio.c:__bio_clone_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584340368,
      "name": "__bio_associate_blkg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_associate_blkg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495773480,
      "name": "__bio_associate_blkg",
      "external": false,
      "loc": "block/bio.c:2082",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:__bio_clone_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495773480,
      "name": "__bio_associate_blkg.isra.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __bio_associate_blkg(struct bio * bio, struct blkcg_gq * blkg)
```

```json
{
  "name": "__bio_associate_blkg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229123316,
      "name": "__bio_associate_blkg",
      "external": false,
      "loc": "block/bio.c:2082",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:__bio_clone_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229123316,
      "name": "__bio_associate_blkg",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__bio_associate_blkg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289943568,
      "name": "__bio_associate_blkg",
      "external": false,
      "loc": "block/bio.c:2082",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:__bio_clone_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289943568,
      "name": "__bio_associate_blkg.isra.0",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_associate_blkg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274916304,
      "name": "__bio_associate_blkg",
      "external": false,
      "loc": "block/bio.c:2082",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:__bio_clone_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274916304,
      "name": "__bio_associate_blkg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_associate_blkg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583918464,
      "name": "__bio_associate_blkg",
      "external": false,
      "loc": "block/bio.c:2082",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:__bio_clone_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918464,
      "name": "__bio_associate_blkg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_associate_blkg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583855424,
      "name": "__bio_associate_blkg",
      "external": false,
      "loc": "block/bio.c:2082",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:__bio_clone_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583855424,
      "name": "__bio_associate_blkg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_associate_blkg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583902224,
      "name": "__bio_associate_blkg",
      "external": false,
      "loc": "block/bio.c:2082",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:bio_associate_blkg_from_css",
        "block/bio.c:__bio_clone_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583902224,
      "name": "__bio_associate_blkg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bio_associate_blkg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584003376,
      "name": "__bio_associate_blkg",
      "external": false,
      "loc": "block/bio.c:2082",
      "file": "block/bio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:bio_clone_blkg_association",
        "block/bio.c:bio_associate_blkg_from_css"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584003376,
      "name": "__bio_associate_blkg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __bio_associate_blkg(struct bio * bio, struct blkcg_gq * blkg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void __bio_associate_blkg(struct bio * bio, struct blkcg_gq * blkg)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void __bio_associate_blkg(struct bio * bio, struct blkcg_gq * blkg)
```
</details>
</li>
</ul>

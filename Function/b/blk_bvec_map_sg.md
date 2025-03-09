# Function: <code>blk_bvec_map_sg</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:345",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_bios_map_sg"
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
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:398",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_bios_map_sg"
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
unsigned int blk_bvec_map_sg(struct request_queue * q, struct bio_vec * bvec, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584395248,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:407",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_bios_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584395248,
      "name": "blk_bvec_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
unsigned int blk_bvec_map_sg(struct request_queue * q, struct bio_vec * bvec, struct scatterlist * sglist, struct scatterlist * * sg)
```

```json
{
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584509568,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:423",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:__blk_bios_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584509568,
      "name": "blk_bvec_map_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:422",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_bios_map_sg"
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
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:424",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_bios_map_sg"
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
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:424",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_bios_map_sg"
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
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:461",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_bios_map_sg"
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
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:462",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_bios_map_sg"
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
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:458",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_bios_map_sg"
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
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:398",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_bios_map_sg"
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
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:398",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_bios_map_sg"
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
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:398",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_bios_map_sg"
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
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274964914,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:398",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_bios_map_sg"
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
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:398",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_bios_map_sg"
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
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:398",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_bios_map_sg"
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
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:398",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_bios_map_sg"
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
  "name": "blk_bvec_map_sg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_bvec_map_sg",
      "external": false,
      "loc": "block/blk-merge.c:398",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:__blk_bios_map_sg"
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
unsigned int blk_bvec_map_sg(struct request_queue * q, struct bio_vec * bvec, struct scatterlist * sglist, struct scatterlist * * sg)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
unsigned int blk_bvec_map_sg(struct request_queue * q, struct bio_vec * bvec, struct scatterlist * sglist, struct scatterlist * * sg)
```
</details>
</li>
</ul>

# Function: <code>iomap_dio_submit_bio</code>

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
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582307904,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:61",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582307904,
      "name": "iomap_dio_submit_bio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582406912,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:61",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582406912,
      "name": "iomap_dio_submit_bio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void iomap_dio_submit_bio(struct iomap_dio * dio, struct iomap * iomap, struct bio * bio, loff_t pos)
```

```json
{
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582698832,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:61",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582698832,
      "name": "iomap_dio_submit_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void iomap_dio_submit_bio(struct iomap_dio * dio, struct iomap * iomap, struct bio * bio, loff_t pos)
```

```json
{
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582770224,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:62",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582770224,
      "name": "iomap_dio_submit_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void iomap_dio_submit_bio(struct iomap_dio * dio, struct iomap * iomap, struct bio * bio, loff_t pos)
```

```json
{
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582798960,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:62",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582798960,
      "name": "iomap_dio_submit_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void iomap_dio_submit_bio(const struct iomap_iter * iter, struct iomap_dio * dio, struct bio * bio, loff_t pos)
```

```json
{
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583126032,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:62",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583126032,
      "name": "iomap_dio_submit_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void iomap_dio_submit_bio(const struct iomap_iter * iter, struct iomap_dio * dio, struct bio * bio, loff_t pos)
```

```json
{
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583615104,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:63",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583615104,
      "name": "iomap_dio_submit_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void iomap_dio_submit_bio(const struct iomap_iter * iter, struct iomap_dio * dio, struct bio * bio, loff_t pos)
```

```json
{
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584218480,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:63",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584218480,
      "name": "iomap_dio_submit_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void iomap_dio_submit_bio(const struct iomap_iter * iter, struct iomap_dio * dio, struct bio * bio, loff_t pos)
```

```json
{
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584448032,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:63",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584448032,
      "name": "iomap_dio_submit_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
void iomap_dio_submit_bio(const struct iomap_iter * iter, struct iomap_dio * dio, struct bio * bio, loff_t pos)
```

```json
{
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584670800,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:64",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_bio_iter",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584670800,
      "name": "iomap_dio_submit_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494008136,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:61",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494008136,
      "name": "iomap_dio_submit_bio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void iomap_dio_submit_bio(struct iomap_dio * dio, struct iomap * iomap, struct bio * bio)
```

```json
{
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227472768,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:61",
      "file": "fs/iomap/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227472768,
      "name": "iomap_dio_submit_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287659920,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:61",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287659920,
      "name": "iomap_dio_submit_bio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273521568,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:61",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273521568,
      "name": "iomap_dio_submit_bio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582375648,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:61",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582375648,
      "name": "iomap_dio_submit_bio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582313344,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:61",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313344,
      "name": "iomap_dio_submit_bio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582366128,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:61",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582366128,
      "name": "iomap_dio_submit_bio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
  "name": "iomap_dio_submit_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582445824,
      "name": "iomap_dio_submit_bio",
      "external": false,
      "loc": "fs/iomap/direct-io.c:61",
      "file": "fs/iomap/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/direct-io.c:iomap_dio_bio_actor",
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582445824,
      "name": "iomap_dio_submit_bio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void iomap_dio_submit_bio(struct iomap_dio * dio, struct iomap * iomap, struct bio * bio, loff_t pos)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct iomap_iter * iter</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iomap * iomap</code>
</li>
<li>
<b>Param reordered. </b>
<code>dio, iomap, bio, pos</code> ➡️ <code>iter, dio, bio, pos</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void iomap_dio_submit_bio(struct iomap_dio * dio, struct iomap * iomap, struct bio * bio)
```
</details>
</li>
</ul>

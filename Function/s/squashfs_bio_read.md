# Function: <code>squashfs_bio_read</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int squashfs_bio_read(struct super_block * sb, u64 index, int length, struct bio * * biop, int * block_offset)
```

```json
{
  "name": "squashfs_bio_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583339136,
      "name": "squashfs_bio_read",
      "external": false,
      "loc": "fs/squashfs/block.c:76",
      "file": "fs/squashfs/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583339136,
      "name": "squashfs_bio_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
int squashfs_bio_read(struct super_block * sb, u64 index, int length, struct bio * * biop, int * block_offset)
```

```json
{
  "name": "squashfs_bio_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583455728,
      "name": "squashfs_bio_read",
      "external": false,
      "loc": "fs/squashfs/block.c:76",
      "file": "fs/squashfs/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583455728,
      "name": "squashfs_bio_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
int squashfs_bio_read(struct super_block * sb, u64 index, int length, struct bio * * biop, int * block_offset)
```

```json
{
  "name": "squashfs_bio_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583478176,
      "name": "squashfs_bio_read",
      "external": false,
      "loc": "fs/squashfs/block.c:76",
      "file": "fs/squashfs/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583478176,
      "name": "squashfs_bio_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
int squashfs_bio_read(struct super_block * sb, u64 index, int length, struct bio * * biop, int * block_offset)
```

```json
{
  "name": "squashfs_bio_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_bio_read",
      "external": false,
      "loc": "fs/squashfs/block.c:75",
      "file": "fs/squashfs/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583832544,
      "name": "squashfs_bio_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    },
    {
      "addr": 18446744071592275469,
      "name": "squashfs_bio_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int squashfs_bio_read(struct super_block * sb, u64 index, int length, struct bio * * biop, int * block_offset)
```

```json
{
  "name": "squashfs_bio_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_bio_read",
      "external": false,
      "loc": "fs/squashfs/block.c:75",
      "file": "fs/squashfs/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584400400,
      "name": "squashfs_bio_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
    },
    {
      "addr": 18446744071594057306,
      "name": "squashfs_bio_read.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int squashfs_bio_read(struct super_block * sb, u64 index, int length, struct bio * * biop, int * block_offset)
```

```json
{
  "name": "squashfs_bio_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_bio_read",
      "external": false,
      "loc": "fs/squashfs/block.c:79",
      "file": "fs/squashfs/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585055312,
      "name": "squashfs_bio_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
    },
    {
      "addr": 18446744071596086375,
      "name": "squashfs_bio_read.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int squashfs_bio_read(struct super_block * sb, u64 index, int length, struct bio * * biop, int * block_offset)
```

```json
{
  "name": "squashfs_bio_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_bio_read",
      "external": false,
      "loc": "fs/squashfs/block.c:189",
      "file": "fs/squashfs/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585284128,
      "name": "squashfs_bio_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
    },
    {
      "addr": 18446744071596609836,
      "name": "squashfs_bio_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
int squashfs_bio_read(struct super_block * sb, u64 index, int length, struct bio * * biop, int * block_offset)
```

```json
{
  "name": "squashfs_bio_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_bio_read",
      "external": false,
      "loc": "fs/squashfs/block.c:189",
      "file": "fs/squashfs/block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585517760,
      "name": "squashfs_bio_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 862
    },
    {
      "addr": 18446744071597515732,
      "name": "squashfs_bio_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int squashfs_bio_read(struct super_block * sb, u64 index, int length, struct bio * * biop, int * block_offset)
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

# Function: <code>copy_to_xfs_dqblk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581424087,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:577",
      "file": "fs/quota/quota.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/quota.c:quota_getxquota"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581602288,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:605",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581602288,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581690784,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:607",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581690784,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581744672,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:607",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581744672,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581891728,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:608",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581891728,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582074992,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:609",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582074992,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582169360,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:607",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582169360,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582333040,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:593",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582333040,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582432224,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:593",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582432224,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582726640,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:591",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582726640,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582798608,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:667",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582798608,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582826032,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:669",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582826032,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583158096,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:669",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583158096,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583648080,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:670",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583648080,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584253936,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:670",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584253936,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584485200,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:670",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584485200,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584708160,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:670",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584708160,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494044768,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:593",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494044768,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227505304,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:593",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227505304,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287699760,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:593",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287699760,
      "name": "copy_to_xfs_dqblk",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273547874,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:593",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273547874,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582400960,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:593",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582400960,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582338656,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:593",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582338656,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582391440,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:593",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582391440,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```

```json
{
  "name": "copy_to_xfs_dqblk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582470976,
      "name": "copy_to_xfs_dqblk",
      "external": false,
      "loc": "fs/quota/quota.c:593",
      "file": "fs/quota/quota.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quota_getnextxquota",
        "fs/quota/quota.c:quota_getxquota"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470976,
      "name": "copy_to_xfs_dqblk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void copy_to_xfs_dqblk(struct fs_disk_quota * dst, struct qc_dqblk * src, int type, qid_t id)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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

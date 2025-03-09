# Function: <code>dquot_load_quota_sb</code>

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
int dquot_load_quota_sb(struct super_block * sb, int type, int format_id, unsigned int flags)
```

```json
{
  "name": "dquot_load_quota_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582724048,
      "name": "dquot_load_quota_sb",
      "external": true,
      "loc": "fs/quota/dquot.c:2332",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582724048,
      "name": "dquot_load_quota_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int dquot_load_quota_sb(struct super_block * sb, int type, int format_id, unsigned int flags)
```

```json
{
  "name": "dquot_load_quota_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582795200,
      "name": "dquot_load_quota_sb",
      "external": true,
      "loc": "fs/quota/dquot.c:2333",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582795200,
      "name": "dquot_load_quota_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int dquot_load_quota_sb(struct super_block * sb, int type, int format_id, unsigned int flags)
```

```json
{
  "name": "dquot_load_quota_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582822656,
      "name": "dquot_load_quota_sb",
      "external": true,
      "loc": "fs/quota/dquot.c:2331",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582822656,
      "name": "dquot_load_quota_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1204
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
int dquot_load_quota_sb(struct super_block * sb, int type, int format_id, unsigned int flags)
```

```json
{
  "name": "dquot_load_quota_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dquot_load_quota_sb",
      "external": true,
      "loc": "fs/quota/dquot.c:2336",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592246858,
      "name": "dquot_load_quota_sb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583154192,
      "name": "dquot_load_quota_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1614
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
int dquot_load_quota_sb(struct super_block * sb, int type, int format_id, unsigned int flags)
```

```json
{
  "name": "dquot_load_quota_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dquot_load_quota_sb",
      "external": true,
      "loc": "fs/quota/dquot.c:2346",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594027535,
      "name": "dquot_load_quota_sb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071583635808,
      "name": "dquot_load_quota_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1533
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
int dquot_load_quota_sb(struct super_block * sb, int type, int format_id, unsigned int flags)
```

```json
{
  "name": "dquot_load_quota_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dquot_load_quota_sb",
      "external": true,
      "loc": "fs/quota/dquot.c:2355",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596063011,
      "name": "dquot_load_quota_sb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071584241088,
      "name": "dquot_load_quota_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1533
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
int dquot_load_quota_sb(struct super_block * sb, int type, int format_id, unsigned int flags)
```

```json
{
  "name": "dquot_load_quota_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dquot_load_quota_sb",
      "external": true,
      "loc": "fs/quota/dquot.c:2413",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596586967,
      "name": "dquot_load_quota_sb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071584471616,
      "name": "dquot_load_quota_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1610
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
int dquot_load_quota_sb(struct super_block * sb, int type, int format_id, unsigned int flags)
```

```json
{
  "name": "dquot_load_quota_sb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dquot_load_quota_sb",
      "external": true,
      "loc": "fs/quota/dquot.c:2381",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_fill_super",
        "mm/shmem.c:shmem_fill_super",
        "fs/quota/dquot.c:dquot_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597492737,
      "name": "dquot_load_quota_sb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071584694560,
      "name": "dquot_load_quota_sb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1580
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
int dquot_load_quota_sb(struct super_block * sb, int type, int format_id, unsigned int flags)
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

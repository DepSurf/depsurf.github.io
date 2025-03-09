# Function: <code>ext4_mb_discard_preallocations_should_retry</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_mb_discard_preallocations_should_retry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583085246,
      "name": "ext4_mb_discard_preallocations_should_retry",
      "external": false,
      "loc": "fs/ext4/mballoc.c:4687",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_new_blocks"
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
  "name": "ext4_mb_discard_preallocations_should_retry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583164065,
      "name": "ext4_mb_discard_preallocations_should_retry",
      "external": false,
      "loc": "fs/ext4/mballoc.c:4866",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_new_blocks"
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
  "name": "ext4_mb_discard_preallocations_should_retry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583191079,
      "name": "ext4_mb_discard_preallocations_should_retry",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5399",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_new_blocks"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool ext4_mb_discard_preallocations_should_retry(struct super_block * sb, struct ext4_allocation_context * ac, u64 * seq)
```

```json
{
  "name": "ext4_mb_discard_preallocations_should_retry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583512752,
      "name": "ext4_mb_discard_preallocations_should_retry",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5466",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_new_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583512752,
      "name": "ext4_mb_discard_preallocations_should_retry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
bool ext4_mb_discard_preallocations_should_retry(struct super_block * sb, struct ext4_allocation_context * ac, u64 * seq)
```

```json
{
  "name": "ext4_mb_discard_preallocations_should_retry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584043072,
      "name": "ext4_mb_discard_preallocations_should_retry",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5521",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_new_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584043072,
      "name": "ext4_mb_discard_preallocations_should_retry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 474
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
bool ext4_mb_discard_preallocations_should_retry(struct super_block * sb, struct ext4_allocation_context * ac, u64 * seq)
```

```json
{
  "name": "ext4_mb_discard_preallocations_should_retry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584674560,
      "name": "ext4_mb_discard_preallocations_should_retry",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5492",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_new_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584674560,
      "name": "ext4_mb_discard_preallocations_should_retry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
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
bool ext4_mb_discard_preallocations_should_retry(struct super_block * sb, struct ext4_allocation_context * ac, u64 * seq)
```

```json
{
  "name": "ext4_mb_discard_preallocations_should_retry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584898944,
      "name": "ext4_mb_discard_preallocations_should_retry",
      "external": false,
      "loc": "fs/ext4/mballoc.c:6066",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_new_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584898944,
      "name": "ext4_mb_discard_preallocations_should_retry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
bool ext4_mb_discard_preallocations_should_retry(struct super_block * sb, struct ext4_allocation_context * ac, u64 * seq)
```

```json
{
  "name": "ext4_mb_discard_preallocations_should_retry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585138416,
      "name": "ext4_mb_discard_preallocations_should_retry",
      "external": false,
      "loc": "fs/ext4/mballoc.c:6026",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_new_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585138416,
      "name": "ext4_mb_discard_preallocations_should_retry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool ext4_mb_discard_preallocations_should_retry(struct super_block * sb, struct ext4_allocation_context * ac, u64 * seq)
```
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

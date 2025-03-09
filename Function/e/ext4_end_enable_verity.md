# Function: <code>ext4_end_enable_verity</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```

```json
{
  "name": "ext4_end_enable_verity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582970544,
      "name": "ext4_end_enable_verity",
      "external": false,
      "loc": "fs/ext4/verity.c:195",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582970544,
      "name": "ext4_end_enable_verity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
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
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```

```json
{
  "name": "ext4_end_enable_verity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583285424,
      "name": "ext4_end_enable_verity",
      "external": false,
      "loc": "fs/ext4/verity.c:198",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583285424,
      "name": "ext4_end_enable_verity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
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
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```

```json
{
  "name": "ext4_end_enable_verity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583400976,
      "name": "ext4_end_enable_verity",
      "external": false,
      "loc": "fs/ext4/verity.c:198",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583400976,
      "name": "ext4_end_enable_verity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```

```json
{
  "name": "ext4_end_enable_verity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583423920,
      "name": "ext4_end_enable_verity",
      "external": false,
      "loc": "fs/ext4/verity.c:192",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583423920,
      "name": "ext4_end_enable_verity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```

```json
{
  "name": "ext4_end_enable_verity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_end_enable_verity",
      "external": false,
      "loc": "fs/ext4/verity.c:192",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583773360,
      "name": "ext4_end_enable_verity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
    },
    {
      "addr": 18446744071592272773,
      "name": "ext4_end_enable_verity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```

```json
{
  "name": "ext4_end_enable_verity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_end_enable_verity",
      "external": false,
      "loc": "fs/ext4/verity.c:193",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333456,
      "name": "ext4_end_enable_verity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 555
    },
    {
      "addr": 18446744071594054633,
      "name": "ext4_end_enable_verity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```

```json
{
  "name": "ext4_end_enable_verity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_end_enable_verity",
      "external": false,
      "loc": "fs/ext4/verity.c:193",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584982336,
      "name": "ext4_end_enable_verity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
    },
    {
      "addr": 18446744071596085901,
      "name": "ext4_end_enable_verity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```

```json
{
  "name": "ext4_end_enable_verity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_end_enable_verity",
      "external": false,
      "loc": "fs/ext4/verity.c:191",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585211152,
      "name": "ext4_end_enable_verity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071596609361,
      "name": "ext4_end_enable_verity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```

```json
{
  "name": "ext4_end_enable_verity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_end_enable_verity",
      "external": false,
      "loc": "fs/ext4/verity.c:191",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585443808,
      "name": "ext4_end_enable_verity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071597514960,
      "name": "ext4_end_enable_verity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```

```json
{
  "name": "ext4_end_enable_verity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494647080,
      "name": "ext4_end_enable_verity",
      "external": false,
      "loc": "fs/ext4/verity.c:195",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494647080,
      "name": "ext4_end_enable_verity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```

```json
{
  "name": "ext4_end_enable_verity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228090552,
      "name": "ext4_end_enable_verity",
      "external": false,
      "loc": "fs/ext4/verity.c:195",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228090552,
      "name": "ext4_end_enable_verity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```

```json
{
  "name": "ext4_end_enable_verity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288458800,
      "name": "ext4_end_enable_verity",
      "external": false,
      "loc": "fs/ext4/verity.c:195",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288458800,
      "name": "ext4_end_enable_verity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```

```json
{
  "name": "ext4_end_enable_verity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274014448,
      "name": "ext4_end_enable_verity",
      "external": false,
      "loc": "fs/ext4/verity.c:195",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274014448,
      "name": "ext4_end_enable_verity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
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
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```

```json
{
  "name": "ext4_end_enable_verity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582939280,
      "name": "ext4_end_enable_verity",
      "external": false,
      "loc": "fs/ext4/verity.c:195",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582939280,
      "name": "ext4_end_enable_verity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
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
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```

```json
{
  "name": "ext4_end_enable_verity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582876432,
      "name": "ext4_end_enable_verity",
      "external": false,
      "loc": "fs/ext4/verity.c:195",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582876432,
      "name": "ext4_end_enable_verity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
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
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```

```json
{
  "name": "ext4_end_enable_verity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582927888,
      "name": "ext4_end_enable_verity",
      "external": false,
      "loc": "fs/ext4/verity.c:195",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582927888,
      "name": "ext4_end_enable_verity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
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
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```

```json
{
  "name": "ext4_end_enable_verity",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583015008,
      "name": "ext4_end_enable_verity",
      "external": false,
      "loc": "fs/ext4/verity.c:195",
      "file": "fs/ext4/verity.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015008,
      "name": "ext4_end_enable_verity",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 529
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int ext4_end_enable_verity(struct file * filp, const void * desc, size_t desc_size, u64 merkle_tree_size)
```
</details>
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

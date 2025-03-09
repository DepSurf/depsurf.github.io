# Function: <code>ext4_get_dev_journal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582132639,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4128",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_load_journal"
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
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581906556,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4290",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
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
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581996532,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4415",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
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
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582222694,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4523",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
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
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582371681,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4532",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_load_journal"
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
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582541156,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4643",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_load_journal"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582642276,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4706",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_load_journal"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
```

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582814272,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4796",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582814272,
      "name": "ext4_get_dev_journal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 876
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
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
```

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582917616,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4827",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582917616,
      "name": "ext4_get_dev_journal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 874
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
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
```

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583229104,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4989",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583229104,
      "name": "ext4_get_dev_journal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 878
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
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
```

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583330704,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:5275",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583330704,
      "name": "ext4_get_dev_journal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
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
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
```

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583353232,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:5321",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353232,
      "name": "ext4_get_dev_journal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 865
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
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
```

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583697440,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:5176",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583697440,
      "name": "ext4_get_dev_journal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 865
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
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
```

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584249056,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:5622",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584249056,
      "name": "ext4_get_dev_journal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
```

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584896448,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:5774",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584896448,
      "name": "ext4_get_dev_journal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
```

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585124832,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:5841",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585124832,
      "name": "ext4_get_dev_journal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
```

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494594016,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4827",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494594016,
      "name": "ext4_get_dev_journal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
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
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
```

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228036928,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4827",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228036928,
      "name": "ext4_get_dev_journal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 900
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
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
```

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288395440,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4827",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288395440,
      "name": "ext4_get_dev_journal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1176
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
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
```

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273972022,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4827",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273972022,
      "name": "ext4_get_dev_journal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
```

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582886352,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4827",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582886352,
      "name": "ext4_get_dev_journal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 874
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
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
```

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582823504,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4827",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582823504,
      "name": "ext4_get_dev_journal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 874
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
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
```

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582875248,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4827",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875248,
      "name": "ext4_get_dev_journal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 874
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
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
```

```json
{
  "name": "ext4_get_dev_journal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582961936,
      "name": "ext4_get_dev_journal",
      "external": false,
      "loc": "fs/ext4/super.c:4827",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582961936,
      "name": "ext4_get_dev_journal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 866
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
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
journal_t * ext4_get_dev_journal(struct super_block * sb, dev_t j_dev)
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

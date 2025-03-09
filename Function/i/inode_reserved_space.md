# Function: <code>inode_reserved_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
qsize_t * inode_reserved_space(struct inode * inode)
```

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581404752,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1562",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:inode_get_rsv_space",
        "fs/quota/dquot.c:inode_add_rsv_space",
        "fs/quota/dquot.c:inode_sub_rsv_space",
        "fs/quota/dquot.c:inode_claim_rsv_space",
        "fs/quota/dquot.c:inode_reclaim_rsv_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581404752,
      "name": "inode_reserved_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
qsize_t * inode_reserved_space(struct inode * inode)
```

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581586240,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1570",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:inode_get_rsv_space",
        "fs/quota/dquot.c:inode_sub_rsv_space",
        "fs/quota/dquot.c:inode_reclaim_rsv_space",
        "fs/quota/dquot.c:inode_claim_rsv_space",
        "fs/quota/dquot.c:inode_add_rsv_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586240,
      "name": "inode_reserved_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
qsize_t * inode_reserved_space(struct inode * inode)
```

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581674624,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1567",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:inode_get_rsv_space",
        "fs/quota/dquot.c:inode_sub_rsv_space",
        "fs/quota/dquot.c:inode_reclaim_rsv_space",
        "fs/quota/dquot.c:inode_claim_rsv_space",
        "fs/quota/dquot.c:inode_add_rsv_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581674624,
      "name": "inode_reserved_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
qsize_t * inode_reserved_space(struct inode * inode)
```

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581729504,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1593",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:inode_sub_rsv_space",
        "fs/quota/dquot.c:inode_reclaim_rsv_space",
        "fs/quota/dquot.c:inode_claim_rsv_space",
        "fs/quota/dquot.c:inode_add_rsv_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729504,
      "name": "inode_reserved_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
qsize_t * inode_reserved_space(struct inode * inode)
```

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581875344,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1602",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581875344,
      "name": "inode_reserved_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
qsize_t * inode_reserved_space(struct inode * inode)
```

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582057344,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1599",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057344,
      "name": "inode_reserved_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
qsize_t * inode_reserved_space(struct inode * inode)
```

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582151440,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1599",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582151440,
      "name": "inode_reserved_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
qsize_t * inode_reserved_space(struct inode * inode)
```

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582314160,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1609",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582314160,
      "name": "inode_reserved_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
qsize_t * inode_reserved_space(struct inode * inode)
```

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582413248,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1611",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582413248,
      "name": "inode_reserved_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582720964,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1609",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
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
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582792100,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1610",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
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
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582819947,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1608",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
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
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583150396,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1613",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
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
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583644064,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1623",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
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
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584249455,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1623",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
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
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584480080,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1681",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
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
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584703040,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1635",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
qsize_t * inode_reserved_space(struct inode * inode)
```

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494016552,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1611",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494016552,
      "name": "inode_reserved_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
qsize_t * inode_reserved_space(struct inode * inode)
```

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227487240,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1611",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227487240,
      "name": "inode_reserved_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
qsize_t * inode_reserved_space(struct inode * inode)
```

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287669216,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1611",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287669216,
      "name": "inode_reserved_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
qsize_t * inode_reserved_space(struct inode * inode)
```

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273527350,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1611",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273527350,
      "name": "inode_reserved_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
qsize_t * inode_reserved_space(struct inode * inode)
```

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582381984,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1611",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381984,
      "name": "inode_reserved_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
qsize_t * inode_reserved_space(struct inode * inode)
```

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582319680,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1611",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582319680,
      "name": "inode_reserved_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
qsize_t * inode_reserved_space(struct inode * inode)
```

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582372464,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1611",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582372464,
      "name": "inode_reserved_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
qsize_t * inode_reserved_space(struct inode * inode)
```

```json
{
  "name": "inode_reserved_space",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582454288,
      "name": "inode_reserved_space",
      "external": false,
      "loc": "fs/quota/dquot.c:1611",
      "file": "fs/quota/dquot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_reclaim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:dquot_claim_space_nodirty",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_alloc_space",
        "fs/quota/dquot.c:__dquot_initialize",
        "fs/quota/dquot.c:__dquot_initialize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582454288,
      "name": "inode_reserved_space",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
qsize_t * inode_reserved_space(struct inode * inode)
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

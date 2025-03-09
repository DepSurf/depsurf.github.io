# Function: <code>pde_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581464272,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:540",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581464272,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581648656,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:545",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648656,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581736960,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:547",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581736960,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581790912,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:531",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790912,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581940272,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:541",
      "file": "fs/proc/generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581940272,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582124768,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:641",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124768,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582219232,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:643",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582219232,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582383440,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:644",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582383440,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582482352,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:644",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582482352,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582781232,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:657",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582781232,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582854688,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:677",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582854688,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582882992,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:672",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582882992,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583216608,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:672",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583216608,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583713984,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:675",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:proc_readdir_de",
        "fs/proc/generic.c:proc_readdir_de",
        "fs/proc/generic.c:proc_readdir_de"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583713984,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584325600,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:675",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:proc_readdir_de",
        "fs/proc/generic.c:proc_readdir_de",
        "fs/proc/generic.c:proc_readdir_de"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325600,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584555648,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:674",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:proc_readdir_de",
        "fs/proc/generic.c:proc_readdir_de",
        "fs/proc/generic.c:proc_readdir_de"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555648,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584787504,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:674",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_free_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry",
        "fs/proc/generic.c:proc_readdir_de",
        "fs/proc/generic.c:proc_readdir_de",
        "fs/proc/generic.c:proc_readdir_de"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787504,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494104336,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:644",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494104336,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227553940,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:644",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227553940,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287772736,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:644",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287772736,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273587964,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:644",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273587414,
      "name": "pde_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446743936273590578,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582451088,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:644",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582451088,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582388256,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:644",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582388256,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582441568,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:644",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441568,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void pde_put(struct proc_dir_entry * pde)
```

```json
{
  "name": "pde_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582521744,
      "name": "pde_put",
      "external": true,
      "loc": "fs/proc/generic.c:644",
      "file": "fs/proc/generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_get_inode",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_subtree",
        "fs/proc/generic.c:remove_proc_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521744,
      "name": "pde_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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

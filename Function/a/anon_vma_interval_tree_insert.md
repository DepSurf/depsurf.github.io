# Function: <code>anon_vma_interval_tree_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580650240,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:76",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:expand_downwards",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580650240,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580757408,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:76",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:vma_adjust",
        "mm/mmap.c:vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757408,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580822624,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:76",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822624,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580864720,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:76",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864720,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580955824,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:76",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955824,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090160,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:76",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090160,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581168048,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:76",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581168048,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581239104,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581239104,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581297552,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581297552,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581488416,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581488416,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581530112,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581530112,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581552224,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581552224,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581816000,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581816000,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582205632,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582205632,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582692240,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:vma_expand",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582692240,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582906160,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:vma_complete",
        "mm/mmap.c:vma_complete",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906160,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583080000,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:vma_complete",
        "mm/mmap.c:vma_complete",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583080000,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492704832,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492704832,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226542740,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226542740,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286039792,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286039792,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272705004,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272705004,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581266400,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581266400,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581213056,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581213056,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581257600,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257600,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void anon_vma_interval_tree_insert(struct anon_vma_chain * node, struct rb_root_cached * root)
```

```json
{
  "name": "anon_vma_interval_tree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581321536,
      "name": "anon_vma_interval_tree_insert",
      "external": true,
      "loc": "mm/interval_tree.c:75",
      "file": "mm/interval_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:expand_downwards",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:anon_vma_clone",
        "mm/rmap.c:__anon_vma_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321536,
      "name": "anon_vma_interval_tree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rb_root * root</code> ➡️ <code>struct rb_root_cached * root</code>
</li>
</ul>
</details>
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

# Function: <code>ext4_xattr_delete_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_xattr_delete_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581856368,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:1486",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581856368,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void ext4_xattr_delete_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582052304,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:1588",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052304,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void ext4_xattr_delete_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141936,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:1602",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_free_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141936,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582247552,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2795",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582247552,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 901
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582396512,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2831",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582396512,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 945
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582586880,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2848",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582586880,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 939
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582688320,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2853",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582688320,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 941
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582860832,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2854",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582860832,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582964992,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2854",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964992,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583280144,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2841",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583280144,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1055
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583381376,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2848",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583381376,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1067
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583404192,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2848",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583404192,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1074
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583748528,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2831",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748528,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1087
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584305728,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2846",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584305728,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1055
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584953984,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2872",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584953984,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 905
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585182256,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2919",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585182256,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585415152,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2919",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585415152,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494640360,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2854",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494640360,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1008
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228085416,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2854",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228085416,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1040
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288451472,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2854",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288451472,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1212
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274010120,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2854",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274010120,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 810
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582933728,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2854",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582933728,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582870880,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2854",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582870880,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582922336,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2854",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922336,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
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
int ext4_xattr_delete_inode(handle_t * handle, struct inode * inode, struct ext4_xattr_inode_array * * ea_inode_array, int extra_credits)
```

```json
{
  "name": "ext4_xattr_delete_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583009392,
      "name": "ext4_xattr_delete_inode",
      "external": true,
      "loc": "fs/ext4/xattr.c:2854",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583009392,
      "name": "ext4_xattr_delete_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 956
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ext4_xattr_inode_array * * ea_inode_array</code>
</li>
<li>
<b>Param added. </b>
<code>int extra_credits</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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

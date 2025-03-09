# Function: <code>full_name_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int full_name_hash(const unsigned char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581040656,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1806",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len",
        "fs/dcache.c:d_alloc_name",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dir.c:fuse_readdir",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/smack/smack_access.c:smk_find_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:list_netdevice",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:dev_get_by_name_rcu",
        "net/core/dev.c:dev_change_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581040656,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581200320,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1909",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name_rcu",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:list_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581200320,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581277584,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1902",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name_rcu",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:list_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277584,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581325904,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1912",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name_rcu",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:list_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581325904,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581466016,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1910",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name_rcu",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:list_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581466016,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581623088,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1897",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name_rcu",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:list_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581623088,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581709248,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1938",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/readdir.c:fuse_readdir",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name_rcu",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:list_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581709248,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581827072,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1936",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_hash_and_lookup",
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name_rcu",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:list_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827072,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581899632,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1929",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_hash_and_lookup",
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name_rcu",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:list_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899632,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582129152,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1975",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_common",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/selinux/ss/context.c:context_compute_hash",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:netdev_name_node_alt_create",
        "net/core/dev.c:netdev_name_node_lookup_rcu",
        "net/core/dev.c:netdev_name_node_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582129152,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582175680,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1971",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_common",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/selinux/ss/context.c:context_compute_hash",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:netdev_name_node_alt_create",
        "net/core/dev.c:netdev_name_node_lookup_rcu",
        "net/core/dev.c:netdev_name_node_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582175680,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582198960,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:2057",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_common",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event",
        "fs/notify/fanotify/fanotify.c:fanotify_encode_fh",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/selinux/ss/context.c:context_compute_hash",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:netdev_name_node_alt_create",
        "net/core/dev.c:netdev_name_node_lookup_rcu",
        "net/core/dev.c:netdev_name_node_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582198960,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582516288,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:2085",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_common",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event",
        "fs/notify/fanotify/fanotify.c:fanotify_encode_fh",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/selinux/ss/context.c:context_compute_hash",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:netdev_name_node_alt_create",
        "net/core/dev.c:netdev_name_node_lookup_rcu",
        "net/core/dev.c:netdev_name_node_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582516288,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583040448,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:2131",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_common",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/notify/fanotify/fanotify.c:fanotify_encode_fh",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/selinux/ss/context.c:context_compute_hash",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_get_mac_address",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name",
        "net/core/dev.c:list_netdevice",
        "net/core/dev.c:netdev_name_node_alt_create",
        "net/core/dev.c:netdev_name_node_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583040448,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583602752,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:2108",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_common",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/notify/fanotify/fanotify.c:fanotify_encode_fh",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/selinux/ss/context.c:context_compute_hash",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_get_mac_address",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name",
        "net/core/dev.c:list_netdevice",
        "net/core/dev.c:netdev_name_node_alt_create",
        "net/core/dev.c:netdev_name_node_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583602752,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583819632,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:2113",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_common",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/notify/fanotify/fanotify.c:fanotify_encode_fh",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/selinux/ss/context.c:context_compute_hash",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:default_device_exit_net",
        "net/core/dev.c:dev_get_mac_address",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:netdev_get_by_name",
        "net/core/dev.c:list_netdevice",
        "net/core/dev.c:netdev_name_node_alt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583819632,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584025584,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:2120",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_common",
        "fs/dcache.c:d_hash_and_lookup",
        "fs/notify/fanotify/fanotify.c:fanotify_encode_fh",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/selinux/ss/policydb.c:filenametr_hash",
        "security/selinux/ss/context.c:context_compute_hash",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:default_device_exit_net",
        "net/core/dev.c:dev_get_mac_address",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:netdev_get_by_name",
        "net/core/dev.c:list_netdevice",
        "net/core/dev.c:list_netdevice",
        "net/core/dev.c:netdev_name_node_alt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025584,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493374384,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1929",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_hash_and_lookup",
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/readdir.c:parse_dirplusfile",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name_rcu",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:list_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493374384,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226960636,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1929",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_hash_and_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_fill_cache",
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/readdir.c:parse_dirplusfile",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name_rcu",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:list_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226960636,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286922032,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1929",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_hash_and_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_fill_cache",
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/readdir.c:parse_dirplusfile",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name_rcu",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:list_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286922032,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273101754,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:2006",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_one_len_common"
      ],
      "caller_func": [
        "fs/dcache.c:d_hash_and_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_fill_cache",
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name_rcu",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:list_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273092246,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581868368,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1929",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_hash_and_lookup",
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name_rcu",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:list_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868368,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581805968,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1929",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_hash_and_lookup",
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name_rcu",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:list_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581805968,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581859680,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1929",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_hash_and_lookup",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name_rcu",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:list_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581859680,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
unsigned int full_name_hash(const void * salt, const char * name, unsigned int len)
```

```json
{
  "name": "full_name_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581931264,
      "name": "full_name_hash",
      "external": true,
      "loc": "fs/namei.c:1929",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:d_hash_and_lookup",
        "fs/ext4/dir.c:ext4_d_hash",
        "fs/fat/namei_vfat.c:vfat_hash",
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "security/smack/smack_access.c:smk_find_entry",
        "security/smack/smack_access.c:smk_insert_entry",
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/util.c:tomoyo_fill_path_info",
        "net/core/dev.c:dev_change_name",
        "net/core/dev.c:dev_get_by_name_rcu",
        "net/core/dev.c:__dev_get_by_name",
        "net/core/dev.c:list_netdevice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581931264,
      "name": "full_name_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void * salt</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, len</code> ➡️ <code>salt, name, len</code>
</li>
<li>
<b>Param type changed. </b>
<code>const unsigned char * name</code> ➡️ <code>const char * name</code>
</li>
</ul>
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

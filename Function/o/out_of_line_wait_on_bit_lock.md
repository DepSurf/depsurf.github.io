# Function: <code>out_of_line_wait_on_bit_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587367408,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait.c:445",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:nobh_write_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587367408,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587868224,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait.c:445",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587868224,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588082800,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait.c:442",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588082800,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588309600,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:110",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588309600,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588874960,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:110",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588874960,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589253776,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:110",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589253776,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589496000,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:110",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589496000,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589956784,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589956784,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590184448,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590184448,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591202688,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591202688,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591697776,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591697776,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591640288,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591640288,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592814240,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592814240,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594715968,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594715968,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596463264,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596463264,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597005088,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597005088,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597934432,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bh_read_batch",
        "fs/buffer.c:bh_uptodate_or_lock",
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:block_invalidate_folio",
        "fs/buffer.c:__bread_gfp",
        "drivers/md/dm-zone.c:dm_zone_map_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597934432,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503928048,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503928048,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236537728,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236537728,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297776176,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__sync_dirty_buffer",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297776176,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279796396,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279796396,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589786736,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589786736,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589509280,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589509280,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590230144,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590230144,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int out_of_line_wait_on_bit_lock(void * word, int bit, wait_bit_action_f * action, unsigned int mode)
```

```json
{
  "name": "out_of_line_wait_on_bit_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590280736,
      "name": "out_of_line_wait_on_bit_lock",
      "external": true,
      "loc": "kernel/sched/wait_bit.c:111",
      "file": "kernel/sched/wait_bit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590280736,
      "name": "out_of_line_wait_on_bit_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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

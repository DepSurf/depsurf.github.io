# Function: <code>hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594952053,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:63",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579830758,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:150",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:SyS_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581099542,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:442",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:__insert_inode_hash",
        "fs/inode.c:iunique",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:insert_inode_locked4",
        "fs/inode.c:ilookup",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget5_locked",
        "fs/inode.c:insert_inode_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:609",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:134",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595115823,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:63",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579859462,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:150",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:SyS_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272488,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:450",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked4",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget5_locked",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581401551,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:687",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582101169,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:134",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595358897,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:63",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579915174,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:150",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:SyS_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581350472,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:452",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked4",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget5_locked",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479887,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:939",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582191249,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:134",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596275696,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:64",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579923300,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:141",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581406165,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:452",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked4",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget5_locked",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581534879,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:840",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdget",
        "fs/block_dev.c:bdev_unhash_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582277105,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:134",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602591728,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:65",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579968660,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:142",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581547765,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:452",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked4",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:iget5_locked",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677439,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:830",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdget",
        "fs/block_dev.c:bdev_unhash_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582426241,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:134",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602760725,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:65",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580016264,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:142",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581704987,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:458",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581846325,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:831",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdget",
        "fs/block_dev.c:bdev_unhash_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582617060,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604554842,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:55",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580063272,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:112",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581791835,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:458",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581935605,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:870",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdget",
        "fs/block_dev.c:bdev_unhash_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582718804,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604649116,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:55",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580106933,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:112",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581910443,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:471",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582073749,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:867",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdget",
        "fs/block_dev.c:bdev_unhash_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582892436,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604661377,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:55",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580155989,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:112",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581982971,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:475",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582149893,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:867",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdget",
        "fs/block_dev.c:bdev_unhash_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582999012,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609011206,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:56",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:find_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580220613,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:113",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582217275,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:476",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_by_ino_rcu",
        "fs/inode.c:find_inode_rcu",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582387877,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:863",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583315748,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612073321,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:59",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:find_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580204873,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:113",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582264699,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:477",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_by_ino_rcu",
        "fs/inode.c:find_inode_rcu",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583430660,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614211546,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:71",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:find_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580210171,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:113",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582289963,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:477",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_by_ino_rcu",
        "fs/inode.c:find_inode_rcu",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583452916,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615130290,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:72",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:find_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580355515,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:113",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582608760,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:481",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_by_ino_rcu",
        "fs/inode.c:find_inode_rcu",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583803499,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616893477,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:83",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:find_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580570093,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:113",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617307,
      "name": "hash",
      "external": false,
      "loc": "kernel/bpf/bloom_filter.c:30",
      "file": "kernel/bpf/bloom_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bloom_filter.c:bloom_map_peek_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583140344,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:509",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_by_ino_rcu",
        "fs/inode.c:find_inode_rcu",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584368363,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627484197,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:83",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:find_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830541,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:113",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582001691,
      "name": "hash",
      "external": false,
      "loc": "kernel/bpf/bloom_filter.c:30",
      "file": "kernel/bpf/bloom_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bloom_filter.c:bloom_map_peek_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583712024,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:508",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_by_ino_rcu",
        "fs/inode.c:find_inode_rcu",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585019723,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int hash(int major, int minor, int ino)
```

```json
{
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619228213,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:77",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:find_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580914093,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:70",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582192000,
      "name": "hash",
      "external": false,
      "loc": "kernel/bpf/bloom_filter.c:23",
      "file": "kernel/bpf/bloom_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bloom_filter.c:bloom_map_peek_elem"
      ]
    },
    {
      "addr": 18446744071583929496,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:508",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_by_ino_rcu",
        "fs/inode.c:find_inode_rcu",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585246987,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582192000,
      "name": "hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int hash(int major, int minor, int ino)
```

```json
{
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621517845,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:77",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:find_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581004701,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:70",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582340896,
      "name": "hash",
      "external": false,
      "loc": "kernel/bpf/bloom_filter.c:23",
      "file": "kernel/bpf/bloom_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bloom_filter.c:bloom_map_peek_elem"
      ]
    },
    {
      "addr": 18446744071584136264,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:509",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_by_ino_rcu",
        "fs/inode.c:find_inode_rcu",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585480235,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340896,
      "name": "hash",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510811956,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:55",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491383080,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:112",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493492524,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:475",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493702200,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:867",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdget",
        "fs/block_dev.c:bdev_unhash_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494686104,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243257912,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:55",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
      ],
      "caller_func": []
    },
    {
      "addr": 3225376632,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:112",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3227051984,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:475",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 3227221348,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:867",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdget",
        "fs/block_dev.c:bdev_unhash_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 3228124896,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302376080,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:55",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284316924,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:112",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287053644,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:475",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287294700,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:867",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdget",
        "fs/block_dev.c:bdev_unhash_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288502136,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270608792,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:55",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271865860,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:112",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273168310,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:475",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273318162,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:867",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdget",
        "fs/block_dev.c:bdev_unhash_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274043524,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604587649,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:55",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580125189,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:112",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581951707,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:475",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582118629,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:867",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdget",
        "fs/block_dev.c:bdev_unhash_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582967748,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604579326,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:55",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580070485,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:112",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581889275,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:475",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582056069,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:867",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdget",
        "fs/block_dev.c:bdev_unhash_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582904900,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604665473,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:55",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580116261,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:112",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581943019,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:475",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582109109,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:867",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdget",
        "fs/block_dev.c:bdev_unhash_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582956356,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hash",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604665478,
      "name": "hash",
      "external": false,
      "loc": "init/initramfs.c:55",
      "file": "init/initramfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/initramfs.c:maybe_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580168228,
      "name": "hash",
      "external": false,
      "loc": "kernel/time/posix-timers.c:112",
      "file": "kernel/time/posix-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:__lock_timer",
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582012475,
      "name": "hash",
      "external": false,
      "loc": "fs/inode.c:475",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_nowait",
        "fs/inode.c:ilookup",
        "fs/inode.c:ilookup5_nowait",
        "fs/inode.c:iunique",
        "fs/inode.c:iget_locked",
        "fs/inode.c:inode_insert5",
        "fs/inode.c:__insert_inode_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582175637,
      "name": "hash",
      "external": false,
      "loc": "fs/block_dev.c:867",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdget",
        "fs/block_dev.c:bdev_unhash_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583044278,
      "name": "hash",
      "external": false,
      "loc": "fs/jbd2/revoke.c:131",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:find_revoke_record",
        "fs/jbd2/revoke.c:insert_revoke_hash"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int hash(int major, int minor, int ino)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

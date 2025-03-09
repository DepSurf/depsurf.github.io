# Function: <code>page_waitqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
wait_queue_head_t * page_waitqueue(struct page * page)
```

```json
{
  "name": "page_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580468464,
      "name": "page_waitqueue",
      "external": true,
      "loc": "mm/filemap.c:738",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:wait_on_page_bit",
        "mm/filemap.c:wait_on_page_bit_killable_timeout",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:unlock_page",
        "mm/filemap.c:wait_on_page_bit_killable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580468464,
      "name": "page_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
wait_queue_head_t * page_waitqueue(struct page * page)
```

```json
{
  "name": "page_waitqueue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580548599,
      "name": "page_waitqueue",
      "external": true,
      "loc": "mm/filemap.c:778",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:unlock_page",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:wait_on_page_bit_killable_timeout",
        "mm/filemap.c:wait_on_page_bit_killable",
        "mm/filemap.c:wait_on_page_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545856,
      "name": "page_waitqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580618839,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:746",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:wake_up_page_bit",
        "mm/filemap.c:__filemap_fdatawait_range"
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
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580648626,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:864",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:wake_up_page_bit",
        "mm/filemap.c:__filemap_fdatawait_range"
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
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580732441,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:965",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:wake_up_page_bit",
        "mm/filemap.c:__filemap_fdatawait_range"
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
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580867843,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:965",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:wake_up_page_bit",
        "mm/filemap.c:__filemap_fdatawait_range"
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
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580938940,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:943",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:wake_up_page_bit",
        "mm/filemap.c:__filemap_fdatawait_range"
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
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581033246,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:991",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:wake_up_page_bit"
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
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581088814,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:1000",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:wake_up_page_bit"
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
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581281789,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:975",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:wake_up_page_bit"
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
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581325770,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:1000",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read_pagenotuptodate",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:__wait_on_page_locked_async",
        "mm/filemap.c:wake_up_page_bit"
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
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581337372,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:1024",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_async",
        "mm/filemap.c:wait_on_page_private_2_killable",
        "mm/filemap.c:wait_on_page_private_2",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:wake_up_page_bit"
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
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581585678,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:1079",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_async",
        "mm/filemap.c:wait_on_page_private_2_killable",
        "mm/filemap.c:wait_on_page_private_2",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:wake_up_page_bit"
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492455480,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:1000",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:wake_up_page_bit"
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
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226329048,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:1000",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:wake_up_page_bit"
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
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285730944,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:1000",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:wake_up_page_bit"
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
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272526656,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:1000",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:wake_up_page_bit"
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
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581057662,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:1000",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:wake_up_page_bit"
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
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581004910,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:1000",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:wake_up_page_bit"
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
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581048862,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:1000",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:wake_up_page_bit"
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
  "name": "page_waitqueue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581110542,
      "name": "page_waitqueue",
      "external": false,
      "loc": "mm/filemap.c:1000",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:add_page_wait_queue",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:wake_up_page_bit"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
wait_queue_head_t * page_waitqueue(struct page * page)
```
</details>
</li>
</ul>

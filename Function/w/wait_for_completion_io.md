# Function: <code>wait_for_completion_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587371088,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:153",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq",
        "block/blk-lib.c:blkdev_issue_discard",
        "block/blk-lib.c:blkdev_issue_write_same",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "drivers/lightnvm/core.c:nvm_submit_ppa",
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587371088,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587871920,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:153",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/lightnvm/core.c:__nvm_submit_ppa",
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587871920,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588086464,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:153",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/lightnvm/core.c:__nvm_submit_ppa",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588086464,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588313008,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:156",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/lightnvm/core.c:nvm_erase_sync",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588313008,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588878496,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:170",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588878496,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589256944,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:167",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589256944,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589499168,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:167",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589499168,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589959648,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:167",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589959648,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590187312,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:167",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/lightnvm/core.c:nvm_submit_io_wait",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590187312,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591203776,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:169",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591203776,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591698912,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:169",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591698912,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591641424,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:169",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/lightnvm/core.c:nvm_bb_chunk_sense",
        "drivers/lightnvm/core.c:nvm_submit_io_sync",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591641424,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592815344,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:169",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592815344,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594717600,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:169",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-mq.c:blk_execute_rq",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594717600,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596466032,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:169",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-mq.c:blk_execute_rq",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596466032,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597006736,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:169",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-mq.c:blk_execute_rq",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597006736,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597935328,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:179",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-mq.c:blk_execute_rq",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597935328,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503929792,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:167",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/lightnvm/core.c:nvm_submit_io_wait",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503929792,
      "name": "wait_for_completion_io",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236538524,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:167",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/lightnvm/core.c:nvm_submit_io_wait",
        "drivers/md/dm-io.c:dm_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236538524,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297777120,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:167",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/lightnvm/core.c:nvm_submit_io_wait",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297777120,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279796932,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:167",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/lightnvm/core.c:nvm_submit_io_wait",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279796932,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589789600,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:167",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/lightnvm/core.c:nvm_submit_io_wait",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589789600,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589512096,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:167",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589512096,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590233008,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:167",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/lightnvm/core.c:nvm_submit_io_wait",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590233008,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void wait_for_completion_io(struct completion * x)
```

```json
{
  "name": "wait_for_completion_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590281392,
      "name": "wait_for_completion_io",
      "external": true,
      "loc": "kernel/sched/completion.c:167",
      "file": "kernel/sched/completion.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bio.c:submit_bio_wait",
        "block/blk-exec.c:blk_execute_rq",
        "drivers/lightnvm/core.c:nvm_submit_io_wait",
        "drivers/md/dm-io.c:sync_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590281392,
      "name": "wait_for_completion_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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

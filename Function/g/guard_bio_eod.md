# Function: <code>guard_bio_eod</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void guard_bio_eod(int rw, struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581223152,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "fs/buffer.c:2963",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581223152,
      "name": "guard_bio_eod",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void guard_bio_eod(int op, struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581388352,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "fs/buffer.c:3019",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_bio_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581388352,
      "name": "guard_bio_eod",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void guard_bio_eod(int op, struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581466832,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "fs/buffer.c:3060",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581466832,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void guard_bio_eod(int op, struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581522384,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "fs/buffer.c:3054",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522384,
      "name": "guard_bio_eod",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void guard_bio_eod(int op, struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581664608,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "fs/buffer.c:3014",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664608,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void guard_bio_eod(int op, struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581827904,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "fs/buffer.c:2985",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827904,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void guard_bio_eod(int op, struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581915152,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "fs/buffer.c:2997",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915152,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void guard_bio_eod(int op, struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582052256,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "fs/buffer.c:2994",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052256,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void guard_bio_eod(struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582130144,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "fs/buffer.c:2994",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582130144,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void guard_bio_eod(struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584347184,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "block/bio.c:606",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584347184,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void guard_bio_eod(struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584463920,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "block/bio.c:608",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463920,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void guard_bio_eod(struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584498368,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "block/bio.c:572",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498368,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void guard_bio_eod(struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584909136,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "block/bio.c:601",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584909136,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void guard_bio_eod(struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585608880,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "block/bio.c:657",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_read_folio",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585608880,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
void guard_bio_eod(struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586377808,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "block/bio.c:682",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_read_folio",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586377808,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
void guard_bio_eod(struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586624160,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "block/bio.c:681",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_read_folio",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586624160,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
void guard_bio_eod(struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586895664,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "block/bio.c:681",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_read_folio",
        "fs/mpage.c:mpage_readahead",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586895664,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
void guard_bio_eod(struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493673720,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "fs/buffer.c:2994",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493673720,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void guard_bio_eod(struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227205724,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "fs/buffer.c:2994",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227205724,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void guard_bio_eod(struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287275264,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "fs/buffer.c:2994",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287275264,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void guard_bio_eod(struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273299284,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "fs/buffer.c:2994",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273299284,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void guard_bio_eod(struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582098880,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "fs/buffer.c:2994",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582098880,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void guard_bio_eod(struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582036320,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "fs/buffer.c:2994",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582036320,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void guard_bio_eod(struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582089360,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "fs/buffer.c:2994",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582089360,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void guard_bio_eod(struct bio * bio)
```

```json
{
  "name": "guard_bio_eod",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582162080,
      "name": "guard_bio_eod",
      "external": true,
      "loc": "fs/buffer.c:2994",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:mpage_writepage",
        "fs/mpage.c:mpage_writepages",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:mpage_readpage",
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582162080,
      "name": "guard_bio_eod",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
<code>int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int op</code>
</li>
<li>
<b>Param reordered. </b>
<code>op, bio</code> ➡️ <code>bio</code>
</li>
</ul>
</details>
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

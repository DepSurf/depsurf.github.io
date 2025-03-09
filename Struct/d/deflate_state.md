# Struct: <code>deflate_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
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
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
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
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct deflate_state {
    z_streamp strm;
    int status;
    Byte * pending_buf;
    ulg pending_buf_size;
    Byte * pending_out;
    int pending;
    int noheader;
    Byte data_type;
    Byte method;
    int last_flush;
    uInt w_size;
    uInt w_bits;
    uInt w_mask;
    Byte * window;
    ulg window_size;
    Pos * prev;
    Pos * head;
    uInt ins_h;
    uInt hash_size;
    uInt hash_bits;
    uInt hash_mask;
    uInt hash_shift;
    long int block_start;
    uInt match_length;
    IPos prev_match;
    int match_available;
    uInt strstart;
    uInt match_start;
    uInt lookahead;
    uInt prev_length;
    uInt max_chain_length;
    uInt max_lazy_match;
    int level;
    int strategy;
    uInt good_match;
    int nice_match;
    struct ct_data_s[573] dyn_ltree;
    struct ct_data_s[61] dyn_dtree;
    struct ct_data_s[39] bl_tree;
    struct tree_desc_s l_desc;
    struct tree_desc_s d_desc;
    struct tree_desc_s bl_desc;
    ush[16] bl_count;
    int[573] heap;
    int heap_len;
    int heap_max;
    uch[573] depth;
    uch * l_buf;
    uInt lit_bufsize;
    uInt last_lit;
    ush * d_buf;
    ulg opt_len;
    ulg static_len;
    ulg compressed_len;
    uInt matches;
    int last_eob_len;
    ush bi_buf;
    int bi_valid;
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

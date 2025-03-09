# Struct: <code>assoc_array_edit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
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
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
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
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct assoc_array_edit {
    struct callback_head rcu;
    struct assoc_array * array;
    const struct assoc_array_ops * ops;
    const struct assoc_array_ops * ops_for_excised_subtree;
    struct assoc_array_ptr * leaf;
    struct assoc_array_ptr * * leaf_p;
    struct assoc_array_ptr * dead_leaf;
    struct assoc_array_ptr *[3] new_meta;
    struct assoc_array_ptr *[1] excised_meta;
    struct assoc_array_ptr * excised_subtree;
    struct assoc_array_ptr * *[16] set_backpointers;
    struct assoc_array_ptr * set_backpointers_to;
    struct assoc_array_node * adjust_count_on;
    long int adjust_count_by;
    struct (anon)[2] set;
    struct (anon)[1] set_parent_slot;
    u8[17] segment_cache;
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

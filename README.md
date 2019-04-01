# csx730-paging

Implement demand paging.

* `void csx730_paging_init(const char * filename, size_t page_size, size_t virt_limit, size_t phys_limit);`
* `void csx730_paging_policy(enum policy p);`
* `void * csx730_virt_to_phys(void * virt_addr);`
* `void * csx730_paging_stats(void);`

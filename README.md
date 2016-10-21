# I-Spinlock
we propose I-Spinlock (for Informed Spinlock), a new spinlock implementation for virtualized environments. The main principle is to make the spinlock primitive be aware (informed) of its time-to-
preemption (by the hypervizor). Thanks to this information, the primitive will attempt to acquire the lock only if its time-to-preemption is sufficient to enter and leave the critical section.


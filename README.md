\# memorywam-toy



Hybrid attention mask from MemoryWAM (arXiv 2606.20562), on a toy setup.



!\[mask](toy\_mask\_memorywam.png)



12 steps, 3 frame + 2 gist + 2 action tokens per step, 2 anchor steps, recent window of 4 (including current step). All mask checks pass.



Next: cached pass with eviction, checked against the full masked pass.


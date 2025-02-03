# GRPO_tests
Playing with GRPO for LLM training

Initial resources/links:

- https://huggingface.co/blog/open-r1/update-1 has a fantastic list of other resources and attempts to re-create. TRL has their GRPO but I kinda want to do something minimal.
- https://www.philschmid.de/mini-deepseek-r1 has a 'small' (6 hours on 4XH100s) experiment showing an improvement on a maths task
- https://yugeten.github.io/posts/2025/01/ppogrpo/ is a post with good coverage of PPO/GRPO for non-RL people. Note: uses full KL not approx as used in TRL and I think R1.

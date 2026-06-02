# bug_stats_generator4free_coding_llms_jl
Generate dataset of buggy Julia code using free coding LLM to collect stats, top50 types of ERRORs 

Main motto:

Your code must be as simple and robust as to fit 7B-8B coding LLMs cabability. No more 480B-1T coding models!

2) Single lang in pretrain let us eleminate confusion caused by multi lang datasets in pretrain. Python in datasets causes buggy Julia code. Below 0.8B LLM possible via single lang datasets pretrain.

3) The above confusion can be supported by the collected stats.

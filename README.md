# analyzing commits from the Megatron-LM framework repository using Spark

**Repository**: https://github.com/NVIDIA/Megatron-LM

In order to get the logs, you need to clone the repository, go to the folder with it, and then run the command:

```bash
git log --pretty=format:"%H|%an|%ae|%ad|%s" --date=iso > /path/git_log.txt 
```
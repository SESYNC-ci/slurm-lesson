# Notes: Lesson on high-performance computing with Slurm

## Introduction

- Intro: What is Slurm and how parallel computing works (very brief and no technical language)

## The basics of Slurm

- How to look at the cluster status
- How to submit a Slurm job
- How to monitor the progress of your job
- What to do when the job is finished (dealing with output files)

## More advanced Slurm stuff

- Job arrays
- Setting time and memory limits, limiting the number of tasks that can run at once, etc.
- Using the cluster interactively

## Best practices

- Some tips for optimizing your jobs so they will run faster and use as little resources as possible
- Where to save output
- Use of temporary directories

## rslurm

- What is rslurm and brief non-technical description of how it works
- Summarize some of the stuff from the rslurm vignette: how to write slurm calls with slurm_call(), slurm_apply(), slurm_map()
- Adding options to slurm calls using slurm_options and other arguments
- Monitoring progress of job from rslurm
- Dealing with output files


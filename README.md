## script-nf

Minimal example to run unix commands inside Nextflow script and print the output

### Usage:

To test locally:

```bash
git clone https://github.com/lifebit-ai/script-nf.git
cd gpu-nf
nextflow run . --script 'df -h'--echo true --reps 4 --config conf/awsbatch.config
```

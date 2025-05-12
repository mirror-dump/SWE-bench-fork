## SWE-bench Fork for Running SWE-rebench

This fork of SWE-bench includes updates necessary for running SWE-rebench files. This repository was forked at commit `fea293e`.

The original `README.md` is available [here](https://github.com/SWE-Gym/SWE-Bench-Fork/blob/main/Original_README.md).

To run a sample evaluation, use the following command:

```bash
python -m swebench.harness.run_evaluation \
    --dataset_name nebius/SWE-rebench \
    --predictions_path gold \
    --instance_ids oemof__tespy-653 \
    --cache_level instance \
    --run_id validate-gold \
    --namespace ""
```
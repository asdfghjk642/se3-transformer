This is a re-implementation of the n-body experiment from the paper.

These are the steps to run an experiment:

1) Creating a dataset with the scripts in the folder `data_generation`
2) Training an SE3-Transformer using the script, e.g.:

    ```python nbody_run.py --ri_delta_t 10 --num_degrees 4 --batch_size 128 --num_channels 8 --div 4 --ri_burn_in 0 --siend att --xij add --head 2```



# emspipe_wheel

## easy start

``` 
conda create --name emsflow python=3.10.9
export TMPDIR=/path/to/large/tmp
pip install https://github.com/emsr-project/emscli_wheel/releases/download/v0.3.10/emsbatch-0.3.10-py3.10.9-none-any.whl
export EMS_BATCH_CODE_PATH=/home/magics/hdd/ems_ws/efs_fake/private
export EMS_BATCH_CONTAINER_MOUNT=/home/magics/hdd/ems_ws/efs_fake/private
export EMS_BATCH_SLURM_OUTPUT_PATH=/home/magics/hdd/ems_ws/efs_fake/private
export EMS_BATCH_CODE_UNZIP_PATH=/home/magics/hdd/ems_ws/efs_fake/tmp
pip install https://github.com/emsr-project/emspipe_wheel/releases/download/v0.0.1/emspipe-0.0.1-py3.10.9-none-any.whl
``` 


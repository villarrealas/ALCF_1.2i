Bootstrap: docker
From: avillarreal/alcf_run2.0i:production20181214

%environment
   source /DC2/docker_run.sh

%runscript
   exec python /DC2/ALCF_1.2i/scripts/run_imsim.py "$@"


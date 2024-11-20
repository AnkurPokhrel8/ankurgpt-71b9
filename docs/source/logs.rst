Latest Logs From Latest Build
==============================

Generated On: 2024-11-20 15:34:51 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/AnkurPokhrel8/raspberryCYT180/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-20_15:32:12] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-20_15:32:19] STEP 2: Create topics started

  [INFO 2024-11-20_15:32:42] STEP 2: Completed

  [INFO 2024-11-20_15:32:54] STEP 3: producing data started

  [INFO 2024-11-20_15:33:00] MQTT connection established...

  [INFO 2024-11-20_15:33:01] STEP 4: Preprocessing started

  [INFO 2024-11-20_15:33:06] STEP 4: Preprocessing started

  [INFO 2024-11-20_15:33:08] STEP 7: Visualization started

  [INFO 2024-11-20_15:33:15] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-20_15:33:25] STEP 9: Starting privateGPT

  [INFO 2024-11-20_15:33:36] STEP 8: Starting docker push for: pokhrelankur8@gmail.com/ankurgpt-71b9-amd64

  [INFO 2024-11-20_15:33:38] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [WARN 2024-11-20_15:33:56] STEP 8: There seems to be an issue creating the container.  Here is the commit command: docker commit dcf44bd517b4 pokhrelankur8@gmail.com/ankurgpt-71b9-amd64 - message=1.  Container may NOT pushed.

  [WARN 2024-11-20_15:34:16] STEP 8: There may be an issue pushing to Docker Hub, or just wait few seconds to see if the container shows up.  Here is the command: docker push pokhrelankur8@gmail.com/ankurgpt-71b9-amd64 - message=1

  [INFO 2024-11-20_15:34:49] STEP 10: Started to build the documentation

  [INFO 2024-11-20_15:34:53] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds



# BigDL-llm loader Text generation web UI for intel Arc GPU
1) Some features may not work.
2) HF fp16 and some GGUF (Q4_0, Q4_1, Q5_0, Q5_1, Q8_0) models only.
3) Tested only on Windows. (If you are a Linux OS user, good luck!)
4) BigDL-llm loader from https://github.com/intel-analytics/BigDL/tree/44660d6176efbbac542eaa593c9e1c2fbf43df43/python/llm/example/Text-Generation-WebUI/modules

## How to install
1) Clone or [download](https://github.com/ccvv804/text-generation-webui/archive/refs/heads/main.zip) the repository.
2) Run the `start_windows.bat`
3) Select D when asked.
4) Once the installation ends, close text-generation-webui cmd.
5) Run the `cmd_windows.bat`
6) Type `pip install --pre --no-deps bigdl-llm[xpu] bigdl-core-xe-21`
7) close cmd.

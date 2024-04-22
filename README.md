## Purpose of SampleEnclave

The project demonstrates several fundamental usages of Intel(R) Software Guard 
Extensions (Intel(R) SGX) SDK:
- Initializing and destroying an enclave
- Creating ECALLs or OCALLs
- Calling trusted libraries inside the enclave


## How to Build/Execute the Sample Code

1. Install Intel(R) SGX SDK for Linux* OS
2. Make sure your environment is set:
    ```shell
    source ${sgx-sdk-install-path}/environment
    ```  
3. Build the project with the prepared Makefile: Hardware Mode, Debug build:
    ```shell
    make
    ```
4. Execute the binary directly:
    ```shell
    ./app
    ```
5. Remember to `make clean` before switching build mode.

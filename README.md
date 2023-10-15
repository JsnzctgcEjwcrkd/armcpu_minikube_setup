# ARM CPU Minikube Setup

These are the steps to start minikube bare in an armCPU environment such as apple silicon.

## Procedure

1. Download ubuntu image for arm.

    [Ubuntu Server for ARM](https://ubuntu.com/downloald/server/arm)

1. VWware Fusion Player

    1. Follow the instructions to create a VMware Customer Connect account to obtain a personal use license for VWware Fusion Player.

        ["VMware Customer Connect" Register](https://customerconnect.vmware.com/jp/account-registration)

    1. Download
        [Try VMware Fusion Pro for Intel or Apple Silicon Macs](https://www.vmware.com/products/fusion/fusion-evaluation.html)

        ![TRY PRO FOR　FREE](images/2023-10-15-11-14-34.png)

    1. Installation and activation
        1. Double-click the downloaded `.dmg` file to proceed with the installation.
            ![Installation top screen](images/2023-10-15-11-22-51.png)
            ![Start permission warning](images/2023-10-15-11-24-38.png)
        1. ライセンス認証画面での進み方
            ![License authentication screen](images/2023-10-15-11-26-07.png)
            ![VMware Customer Connect menu screen](images/2023-10-15-11-28-31.png)
            ![press login](images/2023-10-15-11-31-35.png)
            ![After logging in, you can press the register button](images/2023-10-15-11-35-11.png)
            ![Agree to missing user information and license agreement](images/2023-10-15-11-38-56.png)
            ![License key can be obtained](images/2023-10-15-11-48-44.png)
            ![Paste on license authentication screen](images/2023-10-15-11-50-21.png)
        1. アクセシビリティを許可する
            ![Allow accessibility](images/2023-10-15-11-52-25.png)

    1. Starting a virtual machine
        1. Drag and drop the `.iso` file onto the new screen of VMware Fusion Player
            ![top screen](images/2023-10-15-12-05-45.png)
        1. 続ける押下
            ![Configuration screen](images/2023-10-15-12-15-41.png)
        1. スペックはデフォルトでよい終了
            ![End screen](images/2023-10-15-12-17-49.png)
